# Lab2cRobot-Beta
This repository is just for test
1. First download git bash
2. Config your github account and github email by
   git config --global user.name:yourusername
   git config --global user.email:youremail
   "--global" means this account will be used for all git repo on this computer. 
3. generate ssh key by
   cd ~/.ssh
   ssh-keygen -t rsa -C "your_email@example.com"
   I suggest you naming the file that restore the key as "id_rsa"
4. Try
   ssh git@github.com
   If you see "Hi yourname You've successfully authenticated, but GitHub does not provide shell access. ", 
   you are connected to Github now.
5. Use "git clone 'git@github:repositeryname' " to clone this repo to your laptop
   You can find relative link which should be in '' by clicking the button "clone or download". 
