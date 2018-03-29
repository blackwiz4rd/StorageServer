# DASHServer
A simple python server in django was created to allow developers to test their algorithms using provided media files for https://github.com/blackwiz4rd/DASHPlayer, but it can be used for many other purposes.

# Dependencies
To install dependencies run
```chmod +x setup.sh```</br>
```sh setup.sh```

# Run the server
First of all check your ip-address and edit
```sh start_server.sh```
accordingly.</br>
To start the server run:
```sh start_server.sh```</br>
In ```src/server/media/``` static video content is stored.
By default the script lets you access the server from any ip on the network for easy testing on multiple clients.

# How to open your content in media/
On a local network visit:
```http://my-ip:8080/media/image.png```

On the server visit:
```http://localhost:8080/media/image.png```

# Implementation
Refer to https://docs.djangoproject.com/en/2.0/ref/views/ to see how implementation was done.

===========================================

This directory contains the source code of my bachelor's degree final exam.

Bachelor Degree in Information Engineering
University of Padua, Italy

Copyright and license information can be found in the file LICENSE. 
Additional information can be found in the file NOTICE.

# Author
Luca Attanasio.
