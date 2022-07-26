# Frontend example with Parcel, React and Less

This is the simplest possible example of a frontend built with JavaScript and React and bundled with Parcel (v2).

If you like this project, please star this repo and [support my work](https://www.codecapers.com.au/about#support-my-work)

## Setup

You need [Node.js](https://nodejs.org/en/) installed to use this code.

Uses pnpm because it's faster than npm.

First install pnpm:

```bash
npm install -g pnpm
```

Then clone this repo then install dependenices:

```bash
pnpm install
```

## Serve the web page with live reload

```bash
npm start
```

Open a browser and navigate to [http://localhost:1234/](http://localhost:1234/).

## Build the static web page

```bash
npm run build
```

The static web page is output to the `dist` subdirectory.

You can test it using `live-server`:

```bash
cd dist
npx live-server
```
