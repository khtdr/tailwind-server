# Tailwind CSS dev-server

Simple quick way to get started learning and playing with Tailwind CSS

<img style='max-width: 100%; display: block; height: auto;'
     src='https://raw.githubusercontent.com/khtdr/tailwind-dev-server/master/sample-logs.png'
/>

  - No "transpiling" configuration is needed (or used).
  - No build tools need to be set up.
  - Small and documented web server,
  - ~115 lines of code
  - minimal dependencies:
    - `socket.io` for **server** &laquo;&mdash;&raquo; **browser** communication,
    - `chalk` for color,
    - and `tailwindcss` of course.
  
## Installation
```bash
git clone https://github.com/khtdr/tailwind-dev-server.git
cd tailwind-dev-server
yarn
```

## Running
```bash
yarn start
```

Open `http://0.0.0.0:8080`

## Development

Edit any of the following entry point files:
 - [index.html](https://github.com/khtdr/tailwind-dev-server/blob/master/index.html)
 - [style.css](https://github.com/khtdr/tailwind-dev-server/blob/master/style.css)
 - [tailwind.js](https://github.com/khtdr/tailwind-dev-server/blob/master/tailwind.js)

Changes will be recompiled and automatically refreshed in your browser.

Create any additional HTML files as needed, using
[index.html](https://github.com/khtdr/tailwind-dev-server/blob/master/index.html)
as a reference.

## Building
If you like what you see and want to save it and use it, run:
```bash
yarn build
```

And use your newly built `./tailwind-bundle.css` stylesheet.
