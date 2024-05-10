### O Cliente pede e o Servidor responde


#### Modelo de Requisição e Resposta

- O HTTP não guarda requisição;
    - Uma requisição sempre deve ser enviada com todas as informações necessárias, o que faz uma requisição ser sempre independente das demais.
    - Todas as informações necessárias sempre devem estar contidas na requisição que será enviada, tornando-a independente das demais. 
- O HTTP usa sessões para salvar informações do usuário
Sessões só são possíveis por uso de Cookies
- Cookies são pequenos arquivos que guardam informações no navegador
- O HTTP é stateless, não mantem estado.

#### Sessão HTTP

- É o tempo que o cliente utiliza um web app.
- Uma sessão HTTP nada mais é que um tempo que o cliente permanece ativo no sistema! Isso é parecido com uma sessão no cinema. Uma sessão, nesse contexto, é o tempo que o cliente usa a sala no cinema para assistir a um filme. Quando você sai da sala, termina a sessão. Ou seja, quando você se desloga, a Alura termina a sua sessão.

#### Cookies

- Basicamente é um arquivo texto criado pela aplicação, para guardar algumas informações sobre o usuário;
- Exemplos:
    - Sessão do usuário criada após o login;
    - Carrinho de Compras, onde fica armazenado o que o usuário quer comprar;
- O cookie fica armazenado no browser e pode ser manipulado;

#### Comunicação em HTTP

- Uma comunicação com HTTP sempre é iniciada pelo cliente que manda uma requisição ao servidor esperando por uma resposta.

- No HTTP: Request -> espera -> Resposta

#### Resumo

- O protocolo HTTP segue o modelo Requisição-Resposta
Sempre o cliente inicia a comunicação
- Uma requisição precisa ter todas as informações para o servidor gerar a resposta
- HTTP é stateless, não mantém informações entre requisições
- As plataformas de desenvolvimento usam sessões para guardar informações entre requisições