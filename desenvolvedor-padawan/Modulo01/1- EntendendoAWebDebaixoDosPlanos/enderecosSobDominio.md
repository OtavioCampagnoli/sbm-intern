### Endereço e Domínio


### Regras a serem seguidas


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