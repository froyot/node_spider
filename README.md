### 功能

使用nodejs爬取廖雪峰网站教程。

### 使用

```
var Spider = require('./spider.js');

var spider = new Spider();
spider.getData("http://www.liaoxuefeng.com/wiki/001434446689867b27157e896e74d51a89c25cc8b43bdb3000");//填入第一页地址

```

### 缘由

在线查看教程，没次看完一页之后点下一页，遇到网络卡的情况小，需要好久之后界面才渲染，非常耽误时间，因此想爬取到本地。又近日
看到有人用python爬取该站点的python教程，所以使用nodejs写一个。


