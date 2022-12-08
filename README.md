# How to Install Github Desktop for Ubuntu 22.04 LTS

GitHub Desktop is an application that enables you to interact with GitHub using a GUI instead of the command line or a web browser. GitHub Desktop encourages you and your team to collaborate using best practices with Git and GitHub. You can use GitHub Desktop to complete most Git commands from your desktop with visual confirmation of changes. You can push to, pull from, and clone remote repositories with GitHub Desktop, and use collaborative tools such as attributing commits and creating pull requests.

This is how I installed the Github Desktop for Ubuntu 22.04LTS

#1.Terminal Command 
sudo apt-get install gdebi-core

#2.Provide Sudo password for user

#3. Terminal Command
wget https://github.com/shiftkey/desktop/releases/download/release-2.9.3-linux3/GitHubDesktop-linux-2.9.3-linux3.deb && sudo dpkg -i GitHubDesktop-linux-2.9.3-linux3.deb

#4.To open github desktop Command
github
