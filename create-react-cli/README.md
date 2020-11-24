# simple-craete-react-cli
生成简单较完整的react项目环境的脚手架

# 脚手架主要内容
1. 通过commander实现命令行的交互
2. 通过download-git-repo实现仓库代码的拉取
3. 通过inquirer实现配置的选择和相关项的填写，实现可选配置
4. 通过handlebars实现对package.json模板的替换
5. 通过chalk和ora对命令行的输出进行美化
6. 通过child_process模块开启子进程，实现依赖的npm install

# 使用
`npm install -g simple-create-react`  全局安装

`simple-create-react init projectName` 拉取模板进行初始化

# 项目启动步骤（/simple-craete-react-cli# 路径下）
1. npm install simple-create-react
2. node staticFilePull.js --help --》 如果有正确提示就说明依赖已经安装好了
3. node staticFilePull.js init projectDemo --》新建一个项目projectDemo
4. cd projectDemo/ --》按照操作提示进入目录下 然后npm install安装依赖
5. npm run dev --》按照操作提示 运行项目，然后就启动成功了！

# 效果

项目生成后就可以看见皮卡丘啦！
![pika](https://github.com/oniya24/simple-craete-react-cli/blob/master/result.png)
