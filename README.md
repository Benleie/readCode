
## 记录学习中解决的bugs

+ git每次push时需要输入密码
  + git通过http或https的方式连接远程仓库时用户名和密码的记忆存储问题


+ `Unknown custom element:<panos>  did you register the component correctly? For recursive components, make sure to provide the "name"`
	+ 一般这个报错是因为components注册组件时写错
	+ 本次报错是因为在typescript的开发中，没注意引入了别的包含panos组件的模板
	```ts
	@Component({
	    template: require('./welcome.html')
	})
	```
