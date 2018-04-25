# Webpack4.X-install-Demo
关于Webpack4.X的安装与配置 <br/>
<h1>请确保你的电脑安装了npm!!! </h1><br/>
<h3>1:下载该项目到本地 </h3><br/>
<h3>2:将shell或者命令行定位到该项目，安装webpack </h3><br/>
	安装webpack和webpack-cli 推荐使用cnpm <br/>
  npm install -g webpack	 <br/>
  npm install -g webpack-cli <br/>
  先安装到全局 然后放到本地项目内 <br/>
  npm install --save-dev webpack <br/>
  npm i webpack-cli --save-dev <br/>
<h3>3:安装babel</h3>,参照官网https://babeljs.cn/docs/setup#installation <br/>
  配置信息已经写好了 不需要配置 <br/>
  npm install --save-dev babel-loader babel-core <br/>
  npm install babel-preset-env --save-dev <br/>
<h3>4:运行</h3> <br/>
  不压缩 开发推荐 <br/>
  npm run dev <br/>
  压缩 生产推荐 <br/>
  npm run build <br/>
  运行index.html 以及可以使用了 <br/>
