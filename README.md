## 介绍
    
 学习nodejs入门项目,数据库使用的MySQL。
 使用nodejs 开发定位于企业网站的简易CMS，目标为容易拓展、部署，前端开发者容易使用的CMS系统。

## 特性

- 使用nodejs 开发，为前端开发者准备的，前后端都使用JS，做个企业网站就很容易了
- 简单（其实是懒），主要是首页、根据数据模型的列表页、详情页，单页，满足一般企业站点需要
- 容易拓展，功能不满足可以容易拓展
- 多模板
- 支持不同模型列表、详情指定模板，更加灵活嵌入单页

## 安装

在根目录下使用命令行执行下面代码，安装nodejs 依赖的模块
```shell
npm install 
```

## 数据库

在根目录下找到`nodecms.sql`文件，导入到你的 ` MySQL 数据库`中

修改`config/connections.js` 文件,根据上一步的数据库信息，修改数据库连接

```javascript
        // 修改数据库连接地址
        someMysqlServer: {
            host: 'localhost',
            user: 'root',
            password: 'yourpassword',
            database: 'nodecms'
        },
```

## 启动项目 
```shell
node app.js
```


后台地址 `/admin/user/login `
默认用户 admin admin






