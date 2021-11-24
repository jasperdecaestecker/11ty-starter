# 11ty - Starter
- sass compatible
- autocopy assets to dist(output folder)

## How to use
- assets like img/files/favicon etc should be added in src/assets
- sass should be added to src/sass this will be automatically compiled on dev run/build

## Install
`npm install`

## Dev mode
`npm run start`

This will setup local dev server for 11ty as well as watch any scss changes and build css files accordingly

## Build
`npm run build`

This will generate the website and move the output to dist

## Hosting

I strongly recommend using netlify. Selecting your project from github should be all you need, if not configure netlify to use `npm run build` and use the dist folder as content to host.