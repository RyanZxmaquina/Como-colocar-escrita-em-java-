sudo nano index.js

var http = require('http');


-------------------------------------------------------------------------
http.createServer(function (req, res) {
  res.writeHead(200, {'Content-Type': 'text/plain'});
  res.end('ESCREVA OQUE VOCÊ DESEJAR AQUI');
}).listen( ESCOLHA PORTA DE ENTRADA );
---------------------------------------------------------------------------


abra o visual code, e vá para terminal, ligue o seu nodered com o comando : "node index.js".

para saber se funcionou abra o browser e digite localhost/"a porta de entrada que você escolheu"
