# behat-for-qateam
# Here we could be able to add our behat achievements

For setup the invironment:
* Create folder where you can put you project
* add in this folder composer.json file
* install composer in this directory
* curl -sS https://getcomposer.org/installer | php
* php composer.phar install
* change rights
* sudo chmod 777 - R {youDirectoryname}
* create feature folder with
* behat --init
* replace file FeatureContext.php in bootstrap directory with current one (which placed on this repo)
* add current feature file in the features/ folder (which placed on this repo)
* add current behat.yml file in the root folder (which placed on this repo)
* download Selenium Standalone Server http://www.seleniumhq.org/download/ and move it into the project folder
* run server from the folder where you placed it with
* java - jar selenium-server-standalone-2.**.**.jar (* here you should put actual numbers from current version of server)
* run tests with
* bin/behat
