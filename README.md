# conn2
SSH conections manager.

This script will allow you to connect to your ssh servers only by remembering the name of each server.

Instead of typing:
>ssh richard@piedpiper.com -p 3141

Just type:
>conn2 piedpiper

## Use:
In a open terminal type
>**conn2** *action*

Where *actions* can be:
- new - To register a new ssh server
- list - List all servers you registered
- *[name]* - The name you registered for the server you want to connect.

##Where are all the data?
All the data of your connections are stored in a json file inside your home folder:
>~ /.conn2_config /servers.json

---
Made with <3 in Perú