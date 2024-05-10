#### Parametros na requisição com métodos GET E POST

- Exemplo com o youtube
    - https://www.youtube.com/results?  search_query=Testando
    - parametro da requisicao: **search_query**;
    - para enviar mais de um parametro podemos usar o caracter **&**;

#### Parâmetros com GET

- Uma das caracteristicas do method GET é enviar os parametros pela URL;
- Quando usamos informações sensíveis nao é bom usar o method GET;
- Imagina que você efetue o login no seu banco e na URL apareça: https://www.bb.com.br/login?login=nico&password=supersecreto

### O método HTTP POST

- Quando usamos o method POST a informacao sao enviadas no corpo da requisicao e nao na URL;
- Geralmente se usa o method POST para criar alguma coisa;
- Mas no caso de um login usamos POST para esconder os dados sensiveis no envio da requisicao, sem passar essa dados na URL.

- Passar o parametro deve ser colocado ? apos o recurso, depois o nome do parametro e depois um =
- Caso vc deseje passar outro parametro vc deve colocar (&);
    - primeiroParametro=conteudo&nomedoparametro=conteudo

Usar depois:

https://viacep.com.br/ws/03451040/xml
https://viacep.com.br/ws/03451040/json


#### Web Services

Quando falamos de um Web Service, sempre usamos o protocolo da web, ou seja o HTTP.

Um Web Service disponibiliza uma funcionalidade na web, através do protocolo HTTP. As funcionalidades variam muito e dependem muito da empresa e do negócio dela, mas por exemplo, na Alura temos um Web Service que traz todas as informações de um curso (nome, capítulos, exercícios, etc). O Google ou Facebook possuem muitos Web Services para acessar um usuário, ver os posts dele, interesses, etc. Muitas vezes esses serviços são pagos.

O importante é que sempre usamos o protocolo HTTP. A grande diferença de um Web Service é que os dados não vem no formato HTML, e sim em algum formato independente da visualização, como XML ou JSON.

#### Outros metodos

- PUT
    - para atualizar informacoes;

- DELETE
    - para remover informacoes;

- Esses metodos sao utilizados mais em web services;

- Com tipos de visualizacoes diferentes, quando usamos get e post.