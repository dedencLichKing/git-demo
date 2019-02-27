














1. 先进入到项目根目录
	cd 项目 

2. 命令行创建npm的配置文件
  a. npm init
  
3. 添加一个gulp的依赖
  npm install gulp --save-dev
  
4. 在项目根目录下添加一个gulpfile.js文件，这个是gulp的主文件，这个文件名是固定的

5. 当前目录下命令行引入插件
		npm install gulp-less gulp-concat gulp-uglify gulp-cssnano gulp-htmlmin gulp-watch --save-dev
		npm install browser-sync --save-dev
6.在gulpfile中抽象我们需要做的任务