# **Synthetic Manglish Corpus of Customer Reviews from Amazon**

CSI Score for the synthetic Manglish reviews in native script: 0.9034212958294366

CSI Score for the Manglish reviews in transliterated form: 0.9007951219242283


### How to save large files in git

Follow the commands 

cd {filepath} eg:/home

sudo apt update

sudo apt install git

sudo apt install make libssl-dev libghc-zlib-dev libcurl4-gnutls-dev libexpat1-dev gettext unzip

curl -s https://packagecloud.io/install/repositories/github/git-lfs/script.deb.sh | sudo bash

sudo apt-get install git-lfs

git lfs install

git clone {gitrepo_url} 

cd reponame {Datasets}

git lfs track

git add {filename} eg:amazon_fullReviews.csv # COPY file amazon_fullReviews.csv in this folder

git config --global user.email "git mail id" 

git config --global user.name "git username"

git commit -m "Add csv file"

git config --global push.default simple

git push
#while entering password, give your Personal Access Token on GitHub

To Create Personal Access Token on GitHub

From your GitHub account, go to Settings => Developer Settings => Personal Access Token => Generate New Token (Give your password) => Fillup the form ( Check all requirements) => click Generate token => Copy the generated Token, it will be something like ghp_sFhFsSHhTzMDreGRLjmks4Tzuzgthdvfsrta.
use this token as the password in the git push command
