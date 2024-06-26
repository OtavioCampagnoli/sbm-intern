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

#### Porta padrão HTTP

80 - Correto e como ela é o padrão você pode omiti-la no endereço.

Como as portas padrões são conhecidas pelo navegador, elas podem ser omitidas ao escrevermos uma URL.

Vários protocolos definem a sua porta padrão como por exemplo o FTP que usa 21 ou SSH que usa 22.

#### Recursos

Basicamente na URL temos o seguinte: https://dominio/porta/recurso
- O recurso basicamente serve para a gente acessar literalmente um recurso que o site oferece;
- Por exemplo eu posso passar um recurso chamado "dashboard"; "courses";
- Estrutura padrão é a:
    - protocolo://dominio:porta/caminho/recurso
    - esse padrão é chamado de URL (Uniform Resource Locator);
     ![alt text](image-3.png)


#### URL vs IRL

- URL (Uniform Resource Locator) -> Basicamente é um recurso unico que está num endereço;
- URI (Uniform Resource Identifier);
    - Existem URI's que identificam um recurso sem definir o endereço, nem o protocolo;
- Uma URL é basicamente uma URI alocada.
- Exemplo de URN (Uniform Resource Name): urn:cursos:alura:course:introducao-html-css
![alt text](image-4.png)