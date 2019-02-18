# go-tut

Download pkg from go site and install : https://golang.org/doc/install?download=go1.11.5.darwin-amd64.pkg

add the following to bash_profile as env settings for go installation
export GOROOT=$HOME/go
export GOBIN=$GOROOT/bin
export PATH=$PATH:$GOROOT/bin

create ~/home/mygo with folowing dir structure
├── mygo
│   ├── bin
│   ├── pkg
│   └── src

add this to bash_profile as a workspace indicator
export GOPATH=${HOME}/mygo
