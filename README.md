# mobile_phone

> A Vue.js project

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

# run unit tests
npm run unit

# run e2e tests
npm run e2e

# run all tests
npm test
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).


# less使用方法
1、安装 less 和 less-loader ，在项目目录下运行如下命令
	npm install less less-loader --save-dev
2、安装成功后，打开 build/webpack.base.conf.js ，在 module.exports = 的对象的 module.rules 后面添加一段：
	module.exports = {
	 
	    module: {
	        rules: [
	        
	          {
	            test: /\.less$/,
	            loader: "style-loader!css-loader!less-loader",
	          }
	        ]
	    }
	}