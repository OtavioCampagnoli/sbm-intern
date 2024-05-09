### O que é HTTP?


#### Origem

- HTTP (HyperText Transfer Protocol);
- Usada pela rede munidal de computadores WWW (World-Wide-Web);
- Iniciativa da World-Wide-Web desde 1990;
- HTTP/0.9: Protocolo simples para transferência de dados brutos pela Internet.
    - Sendo assim quando era feita um pedido/requisição você tinha o conteudo da pagina sendo enviado inteiro;
    - Por exemplo se a gente pedisse index.html nessa versão o código seria passado inteiro sem nenhum cabeçario, sem estar especificando o que é cada coisa;
- HTTP/1.0 (RFC 1945): Melhorou permitindo mensagens no formato de MIME-like, contendo metainformações sobre os dados transferidos e modificadores sobre a semântica da solicitação/resposta.
    - Sendo assim a versão 1.0 ela permite a gente comunicar deixando o conteudo mais organizado.
    - E não somente organizado, mas outros tipos de arquivos foram permitidos também nas requests e responses;

### Objetivo

- Navegador com o Servidor precisa conversar (Cliente-Servidor);
- Porém para essa conversa ser feita onde todas as partes entendam precisamos ter **regras**
- Regras de comunicação: 
    - Protocolo de comunicação;
    - Sendo um protocolo um conjunto de regras;
    - Regras devem ser bem documentadas;
        - https://tools.ietf.org/html/rfc2616
        - Se usa no momento que o video foi gravado a versão 1.1;
        - No momento do vídeo a versão mais recente é 2.0


### Conclusão

- O HTTP foi criado para que a gente consiga se comunicar através da internet (client-server com um servidor);
- Foi melhorada continuamente;
- A implementação de cabeçarios na versão 1.0 foi muito importante para a organização do envio;
    - dando suporte para diferentes tipos de arquivos (content-type);
    - melhorou a semântica das mensagens, permitindo mensagens mais complexas e estruturadas;


*fontes de pesquisa:* **https://datatracker.ietf.org/doc/html/rfc2616**; **https://cursos.alura.com.br/course/http-fundamentos/task/25367**.
