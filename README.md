# Introduction

This repo demonstrate how three apps communicate with each other 

# Features

##  Emitter App (https://github.com/MohamedGElsharkawy/YelloEmitter)
- [x] Display list of users
- [x] Refresh for loading the latest users
- [x] Send and Receive data from MiddleMan App with broadcast receiver

##  MiddleMan App (https://github.com/MohamedGElsharkawy/YelloMiddleMan)
- [x] Display received user from Emitter App
- [x] Transfer the received user to Receiver App with local server client
- [x] Recieve saving status from Reciever App 
- [x] Send saving status to Emitter App

##  Receiver App (https://github.com/MohamedGElsharkawy/YelloReceiver)
- [x] Saving received user from MiddleMan App in Room DB
- [x] Display saved user from DB
- [x] Transfer saving status to MiddleMan App with local server client


# Demo
![DEMO](https://github.com/MohamedGElsharkawy/Yello/blob/main/Task.gif)
