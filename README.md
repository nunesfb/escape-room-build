# Operação Cofre Zero — Escape Room BD2

Jogo de equipe com **10 incidentes de PostgreSQL** (transações, isolamento, concorrência, triggers, índices, views materializadas, procedures e functions). Vocês têm **60 minutos** para conter todos.

Antes de começar, leiam o **[briefing da missão](BRIEFING_ALUNOS.md)**.

## Como abrir o jogo

Não é preciso instalar nada. O jogo é um único arquivo, `index.html`.

1. Nesta página do GitHub, clique em **Code → Download ZIP**.
2. Extraia o ZIP em uma pasta do computador.
3. Dê **duplo clique em `index.html`**. O jogo abre no navegador (Chrome, Edge ou Firefox).

Também é possível baixar só o arquivo: clique em `index.html` aqui na lista e depois no botão de download (**Download raw file**).

## Regras rápidas

- **Uma equipe por navegador.** O progresso fica salvo no navegador onde o jogo foi aberto.
- O cronômetro de **60 minutos** começa quando a equipe digita o nome e clica em **Iniciar missão**. Ele não pausa, nem ao recarregar a página.
- Cada incidente vale **100 pontos**: −20 por resposta errada e −15 por pista (máximo de 2 pistas), com mínimo de 40 pontos por incidente resolvido.
- Errar não elimina: discutam e tentem outra alternativa.
- Depois de cada acerto, leiam a explicação **"Por que funciona?"** antes de avançar.
- O botão **ⓘ Como jogar** mostra o manual dentro do jogo.
- Ao terminar, usem **⎙ Imprimir resultado** ou tirem um print da tela final para registrar a pontuação.

## Problemas comuns

- **O jogo voltou para a tela inicial ou mostra outra equipe:** vocês estão em outro navegador, em uma janela anônima ou abriram o jogo em outro computador. Voltem ao navegador onde começaram.
- **A fonte parece diferente:** sem internet o jogo usa uma fonte padrão. Isso não afeta o jogo.
- **Duas equipes no mesmo computador:** usem navegadores diferentes (por exemplo, uma no Chrome e outra no Edge), porque o progresso salvo é compartilhado dentro do mesmo navegador.
- **Reiniciar do zero:** botão **↺ Reiniciar operação** na barra lateral. Isso apaga o progresso da equipe.

O jogo é uma simulação: não executa SQL e não envia dados para nenhum servidor.
