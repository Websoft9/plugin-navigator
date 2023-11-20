# Developer

## Modify source Code

Websoft9 don't maintain source code of Navicator, we just download and modify source code by action:

```
...
git clone https://github.com/45Drives/cockpit-navigator.git
mkdir navigator artifacts
sed -i '/logo-45d/c\                            <label id="logo-45d"/>' cockpit-navigator/navigator/index.html
```

## Depends on components at Server

Some cockpit-plugin only have static web pages can work properly, but plugin-navigator requires system packages support for Linux OS. You can view specific dependency packages through the [mainfest.json](https://github.com/45Drives/cockpit-navigator/blob/main/manifest.json), example of how to install is as follows:

```
# Ubuntu
sudo apt install coreutils
# Centos
sudo yum install zip
```