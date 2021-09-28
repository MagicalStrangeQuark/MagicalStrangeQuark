## ⚠️ Atenção - Possívels Erros

* A porta esperada para enviar as requisições é `8000`, se outra for estabelecida, alterar o conteúdo de `baseURL` em `frontend\src\services\http.js`.

* Caso ocorra algum erro na instalação das dependências do `Laravel` através do `Composer`, deve-se habilitar as extensões presentes no arquivo de configuração `php.ini`.

* O local do arquivo de configuração `php.ini` pode ser visualizado digitando-se `php --ini` no terminal.

* Caso ocorra um erro relacionado ao certificado SSL ao efetuar as requisições para o serviço externo, retornando uma mensagem de erro semelhante à essa `cURL error 60: SSL certificate problem: unable to get local issuer certificate`, pode-se resolver através da resposta presente em `https://stackoverflow.com/questions/24611640/curl-60-ssl-certificate-problem-unable-to-get-local-issuer-certificate`