#### A web segura - HTTPS


#### Introdução

- Basicamente o HTTPS é o HTTP com uma camada de segurança;
- Dados devem ser protegidos pois a request para por algumas camadas da rede até chegar no servidor;
    - Navegador to roteador to modem to provedor to firewall to servidor;
- Como o http envia informações eu tenho que esconder essas informações, pois eu as vezes preciso passar minha senha do banco para acessar o banco, essa senha com o HTTP fica exposta;
- Ai que surge a necessidade de fazer a segurança disso.    
- Exemplo abaixo o usuario e senha ficaram sem se vulneraveis;

    ![alt text](image.png)

- SSL/TLS: Secure Sockets Layer / Transport Layer Security
    - Basicamente é a camada adicional que foi implementada no HTTP;
    - TLS é a mais recente;


#### Funcionamento do HTTPS

- Para que a pagina se torne segura
- Precisamos de uma identidade confirmada;
    - Uma identidade na web = Certificado Digital;
    - O certificado vai ter uma chave pública para criptografar os dados;
    - E do lado do servidor a minha aplicação vai ter uma chave privada que só ela vai conseguir acessar essa chave que o cliente (browser) passar;
    -  Só quem consegue descriptografar é quem tem a chave privada;
    - No caso somente a aplicação web (servidor);
    - Aba de segurança conseguimos ver os dados criptografados;
    - Para essa web ficar segura é preciso que a gente garanta uma identidade;
    - Chave pública no browser e chave privada no servidor;


#### Certificado Digital

Quando precisamos informar nossos dados a algum servidor, queremos ter certeza que este servidor realmente representa a entidade em questão. Queremos confiar em quem estamos fornecendo nossos dados!

Um certificado digital prova uma identidade para um site, onde temos informações sobre o seu domínio e a data de expiração desse certificado.

Além disso, o certificado ainda guarda a chave pública que é utilizada para criptografar (cifrar) os dados que são trafegados entre cliente e servidor.


#### Qual o objetivo das autoridades certificadoras?

- Garantir que os certificados que estao sendo utilizados podem ser confiados;

- Essa garantia eh feita atraves de uma assinatura digital;

- A autoridade certificadora (CA) assinam digitalmente o certificado;

- Basicamente igual na vida real;

- CA - Certificate Authority;

- Que eh um orgao que garante que o navegador e ao usuario que a identidade de um servidor eh realmente valida;

- Assim podemos trocar informacoes no site sem problemas se ha uma certificado de autoridade;

- No caso um certificado digital assinado.


#### Para saber mais: As chaves do HTTPS


###### Metodo Criptografia assimetrica:
- Chave publica (browser) e chave privada (para o servidor);
- As chaves estao ligadas matematicamente;
- Duas chaves diferentes envolvidas;
- O problema eh que a criptografia desse jeito eh lenta.

    ![alt text](image-1.png)

###### Metodo Criptografia Simetrica:

- Usa a mesma chave para cifrar e decifrar os dados;
- Igual na vida real, quando usamos a mesma chave para abrir e fechar uma porta;
- Acaba sendo mais rapida.

    ![alt text](image-2.png)

##### O HTTPS usa os dois metodos

- Basicamente quando o cliente faz a requisicao tendo o certificado digital assinado, o HTTPS gera uma chave publica e do lado do servidor tem uma chave privada, sendo assim a conexao eh feita;

- Porem ha um detalhe, quando se estabele uma conexao do cliente com o servidor o HTTPS cria uma chave simetrica, ou seja uma chave igual para que nesse e nossas proximas requisoes (por um periodo de tempo), se utilize dessa chave igual e consiga passar a request e a response de uma maneira mais rapida, atraves dessa chave simetrica "temporaria".