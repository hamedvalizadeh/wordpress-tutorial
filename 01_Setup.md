# Installing WordPress

1. download and install ((Visual C++ Redistributable Visual Studio 2015-2022))form ((https://aka.ms/vs/17/release/VC_redist.x86.exe)).
2. download and install wamp server.
   1. before starting installation, be sure that port 80 is free. 
   2. after installation finished, open wampserver app, and wait until the wampserver starts completely, and it's color in app tray of windows change to green.
   3. now you can browse to index page of wamp server by navigating to address ((http://localhost/)).
3. navigate to admin panel of wampserver by typing ((http://localhost/phpmyadmin/)) in browser, or clicking on windows app tray and click on wampserver icon, and selecting ((phpMyAdmin)) item.
4. login to ((phpMyAdmin)), with ((root)) as username and no password.
5. in admin panel create a new database; as an example name it ((wptestdb)).
6. download the latest wordpress zip file from ((https://wordpress.org/download/)).
7. extract the zip file to the ((www)) folder of wampserver root path. for example ((C:\wamp64\www)); you can rename the new extracted folder to what-ever you desire, for instance ((wordpress_test)).
8. navigate to ((http://localhost/wordpress_test)) in your browser; it will guide you through your wordpress admin panel installation steps.
   1. in database selection step, enter the name of database as ((wptestdb)) and enter ((root)) for database user, and no pass.
   2. in user name creation step you can choose what-ever you want, for example ((wptest)) with password ((123)).
   3. after finishing installation you can navigate to address ((http://localhost/wordpress_test/wp-login.php)) in your browser to open your new installed wordpress  admin panel. you should use the authentication info of user ((wptest)) in order to login.
   4. your wordpress site address would be ((http://localhost/wordpress_test))