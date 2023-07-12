# Codepad Masters an PWA App

## project Overview

     title : Codepad Masters

     description : notes app

- some basics features
  - Serve and Run our web App
  - work on the User Interface
  - Create instllationMeta Data
  - Make it offline capable
- tech stack
  - HTML + CSS + Javascript

## steps

- Serve and Run the web APp
- work on the user interface
- create installation meta data
- make it offline- capable
- preapare it for app store distribution (future)

### service worker

a javascript file running its own thread that will act as a middle ware offering a local installed web server or web proxy for our PWA , including resources and API

- Runs client -side in browsers engine
- HTTPS required
- installed by a web page
- own threads and lifecycle
- acts as a network proxy or local web server in the name of the real server

- abilities to run in the background
- no need for users permission
- every service worker have scope , an origin (host and port ) and a path

- it manages all pages within bowser and within installed app from scope
- its installed by any page in the scope
- after install , it can serve all files requested from the scope
- only one service worker is allowed

### android steps to make pwa

- download html
- html register service worker
- service worker installs some resources
- browser downlod resources on demnds , they served from the service worker or server
- app consume web services
  offline works
