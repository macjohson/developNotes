browser-sync使用
-----------------
###安装browser-sync
	npm install -g browser-sync

###项目中使用browser-sync
1.	使用`npm`初始化项目

		npm init
	
2.	项目中安装browser-sync
		
		npm install browser-sync --save-dev

3.	启动browser-sync
		
		browser-sync start --server ./ --files "index.html"
		
###参数说明
> `--server ./` 服务根目录
	
**使用代理服务器,可替换为参数`--proxy localhost:80`**


> `--files 'index.html'` 要监视的文件