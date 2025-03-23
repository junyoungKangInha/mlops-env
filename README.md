# mlops-env

# wsl reset 

wsl --unregister Ubuntu-20.04

wsl --shutdown

wsl --unregister docker-desktop

wsl --unregister docker-desktop-data

wsl --set-default-version 2

wsl --install -d Ubuntu-20.04

# git 기본설정
sudo apt update && sudo apt install -y git

git config --global user.name "name"

git config --global user.email "email_addr"

git config --global --list
