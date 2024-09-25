# Jogo da velha com HTML, CSS e JavaScript

**Este jogo clássico permite que dois jogadores se enfrentem em uma grade de 3x3, alternando turnos até que um dos jogadores vença ou ocorra um empate.**

## Funcionalidades

- Modo de jogo para dois jogadores: Dois jogadores podem se revezar no mesmo dispositivo.
- Detecção automática de vencedor ou empate: O jogo verifica automaticamente as condições de vitória ou empate.
- Interface interativa: Cada vez que um jogador clica em uma célula, seu símbolo (X ou O) aparece

## Tecnologias usadas:
- HTML5: Estruturação básica do jogo.
- CSS3: Estilização da interface e responsividade.
- JavaScript: Lógica do jogo (detecção de vitória, empate, alternância de turnos).

## Como Jogar
1. Abra o arquivo index.html no seu navegador.
2. A primeira célula clicada será preenchida com o símbolo "X".
3. O jogador 2 deve clicar na próxima célula, que será preenchida com o símbolo "O".
3. O jogo alterna automaticamente entre os jogadores.
4. O jogo verifica após cada turno se um jogador venceu ou se houve empate:
   - Vitória ocorre quando três símbolos iguais (X ou O) são alinhados na horizontal, vertical ou diagonal.
   - Empate ocorre quando todas as células estão preenchidas e nenhum jogador venceu.
   
7. Reinicie o jogo clicando no botão de "Reiniciar" para começar uma nova partida.

## Como executar o projeto:
**1. Clone o repositório para a sua máquina local:**
```bash
  git clone https://github.com/CauanLagrotta/jogo-da-velha.git
```

**2. Navegue até a pasta do projeto:**
```bash
  cd jogo-da-velha
```

**3. Abra o arquivo index.html no seu navegador ou utilize uma extensão de servidor local para visualizá-lo.**
