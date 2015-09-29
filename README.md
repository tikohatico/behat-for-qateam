# behat-for-qateam
# Here we could be able to add our behat achievements

For setup the invironment: \n
1) Create folder where you can put you project \n
2) add in this folder composer.json file \n
3) install composer in this directory \n
curl -sS https://getcomposer.org/installer | php \n
php composer.phar install \n
4) change rights \n
sudo chmod 777 - R {youDirectoryname} \n
5) create feature folder with \n
behat --init \n
6) replace file FeatureContext.php in bootstrap directory with current one (which placed on this repo) \n
7) add current feature file in the features/ folder (which placed on this repo) \n
8) add current behat.yml file in the root folder (which placed on this repo) \n
9) download Selenium Standalone Server http://www.seleniumhq.org/download/ and move it into the project folder \n
10) run server from the folder where you placed it with  \n
java - jar selenium-server-standalone-2.**.**.jar (* here you should put actual numbers from current version of server) \n
11) run tests with \n
bin/behat \n
