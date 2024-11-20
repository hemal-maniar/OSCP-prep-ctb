/robots\.txt

User\-agent: \*
Disallow: /wp\-admin/
Allow: /wp\-admin/admin\-ajax\.php

/xmlrpc\.php is enabled

Burpsuite to make a POST request to /xmlrpc\.php

\<methodCall\>
\<methodName\>system\.listMethods\</methodName\>
\<params\>\</params\>
\</methodCall\>

got a response such as 

\<value\>\<string\>system\.multicall\</string\>\</value\>
\<value\>\<string\>system\.listMethods\</string\>\</value\>
\<value\>\<string\>system\.getCapabilities\</string\>\</value\>
\<value\>\<string\>demo\.addTwoNumbers\</string\>\</value\>
\<value\>\<string\>demo\.sayHello\</string\>\</value\>
\<value\>\<string\>pingback\.extensions\.getPingbacks\</string\>\</value\>
\<value\>\<string\>pingback\.ping\</string\>\</value\>
\<value\>\<string\>mt\.publishPost\</string\>\</value\>
\<value\>\<string\>mt\.getTrackbackPings\</string\>\</value\>
\<value\>\<string\>mt\.supportedTextFilters\</string\>\</value\>
\<value\>\<string\>mt\.supportedMethods\</string\>\</value\>
\<value\>\<string\>mt\.setPostCategories\</string\>\</value\>
\<value\>\<string\>mt\.getPostCategories\</string\>\</value\>
\<value\>\<string\>mt\.getRecentPostTitles\</string\>\</value\>

