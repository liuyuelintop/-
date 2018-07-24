###结果
![](https://upload-images.jianshu.io/upload_images/13089440-49e46e9a6a74a184.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

---

###报错
```
liuyuelin@liuyuelindeMacBook-Pro ⮀ ~/Desktop/deploy-projects/movie ⮀ node app
connect.multipart() will be removed in connect 3.0
visit https://github.com/senchalabs/connect/wiki/Connect-3.0 for alternatives
connect.limit() will be removed in connect 3.0
connect.multipart() will be removed in connect 3.0
visit https://github.com/senchalabs/connect/wiki/Connect-3.0 for alternatives
connect.limit() will be removed in connect 3.0
imooc started on port 3000
/Users/liuyuelin/Desktop/deploy-projects/movie/node_modules/connect-mongo/lib/connect-mongo.js:155
          throw new Error('Error connecting to database <' + err + '>');
          ^

Error: Error connecting to database <Error: failed to connect to [localhost:27017]>
    at /Users/liuyuelin/Desktop/deploy-projects/movie/node_modules/connect-mongo/lib/connect-mongo.js:155:17
    at /Users/liuyuelin/Desktop/deploy-projects/movie/node_modules/connect-mongo/node_modules/mongodb/lib/mongodb/db.js:229:16
    at exports.ConnectionPool.<anonymous> (/Users/liuyuelin/Desktop/deploy-projects/movie/node_modules/connect-mongo/node_modules/mongodb/lib/mongodb/connection/server.js:578:7)
    at emitThree (events.js:136:13)
    at exports.ConnectionPool.emit (events.js:217:7)
    at exports.Connection.<anonymous> (/Users/liuyuelin/Desktop/deploy-projects/movie/node_modules/connect-mongo/node_modules/mongodb/lib/mongodb/connection/connection_pool.js:139:15)
    at emitTwo (events.js:126:13)
    at exports.Connection.emit (events.js:214:7)
    at Socket.<anonymous> (/Users/liuyuelin/Desktop/deploy-projects/movie/node_modules/connect-mongo/node_modules/mongodb/lib/mongodb/connection/connection.js:475:10)
    at emitOne (events.js:116:13)
    at Socket.emit (events.js:211:7)
    at emitErrorNT (internal/streams/destroy.js:64:8)
    at _combinedTickCallback (internal/process/next_tick.js:138:11)
    at process._tickCallback (internal/process/next_tick.js:180:9)
 ✘ liuyuelin@liuyuelindeMacBook-Pro ⮀ ~/Desktop/deploy-projects/movie ⮀ grunt
Running "concurrent:tasks" (concurrent) task
Running "nodemon:dev" (nodemon) task
Running "watch" task
Waiting...
Running "less:development" (less) task
Running "jshint:all" (jshint) task
Warning: Path must be a string. Received null Used --force, continuing.

Done, but with warnings.
File public/build/index.css created: 36 B → 28 B


    Running "uglify:development" (uglify) task

Done, without errors.


    24 Jul 10:04:12 - [nodemon] v0.7.10
24 Jul 10:04:12 - [nodemon] to restart at any time, enter `rs`
24 Jul 10:04:12 - [nodemon] watching: /Users/liuyuelin/Desktop/deploy-projects/movie

Done, without errors.
24 Jul 10:04:12 - [nodemon] starting `node app.js`


    24 Jul 10:04:12 - [nodemon] reading ignore list
connect.multipart() will be removed in connect 3.0
visit https://github.com/senchalabs/connect/wiki/Connect-3.0 for alternatives
connect.limit() will be removed in connect 3.0
connect.multipart() will be removed in connect 3.0
visit https://github.com/senchalabs/connect/wiki/Connect-3.0 for alternatives
connect.limit() will be removed in connect 3.0
>> File "public/build/admin.min.js" changed.
>> File "public/build/detail.min.js" changed.
imooc started on port 3000
/Users/liuyuelin/Desktop/deploy-projects/movie/node_modules/connect-mongo/lib/connect-mongo.js:155
          throw new Error('Error connecting to database <' + err + '>');
          ^

Error: Error connecting to database <Error: failed to connect to [localhost:27017]>
    at /Users/liuyuelin/Desktop/deploy-projects/movie/node_modules/connect-mongo/lib/connect-mongo.js:155:17
    at /Users/liuyuelin/Desktop/deploy-projects/movie/node_modules/connect-mongo/node_modules/mongodb/lib/mongodb/db.js:229:16
    at exports.ConnectionPool.<anonymous> (/Users/liuyuelin/Desktop/deploy-projects/movie/node_modules/connect-mongo/node_modules/mongodb/lib/mongodb/connection/server.js:578:7)
    at emitThree (events.js:136:13)
    at exports.ConnectionPool.emit (events.js:217:7)
    at exports.Connection.<anonymous> (/Users/liuyuelin/Desktop/deploy-projects/movie/node_modules/connect-mongo/node_modules/mongodb/lib/mongodb/connection/connection_pool.js:139:15)
    at emitTwo (events.js:126:13)
    at exports.Connection.emit (events.js:214:7)
    at Socket.<anonymous> (/Users/liuyuelin/Desktop/deploy-projects/movie/node_modules/connect-mongo/node_modules/mongodb/lib/mongodb/connection/connection.js:475:10)
    at emitOne (events.js:116:13)
    at Socket.emit (events.js:211:7)
    at emitErrorNT (internal/streams/destroy.js:64:8)
    at _combinedTickCallback (internal/process/next_tick.js:138:11)
    at process._tickCallback (internal/process/next_tick.js:180:9)
24 Jul 10:04:12 - [nodemon] app crashed - waiting for file changes before starting...
Running "jshint:all" (jshint) task
Warning: Path must be a string. Received null Used --force, continuing.

Done, but with warnings.
Completed in 0.520s at Tue Jul 24 2018 10:04:13 GMT+0800 (CST) - Waiting...
^C24 Jul 10:05:24 - [nodemon] exiting

 ✘ liuyuelin@liuyuelindeMacBook-Pro ⮀ ~/Desktop/deploy-projects/movie ⮀ node app

connect.multipart() will be removed in connect 3.0
visit https://github.com/senchalabs/connect/wiki/Connect-3.0 for alternatives
connect.limit() will be removed in connect 3.0
connect.multipart() will be removed in connect 3.0
visit https://github.com/senchalabs/connect/wiki/Connect-3.0 for alternatives
connect.limit() will be removed in connect 3.0
imooc started on port 3000
/Users/liuyuelin/Desktop/deploy-projects/movie/node_modules/connect-mongo/lib/connect-mongo.js:155
          throw new Error('Error connecting to database <' + err + '>');
          ^

Error: Error connecting to database <Error: failed to connect to [localhost:27017]>
    at /Users/liuyuelin/Desktop/deploy-projects/movie/node_modules/connect-mongo/lib/connect-mongo.js:155:17
    at /Users/liuyuelin/Desktop/deploy-projects/movie/node_modules/connect-mongo/node_modules/mongodb/lib/mongodb/db.js:229:16
    at exports.ConnectionPool.<anonymous> (/Users/liuyuelin/Desktop/deploy-projects/movie/node_modules/connect-mongo/node_modules/mongodb/lib/mongodb/connection/server.js:578:7)
    at emitThree (events.js:136:13)
    at exports.ConnectionPool.emit (events.js:217:7)
    at exports.Connection.<anonymous> (/Users/liuyuelin/Desktop/deploy-projects/movie/node_modules/connect-mongo/node_modules/mongodb/lib/mongodb/connection/connection_pool.js:139:15)
    at emitTwo (events.js:126:13)
    at exports.Connection.emit (events.js:214:7)
    at Socket.<anonymous> (/Users/liuyuelin/Desktop/deploy-projects/movie/node_modules/connect-mongo/node_modules/mongodb/lib/mongodb/connection/connection.js:475:10)
    at emitOne (events.js:116:13)
    at Socket.emit (events.js:211:7)
    at emitErrorNT (internal/streams/destroy.js:64:8)
    at _combinedTickCallback (internal/process/next_tick.js:138:11)
    at process._tickCallback (internal/process/next_tick.js:180:9)
```
---
❌错误原因：
1+本地没有下载 mongodb 以及完成路径设置
2+在运行项目之前，应该先在本地开启 **mongodb**，否者这个服务就会失败。
---
✅解决方法：
慕课网Nodejs 线上项目部署与发布这个课程没有教 mongodb 的下载和安装，笔者也是自己踩了很多坑，找到一个比较不错的 Mac 安装教程:

[Mac下安装 MongoDB](https://www.cnblogs.com/weixuqin/p/7258000.html)

下面是服务器启动成功的视图：
![](https://upload-images.jianshu.io/upload_images/13089440-19994207af6b35ca.gif?imageMogr2/auto-orient/strip)

项目启动成功的视图：
![](https://upload-images.jianshu.io/upload_images/13089440-4680888ebbdbf949.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/13089440-49e46e9a6a74a184.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

---
刘月林
写于湖北沙洋
2018/07/24
