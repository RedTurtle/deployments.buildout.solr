# A Solr 4.6 buildout #

[![Build Status](https://travis-ci.org/RedTurtle/deployments.buildout.solr.png?branch=master)](https://travis-ci.org/RedTurtle/deployments.buildout.solr)

[TOC]

## Introduction ##
This is the a very basic buildout template to run solr.

## I am feeling lucky! ##
Lucky people read the documentation,
anyway if you have a local copy of this buildout,
try to run this command:
```bash
make
```
## For the impatients ##
To start the buildout:
```bash
python2.7 bootstrap.py &&  ./bin/buildout
```
To launch solr:
```bash
./bin/solr
```

## Requirements ##
You may want to install this to get this buildout working:
```bash
# python stuff
apt-get install python-dev python-virtualenv
# other stuff
apt-get install libpcre++-dev libreadline-dev
```
