
<!DOCTYPE html>
<!--==============================================================================
	           "GitHub HTML5 Pandoc Template" v1.2 — by Tristano Ajmone           
	==============================================================================
	(c) Tristano Ajmone, 2017, MIT License (MIT). Project's home repository:

	- https://github.com/tajmone/pandoc-goodies

	This template reuses source code taken from the following projects:

	- GitHub Markdown CSS: © Sindre Sorhus, MIT License (MIT):
	  https://github.com/sindresorhus/github-markdown-css

	- Primer CSS: © 2016 GitHub Inc., MIT License (MIT):
	  http://primercss.io/
	==============================================================================-->
<html lang="es">
<head>
  <meta charset="utf-8" />
  <meta name="generator" content="pandoc" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes" />
  <meta name="author" content="José Juan Sánchez Hernández" />
  <title>IAW - Práctica 11</title>
  <style type="text/css">@font-face{font-family:octicons-link;src:url(data:font/woff;charset=utf-8;base64,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) format('woff')}.markdown-body{-ms-text-size-adjust:100%;-webkit-text-size-adjust:100%;color:#24292e;font-family:-apple-system,system-ui,BlinkMacSystemFont,"Segoe UI",Helvetica,Arial,sans-serif,"Apple Color Emoji","Segoe UI Emoji","Segoe UI Symbol";font-size:16px;line-height:1.5;word-wrap:break-word;box-sizing:border-box;min-width:200px;max-width:980px;margin:0 auto;padding:45px}.markdown-body .octicon{display:inline-block;fill:currentColor;vertical-align:text-bottom}.markdown-body a{background-color:transparent;-webkit-text-decoration-skip:objects;color:#0366d6;text-decoration:none}.markdown-body a:active,.markdown-body a:hover{outline-width:0}.markdown-body h1{margin:.67em 0}.markdown-body img{border-style:none}.markdown-body svg:not(:root){overflow:hidden}.markdown-body code,.markdown-body kbd,.markdown-body pre{font-family:monospace,monospace}.markdown-body input{font:inherit;margin:0;overflow:visible;font-family:inherit;font-size:inherit;line-height:inherit}.markdown-body [type=checkbox]{box-sizing:border-box;padding:0}.markdown-body *{box-sizing:border-box}.markdown-body a:hover{text-decoration:underline}.markdown-body strong{font-weight:600}.markdown-body hr{box-sizing:content-box;overflow:hidden;background:0 0;border-bottom:1px solid #dfe2e5}.markdown-body hr::before{display:table;content:""}.markdown-body hr::after{display:table;clear:both;content:""}.markdown-body table{border-spacing:0;border-collapse:collapse;display:block;width:100%;overflow:auto}.markdown-body td,.markdown-body th{padding:0}.markdown-body blockquote{margin:0}.markdown-body ol ol,.markdown-body ul ol{list-style-type:lower-roman}.markdown-body ol ol ol,.markdown-body ol ul ol,.markdown-body ul ol ol,.markdown-body ul ul ol{list-style-type:lower-alpha}.markdown-body dd{margin-left:0}.markdown-body code{font-family:SFMono-Regular,Consolas,"Liberation Mono",Menlo,Courier,monospace}.markdown-body pre{font:12px SFMono-Regular,Consolas,"Liberation Mono",Menlo,Courier,monospace;word-wrap:normal}.markdown-body .pl-0{padding-left:0!important}.markdown-body .pl-1{padding-left:4px!important}.markdown-body .pl-2{padding-left:8px!important}.markdown-body .pl-3{padding-left:16px!important}.markdown-body .pl-4{padding-left:24px!important}.markdown-body .pl-5{padding-left:32px!important}.markdown-body .pl-6{padding-left:40px!important}.markdown-body::before{display:table;content:""}.markdown-body::after{display:table;clear:both;content:""}.markdown-body>:first-child{margin-top:0!important}.markdown-body>:last-child{margin-bottom:0!important}.markdown-body a:not([href]){color:inherit;text-decoration:none}.markdown-body .anchor{float:left;padding-right:4px;margin-left:-20px;line-height:1}.markdown-body .anchor:focus{outline:0}.markdown-body blockquote,.markdown-body dl,.markdown-body ol,.markdown-body p,.markdown-body pre,.markdown-body table,.markdown-body ul{margin-top:0;margin-bottom:16px}.markdown-body hr{height:.25em;padding:0;margin:24px 0;background-color:#e1e4e8;border:0}.markdown-body blockquote{padding:0 1em;color:#6a737d;border-left:.25em solid #dfe2e5}.markdown-body blockquote>:first-child{margin-top:0}.markdown-body blockquote>:last-child{margin-bottom:0}.markdown-body kbd{font-size:11px;box-shadow:inset 0 -1px 0 #959da5}.markdown-body h1,.markdown-body h2,.markdown-body h3,.markdown-body h4,.markdown-body h5,.markdown-body h6{margin-top:24px;margin-bottom:16px;font-weight:600;line-height:1.25}.markdown-body h1 .octicon-link,.markdown-body h2 .octicon-link,.markdown-body h3 .octicon-link,.markdown-body h4 .octicon-link,.markdown-body h5 .octicon-link,.markdown-body h6 .octicon-link{color:#1b1f23;vertical-align:middle;visibility:hidden}.markdown-body h1:hover .anchor,.markdown-body h2:hover .anchor,.markdown-body h3:hover .anchor,.markdown-body h4:hover .anchor,.markdown-body h5:hover .anchor,.markdown-body h6:hover .anchor{text-decoration:none}.markdown-body h1:hover .anchor .octicon-link,.markdown-body h2:hover .anchor .octicon-link,.markdown-body h3:hover .anchor .octicon-link,.markdown-body h4:hover .anchor .octicon-link,.markdown-body h5:hover .anchor .octicon-link,.markdown-body h6:hover .anchor .octicon-link{visibility:visible}.markdown-body h1{padding-bottom:.3em;font-size:2em;border-bottom:1px solid #eaecef}.markdown-body h2{padding-bottom:.3em;font-size:1.5em;border-bottom:1px solid #eaecef}.markdown-body h3{font-size:1.25em}.markdown-body h4{font-size:1em}.markdown-body h5{font-size:.875em}.markdown-body h6{font-size:.85em;color:#6a737d}.markdown-body ol,.markdown-body ul{padding-left:2em}.markdown-body ol ol,.markdown-body ol ul,.markdown-body ul ol,.markdown-body ul ul{margin-top:0;margin-bottom:0}.markdown-body li>p{margin-top:16px}.markdown-body li+li{margin-top:.25em}.markdown-body dl{padding:0}.markdown-body dl dt{padding:0;margin-top:16px;font-size:1em;font-style:italic;font-weight:600}.markdown-body dl dd{padding:0 16px;margin-bottom:16px}.markdown-body table th{font-weight:600}.markdown-body table td,.markdown-body table th{padding:6px 13px;border:1px solid #dfe2e5}.markdown-body table tr{background-color:#fff;border-top:1px solid #c6cbd1}.markdown-body table tr:nth-child(2n){background-color:#f6f8fa}.markdown-body img{max-width:100%;box-sizing:content-box;background-color:#fff}.markdown-body code{padding:.2em 0;margin:0;font-size:85%;background-color:rgba(27,31,35,.05);border-radius:3px}.markdown-body code::after,.markdown-body code::before{letter-spacing:-.2em;content:"\00a0"}.markdown-body pre>code{padding:0;margin:0;font-size:100%;word-break:normal;white-space:pre;background:0 0;border:0}.markdown-body .highlight{margin-bottom:16px}.markdown-body .highlight pre{margin-bottom:0;word-break:normal}.markdown-body .highlight pre,.markdown-body pre{padding:16px;overflow:auto;font-size:85%;line-height:1.45;background-color:#f6f8fa;border-radius:3px}.markdown-body pre code{display:inline;max-width:auto;padding:0;margin:0;overflow:visible;line-height:inherit;word-wrap:normal;background-color:transparent;border:0}.markdown-body pre code::after,.markdown-body pre code::before{content:normal}.markdown-body .full-commit .btn-outline:not(:disabled):hover{color:#005cc5;border-color:#005cc5}.markdown-body kbd{display:inline-block;padding:3px 5px;font:11px SFMono-Regular,Consolas,"Liberation Mono",Menlo,Courier,monospace;line-height:10px;color:#444d56;vertical-align:middle;background-color:#fcfcfc;border:1px solid #c6cbd1;border-bottom-color:#959da5;border-radius:3px;box-shadow:inset 0 -1px 0 #959da5}.markdown-body :checked+.radio-label{position:relative;z-index:1;border-color:#0366d6}.markdown-body .task-list-item{list-style-type:none}.markdown-body .task-list-item+.task-list-item{margin-top:3px}.markdown-body .task-list-item input{margin:0 .2em .25em -1.6em;vertical-align:middle}.markdown-body hr{border-bottom-color:#eee}.flash{position:relative;padding:16px;color:#246;background-color:#e2eef9;border:1px solid #bac6d3;border-radius:3px}.flash p:last-child{margin-bottom:0}.flash-messages{margin-bottom:24px}.flash-warn{color:#4c4a42;background-color:#fff9ea;border-color:#dfd8c2}.flash-error{color:#911;background-color:#fcdede;border-color:#d2b2b2}.flash-success{color:#22662c;background-color:#e2f9e5;border-color:#bad3be}.flash-plain{color:#4c4a42;background-color:#f5f5f5;border-color:#c1c1c1}</style>
  <style type="text/css">code{white-space: pre;}</style>
  <style type="text/css">img{display: block; margin-left: auto; margin-right: auto;}</style>
  <style type="text/css">
a.sourceLine { display: inline-block; line-height: 1.25; }
a.sourceLine { pointer-events: none; color: inherit; text-decoration: inherit; }
a.sourceLine:empty { height: 1.2em; }
.sourceCode { overflow: visible; }
code.sourceCode { white-space: pre; position: relative; }
div.sourceCode { margin: 1em 0; }
pre.sourceCode { margin: 0; }
@media screen {
div.sourceCode { overflow: auto; }
}
@media print {
code.sourceCode { white-space: pre-wrap; }
a.sourceLine { text-indent: -1em; padding-left: 1em; }
}
pre.numberSource a.sourceLine
  { position: relative; left: -4em; }
pre.numberSource a.sourceLine::before
  { content: attr(title);
    position: relative; left: -1em; text-align: right; vertical-align: baseline;
    border: none; pointer-events: all; display: inline-block;
    -webkit-touch-callout: none; -webkit-user-select: none;
    -khtml-user-select: none; -moz-user-select: none;
    -ms-user-select: none; user-select: none;
    padding: 0 4px; width: 4em;
    color: #aaaaaa;
  }
pre.numberSource { margin-left: 3em; border-left: 1px solid #aaaaaa;  padding-left: 4px; }
div.sourceCode
  {  }
@media screen {
a.sourceLine::before { text-decoration: underline; }
}
code span.al { color: #ff0000; font-weight: bold; } /* Alert */
code span.an { color: #60a0b0; font-weight: bold; font-style: italic; } /* Annotation */
code span.at { color: #7d9029; } /* Attribute */
code span.bn { color: #40a070; } /* BaseN */
code span.bu { } /* BuiltIn */
code span.cf { color: #007020; font-weight: bold; } /* ControlFlow */
code span.ch { color: #4070a0; } /* Char */
code span.cn { color: #880000; } /* Constant */
code span.co { color: #60a0b0; font-style: italic; } /* Comment */
code span.cv { color: #60a0b0; font-weight: bold; font-style: italic; } /* CommentVar */
code span.do { color: #ba2121; font-style: italic; } /* Documentation */
code span.dt { color: #902000; } /* DataType */
code span.dv { color: #40a070; } /* DecVal */
code span.er { color: #ff0000; font-weight: bold; } /* Error */
code span.ex { } /* Extension */
code span.fl { color: #40a070; } /* Float */
code span.fu { color: #06287e; } /* Function */
code span.im { } /* Import */
code span.in { color: #60a0b0; font-weight: bold; font-style: italic; } /* Information */
code span.kw { color: #007020; font-weight: bold; } /* Keyword */
code span.op { color: #666666; } /* Operator */
code span.ot { color: #007020; } /* Other */
code span.pp { color: #bc7a00; } /* Preprocessor */
code span.sc { color: #4070a0; } /* SpecialChar */
code span.ss { color: #bb6688; } /* SpecialString */
code span.st { color: #4070a0; } /* String */
code span.va { color: #19177c; } /* Variable */
code span.vs { color: #4070a0; } /* VerbatimString */
code span.wa { color: #60a0b0; font-weight: bold; font-style: italic; } /* Warning */
  </style>
  <!--[if lt IE 9]>
    <script src="//cdnjs.cloudflare.com/ajax/libs/html5shiv/3.7.3/html5shiv-printshiv.min.js"></script>
  <![endif]-->
</head>
<body>
<article class="markdown-body">
<header>
<h1 class="title">IAW - Práctica 11</h1>
<p class="author">José Juan Sánchez Hernández</p>
<p class="date">IES Celia Viñas (Almería) - 2020/2021</p>
</header>
<nav id="TOC">
<ul>
<li><a href="#práctica-11-auditoría-de-seguridad-en-wordpress"><span class="toc-section-number">1</span> Práctica 11: Auditoría de seguridad en WordPress</a><ul>
<li><a href="#wpscan"><span class="toc-section-number">1.1</span> WPScan</a></li>
<li><a href="#ejemplo-básico-de-uso"><span class="toc-section-number">1.2</span> Ejemplo básico de uso</a></li>
<li><a href="#contenedor-docker-con-wpscan"><span class="toc-section-number">1.3</span> Contenedor Docker con WPScan</a></li>
<li><a href="#seguridad-en-wordpress"><span class="toc-section-number">1.4</span> Seguridad en WordPress</a></li>
</ul></li>
<li><a href="#referencias"><span class="toc-section-number">2</span> Referencias</a></li>
<li><a href="#licencia"><span class="toc-section-number">3</span> Licencia</a></li>
</ul>
</nav>

<h1 id="práctica-11-auditoría-de-seguridad-en-wordpress"><span class="header-section-number">1</span> Práctica 11: Auditoría de seguridad en WordPress</h1>
<p>En esta práctica vamos a realizar una auditoría de seguridad sobre nuestra instalación de <a href="https://wordpress.org">WordPress</a> con la que hemos estado trabajando en las prácticas anteriores.</p>
<h2 id="wpscan"><span class="header-section-number">1.1</span> WPScan</h2>
<p>La herramienta que vamos a utilizar para realizar la auditoría de nuestro sitio web <a href="https://wordpress.org">WordPress</a> es <a href="https://wpscan.org"><code>wpscan</code></a>.</p>
<p>Si ejecutamos <code>wpscan --help</code> podemos ver todas las opciones que podemos realizar con <a href="https://wpscan.org"><code>wpscan</code></a>.</p>
<pre><code># wpscan  --help
_______________________________________________________________
        __          _______   _____
        \ \        / /  __ \ / ____|
         \ \  /\  / /| |__) | (___   ___  __ _ _ __
          \ \/  \/ / |  ___/ \___ \ / __|/ _` | &#39;_ \
           \  /\  /  | |     ____) | (__| (_| | | | |
            \/  \/   |_|    |_____/ \___|\__,_|_| |_|

        WordPress Security Scanner by the WPScan Team
                       Version 2.6
          Sponsored by Sucuri - https://sucuri.net
   @_WPScan_, @ethicalhack3r, @erwan_lr, pvdl, @_FireFart_
_______________________________________________________________

Help :

Some values are settable in a config file, see the example.conf.json

--update                            Update to the database to the latest version.
--url       | -u &lt;target url&gt;       The WordPress URL/domain to scan.
--force     | -f                    Forces WPScan to not check if the remote site is running WordPress.
--enumerate | -e [option(s)]        Enumeration.
  option :
    u        usernames from id 1 to 10
    u[10-20] usernames from id 10 to 20 (you must write [] chars)
    p        plugins
    vp       only vulnerable plugins
    ap       all plugins (can take a long time)
    tt       timthumbs
    t        themes
    vt       only vulnerable themes
    at       all themes (can take a long time)
  Multiple values are allowed : &quot;-e tt,p&quot; will enumerate timthumbs and plugins
  If no option is supplied, the default is &quot;vt,tt,u,vp&quot;

--exclude-content-based &quot;&lt;regexp or string&gt;&quot;
                                    Used with the enumeration option, will exclude all occurrences based on the regexp or string supplied.
                                    You do not need to provide the regexp delimiters, but you must write the quotes (simple or double).
--config-file  | -c &lt;config file&gt;   Use the specified config file, see the example.conf.json.
--user-agent   | -a &lt;User-Agent&gt;    Use the specified User-Agent.
--cookie &lt;String&gt;                   String to read cookies from.
--random-agent | -r                 Use a random User-Agent.
--follow-redirection                If the target url has a redirection, it will be followed without asking if you wanted to do so or not
--batch                             Never ask for user input, use the default behaviour.
--no-color                          Do not use colors in the output.
--wp-content-dir &lt;wp content dir&gt;   WPScan try to find the content directory (ie wp-content) by scanning the index page, however you can specified it.
                                    Subdirectories are allowed.
--wp-plugins-dir &lt;wp plugins dir&gt;   Same thing than --wp-content-dir but for the plugins directory.
                                    If not supplied, WPScan will use wp-content-dir/plugins. Subdirectories are allowed
--proxy &lt;[protocol://]host:port&gt;    Supply a proxy. HTTP, SOCKS4 SOCKS4A and SOCKS5 are supported.
                                    If no protocol is given (format host:port), HTTP will be used.
--proxy-auth &lt;username:password&gt;    Supply the proxy login credentials.
--basic-auth &lt;username:password&gt;    Set the HTTP Basic authentication.
--wordlist | -w &lt;wordlist&gt;          Supply a wordlist for the password brute forcer.
--username | -U &lt;username&gt;          Only brute force the supplied username.
--usernames     &lt;path-to-file&gt;      Only brute force the usernames from the file.
--threads  | -t &lt;number of threads&gt; The number of threads to use when multi-threading requests.
--cache-ttl       &lt;cache-ttl&gt;       Typhoeus cache TTL.
--request-timeout &lt;request-timeout&gt; Request Timeout.
--connect-timeout &lt;connect-timeout&gt; Connect Timeout.
--max-threads     &lt;max-threads&gt;     Maximum Threads.
--help     | -h                     This help screen.
--verbose  | -v                     Verbose output.
--version                           Output the current version and exit.


Examples :

-Further help ...
ruby ./wpscan.rb --help

-Do &#39;non-intrusive&#39; checks ...
ruby ./wpscan.rb --url www.example.com

-Do wordlist password brute force on enumerated users using 50 threads ...
ruby ./wpscan.rb --url www.example.com --wordlist darkc0de.lst --threads 50

-Do wordlist password brute force on the &#39;admin&#39; username only ...
ruby ./wpscan.rb --url www.example.com --wordlist darkc0de.lst --username admin

-Enumerate installed plugins ...
ruby ./wpscan.rb --url www.example.com --enumerate p

-Enumerate installed themes ...
ruby ./wpscan.rb --url www.example.com --enumerate t

-Enumerate users ...
ruby ./wpscan.rb --url www.example.com --enumerate u

-Enumerate installed timthumbs ...
ruby ./wpscan.rb --url www.example.com --enumerate tt

-Use a HTTP proxy ...
ruby ./wpscan.rb --url www.example.com --proxy 127.0.0.1:8118

-Use a SOCKS5 proxy ... (cURL &gt;= v7.21.7 needed)
ruby ./wpscan.rb --url www.example.com --proxy socks5://127.0.0.1:9000

-Use custom content directory ...
ruby ./wpscan.rb -u www.example.com --wp-content-dir custom-content

-Use custom plugins directory ...
ruby ./wpscan.rb -u www.example.com --wp-plugins-dir wp-content/custom-plugins

-Update the DB ...
ruby ./wpscan.rb --update

-Debug output ...
ruby ./wpscan.rb --url www.example.com --debug-output 2&gt;debug.log

See README for further information.</code></pre>
<h2 id="ejemplo-básico-de-uso"><span class="header-section-number">1.2</span> Ejemplo básico de uso</h2>
<p>Para obtener la lista de <em>plugins</em> instalados en nuestro sitio WordPress podemos ejecutar:</p>
<div class="sourceCode" id="cb2"><pre class="sourceCode bash"><code class="sourceCode bash"><a class="sourceLine" id="cb2-1" title="1"><span class="ex">wpscan</span> --url http://192.168.22.20 --enumerate p</a></code></pre></div>
<p>Donde <strong>192.168.22.20</strong> será la dirección IP de nuestro balanceador web.</p>
</body>
</html>
 <title>Resultado 1:</title>

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


 <title>Resultado 2:</title>

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
