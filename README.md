Resultado 1:

ubuntu@ip-172-31-90-230:~$ sudo docker run -it --rm wpscanteam/wpscan --url http://www.iessierradegador.com/  --enumerate p
Unable to find image 'wpscanteam/wpscan:latest' locally
latest: Pulling from wpscanteam/wpscan
801bfaa63ef2: Pull complete 
ba81004cc3f9: Pull complete 
b516164300bc: Pull complete 
d0535b286e7c: Pull complete 
dc21f12d6926: Pull complete 
d2ddb5959eb9: Pull complete 
185a843c8d22: Pull complete 
c203de95ec6f: Pull complete 
a4c7ba5887e8: Pull complete 
4f4fb700ef54: Pull complete 
a249900b799d: Pull complete 
Digest: sha256:1d4c161890d68024028bf0fdcadbc956ca83b9e8308552a7cb715750f6fbc352
Status: Downloaded newer image for wpscanteam/wpscan:latest
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

[+] URL: http://www.iessierradegador.com/ [149.202.128.251]
[+] Effective URL: https://www.iessierradegador.com/
[+] Started: Tue Jan 12 19:49:22 2021

Interesting Finding(s):

[+] Headers
 | Interesting Entries:
 |  - server: nginx
 |  - x-microcache: True
 | Found By: Headers (Passive Detection)
 | Confidence: 100%

[+] XML-RPC seems to be enabled: https://www.iessierradegador.com/xmlrpc.php
 | Found By: Link Tag (Passive Detection)
 | Confidence: 30%
 | References:
 |  - http://codex.wordpress.org/XML-RPC_Pingback_API
 |  - https://www.rapid7.com/db/modules/auxiliary/scanner/http/wordpress_ghost_scanner
 |  - https://www.rapid7.com/db/modules/auxiliary/dos/http/wordpress_xmlrpc_dos
 |  - https://www.rapid7.com/db/modules/auxiliary/scanner/http/wordpress_xmlrpc_login
 |  - https://www.rapid7.com/db/modules/auxiliary/scanner/http/wordpress_pingback_access

[+] WordPress version 5.6 identified (Latest, released on 2020-12-08).
 | Found By: Emoji Settings (Passive Detection)
 |  - https://www.iessierradegador.com/, Match: 'wp-includes\/js\/wp-emoji-release.min.js?ver=5.6'
 | Confirmed By: Meta Generator (Passive Detection)
 |  - https://www.iessierradegador.com/, Match: 'WordPress 5.6'

[+] WordPress theme in use: twentyeleven
 | Location: http://www.iessierradegador.com/wp-content/themes/twentyeleven/
 | Latest Version: 3.6
 | Last Updated: 2020-12-09T00:00:00.000Z
 | Style URL: https://www.iessierradegador.com/wp-content/themes/twentyeleven/style.css?ver=20190507
 |
 | Found By: Css Style In Homepage (Passive Detection)
 | Confirmed By: Css Style In 404 Page (Passive Detection)
 |
 | The version could not be determined.

[+] Enumerating Most Popular Plugins (via Passive Methods)
[+] Checking Plugin Versions (via Passive and Aggressive Methods)

[i] Plugin(s) Identified:

[+] advanced-post-slider
 | Location: http://www.iessierradegador.com/wp-content/plugins/advanced-post-slider/
 | Latest Version: 2.5.1
 | Last Updated: 2018-05-19T09:55:00.000Z
 |
 | Found By: Urls In Homepage (Passive Detection)
 | Confirmed By: Urls In 404 Page (Passive Detection)
 |
 | The version could not be determined.

[+] contact-form-7
 | Location: http://www.iessierradegador.com/wp-content/plugins/contact-form-7/
 | Latest Version: 5.3.2 (up to date)
 | Last Updated: 2020-12-17T11:42:00.000Z
 |
 | Found By: Urls In Homepage (Passive Detection)
 | Confirmed By: Urls In 404 Page (Passive Detection)
 |
 | Version: 5.3.2 (20% confidence)
 | Found By: Query Parameter (Passive Detection)
 |  - https://www.iessierradegador.com/wp-content/plugins/contact-form-7/includes/css/styles.css?ver=5.3.2
 |  - https://www.iessierradegador.com/wp-content/plugins/contact-form-7/includes/js/scripts.js?ver=5.3.2

[+] jetpack
 | Location: http://www.iessierradegador.com/wp-content/plugins/jetpack/
 | Latest Version: 9.2.1
 | Last Updated: 2020-12-10T14:14:00.000Z
 |
 | Found By: Urls In Homepage (Passive Detection)
 | Confirmed By: Urls In 404 Page (Passive Detection)
 |
 | The version could not be determined.

