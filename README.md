# Webpack4.X-install-Demo
关于Webpack4.X的安装与配置 
请确保你的电脑安装了npm!!!
1:下载该项目到本地
2:将shell或者命令行定位到该项目，安装webpack
  安装webpack和webpack-cli 推荐使用cnpm
  npm install -g webpack	
  npm install -g webpack-cli
  先安装到全局 然后放到本地项目内
  npm install --save-dev webpack
  npm i webpack-cli --save-dev
3:安装babel,参照官网https://babeljs.cn/docs/setup#installation
  配置信息以及写好了 不需要配置
  npm install --save-dev babel-loader babel-core
  npm install babel-preset-env --save-dev
4:运行
  不压缩 开发推荐
  npm run dev
  压缩 生产推荐
  npm run build
  运行index.html 以及可以使用了
