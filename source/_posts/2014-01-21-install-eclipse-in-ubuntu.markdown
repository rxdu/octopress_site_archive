---
layout: post
title: "Install Eclipse in Ubuntu"
date: 2014-01-21 22:11:45 -0500
comments: true
categories: [Ubuntu, Eclipse]
---

First make sure you have installed JAVA in ubuntu to run Eclipse.
```
$ sudo add-apt-repository ppa:webupd8team/java
$ sudo apt-get update
$ sudo apt-get install oracle-java7-installer
```

1. Download the latest Eclipse from its official website.
2. Extract the files from the archive.
3. Move the extracted folder to whereever you want to put it. 
```
$ sudo mv eclipse /opt/ 
```

4. Create a symlink in /usr/local/bin using
```
$ cd /usr/local/bin
$ sudo ln -s /opt/eclipse/eclipse
```

5. Now you should be able to run eclipse from a terminal.
