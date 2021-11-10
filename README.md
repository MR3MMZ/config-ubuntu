# config-ubuntu
<br>

> setup git
```
sudo apt install git -y && git version
git config --global user.name "your username"
git config --global user.email "your email"
git config --global user.password "your password"
git config --global credential.helper store
```
<br>

> setup golang
```
sudo apt install golang-go && go version
bash < <(curl -s -S -L https://raw.githubusercontent.com/moovweb/gvm/master/binscripts/gvm-installer)
source ~/.gvm/scripts/gvm
sudo apt install bison
sudo apt install make
gvm && gvm version
```

> setup node
```
sudo apt install nodejs && node --version
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.0/install.sh | bash
export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"  # This loads nvm
[ -s "$NVM_DIR/bash_completion" ] && \. "$NVM_DIR/bash_completion"  # This loads nvm bash_completion
nvm use v16.13.0 --default
nvm --version && node --version
```


