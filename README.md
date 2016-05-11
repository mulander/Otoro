# Otoro
fat tuna in the OpenBSD ports fish-tank

[oh-toh-roh](http://www.sushifaq.com/sushi-sashimi-info/sushi-terminology/) stands for the fattest portion of the tuna, found on the underside of the fish.
This talk will cover Otoro in the OpenBSD ports infrastructure. Building blocks of the ports infrastructure
both technical and cultural.

This talk is planned for [pkgsrcCon 2016](pkgsrc.org/pkgsrcCon/2016/)

## Setup

The go present tool is used to deliver the slides. You can install it on an OpenBSD near you with the following commands: 

```shell
doas pkg_add go
export GOPATH=$HOME/go
export PATH=$PATH:$GOPATH/bin
go install golang.org/x/tools/cmd/present
```
