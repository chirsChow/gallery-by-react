安装yeoman

$  npm install -g yo
1
安装generator-react-webapck

$  npm install -g generator-react-webpack
1
新建一个工程cd到工程目录

$ yo react-webpack
1
根据提示即可新建一个项目

可能出现的错误

node-sass安装失败 https://github.com/luqin/blog/issues/9


常用命令:

启动开发环境服务器
$  npm start
//或者
$  npm run serve
1
2
3

启动压缩版本的服务器
$  npm run serve:dist
//或者
$  npm run dist
1
2
3

测试
$  npm test
1

创建新的组件
$  yo react-webpack:component my/namespaced/components/name
1


相关文档
yeoman官网 http://yeoman.io/
generator-react-webpack文档 https://www.npmjs.com/package/generator-react-webpack
