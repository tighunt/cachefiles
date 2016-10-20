nodebob ( ͡° ͜ʖ ͡°)
---

nodebob is a **build tool** for **node-webkit** written in windows batch script.

Write your node-webkit project inside the ```app``` folder and build your native win application in just one click!

* nodebob creates the folder ```release``` that contains all the necessary files to build a standalone application without dependencies
* you can also add your custom application icon in ```app/app.ico```
    
**node-webkit** is an app runtime based on ```Chromium``` and ```node.js```.

> You can write native apps in HTML and Javascript with node-webkit. It also lets you to call Node.js modules directly from DOM and enables a new way of writing native applications with all Web technologies.

>**Features**

>* Apps written in modern HTML5, CSS3, JS and WebGL.
* Complete support for Node.js APIs and all its third party modules.
* Good performance: Node and WebKit runs in the same thread: Function calls are made straightforward;
* objects are in the same heap and can just reference each other;
* Easy to package and distribute apps.
* Available on Linux, Mac OSX and Windows

> [source] [1]

Tech
-
nodebob uses a number of open source projects to work properly:

* [7-zip] - a lightware file archiver, v9.20
* [Anolis Resourcer] - a windows resource editor, v0.9.0
* [node-webkit] - v0.8.3-win32

Version
-
0.1

Windows versions
-
Tested on `Windows 7 32-bit & 64-bit`.

Quick start
-

**Install**

`git clone https://github.com/geo8bit/nodebob.git nodebob`

**Run**

Execute `nodebob/build.bat`

License
-
MIT

[node-webkit]: https://github.com/rogerwang/node-webkit
[7-zip]: http://www.7-zip.org/
[Anolis Resourcer]: http://anolis.codeplex.com/
[1]: https://github.com/rogerwang/node-webkit#introduction 