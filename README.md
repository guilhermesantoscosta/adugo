# ADUGO – Jogo da Onça

Este é um jogo de tabuleiro digital baseado no tradicional **Jogo da Onça**, conhecido entre os povos indígenas brasileiros como *Adugo*. Nele, um jogador controla a onça e o outro controla os cachorros. A onça vence ao capturar cinco cachorros; os cachorros vencem ao cercar a onça, deixando-a sem movimentos.

O jogo foi desenvolvido em HTML, CSS e JavaScript, com a biblioteca Three.js para renderização 3D. Funciona inteiramente no navegador.

## Modos de jogo

- **Onça contra CPU** – você joga com a onça, o computador controla os cachorros.
- **CPU contra Cachorro** – você joga com os cachorros, o computador controla a onça.
- **Dois jogadores (PvP)** – duas pessoas se alternam no mesmo dispositivo.

## Como jogar

No menu principal, escolha o modo desejado. Durante a partida:

- Para mover a onça, clique em uma casa destacada em verde.
- A onça pode capturar um cachorro pulando sobre ele, desde que a casa de destino esteja vazia.
- Para movimentar um cachorro, primeiro clique nele (ele ficará realçado) e depois clique em uma casa verde.
- O jogo termina quando a onça faz cinco capturas ou quando os cachorros a encurralam.

## Tecnologias

- Three.js – para gráficos 3D e cena interativa.
- CSS com animações e design responsivo.
- JavaScript puro para a lógica do jogo e para a inteligência artificial.

## Inteligência artificial

A CPU usa o algoritmo Minimax com profundidade 4, complementado por uma função de avaliação heurística. Um sistema anti-loop evita que a IA repita o mesmo movimento várias vezes seguidas, tornando o comportamento mais natural.

## Como executar

O jogo está contido em um único arquivo HTML. Basta baixá-lo e abri-lo em qualquer navegador moderno. Não são necessárias instalações ou dependências externas.

## Contribuições

Sugestões e melhorias são bem-vindas. Se você deseja contribuir, por favor, abra uma issue ou envie um pull request. Para mais detalhes, consulte o arquivo CONTRIBUTING.md.

## Licença

Este projeto é distribuído sob a licença MIT. Consulte o arquivo LICENSE para mais informações.

## Créditos

- A mecânica do jogo é inspirada na tradição dos povos Bororo.
- Implementação e design por Guilherme Henrique Santos da Costa e Estudantes do Laboratório de Jogos Eletrônicos do CEU EMEF Três Pontes da Prefeitura de São Paulo.
- A trilha sonora foi criada com a Web Audio API e é de autoria dos mesmos criadores do jogo.
