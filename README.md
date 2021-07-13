# Connected
~Web Browser based Free Video Calling platform~
<br>
 Hey everyone, I'm Shikhar Chauhan! 
 This is my entry for Microsoft Engage'21 --> https://microsoft.acehacker.com/engage2021

## Features

-   No download, plug-in or login required, entirely browser based
-   Unlimited number of conference rooms without call time limitation
-   Desktop and Mobile compatible
-   Optimized Room Url Sharing (share it to your participants, wait them to join)
-   WebCam Streaming (Front - Rear for mobile)
-   Audio Streaming
-   Screen Sharing to present documents, slides, and more...
-   File Sharing, share any files to your participants in the room
-   Select Audio Input - Output && Video source
-   Ability to set video quality up to 4K and adapt the FPS
-   Recording your Screen, Audio and Video
-   Chat with Emoji Picker & Private messages & Save the conversations
-   Simple collaborative whiteboard for the teachers
-   Full Screen Mode on mouse click on the Video element
-   Possibility to Change UI Themes
-   Right click on the Video elements for more options
-   Direct `peer-to-peer` connection ensures lowest latency thanks to `webrtc`


## Demo

-   `Open` 


## Quick start

-   You will need to have [Node.js](https://nodejs.org/en/blog/release/v12.22.1/) installed, this project has been tested with Node version 14.17.3 (latest)
-   Clone this repo

```bash
git clone 
cd Connected
```

## Setup Turn and Ngrok

`Turn`

Not mandatory but `recommended`.

-   Create an account on http://numb.viagenie.ca
-   Get your Account USERNAME and PASSWORD
-   Fill in your credentials in the `.env` file
-   Set `TURN_ENABLED=true`, if you want enable the Turn Server.

`Ngrok`

Not mandatory at all, but useful for tests and debug.

-   Get started for free https://ngrok.com/
-   Fill in your authtoken in the `.env` file
-   Set `NGROK_ENABLED=true`, if you want to expose the server using the https tunnel, starting it from your local PC.

## Install dependencies

```js
npm install
```

## Start the server

```js
npm start
```

-   Open http://localhost:3000 in browser

---

## Credits

 (html [template](https://cruip.com/demos/neon/))

From where I took inspiration for this project. ❤️


<p align="center"> Made with ❤️ by <a href="https://www.linkedin.com/in/shikhar-chauhan-2001">Shikhar Chauhan</a></p>
