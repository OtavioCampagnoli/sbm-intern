### Position


- Basicamente existem 5 metodos principais para modificar as posições dos elementos HTML
- static (default);
    - são posicionados em relação o fluxo normal do documento/página;
    - é o valor padrao do elemento;
- relative;
    - é posicionado em relação à sua posição original no fluxo do documento;
- absolute;
    - a posição fica absoluta em relação ao container mais proximo, com posição relativa ou fixa;
    - Se não tiver esse container relativo ou fixo, o container com a absolute vai ficar absoluto à página;
- fixed;
    - O elemento sempre estará fixo em relação à página, ou seja se eu usar o scrool para baixo o elemento acompanha a página;
    - é bom para realizar header que acompanham a pagina enquanto você navega;
    - ele não se move basicamente é isso;
- sticky (relative + fixed);
    - Usando ela o elemento acompanha o scroll da pagina como no fixed, porém quando o scroll chega na posição original dela, o elemento respeita essa posição inicial;
    - Ou seja enquanto eu uso o scroll para baixo ele o elemento se comporto acompanhando a página, quando eu volto o scroll e passo na posição inicial o elemento volta para a posição inicial;