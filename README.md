![icon](https://raw.githubusercontent.com/stkim1/pocketcluster/master/images/icon_256x256.png)

# One-Step Spark/Hadoop Installer v0.1.1  

A one-step utility to setup single-node pseudo-distributed Spark/Hadoop cluster on OSX. 

> ### [Download Installer](https://github.com/stkim1/pocketcluster/raw/master/release/PocketCluster-OSX-0.1.1.zip) 

### Current Packages Supported  

| Package  | Version | Release Note |
|:----------|:-------------:|:------:|
| Apache Spark | 1.4.1 | [RN 1.4.1](http://spark.apache.org/releases/spark-release-1-4-1.html) |
| Apache Hadoop | 2.4.0 | [RN 2.4.1](http://hadoop.apache.org/docs/r2.4.1/hadoop-project-dist/hadoop-common/releasenotes.html) |

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

### [Download installer](https://github.com/stkim1/pocketcluster/raw/master/release/PocketCluster-OSX-0.1.0.zip)

1. Unzip & execute installer.  
2. Select **"Install Package"** from menu.  
![](https://raw.githubusercontent.com/stkim1/pocketcluster/master/images/install-010-0.png)  

3. Click **"Install"** button.  
![](https://raw.githubusercontent.com/stkim1/pocketcluster/master/images/install-010-1.png)  

3. Once completed, open **"Terminal"** or **"iTerm"**  
4. To start, type ```start-service.sh```  
	- Check out [Spark Console](http://localhost:8080) if Spark comes up online.  
	- Same for [Hadoop Namenode](http://localhost:50070).  
5. To stop, type ```stop-service.sh```  


## F.A.Q  

If you have a question, leave it to my [blog post](https://pocketcluster.wordpress.com/2015/07/15/one-step-sparkhadoop-installer-for-osx-v0-1-0/) or [tweet me](https://twitter.com/stkim1).  


