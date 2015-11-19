![icon](https://raw.githubusercontent.com/stkim1/pocketcluster/master/images/icon_256x256.png)

# One-Step Spark/Hadoop Installer v0.1.2  

A one-step utility to setup single-node pseudo-distributed Spark/Hadoop cluster on OSX. 

> ### [Download Installer](https://github.com/stkim1/pocketcluster/raw/master/release/PocketCluster-0.1.2.dmg) 

### Current Packages Supported  

| Package  | Version | Release Note |
|:----------|:-------------:|:------:|
| Apache Hadoop | 2.4.0 | [RN 2.4.1](http://hadoop.apache.org/docs/r2.4.1/hadoop-project-dist/hadoop-common/releasenotes.html) |

# Supported Platform

### OSX El Capitan  

This installer has only been tested on El Capitan. May work fine on Yosemite 10.10.  

- [El Capitan](https://itunes.apple.com/WebObjects/MZStore.woa/wa/viewSoftware?id=1018109117&mt=12&ls=1)  

## System Setup  

In order for Spark/Hadoop to work, you need to open SSH server just for yourself.  

![](https://raw.githubusercontent.com/stkim1/pocketcluster/master/images/system-setup.png)

1. Open **"System Preference"**  
2. Open **"Sharing"**  
3. Check **"Remote Login"** for **"Administators"** only.  

# Pre-requisites

### 1. Java  

Please use Java 8. More and more Apache projects drop supporting for old Java version.  

- [Oracle Java 8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)   

### 2. Homebrew

HomeBrew is required to install dependent library.

- [Homebrew](http://brew.sh)  

## For Vagrant/VirtualBox Cluster
### 1. VirtualBox   

If you're to go with Vagrant version, please install VirtualBox first. If possible, please use the lastest version.  

- [VirtualBox 5.0.10 for OS X hosts](http://download.virtualbox.org/virtualbox/5.0.10/VirtualBox-5.0.10-104061-OSX.dmg)

### 2. Vagrant  

Finally, Vagrant. Please use the lastest version.

- [Vagrant 1.7.4 for OSX](https://releases.hashicorp.com/vagrant/1.7.4/vagrant_1.7.4.dmg)  

## Raspberry PI 2 Cluster  

### Rasperry PI 2 Image
Should you brave Raspberry PI 2, here's an image you are asked to use.  
 
- [2015-11-13-ubuntu-trusty.img.zip (232 MB)](https://drive.google.com/open?id=0B2HeHl9cRYJHNUlQb1ZJMlJNYzA)   
- MD5 : 687a2e9b6c04f7a35449cc95405946e2  

### (Optional) Image Baker  
You can certainly use Diskutil or dd. Nonetheless, here's a great tool for baking Raspberry PI images.

- [ApplePi-Baker 1.81] (http://www.tweaking4all.com/?wpfb_dl=94)


## F.A.Q  

If you have a question, leave it to my [blog post](https://pocketcluster.wordpress.com/2015/07/15/one-step-sparkhadoop-installer-for-osx-v0-1-0/) or [tweet me](https://twitter.com/stkim1).  
