##	快速上手

###	使用vue-cli@3
*	新版的 vue-cli 准备了相应的[ Ant Design Vue](https://github.com/vueComponent/vue-cli-plugin-ant-design) 插件，你可以用它们快速地搭建一个基于 Ant Design Vue 的项目。

###	引入ant-design-vue
*	安装脚手架工具(vle-cli)
	*	`npm install -g @vue/cli`
	*	OR
	*	`yarn global add @vue.cli`
*	创建一个项目
	*	`vue craete antd-demo`
	*	并配置项目。
*	然后我们进入项目并启动
	*	`cd antd-demo`
	*	`npm run serve`
*	使用组件
	*	`npm install ant-design-vue --save`

###	兼容性
*	Ant Design Vue 支持所有的现代浏览器和 IE9+。
*	对于 IE 系列浏览器，需要提供 es5-shim 和 es6-shim 等 Polyfills 的支持。
*	如果你使用了 babel，强烈推荐使用 babel-polyfill 和 babel-plugin-transform-runtime 来替代以上两个 shim。

###	按需加载


##	在 vue-cli 中使用

###	安装和初始化
	*	安装脚手架工具(vle-cli)
		*	`npm install -g @vue/cli`
		*	OR
		*	`yarn global add @vue.cli`
	*	创建一个项目
		*	`vue craete antd-demo`
		*	并配置项目。
	*	然后我们进入项目并启动
		*	`cd antd-demo`
		*	`npm run serve`
###	引入antd
	*	从 yarn 或 npm 安装并引入 ant-design-vue。
		*	`npm install ant-design-vue --save`
		*	OR
		*	`yarn add ant-design-vue`
###	高级配置
####使用babel-plugin-import
*	[babel-plugin-import ](https://github.com/ant-design/babel-plugin-import)是一个用于按需加载组件代码和样式的 babel 插件。
	*	`npm install babel-plugin-import --save-dev`

##	定制主题
###	Ant Design Vue 的样式变量
*	antd 的样式使用了 Less 作为开发语言，并定义了一系列全局/组件的样式变量，你可以根据需求进行相应调整。
*	[所有样式变量](https://github.com/vueComponent/ant-design-vue/blob/master/components/style/themes/default.less)。

###	定制方式
