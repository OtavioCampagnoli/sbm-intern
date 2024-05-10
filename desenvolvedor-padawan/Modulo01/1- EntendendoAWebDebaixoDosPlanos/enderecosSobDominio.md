### Endereço e Domínio


#### Regras a serem seguidas


- Especifica qual tipo de domínio
- O domínio basicamente pega o IP e da um nome;
- Quem faz isso é o DNS (Domain Name System);
    - Basicamente ele pega a requisição converte pega o nome do domínio e retorna um endereço IP;
    - Age como se fosse uma base de dados, com os números dos IPS e nomes dos dominios equivalentes;
    - Resultando basicamente em no site.
- Exemplo: 
    - google.com.br
- Comando para verificar o ip do domínio desejado;
    - nslookup [nomeDoDominio];
    - Resposta: 
        `Server:		127.0.0.53
        Address:	127.0.0.53#53

        Non-authoritative answer:
        Name:	google.com.br
        Address: 172.217.30.3
        Name:	google.com.br
        Address: 2800:3f0:4001:83a::2003`

#### O que é domínio

O domínio é o nome do site na Web. Ele facilita a navegação do usuário, que não precisa lembrar o IP de cada site.


Alternativa correta, o domínio é o nome do site na web e serve para facilitar a navegação do usuário, que acaba não precisando lembrar o IP de cada site.

#### O que é DNS?

O DNS tem como função realizar a tradução do nome de um domínio para o endereço de IP correspondente.


O DNS realiza a tradução do nome de um domínio para o endereço de IP. Existem vários servidores DNS no mundo e é fundamental para a nossa web o funcionamento deles.

#### Portas

Conceito:
    - Basicamente é  uma porta de um apartamento;
    - Se essa porta nao tiver aberta você não consegue acessar, aquela página em especifico. Retornando a pagina hospedada naquela porta.

- Usando HTTP:
    - Porta 80 default (Não precisa preencher).

- Usando HTTPS: 
    - Porta default é a 443.