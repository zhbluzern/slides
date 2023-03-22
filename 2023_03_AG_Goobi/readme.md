## Make Slides

`pandoc -s -i -t revealjs --variable revealjs-url=C:/Temp/slides-revealjs/build/reveal.js --variable theme="zhbluzern" .\slides.md -o index.html`

## Install reveal.js local
* Create a Working Directory for reveal-js based slides
* Download the latest reveal-js.zip, unpack it and move it to /build/reveal.js directory
* Copy npm-shrinkwrap.json to /build/reveal.js
* Run `npm install`
* Run `npm audit fix`

## Change ZHB-Luzern Theme

* In build/revealjs/css/source/zhbluzern.scss können scss-Konfiguration für das ZHB-Theme angepasst werden. 
* Um zum zhbluzern.css zukommen muss das build neu durchlaufen werden.
* Go To build/reveal.js -> `npm run build -- css-themes`


