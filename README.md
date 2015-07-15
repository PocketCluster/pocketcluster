![icon](https://raw.githubusercontent.com/stkim1/pocketcluster/master/images/icon_256x256.png)

# One-Step Spark/Hadoop Installer  
-

A small utility to setup a laptop/desktop for single-node pseudo-distributed Spark/Hadoop cluster in one-step. This version installs **Spark 1.4.0** and **Hadoop 2.4.0**.

## Pre-requisites  

### 1. OSX Yosemite  

This installer has only been tested on Yosemite 10.10. May work fine on El Capitan.  

- [OSX Yosemite](https://itunes.apple.com/WebObjects/MZStore.woa/wa/viewSoftware?id=915041082&mt=12&ls=1)

### 2. Java  

You have two choices. Either one works just fine.  

- [Oracle Java 8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)  
- [Apple Java 6 2015-001](https://support.apple.com/kb/DL1824?locale=en_US)

### 3. R (Optional)  

Spark 1.4.0 comes with SparkR. In case you'd like to delve into it, install R.  

- [R 3.2.1](http://cran.r-project.org/bin/macosx/R-3.2.1.pkg)


## System Setup  

In order for Spark/Hadoop to work in pseudo-distributed mode, you need to open SSH server just for yourself.  

![](https://raw.githubusercontent.com/stkim1/pocketcluster/master/images/system-setup.png)

1. Open **"System Preference"**  
2. Open **"Sharing"**  
3. Check **"Remote Login"** for **"Administators"** only.  

## Install  

### Download installer from [here](https://github.com/stkim1/pocketcluster/raw/master/release/PocketCluster-OSX-0.1.0.zip)

![](https://raw.githubusercontent.com/stkim1/pocketcluster/master/images/install-0.png)  
![]()  

1. Unzip & execute installer.  
2. Select **"Install Package"** from menu & click **"Install"** button.  
3. Once completed, open **"Terminal"** or **"iTerm"**  
4. To start, type ```start-service.sh```  
5. To stop, type ```stop-service.sh```  


## F.A.Q  
