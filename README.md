![icon](https://raw.githubusercontent.com/stkim1/pocketcluster/master/images/icon_256x256.png)

# PocketCluster v0.1.3  

A one-step utility to setup a multi-nodes BigData cluster on OSX. 

> ## [Download Installer](https://github.com/stkim1/pocketcluster/raw/master/release/PocketCluster-0.1.3.dmg) 

### Current Packages Supported  

| Package  | Version | Release Note |
|:----------|:-------------:|:------:|
| Apache Spark | 1.5.2 | [RN 2.4.1](https://spark.apache.org/releases/spark-release-1-5-2.html) |
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

# Common Pre-requisites  

### Java  

- [Oracle Java 8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)  

### Homebrew  

- [Homebrew](http://brew.sh)  

## For Vagrant/VirtualBox Cluster   

- Install following two additional requirements.  
- **Mac with at least 8GB Memory and 10 GB of free disk space is strongly recommended.**  

### VirtualBox  

- [VirtualBox 5.0.10 for OS X hosts](http://download.virtualbox.org/virtualbox/5.0.10/VirtualBox-5.0.10-104061-OSX.dmg)

### Vagrant  

- [Vagrant 1.7.4 for OSX](https://releases.hashicorp.com/vagrant/1.7.4/vagrant_1.7.4.dmg)  

### Video Instruction    
[![Build Hadoop Cluster on Vagrant](http://img.youtube.com/vi/daNc14JL7as/0.jpg)](https://www.youtube.com/watch?v=daNc14JL7as&vq=hd720)  

## For Raspberry PI 2 Cluster  

- All Raspberry PI 2 and a Mac should be behind the same router.  
- Ethernet Connection required.  
- Must use the image provided below.  
- **YOU DO NOT NEED TO CONFIGURE A SINGLE THING FOR ALL RASPBERRY PIs!!!**  

### Rasperry PI 2 Ubuntu 14.04 Image
 
- [2015-11-13-ubuntu-trusty.img.zip (232 MB)](https://drive.google.com/open?id=0B2HeHl9cRYJHNUlQb1ZJMlJNYzA)   
- Checksum: 687a2e9b6c04f7a35449cc95405946e2  

### (Optional) ApplePi OSX Image Baker  

- [ApplePi-Baker 1.81] (http://www.tweaking4all.com/?wpfb_dl=94)

### Video Instruction   
[![Build Hadoop Cluster on Raspberry PI](http://img.youtube.com/vi/0TzPHj9C0Ak/0.jpg)](https://www.youtube.com/watch?v=0TzPHj9C0Ak&vq=hd720)  

## Updates & Questions  

You can follow how and what progresses are made at [https://pocketcluster.wordpress.com](https://pocketcluster.wordpress.com).  
If you have a question, tweet me [@stkim1](https://twitter.com/stkim1).  

PocketCluster is Copyright (C) 2015 Sung-Taek, Kim, All Rights Reserved.
