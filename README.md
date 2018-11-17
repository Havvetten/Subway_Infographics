# Subway Infographics
Group 20 - School Project

## Installation
* Download Git
* Create github account

## Setting Up Git
```bash
git config --global user.name "YOUR GIT EMAIL"
git config --global user.email "YOUR GIT EMAIL"
```
## SSH Key Setup
Create new key `ssh-keygen -t rsa -b 4096 -C "YOUR GIT EMAIL"`

Start ssh-agent `eval "$(ssh-agent -s)"`

Add key to agent `ssh-add -K ~/.ssh/id_rsa`

Copy key for use in github repo `pbcopy < ~/.ssh/id_rsa.pub`

Finally, add key in github -> settings > SSH

## Repository Setup
Clone github repo to you computer (cd into your fav location) `git clone LINK TO GITHUB REPO`

Now, cd into the downloaded folder

Add main repo (upstream) to local repo for pull/push `git remote add upstream LINK TO GITHUB REPO`

ELEMENTS
Comming soon
