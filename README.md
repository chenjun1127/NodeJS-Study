## NodeJs的基本学习
#### 克隆项目 cd 到 NodeJS-Study;
```bash
git clone git@github.com:chenjun1127/NodeJS-Study.git
```
#### 进入到各个文件夹，node 运行各个 js 文件，有 package.json 需要先安装依赖;
```bash
cd xx
npm install 
```

----
## 以下为Node的基本安装：
#### 安装node
请到 Node 官网[nodejs.org](https://nodejs.org/en/)，或者国内镜像[npm.taobao.org/mirrors/node](https://npm.taobao.org/mirrors/node)，下载安装包。推荐安装最新的稳定版，目前是v6.x。

安装完成后，命令行执行下面的命令，确认是否安装成功。
```javascript
node -v
```
Node 的模块管理器 npm 会一起安装好。由于 Node 的官方模块仓库网速太慢，模块仓库需要切换到阿里的源。
```javascript
npm config set registry https://registry.npm.taobao.org/
```
执行下面的命令，确认是否切换成功。
```javascript
npm config get registry
```
以上基本安装步骤来自[阮一峰老师的github](https://github.com/ruanyf/jstraining/blob/master/docs/preparation.md)
