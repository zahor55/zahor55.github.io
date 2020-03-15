---
layout: project
type: project
image: images/sending_tracker.jpg
title: sending_tracker
permalink: projects/vacay
labels:
  - React native
  - Redux
  - Node js
  - Expo
 
summary: app to send tracking number for your store in hebrew
---
#front-react native app
can see screenshot in my [GitHub](https://github.com/zahor55/sending_tracker) project page
#back-api

server that handle request to send tracking details to costumers

api-

```
#send with tracking number
   https://trackebay.herokuapp.com/num/${trackNum}/${mail}/${clientName}/{const.id}
   #trackNum=the tracking number
   #mail=the customer mail
   #clientName=the client name
   #const.id=id from const file-the same in server and client for authentication
   
   #send without tracking number
   https://trackebay.herokuapp.com/noNum/${value}/${mail}/${clientName}/{const.id}
   #value={24,express,regular}
   #mail=the customer mail
   #clientName=the client name
   #const.id=id from const file-the same in server and client for authentication
```