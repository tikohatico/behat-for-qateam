# behat-for-qateam
# Here we could be able to add our behat achievements

For setup the invironment:
1) Create folder where you can put you project
2) add in this folder composer.json file
3) install composer in this directory
curl -sS https://getcomposer.org/installer | php
php composer.phar install
4) change rights
sudo chmod 777 - R {youDirectoryname}
5) create feature folder with
behat --init
6) replace file FeatureContext.php in bootstrap directory with current one (which placed on this repo)
7) add current feature file in the features/ folder (which placed on this repo)
8) add current behat.yml file in the root folder (which placed on this repo)
9) download Selenium Standalone Server http://www.seleniumhq.org/download/ and move it into the project folder
10) run server from the folder where you placed it with 
java - jar selenium-server-standalone-2.**.**.jar (* here you should put actual numbers from current version of server)
11) run tests with
bin/behat
