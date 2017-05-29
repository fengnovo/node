## 腾讯云测试  
const http = require('http');

const server = http.createServer((req, res) => {
    res.statusCode = 200;
res.setHeader('Content-Type', 'text/plain');
res.end('Hello World\n');
});

server.listen(3000, () => {
    console.log(`node server is now running/`);
});


## 访问地址  

[demo](http://htmlpreview.github.io/?https://github.com/fengnovo/node/blob/master/index.html)

