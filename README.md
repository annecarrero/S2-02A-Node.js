passo a passo
1) ativar o node-env.
    source nodejs-env/bin/activate
3) entrar na pasta onde o node-env está localizado.
    ex: cd src/
4) abrir o nano do arquivo "index.js"
    sudo nano index.js
obs: caso não seja proprietario fazer "sudo chown (usuario)__:__(classe) index.js"
5) dentro do nano coloque o codigo que precisar.
   
   var http = require('http');

http.createServer(function (req, res) {
  res.writeHead(200, {'Content-Type': 'text/plain'});
  res.end('Annely Leticia Moreira Carrero 19/09/2023!');
}).listen(8013);

6) apertar o ctrl+o para salvar as atualizações, confirmar com enter e apertar ctrl+x para fechar.
7) fazer o node funcionar com "node index.js"
8) e testar o funcionamento entrando no localhost/(o numero da sua porta)

 
