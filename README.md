# SnakeCash 🐍💰

## Sobre o Projeto
SnakeCash é um jogo de cobrinha desenvolvido para o projeto de PIF do 2º período da CESAR School. Inspirado no clássico jogo da cobrinha, SnakeCash adiciona um toque moderno ao desafio: coletar dinheiro e evitar obstáculos para se tornar a cobrinha mais rica!

## Como Jogar
- Use as teclas de WASD para mover a cobrinha pelo campo de jogo.
- Colete os ícones de dinheiro para aumentar sua pontuação.
- Evite os campos e se enrolar.
- O jogo termina quando a cobrinha colide com um obstáculo ou com ela mesma.

## Funcionalidades
- Jogabilidade clássica com um objetivo moderno.
- Sistema de pontuação baseado em dinheiro coletado.

## Tecnologias Utilizadas
- **Linguagem de Programação**: C
- **Ambiente de Desenvolvimento**: Baseado no repositório do Professor Thiaguinho https://github.com/tgfb/cli-lib

## Instalação e Execução
1. Clone o repositório do SnakeCash.
2. **Abra um terminal**.
3. **Navegue até o diretório** onde este Makefile está localizado usando o comando `cd`.
   Por exemplo, se o Makefile estiver no diretório `~/myproject`, você usaria o comando `cd ~/myproject`.
4. **Digite `make`** e pressione Enter. O comando `make` irá procurar um arquivo chamado "Makefile" no diretório atual e executar as instruções nele.
   Isso irá compilar seu código e criar o executável `cli-lib`.
5. **Após a compilação bem-sucedida**, você pode executar o programa com `./cli-lib` (no Linux ou Mac) ou `cli-lib.exe` (no Windows, se você estiver usando Cygwin ou MinGW).

Se você quiser limpar todos os arquivos compilados (arquivos objeto e o executável), você pode usar o comando `make clean`.
Isso irá executar a regra 'clean' neste Makefile, que remove todos os arquivos objeto e o executável `cli-lib`.
