In this login have to install golang
#apt update
#wget -c https://dl.google.com/go/go1.14.2.linux-amd64.tar.gz -O - | sudo tar -xz -C /usr/local
#export PATH=$PATH:/usr/local/go/bin
# source ~/.profile
# go version
create a Directory and changing directory  
#mkdir go
#cd go
#mkdir src
#cd src
Pulling the code form repo
#git clone https://github.com/zelar-soft-todoapp/login.git
#ls
Changing to login 
#cd login
#export GOPATH=/go
#depmod
Installed the go-dep 
#apt install go-dep
#go get
#go build
./login
We need to update the IP address of Users Server in systemd.service file
vi /etc/systemd/system/login.service
#systemctl daemon-reload
#systemctl enable login
#systemctl restart login
#sysytemctl start login
#systemctl status login
