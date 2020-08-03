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


# Install dependencies
npm install
# Run the app
npm start
```
## License

[CC0 1.0 (Public Domain)](LICENSE.md)
