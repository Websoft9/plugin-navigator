# Code onwer Guide

## Cockpit-plugin analysis

Some cockpit-plugin only have static web pages can work properly, but plugin-navigator requires system packages support for Linux OS. You can view specific dependency packages through the [mainfest.json](https://github.com/45Drives/cockpit-navigator/blob/main/manifest.json), example of how to install is as follows:

```
# Ubuntu
sudo apt install coreutils
# Centos
sudo yum install zip
```
