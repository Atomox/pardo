## Client Work 2024 ##

To run this locally, we'll need to install NPM, so we can install the package.json, and get the local webserver, called http-server.

1. From the terminal, install NPM (Node Package Manager)
```
sudo apt install npm
```

2. Download this repository code to your computer.

3. From the root of this folder, run the install for this package. This will install all the dependencies, including http-server, which will allow you to run this locally.
```
npm install
```

4. Once complete, start the server:
```
npm run dev
```

5. From your browser, open the website, by visiting:
```
http://127.0.0.1:8080/index.html
```


#### Gulpfile.js

There is an included an optional Gulp file to help you get started with theme customization. You’ll need to install Node.js and Gulp before using our included gulpfile.js.

To install Node visit [https://nodejs.org/download](https://nodejs.org/download/).

To install gulp, run the following command:

```
$ npm install gulp -g
```

When you’re done, install the rest of the theme's dependencies:

```
$ npm install
```

From here, simply run `gulp` from your terminal and you're good to go!

+ `gulp` - recompiles your theme assets.

