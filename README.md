# hello-world
To learn nodeJs carefully

var http = require('http');

http.createServer(function(req, res){
  res.writeHead(200,{'Content-Type': 'text/plain'});
  res.write('I am Holoncaro, learn nodeJs next step.');
  res.end();
}).listen(2017);

console.log('Http Server Success!');
