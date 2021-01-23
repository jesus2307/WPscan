Resultado 1:

PS C:\Users\jesus> docker run -it --rm wpscanteam/wpscan --url http://3.236.92.160/  --enumerate p
_______________________________________________________________
         __          _______   _____
         \ \        / /  __ \ / ____|
          \ \  /\  / /| |__) | (___   ___  __ _ _ __ ®
           \ \/  \/ / |  ___/ \___ \ / __|/ _` | '_ \
            \  /\  /  | |     ____) | (__| (_| | | | |
             \/  \/   |_|    |_____/ \___|\__,_|_| |_|

         WordPress Security Scanner by the WPScan Team
                         Version 3.8.13
       Sponsored by Automattic - https://automattic.com/
       @_WPScan_, @ethicalhack3r, @erwan_lr, @firefart
_______________________________________________________________

[+] URL: http://3.236.92.160/ [3.236.92.160]
[+] Started: Thu Jan 14 21:56:04 2021

Interesting Finding(s):

[+] Headers
 | Interesting Entries:
 |  - Server: Apache
 |  - X-Powered-By: PHP/7.4.13
 |  - X-Mod-Pagespeed: 1.13.35.2-0
 | Found By: Headers (Passive Detection)
 | Confidence: 100%

[+] robots.txt found: http://3.236.92.160/robots.txt
 | Interesting Entries:
 |  - /wp-admin/
 |  - /wp-admin/admin-ajax.php
 | Found By: Robots Txt (Aggressive Detection)
 | Confidence: 100%

[+] XML-RPC seems to be enabled: http://3.236.92.160/xmlrpc.php
 | Found By: Direct Access (Aggressive Detection)
 | Confidence: 100%
 | References:
 |  - http://codex.wordpress.org/XML-RPC_Pingback_API
 |  - https://www.rapid7.com/db/modules/auxiliary/scanner/http/wordpress_ghost_scanner
 |  - https://www.rapid7.com/db/modules/auxiliary/dos/http/wordpress_xmlrpc_dos
 |  - https://www.rapid7.com/db/modules/auxiliary/scanner/http/wordpress_xmlrpc_login
 |  - https://www.rapid7.com/db/modules/auxiliary/scanner/http/wordpress_pingback_access

[+] WordPress readme found: http://3.236.92.160/readme.html
 | Found By: Direct Access (Aggressive Detection)
 | Confidence: 100%

[+] The external WP-Cron seems to be enabled: http://3.236.92.160/wp-cron.php
 | Found By: Direct Access (Aggressive Detection)
 | Confidence: 60%
 | References:
 |  - https://www.iplocation.net/defend-wordpress-from-ddos
 |  - https://github.com/wpscanteam/wpscan/issues/1299

[+] WordPress version 5.6 identified (Latest, released on 2020-12-08).
 | Found By: Rss Generator (Passive Detection)
 |  - http://3.236.92.160/feed/, <generator>https://wordpress.org/?v=5.6</generator>
 |  - http://3.236.92.160/comments/feed/, <generator>https://wordpress.org/?v=5.6</generator>

[+] WordPress theme in use: twentytwentyone
 | Location: http://3.236.92.160/wp-content/themes/twentytwentyone/
 | Last Updated: 2020-12-22T00:00:00.000Z
 | Readme: http://3.236.92.160/wp-content/themes/twentytwentyone/readme.txt
 | [!] The version is out of date, the latest version is 1.1
 | Style URL: http://3.236.92.160/wp-content/themes/twentytwentyone/style.css?ver=1.0
 | Style Name: Twenty Twenty-One
 | Style URI: https://wordpress.org/themes/twentytwentyone/
 | Description: Twenty Twenty-One is a blank canvas for your ideas and it makes the block editor your best brush. Wi...
 | Author: the WordPress team
 | Author URI: https://wordpress.org/
 |
 | Found By: Css Style In Homepage (Passive Detection)
 | Confirmed By: Css Style In 404 Page (Passive Detection)
 |
 | Version: 1.0 (80% confidence)
 | Found By: Style (Passive Detection)
 |  - http://3.236.92.160/wp-content/themes/twentytwentyone/style.css?ver=1.0, Match: 'Version: 1.0'

[+] Enumerating Most Popular Plugins (via Passive Methods)

[i] No plugins Found.

[!] No WPScan API Token given, as a result vulnerability data has not been output.
[!] You can get a free API token with 50 daily requests by registering at https://wpscan.com/register

[+] Finished: Thu Jan 14 21:56:12 2021
[+] Requests Done: 31
[+] Cached Requests: 7
[+] Data Sent: 7.384 KB
[+] Data Received: 213.459 KB
[+] Memory used: 241.055 MB
[+] Elapsed time: 00:00:07
 
 
# Resultado 2:

PS C:\Users\jesus> docker run -it --rm wpscanteam/wpscan --url http://3.236.92.160/  --api-token 7aUhTRe0G0WB5M0R7HZLJdY4Sg4EZN7ScIZU2b6hiDI
_______________________________________________________________
         __          _______   _____
         \ \        / /  __ \ / ____|
          \ \  /\  / /| |__) | (___   ___  __ _ _ __ ®
           \ \/  \/ / |  ___/ \___ \ / __|/ _` | '_ \
            \  /\  /  | |     ____) | (__| (_| | | | |
             \/  \/   |_|    |_____/ \___|\__,_|_| |_|

         WordPress Security Scanner by the WPScan Team
                         Version 3.8.13
       Sponsored by Automattic - https://automattic.com/
       @_WPScan_, @ethicalhack3r, @erwan_lr, @firefart
_______________________________________________________________

[+] URL: http://3.236.92.160/ [3.236.92.160]
[+] Started: Thu Jan 14 21:57:31 2021

Interesting Finding(s):

[+] Headers
 | Interesting Entries:
 |  - Server: Apache
 |  - X-Powered-By: PHP/7.4.13
 |  - X-Mod-Pagespeed: 1.13.35.2-0
 | Found By: Headers (Passive Detection)
 | Confidence: 100%

[+] robots.txt found: http://3.236.92.160/robots.txt
 | Interesting Entries:
 |  - /wp-admin/
 |  - /wp-admin/admin-ajax.php
 | Found By: Robots Txt (Aggressive Detection)
 | Confidence: 100%

[+] XML-RPC seems to be enabled: http://3.236.92.160/xmlrpc.php
 | Found By: Direct Access (Aggressive Detection)
 | Confidence: 100%
 | References:
 |  - http://codex.wordpress.org/XML-RPC_Pingback_API
 |  - https://www.rapid7.com/db/modules/auxiliary/scanner/http/wordpress_ghost_scanner
 |  - https://www.rapid7.com/db/modules/auxiliary/dos/http/wordpress_xmlrpc_dos
 |  - https://www.rapid7.com/db/modules/auxiliary/scanner/http/wordpress_xmlrpc_login
 |  - https://www.rapid7.com/db/modules/auxiliary/scanner/http/wordpress_pingback_access

[+] WordPress readme found: http://3.236.92.160/readme.html
 | Found By: Direct Access (Aggressive Detection)
 | Confidence: 100%

[+] The external WP-Cron seems to be enabled: http://3.236.92.160/wp-cron.php
 | Found By: Direct Access (Aggressive Detection)
 | Confidence: 60%
 | References:
 |  - https://www.iplocation.net/defend-wordpress-from-ddos
 |  - https://github.com/wpscanteam/wpscan/issues/1299

[+] WordPress version 5.6 identified (Latest, released on 2020-12-08).
 | Found By: Rss Generator (Passive Detection)
 |  - http://3.236.92.160/feed/, <generator>https://wordpress.org/?v=5.6</generator>
 |  - http://3.236.92.160/comments/feed/, <generator>https://wordpress.org/?v=5.6</generator>

[+] WordPress theme in use: twentytwentyone
 | Location: http://3.236.92.160/wp-content/themes/twentytwentyone/
 | Last Updated: 2020-12-22T00:00:00.000Z
 | Readme: http://3.236.92.160/wp-content/themes/twentytwentyone/readme.txt
 | [!] The version is out of date, the latest version is 1.1
 | Style URL: http://3.236.92.160/wp-content/themes/twentytwentyone/style.css?ver=1.0
 | Style Name: Twenty Twenty-One
 | Style URI: https://wordpress.org/themes/twentytwentyone/
 | Description: Twenty Twenty-One is a blank canvas for your ideas and it makes the block editor your best brush. Wi...
 | Author: the WordPress team
 | Author URI: https://wordpress.org/
 |
 | Found By: Css Style In Homepage (Passive Detection)
 | Confirmed By: Css Style In 404 Page (Passive Detection)
 |
 | Version: 1.0 (80% confidence)
 | Found By: Style (Passive Detection)
 |  - http://3.236.92.160/wp-content/themes/twentytwentyone/style.css?ver=1.0, Match: 'Version: 1.0'

[+] Enumerating All Plugins (via Passive Methods)

[i] No plugins Found.

[+] Enumerating Config Backups (via Passive and Aggressive Methods)
 Checking Config Backups - Time: 00:00:01 <===========================================> (22 / 22) 100.00% Time: 00:00:01

[i] No Config Backups Found.

[+] WPScan DB API OK
 | Plan: free
 | Requests Done (during the scan): 2
 | Requests Remaining: 38

[+] Finished: Thu Jan 14 21:57:39 2021
[+] Requests Done: 57
[+] Cached Requests: 7
[+] Data Sent: 13.792 KB
[+] Data Received: 225.136 KB
[+] Memory used: 207.516 MB
[+] Elapsed time: 00:00:08
