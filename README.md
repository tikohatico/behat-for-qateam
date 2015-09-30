# behat-for-qateam
# Here we could be able to add our behat achievements

For setup the invironment:
* Create folder where you can put you project
* add in this folder composer.json file
* install composer in this directory:
> <code>curl -sS https://getcomposer.org/installer | php</code>
> <code>php composer.phar install</code>
* change rights for the folder:
> <code>sudo chmod 777 - R {youDirectoryname}</code>
* create feature folder with this command:
> <code>behat --init</code>
* replace file FeatureContext.php in bootstrap directory with current one (which placed on this repo)
* add current feature file in the features/ folder (which placed on this repo)
* add current behat.yml file in the root folder (which placed on this repo)
* download Selenium Standalone Server http://www.seleniumhq.org/download/ and move it into the project folder
* run server from the folder where you placed it with this command:
> <code>java - jar selenium-server-standalone-2.**.**.jar</code> (* here you should put actual numbers from current version of server)
* run tests with this command:
> <code>bin/behat</code>
