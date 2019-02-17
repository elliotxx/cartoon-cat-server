# cartoon-cat-server

博客地址：http://www.miaoerduo.com/nodejs/简易漫画网站搭建-漫画喵server版.html

与cartoon-cat的配套的漫画服务器，用于在线的漫画阅读。具体的细节请参阅博客。

使用：

```
git clone git@github.com:miaoerduo/cartoon-cat-server.git
cd cartoon-cat-server
npm install
node main.js
```

然后访问本地 http://localhost:3000 即可阅读漫画。ip和端口也可以自己设置。

## 生成目录
1. 进入 ./public/store 目录运行以下命令
linux
```
ls -t -r > index
```

windows
```
dir /OD /B > index
```

2. 然后编辑这个文件，删掉index这一行
