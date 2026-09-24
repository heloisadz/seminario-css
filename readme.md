box-sizing: border-box;

    - Ao usar box-sizing: border-box, você muda essa lógica:

    - O que ele faz: Ele força o tamanho que você definiu a ser o tamanho final absoluto da caixa.

    - Exemplo: Se você define width: 100px e adiciona padding: 20px, a caixa continua medindo exatamente 100px. O navegador empurra o conteúdo para dentro para fazer o espaçamento caber sem aumentar o tamanho da caixa.

    - Resumo: border-box garante que a largura/altura que você digitou no CSS seja exatamente o tamanho real que a caixa vai ocupar na tela, sem somar bordas ou paddings por fora.


rem = tamanho usado p definir tmahjo de fonte definido no html

    -ele é relativo à raiz do documento (daí o nome Root EM).

    - por padrao nos navegadores a ofnte mede 16px

    - se o tamanho da fonte no html for 12px, 1 rem é 12px, 2 sao 24px
    usado p layouts mais responsivos, pq se altera tamanho da fonte, tudo altera proporcionalmente

    - melhor p casos de acessibilidade, pq o usuario poe precisar aumentar ou diminiuir

    - se precisar mudar todo o layout de vez basta aumentar o font size do html

