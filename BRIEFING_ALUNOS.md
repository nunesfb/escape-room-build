# OPERAÇÃO COFRE ZERO — BRIEFING DOS ALUNOS

## Uma noite crítica na LojaNexa

São 20h15 e a LojaNexa enfrenta uma sequência de falhas durante uma campanha de vendas. O time de suporte reportou divergências em pedidos, estoque, saldos bancários e faturamento. A área de tecnologia precisa recuperar a operação antes que os problemas se agravem.

Vocês fazem parte da equipe de resposta a incidentes. O acesso ao sistema está dividido em **dez etapas**. Para avançar, analisem o chamado, leiam o trecho SQL, discutam as hipóteses e confirmem uma decisão. Cada etapa desbloqueada revela a próxima.

## Sua missão

Investigar e conter dez incidentes relacionados a transações, isolamento, concorrência, auditoria, índices, views materializadas, triggers, procedures e functions do PostgreSQL. As decisões devem ser justificáveis tecnicamente: uma alternativa aparentemente plausível pode deixar o problema de produção sem solução.

## Regras da operação

1. Definam um nome para a equipe e leiam as instruções antes de iniciar o jogo.
2. O cronômetro é de **60 minutos corridos**. Ele não pausa ao trocar de aba ou recarregar a página.
3. Cada incidente possui quatro alternativas e apenas uma é considerada a melhor solução no contexto apresentado.
4. Debatam antes de responder. Se a alternativa estiver incorreta, tentem novamente: há penalização, mas não eliminação.
5. É permitido consultar material da disciplina e documentação do PostgreSQL. O objetivo é aprender a interpretar problemas, e não decorar respostas.
6. Cada desafio vale até **100 pontos**. Cada resposta errada reduz **20 pontos** e cada pista solicitada reduz **15 pontos**, respeitando o mínimo de **40 pontos por desafio resolvido**.
7. O jogo é uma simulação interativa: **não executa comandos SQL de verdade** e não requer conexão ao banco.
8. Cada grupo deve operar em um único navegador/dispositivo. O progresso fica armazenado localmente nesse navegador.
9. Ao concluir, registrem a pontuação e discutam com o professor pelo menos um erro ou decisão que surpreendeu a equipe.

## Papéis sugeridos

- **DBA:** interpreta consultas, bloqueios e índices.
- **Desenvolvedor(a):** avalia código, triggers e rotinas SQL.
- **Analista de negócio:** relaciona a falha ao efeito sobre clientes e operação.
- **Responsável pela decisão:** conduz a discussão e confirma a escolha da equipe.

Em grupos de três, acumulem dois papéis. Alternem as funções a cada dois ou três incidentes.

## Como vencer

**Vitória completa:** solucionar os dez incidentes antes do relógio zerar.  
**Vitória parcial:** resolver o máximo de incidentes possíveis, explicando corretamente as decisões tomadas.  
**Importante:** terminar rápido não substitui compreender o motivo de cada resposta.

## Encerramento — conversa com o professor

Ao final, estejam prontos para responder: **Qual decisão parecia correta, mas escondia um risco? Que evidência SQL ajudou o grupo a identificar o problema? Como essa falha poderia aparecer em um sistema real?**

**Boa investigação. A operação está nas mãos da equipe.**
