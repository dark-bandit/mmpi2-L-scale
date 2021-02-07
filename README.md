# mmpi2-L-scale
This is a PHP version of the uncommon virtues "L" Scale from the Minnesota Multiphasic Personality Inventory Second Edition (MMPI-2) for purposes of conducting research utilizing the L-scale from the MMPI-2.

System Requirements:
Linux OS with preinstalled LAMP server. 
PHP 5.x. The php script(s) were not tested with, may not work with versions before or after PHP5x.

Instructions for deployment: 

1. Enable mod_rewrite and mod_headers within Apache server. 

2. Replace or add apache2.conf and ports.conf files in the appropriate directories for your system.

3. place l.html and score.php in the root directory of your Apache server. 

4. you may rename l.html to any name. This is the file users will access to take the test.

5. To take the test open a browser and navigate to one of the following, where www.example.com is your external
domain name and foo.html is the name of the l.html file if you've renamed it:
http://localhost/foo.html
http://www.example.com/foo.html

6. If you desire to save test results, you may add your SQL database code to store the results  at the appropriate place
in the score.php file. 

7. users should now be able to take the test. 
