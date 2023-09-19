# nome-e-data
Primeiro é necessário ativar o nodejs colocando o seguinte código no terminal (source ./nodejs-env/bin/activate), em seguida (sudo namo index.js) e modificar o código base do professor, colocando o "meu nome" a data e modificando a porta (var http = require('http');
http.createServer(function (req, res) {
res.writeHead(200, {'Content-Type': 'text/plain'});
res.end('Milleny da Silva Leopoldino. 19/09/2023');
}).listen(8007);)
Para testar, abra um novo terminal e e digite (ip addr) para saber seu ip. Após isso abra o firefox digite seu ip:porta de entrada 
Exemplo: 192.168.40.22:8007

