systeminfo
systeminfo | findstr /B /C:"OS Name" /C:"OS Version" /C:"System Type"

wmic qfe-  returns information about system and shows all patches made on system
\(based on retrieved Knowledge Bases we can determine what updates/patches are made on the system\)

wmic logicaldisk get caption,description,providername

