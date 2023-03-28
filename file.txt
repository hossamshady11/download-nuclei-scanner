here how to download nuclei scanner in linux 

first install golang 
#apt install golang
#export GOROOT=/usr/local/go
#export GOPATH=$HOME/go
#export PATH=$GOPATH/bin:$GOROOT/bin:$HOME/.local/bin:$PATH
git clone https://github.com/projectdiscovery/nuclei.git;
cd nuclei/v2/cmd/nuclei;
go build;
mv nuclei /usr/local/bin/;
nuclei -version;
go env GOPATH
install gobuster 
## git cloen https://github.com/OJ/gobuster.git
## cd gobuster 
## sudo su
## go build;
## mv gobuster /usr/local/bin/;
## gobuster --version

>> addition if you can't download go language 
sudo rm -rf /usr/local/go #decompressing to /usr/local
sudo tar -C /usr/local -xzf go1.16.5.linux-amd64.tar.gz#add variables to .bashrc echo 'export GOROOT=/usr/local/go' >> ~/.bashrc
echo 'export GOPATH=$HOME/go' >> ~/.bashrc
echo 'export PATH=$GOPATH/bin:$GOROOT/bin:$HOME/.local/bin:$PATH' >> ~/.bashrc #reload .bashrc
source ~/.bashrc#check version
go versiongo1.16.5 

The new http://cs.github.com search allows for regex, which means brand **new** regex GitHub Dorks are possible! 

Eg, find SSH and FTP passwords via connection strings with:
/ssh:\/\/.*:.*@.*target\.com/ 
/ftp:\/\/.*:.*@.*target\.com/ 