[!] No WPScan API Token given, as a result vulnerability data has not been output.
[!] You can get a free API token with 50 daily requests by registering at https://wpscan.com/register

[+] Finished: Tue Jan 12 19:55:33 2021
[+] Requests Done: 48
[+] Cached Requests: 3
[+] Data Sent: 16.105 KB
[+] Data Received: 249.526 KB
[+] Memory used: 246.117 MB
[+] Elapsed time: 00:06:10


Scan Aborted: The url supplied 'http://http//34.235.137.45/' seems to be down (Couldn't resolve host name)


 Resultado 2:

ubuntu@ip-172-31-90-230:~$ sudo docker run -it --rm wpscanteam/wpscan --url http://egosportcenter.com/  --api-token 7aUhTRe0G0WB5M0R7HZLJdY4Sg4EZN7ScIZU2b6hiDI
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

[+] URL: http://egosportcenter.com/ [51.77.242.168]
[+] Started: Tue Jan 12 20:25:17 2021

Interesting Finding(s):

[+] Headers
 | Interesting Entries:
 |  - Server: Apache
 |  - X-Powered-By: PHP/5.4.16, PleskLin
 |  - P3P: CP="ALL DSP NID CURa ADMa DEVa HISa OTPa OUR NOR NAV DEM"
 | Found By: Headers (Passive Detection)
 | Confidence: 100%

[+] robots.txt found: http://egosportcenter.com/robots.txt
 | Interesting Entries:
 |  - /wp-admin/
 |  - /wp-admin/admin-ajax.php
 | Found By: Robots Txt (Aggressive Detection)
 | Confidence: 100%

[+] XML-RPC seems to be enabled: http://egosportcenter.com/xmlrpc.php
 | Found By: Link Tag (Passive Detection)
 | Confidence: 100%
 | Confirmed By: Direct Access (Aggressive Detection), 100% confidence
 | References:
 |  - http://codex.wordpress.org/XML-RPC_Pingback_API
 |  - https://www.rapid7.com/db/modules/auxiliary/scanner/http/wordpress_ghost_scanner
 |  - https://www.rapid7.com/db/modules/auxiliary/dos/http/wordpress_xmlrpc_dos
 |  - https://www.rapid7.com/db/modules/auxiliary/scanner/http/wordpress_xmlrpc_login
 |  - https://www.rapid7.com/db/modules/auxiliary/scanner/http/wordpress_pingback_access

[+] WordPress readme found: http://egosportcenter.com/readme.html
 | Found By: Direct Access (Aggressive Detection)
 | Confidence: 100%

[+] The external WP-Cron seems to be enabled: http://egosportcenter.com/wp-cron.php
 | Found By: Direct Access (Aggressive Detection)
 | Confidence: 60%
 | References:
 |  - https://www.iplocation.net/defend-wordpress-from-ddos
 |  - https://github.com/wpscanteam/wpscan/issues/1299

[+] WordPress version 4.9.16 identified (Latest, released on 2020-10-29).
 | Found By: Rss Generator (Passive Detection)
 |  - http://egosportcenter.com/feed/, <generator>https://wordpress.org/?v=4.9.16</generator>
 |  - http://egosportcenter.com/comments/feed/, <generator>https://wordpress.org/?v=4.9.16</generator>

[+] WordPress theme in use: fitpress
 | Location: http://egosportcenter.com/wp-content/themes/fitpress/
 | Readme: http://egosportcenter.com/wp-content/themes/fitpress/readme.txt
 | Style URL: http://egosportcenter.com/wp-content/themes/fitpress/style.css?ver=1.0.0
 | Style Name: Fitpress
 | Style URI: http://www.templatemonster.com/wordpress-themes.php
 | Description: Fitpress - truely multipurpose WordPress theme for real life projects. Built with love and care by T...
 | Author: Template Monster
 | Author URI: http://www.templatemonster.com/
 |
 | Found By: Css Style In Homepage (Passive Detection)
 | Confirmed By: Css Style In 404 Page (Passive Detection)
 |
 | Version: 1.0.0 (80% confidence)
 | Found By: Style (Passive Detection)
 |  - http://egosportcenter.com/wp-content/themes/fitpress/style.css?ver=1.0.0, Match: 'Version: 1.0.0'

[+] Enumerating All Plugins (via Passive Methods)
[+] Checking Plugin Versions (via Passive and Aggressive Methods)

[i] Plugin(s) Identified:

[+] cherry-search
 | Location: http://egosportcenter.com/wp-content/plugins/cherry-search/
 | Last Updated: 2019-05-07T08:57:00.000Z
 | [!] The version is out of date, the latest version is 1.1.5
 |
 | Found By: Urls In Homepage (Passive Detection)
 | Confirmed By: Urls In 404 Page (Passive Detection)
 |
 | Version: 1.1.4 (100% confidence)
 | Found By: Readme - Stable Tag (Aggressive Detection)
 |  - http://egosportcenter.com/wp-content/plugins/cherry-search/readme.txt
 | Confirmed By: Readme - ChangeLog Section (Aggressive Detection)
 |  - http://egosportcenter.com/wp-content/plugins/cherry-search/readme.txt

[+] cherry-team-members
 | Location: http://egosportcenter.com/wp-content/plugins/cherry-team-members/
 | Last Updated: 2019-05-07T10:11:00.000Z
 | [!] The version is out of date, the latest version is 1.4.6
 |
 | Found By: Urls In Homepage (Passive Detection)
 | Confirmed By: Urls In 404 Page (Passive Detection)
 |
 | Version: 1.4.5 (80% confidence)
 | Found By: Readme - Stable Tag (Aggressive Detection)
 |  - http://egosportcenter.com/wp-content/plugins/cherry-team-members/readme.txt

[+] cherry-testi
 | Location: http://egosportcenter.com/wp-content/plugins/cherry-testi/
 | Last Updated: 2019-05-07T10:56:00.000Z
 | [!] The version is out of date, the latest version is 1.1.3
 |
 | Found By: Urls In Homepage (Passive Detection)
 | Confirmed By: Urls In 404 Page (Passive Detection)
 |
 | Version: 1.1.0.5 (90% confidence)
 | Found By: Query Parameter (Passive Detection)
 |  - http://egosportcenter.com/wp-content/plugins/cherry-testi/public/assets/css/style.css?ver=1.1.0.5
 | Confirmed By: Readme - Stable Tag (Aggressive Detection)
 |  - http://egosportcenter.com/wp-content/plugins/cherry-testi/readme.txt

[+] contact-form-7
 | Location: http://egosportcenter.com/wp-content/plugins/contact-form-7/
 | Last Updated: 2020-12-17T11:42:00.000Z
 | [!] The version is out of date, the latest version is 5.3.2
 |
 | Found By: Urls In Homepage (Passive Detection)
 | Confirmed By: Urls In 404 Page (Passive Detection)
 |
 | [!] 2 vulnerabilities identified:
 |
 | [!] Title: Contact Form 7 <= 5.0.3 - register_post_type() Privilege Escalation
 |     Fixed in: 5.0.4
 |     References:
 |      - https://wpscan.com/vulnerability/af945f64-9ce2-485c-bf36-c2ff59dc10d5
 |      - https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2018-20979
 |      - https://contactform7.com/2018/09/04/contact-form-7-504/
 |      - https://plugins.trac.wordpress.org/changeset/1935726/contact-form-7
 |      - https://plugins.trac.wordpress.org/changeset/1934594/contact-form-7
 |      - https://plugins.trac.wordpress.org/changeset/1934343/contact-form-7
 |      - https://plugins.trac.wordpress.org/changeset/1934327/contact-form-7
 |      - https://www.ripstech.com/php-security-calendar-2018/#day-18
 |
 | [!] Title: Contact Form 7 < 5.3.2 - Unrestricted File Upload
 |     Fixed in: 5.3.2
 |     References:
 |      - https://wpscan.com/vulnerability/7391118e-eef5-4ff8-a8ea-f6b65f442c63
 |      - https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2020-35489
 |      - https://www.getastra.com/blog/911/plugin-exploit/contact-form-7-unrestricted-file-upload-vulnerability/
 |      - https://www.jinsonvarghese.com/unrestricted-file-upload-in-contact-form-7/
 |      - https://contactform7.com/2020/12/17/contact-form-7-532/#more-38314
 |
 | Version: 5.0.3 (100% confidence)
 | Found By: Query Parameter (Passive Detection)
 |  - http://egosportcenter.com/wp-content/plugins/contact-form-7/includes/css/styles.css?ver=5.0.3
 |  - http://egosportcenter.com/wp-content/plugins/contact-form-7/includes/js/scripts.js?ver=5.0.3
 | Confirmed By:
 |  Readme - Stable Tag (Aggressive Detection)
 |   - http://egosportcenter.com/wp-content/plugins/contact-form-7/readme.txt
 |  Readme - ChangeLog Section (Aggressive Detection)
 |   - http://egosportcenter.com/wp-content/plugins/contact-form-7/readme.txt

[+] forget-about-shortcode-buttons
 | Location: http://egosportcenter.com/wp-content/plugins/forget-about-shortcode-buttons/
 | Latest Version: 2.1.2 (up to date)
 | Last Updated: 2020-09-28T07:30:00.000Z
 |
 | Found By: Urls In Homepage (Passive Detection)
 | Confirmed By: Urls In 404 Page (Passive Detection)
 |
 | Version: 2.1.2 (100% confidence)
 | Found By: Query Parameter (Passive Detection)
 |  - http://egosportcenter.com/wp-content/plugins/forget-about-shortcode-buttons/public/css/button-styles.css?ver=2.1.2
 | Confirmed By:
 |  Readme - Stable Tag (Aggressive Detection)
 |   - http://egosportcenter.com/wp-content/plugins/forget-about-shortcode-buttons/readme.txt
 |  Readme - ChangeLog Section (Aggressive Detection)
 |   - http://egosportcenter.com/wp-content/plugins/forget-about-shortcode-buttons/readme.txt

[+] moto-tools-integration
 | Location: http://egosportcenter.com/wp-content/plugins/moto-tools-integration/
 |
 | Found By: Urls In Homepage (Passive Detection)
 | Confirmed By: Urls In 404 Page (Passive Detection)
 |
 | The version could not be determined.

[+] motopress-content-editor
 | Location: http://egosportcenter.com/wp-content/plugins/motopress-content-editor/
 |
 | Found By: Urls In Homepage (Passive Detection)
 | Confirmed By: Urls In 404 Page (Passive Detection)
 |
 | Version: 2.4.0 (50% confidence)
 | Found By: Readme - ChangeLog Section (Aggressive Detection)
 |  - http://egosportcenter.com/wp-content/plugins/motopress-content-editor/readme.txt

[+] mp-timetable
 | Location: http://egosportcenter.com/wp-content/plugins/mp-timetable/
 | Last Updated: 2020-12-15T16:33:00.000Z
 | [!] The version is out of date, the latest version is 2.3.12
 |
 | Found By: Urls In Homepage (Passive Detection)
 | Confirmed By: Urls In 404 Page (Passive Detection)
 |
 | Version: 2.1.10 (60% confidence)
 | Found By: Query Parameter (Passive Detection)
 |  - http://egosportcenter.com/wp-content/plugins/mp-timetable/media/css/style.css?ver=2.1.10
 | Confirmed By: Readme - ChangeLog Section (Aggressive Detection)
 |  - http://egosportcenter.com/wp-content/plugins/mp-timetable/readme.txt

[+] power-builder
 | Location: http://egosportcenter.com/wp-content/plugins/power-builder/
 |
 | Found By: Urls In Homepage (Passive Detection)
 | Confirmed By: Urls In 404 Page (Passive Detection)
 |
 | The version could not be determined.

[+] uk-cookie-consent
 | Location: http://egosportcenter.com/wp-content/plugins/uk-cookie-consent/
 | Last Updated: 2019-10-31T13:38:00.000Z
 | [!] The version is out of date, the latest version is 2.3.15
 |
 | Found By: Urls In Homepage (Passive Detection)
 | Confirmed By: Urls In 404 Page (Passive Detection)
 |
 | Version: 2.3.11 (100% confidence)
 | Found By: Readme - Stable Tag (Aggressive Detection)
 |  - http://egosportcenter.com/wp-content/plugins/uk-cookie-consent/readme.txt
 | Confirmed By: Readme - ChangeLog Section (Aggressive Detection)
 |  - http://egosportcenter.com/wp-content/plugins/uk-cookie-consent/readme.txt

[+] Enumerating Config Backups (via Passive and Aggressive Methods)
 Checking Config Backups - Time: 00:00:05 <============================================================================================================================> (22 / 22) 100.00% Time: 00:00:05

[i] No Config Backups Found.

[+] WPScan DB API OK
 | Plan: free
 | Requests Done (during the scan): 12
 | Requests Remaining: 18

[+] Finished: Tue Jan 12 20:25:45 2021
[+] Requests Done: 93
[+] Cached Requests: 7
[+] Data Sent: 27.085 KB
[+] Data Received: 1.047 MB
[+] Memory used: 213.008 MB
[+] Elapsed time: 00:00:28
