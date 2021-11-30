# tonzhon-music

<h3>Listen to the music from different platforms in one place.</h3>

This repository is the early Tonzhon Lite, now Tonzhon Lite has been split into `tonzhon-lite`, `tonzhon-lite-server` and `tonzhon-lite-mobile`.

## Addresses
- [https://tonzhon.com](https://tonzhon.com)
- [lite.tonzhon.com](http://lite.tonzhon.com)

## Features
### Desktop
- Search
 (Searching with query string is supported, try: [http://lite.tonzhon.com/search?keyword=Iron%20Man](http://lite.tonzhon.com/search?keyword=Iron%20Man).)
- Play
- Download
- Get playlist from Netease (try: [http://lite.tonzhon.com/netease-playlist/5132177936](http://lite.tonzhon.com/netease-playlist/5132177936))
- Hot list (including QQ Music, Netease Music and Kuwo Music)
- Record search history

### Mobile
- Search
- Play

## Usage
    # Install dependencies
    npm install
    # Build client-side bundle
    npm run build
    # Start the server
    npm run server
Open `http://localhost:8081` to visit the page that uses the production build.

## Developing
### Server-side
    # Start nodemon dev server (nodemon needs to be installed globally.)
    npm run dev-server

### Client-side
    # Start webpack dev server
    npm start
Open `http://localhost:3000/` for desktop, and `http://localhost:3000/m/` for mobile.

## License
MIT