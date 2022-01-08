# Trivia Game(server based) - Project written in python(readme still in progress)
[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)[![Linux](https://svgshare.com/i/Zhy.svg)](https://svgshare.com/i/Zhy.svg)[![macOS](https://svgshare.com/i/ZjP.svg)](https://svgshare.com/i/ZjP.svg)[![Windows](https://svgshare.com/i/ZhY.svg)](https://svgshare.com/i/ZhY.svg)

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Features](#features)
* [Screenshots](#screenshots)
* [Setup](#setup)
* [Contact](#contact)

## General info
- This project is a trivia game running by a server! ,you can compete with your friends to see who have higher score:smile:
- The server have database of users, you(the admin) can add and remove users from the database
- The server have a quetion database, at the moment the database has only two questions(because i didn't need more than that for the server testing) but you can add more!
	
## Technologies
Project is created with:
* python version: 3.9 .
* visual studio code.
* socket - Library used to setup local server and to send messages bettwen the server with ip address to the client and back.
* select - The library tells the kernel to notify when any of the descriptors in the sets are ready for read/write/exception conditions.
* chatlib - A custom library that have all the functions that make the client and server messages correct according to the protocol we maked.

## Features
- You have dictionary database of users and for every user you have a dictionary inside that dictionary, and inside there: password, score, number of questions asked.
- You have dictionary database of question you can expand as much as you want.
- A custom library that responsibility for building messages with correct structure according to the protocol.

## Screenshots
![Example screenshot](./img/"enter the img name".png)

## Setup
first of all you need to install python on your computer.
1. download all the files.

example of run code:
```
$ cd ../
$ 
```
## Contact
Created by Oshri Agronov, feel free to contact me:v:
