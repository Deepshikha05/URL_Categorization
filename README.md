# URL_Categorization using LDA


# How to install Chrome Driver for Selenium in Ubuntu 18.04

1. sudo-apt get update
2. sudo apt-get install -y unzip xvfb libxi6 libgconf-2-4
3. sudo curl -sS -o - https://dl-ssl.google.com/linux/linux_signing_key.pub | apt-key add
4. sudo echo "deb [arch=amd64]  http://dl.google.com/linux/chrome/deb/ stable main" >> /etc/apt/sources.list.d/google-chrome.list
5. sudo apt-get -y update
6. sudo apt-get -y install google-chrome-stable

7. wget https://chromedriver.storage.googleapis.com/2.41/chromedriver_linux64.zip
8. unzip chromedriver_linux64.zip

9. sudo mv chromedriver /usr/bin/chromedriver
10. sudo chown root:root /usr/bin/chromedriver
11. sudo chmod +x /usr/bin/chromedriver

 