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


