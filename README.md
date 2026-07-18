# Crono-TJPE-html

Gerenciador do cronograma de estudos para o concurso do **TJPE**, em um único arquivo HTML autossuficiente.

## Uso

Abra **[`index.html`](index.html)** no navegador (basta duplo-clique — funciona offline, sem servidor).

- Todos os **73 dias** e **146 sessões** (240 h) são listados, agrupados pelas **3 fases**, detalhando disciplina, temas/subtemas e carga horária.
- Marque cada sessão como concluída no checkbox. A **barra de progresso** e o **gráfico de progressão** (acúmulo de sessões concluídas ao longo dos dias, até 26/09/2026) atualizam em tempo real.
- O progresso é salvo automaticamente no navegador (`localStorage`). Use **Limpar progresso** para zerar.

Os dados do plano ficam embutidos no próprio `index.html`, gerados a partir do plano fixo de estudos.
