# How to Run on Local 📖


### Live Site --> <a href="http://micro.epizy.com" target="_blank">Click Here</a>

- Must install PHP version (FOR WINDOWS) & (FOR MAC) Both
- Tutorial - https://www.youtube.com/watch?v=mVBe75aGBHQ


- Must install xampp (FOR WINDOWS) & MAMP (FOR MAC) 
- Tutorial - https://www.youtube.com/watch?v=at19OmH2Bg4

-------*---------*----------

Step -1   Download zip file 

Step -2   unzip it 

Step -3   Put ls folder inside 

          /Applications/MAMP/htdocs/  folder  (FOR MAC)
          C:/xampp/htdocs/            folder  (FOR WINDOWS)

Step -4   Change in /Applications/MAMP/htdocs/gForm/environment.php. file (FOR MAC)
          
            <?php
               $env_server = "localhost";
               $env_username = "root";
               $env_password = "root";
               $env_database = "url";
               $env_port = "8889";
            ?>

Step -4   Change in htdocs/gForm/environment.php. file (FOR WINDOWS )
          
            <?php
              $env_server = "localhost:3306";
              $env_username = "root";
              $env_password = "";
              $env_database = "url";
              $env_port = "3306";
            ?>

Step -5   Setup db open 

          localhost:8888/phpmyadmin/   (FOR MAC)
          localhost/phpmyadmin/        (FOR WINDOWS)

Step -6   Create database 

Step -7   Database name  "url"

Step -8   Add Three tables from "/" directory in database name "dB2". 

              1) link.sql
              2) users.sql


Step -9   Run in Browser 

          localhost:8888/ls/     (FOR MAC)
          localhost/ls/          (FOR WINDOWS)


