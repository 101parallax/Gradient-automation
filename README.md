# GRADIENT AUTOMATION BOT
This script use Selenium to automate web interaction with ot without rotating proxies to avoiud detection. In my experience running a bot that uses Selenium and Chrome, it has a significant impact on the CPU, and the memory usage increases drastically. If you're using a VPS, I recommend using a VPS with 8 cores or running the bot locally on a laptop or PC.

## Sign UP
Register [HERE](https://app.gradient.network/signup?code=4E5B7E)

## Installing Chrome and ChromeDriver on linux
## If you are new using ubuntu or have error when run the scrypt. You must read this carefully
1. Install ChromeDriver: Use the following commands to download and install ChromeDriver
```
sudo apt install chromedriver
```
or
```
sudo snap install chromedriver
```
2. check chromedriver version, it should be 113.xxx.xxx or 114.xxx.xxx version. This is the latest version of chromedriver
```
chromedriver --version
```
3. check chromium version
```
chromium --version
```
4. if you use ubuntu latest version, chromium version should be 140.xxx.xxx or 130.xxx.xxx
```
chromium --version
```
### 5. if your chromium version is upper then the version of chromedriver, you have to uninstall it and install chromium lower version. same version with chromedriver version. if you use 114 version just install chromium 114 version, if you use chromedriver 113, just install chromium 113 version
6. uninstall chromium
```
sudo apt remove --purge chromium -y
```
or
```
sudo snap uninstall chromium -y
```
7. Find and Download chromium version that matches with your chromedriver [HERE](https://github.com/RobRich999/Chromium_Clang/releases)
```
wget https://github.com/RobRich999/Chromium_Clang/releases/download/v114.0.5728.0-r1134209-linux64-deb-avx/chromium-browser-unstable_114.0.5728.0-1_amd64.deb
```
8. Install that .deb file
```
sudo dpkg -i chromium-browser-unstable_114.0.5728.0-1_amd64.deb
```
### Now you are all set
## RUN THE BOT
1. clone the repo
```
git clone https://github.com/101parallax/Gradient-automation.git
```
2. install dependencies
```
pip3 install -r requirement.txt
```
3. Edit .env.example file
```
nano .env.example
```
```
APP_USER=your_gradinet_email@example.com
APP_PASS=your_gradinet_password
```
4. save or copy that file to ```.env```
5. python3 gradient.py
## The Password was [HERE](https://t.me/+3NQanL5EQ2VkMDBl) 
