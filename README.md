# Operação Cofre Zero — Escape Room BD2

Jogo **individual** com **10 incidentes de PostgreSQL** (transações, isolamento, concorrência, triggers, índices, views materializadas, procedures e functions). Você tem **60 minutos** para conter todos.

Antes de começar, leia o **[briefing da missão](BRIEFING_ALUNOS.md)**.

## Como abrir o jogo

Não é preciso instalar nada. Cada aluno abre o jogo no seu próprio computador.

### Opção 1: pelo link (mais simples)

Abra **https://nunesfb.github.io/escape-room-build/** no navegador.

### Opção 2: baixando o arquivo

O jogo é um único arquivo, `index.html`.

1. Nesta página do GitHub, clique em **Code → Download ZIP**.
2. Extraia o ZIP em uma pasta do computador.
3. Dê **duplo clique em `index.html`**. O jogo abre no navegador (Chrome, Edge ou Firefox).

Também é possível baixar só o arquivo: clique em `index.html` aqui na lista e depois no botão de download (**Download raw file**).

## Regras rápidas

- **Jogo individual:** cada aluno joga no seu computador. O progresso fica salvo no navegador onde o jogo foi aberto.
- O cronômetro de **60 minutos** começa quando você digita o seu nome e clica em **Iniciar missão**. Ele não pausa, nem ao recarregar a página.
- Cada incidente vale **100 pontos**: −20 por resposta errada e −15 por pista (máximo de 2 pistas), com mínimo de 40 pontos por incidente resolvido.
- Errar não elimina: revise a evidência e tente outra alternativa.
- Depois de cada acerto, leia a explicação **"Por que funciona?"** antes de avançar.
- O botão **ⓘ Como jogar** mostra o manual dentro do jogo.
- Ao terminar, use **⎙ Imprimir resultado** ou tire um print da tela final para registrar a sua pontuação.

## Problemas comuns

- **O jogo voltou para a tela inicial ou mostra outro nome:** você está em outro navegador, em uma janela anônima, abriu o jogo em outro computador ou trocou de opção (o link e o arquivo baixado guardam progressos separados). Volte ao navegador e à opção em que começou.
- **O jogo já abriu com o progresso de outra pessoa** (computador compartilhado do laboratório): clique em **↺ Reiniciar operação** na barra lateral e comece com o seu nome.
- **A fonte parece diferente:** sem internet o jogo usa uma fonte padrão. Isso não afeta o jogo.

O jogo é uma simulação: não executa SQL e não envia dados para nenhum servidor.
