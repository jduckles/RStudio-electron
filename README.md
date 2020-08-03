# RStudio Electron 

A simple simple electron app to connect to my RStudio Server within an electron window. 

This is a minimal Electron application based on the [Quick Start Guide](https://electronjs.org/docs/tutorial/quick-start) within the Electron documentation.


## To Use

To clone and run this repository you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

```bash

# Clone this repository
git clone https://github.com/jduckles/RStudio_electron

# Go into the repository
cd RStudio_electron

# Edit main.js
// SET THIS TO YOUR RSTUDIO SERVER, NOT MINE
mainWindow.loadURL('https://yourserver.com:8787')

# Edit package.json to set app name and other metadata

# Install dependencies
npm install

# Run the app
npm start

# To compile to a stand-alone app
npm install -g electron
npm install -g electron-packager
electron-packager . --out dist/

# Build for other platforms 
electron-packager . --platform win32 --out dist/
electron-packager . --platform darwin --out dist/
electron-packager . --platform linux --out dist/


```
## License

[CC0 1.0 (Public Domain)](LICENSE.md)
