### Serviços Web -REST


#### webservices

As aplicações que disponibilizam serviços para outras são chamadas de webservices. E uma API de utilização é documentada para uma integração eficiente entre sistemas.

Temos serviços web para trabalhar com pagamentos(Paypal é um exemplo famoso), upload de imagens, transformação de CEP em endereços textuais e diversos outros. Tudo isso é feito através do poderoso protocolo HTTP.

- Os webservices são são serviços disponibilizados por aplicações;

- Quando utilizamos webservices usamos o HTTP para o envio de informações atraves da internet;

- Porém precisamos pensar no lado do cliente e no consumo dessa internet;

- Se quiser enviar uma listagem de produtos, eu posso rapidamente enviar um html com esses produtos, mas terei um alguns problemas:
    - Conteudo a mais que seria enviado;
    - Para resolver esse problema de enviar informacoes que nao vao ser utilizadas se criou duas formas de extensoes;
        - JSON (JavaScript Object Notation)
        - XML (eXtension Markup Language)
    - Esses tipos de arquivos tem como objetivo formatar o "essencial" para o envio das requisicoes e respostas;
    - Sendo assim eu economizo a banda larga do meu usuario, e facilito no envio dessas informacao, colocando informacoes de forma mais objetiva;
    - Exemplo: 
        - caso eu queria enviar uma listagem dos produtos eu posso fazer das seguintes maneiras:
            - JSON:
                - [
                    {
                        "nome": "Nike Air Force 1",
                        "marca": "Nike",
                        "preco": 500,
                        "quantidadeEmEstoque": 20
                    },
                       {
                        "nome": "Nike Air Max",
                        "marca": "Nike",
                        "preco": 400,
                        "quantidadeEmEstoque": 10
                    }
                ]

- Eu posso especificar na requisicao o formato de arquivo que eu quero aceitar
    - Accept: text/html, Accept: text/css, Accept: application/xml, Accept: application/json, Accept:image/jpeg e Accept: image/*
Ou não definir nenhum formato especifico
    - Accept: */*

#### O que é REST

- REpresentational State Transfer (REST);
- Basicamente é composto por:
    - Os métodos de ações (GET; POST; PUT/PATCH; DELETE);
    - O recurso da URL ou URI;
    - E a representação dessas informações (XML, JSON, HTML).

### MIME types (IANA media types)

- tipo se subtipo;parametro=value
- https://developer.mozilla.org/en-US/docs/Web/HTTP/Basics_of_HTTP/MIME_types
- https://developer.mozilla.org/en-US/docs/Web/HTTP/Basics_of_HTTP/MIME_types