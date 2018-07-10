https://blog.csdn.net/HaoDaWang/article/details/78159989?locationNum=9&fps=1


安装node包： npm install -g electron-prebuilt  npm install -g electron-packager 


初始化项目： appDir (main.js  index.html package.json)  npm init 

开发： 网页该怎么写就怎么写

运行： npm start (electron)

打包：electron-packager . HelloWorld --win --out ../HelloWorldApp --arch=x64 --app-version=0.0.1 --electron-version=1.4.13