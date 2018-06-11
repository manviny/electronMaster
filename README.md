# Electron project with Proton and Vue

## 0.- Electron + Photon + Vue

```bash
 git clone https://github.com/manviny/electronMaster
 cd electronMaster
 npm install && npm start
```


## 1.- [electron](https://electronjs.org/)
```bash
 git clone https://github.com/electron/electron-quick-start
 cd electron-quick-start
 npm install &amp;&amp; npm start
```

## 2.- [minified Photon](https://github.com/connors/photon/releases/download/v0.1.2-alpha/photon-0.1.2-dist.zip)

 **paste photon files to electron-quick-start project**

```js
//change in main.js
  mainWindow.loadFile('index.html')
//by 
  mainWindow.loadFile('template-app/index.html')
```

```bash
 npm install &amp;&amp; npm start
```
## 3.- [VUEJS](https://vuejs.org/)
## npm i vue --save
```html
<script src="https://cdn.jsdelivr.net/npm/vue"></script>
````

## 4.- Recursos

- [AWS Amplify](https://aws.github.io/aws-amplify/media/quick_start)
- [Photon components](http://photonkit.com/components/)
- [Electron Toolkit](https://www.npmjs.com/package/electron-toolkit)
- [TOOLKIT intro](https://hackernoon.com/introducing-electron-toolkit-the-electron-app-to-build-and-launch-electron-apps-6530450e257e)
- 
http://flexslider.woothemes.com/thumbnail-slider.html
http://dfcb.github.io/BigVideo.js/
https://blueimp.github.io/Gallery/

Note: If you're using Linux Bash for Windows, [see this guide](https://www.howtogeek.com/261575/how-to-run-graphical-linux-desktop-applications-from-windows-10s-bash-shell/) or use `node` from the command prompt.

## Resources for Learning Electron

- [electronjs.org/docs](https://electronjs.org/docs) - all of Electron's documentation
- [electronjs.org/community#boilerplates](https://electronjs.org/community#boilerplates) - sample starter apps created by the community
- [electron/electron-quick-start](https://github.com/electron/electron-quick-start) - a very basic starter Electron app
- [electron/simple-samples](https://github.com/electron/simple-samples) - small applications with ideas for taking them further
- [electron/electron-api-demos](https://github.com/electron/electron-api-demos) - an Electron app that teaches you how to use Electron
- [hokein/electron-sample-apps](https://github.com/hokein/electron-sample-apps) - small demo apps for the various Electron APIs

## License

[CC0 1.0 (Public Domain)](LICENSE.md)
