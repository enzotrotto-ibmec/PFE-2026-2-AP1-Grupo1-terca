# Scrum: Projeto Front-end (PKZ Lab & One to One)

> Documento reconstruído a partir do histórico de commits do repositório (103 commits, de 29/08/2026 a 28/09/2026), do README e das atas de reunião. As datas dos sprints e a divisão dos itens são inferidas pelos padrões de atividade. Apenas o papel de Scrum Master consta explicitamente em ata (10/09).

## Papéis

| Papel | Quem |
|---|---|
| Scrum Master | Enzo Trotto (consta na ata de 10/09) |
| Product Owner / stakeholder | Cliente PKZ Lab & One to One (professor Thiago Marcondes como avaliador) |
| Time de desenvolvimento | Alexia Schmid, Bernardo Gomes, Bernardo Nemirovsky, Gabriel Góis, Guilherme Macedo, João Pedro Ferreira, Enzo Trotto |

## Product Backlog (baseado nos entregáveis do README)

| # | Item | Sprint | Status |
|---|---|---|---|
| 1 | Transcrição e demandas das reuniões com o cliente (1 e 2) | 1 e 2 | Feito |
| 2 | 5W2H (PKZ e One to One) | 1 | Feito |
| 3 | Documento de Visão | 2 e 3 | Feito |
| 4 | Brainstorm | 2 | Feito |
| 5 | Mapa mental | 2 | Feito |
| 6 | AHT (Árvore Hierárquica de Tarefas) | 2 e 3 | Feito |
| 7 | Protótipo da interface | 1 e 3 | Feito |
| 8 | Fluxo de agendamento de aula experimental | 3 | Feito |
| 9 | Atas de reunião | 2 e 3 | Feito |
| 10 | Implementação em HTML/CSS (AP2) | Próximo | A fazer |

---

## Sprint 1: Descoberta e organização

**Período:** 29/08 a 03/09 (40 commits)
**Meta:** ter o repositório estruturado e as demandas do cliente registradas.

**Feito:**
- Repositório e README criados (Enzo).
- Transcrição da 1ª reunião com o cliente convertida para markdown, com o documento de demandas (João Pedro).
- 5W2H do PKZ em 6 versões e do One to One em 2 (Nemirovsky, João Pedro).
- Primeiros protótipos e landing page (Enzo, Nemirovsky).
- Pastas numeradas por entregável.

**Destaque:** 02/09 foi o dia mais intenso do sprint (11 commits), quase todos no 5W2H.

---

## Sprint 2: Planejamento e modelagem

**Período:** 08/09 a 15/09 (33 commits)
**Meta:** cobrir as etapas de planejamento que faltavam (brainstorm, mapa mental, visão, AHT).

**Feito:**
- Documento de Visão, do esqueleto ao refinado (Enzo).
- AHT v1 e Painel AHT (Guilherme, Alexia, Gabriel).
- AHT2, com PKZ Lab e One to One separados (Bernardo Gomes, Gabriel).
- Brainstorm V01/V02 (Nemirovsky, João Pedro).
- Mapa mental no Canva (Bernardo Gomes).
- Demandas da 2ª reunião com o cliente, com 126 linhas tratadas (João Pedro).
- Ata de 10/09.
- Reorganização das pastas (Guilherme, Enzo).

**Cerimônia registrada:** a reunião de 10/09 (17h30 às 19h10, Discord) funcionou como um planning/refinamento. O motivo foi a dúvida sobre brainstorm e mapa mental, já que o grupo tinha pulado essas etapas.

---

## Sprint 3: Refinamento e entrega

**Período:** 20/09 a 28/09 (30 commits)
**Meta:** fechar o AHT, entregar o protótipo com a aba de agendamento e preparar a apresentação.

**Feito:**
- Revisão geral dos documentos (João Pedro, 20/09).
- AHT final, com One to One e PKZ Lab, portal do cliente com relatórios de IA e regras de agendamento (Alexia, Bernardo, Guilherme, Gabriel).
- Login/cadastro e seleção de modalidade no fluxo de aula experimental (Alexia).
- 12 telas do protótipo exportadas em PNG (Nemirovsky).
- Ata de 27/09, com ensaio da apresentação (Enzo).
- Atualização do Documento de Visão (Enzo).
- PNG final do AHT (Gabriel).

**Sprint review:** a reunião de 27/09 (domingo) revisou o AHT, o fluxo do protótipo e a apresentação. As correções foram combinadas para 28/09 e entregues.

---

## Contribuição por pessoa

Commits com aliases unificados (o repositório tem 16 nomes de autor para 7 pessoas).

| Pessoa | Commits | Foco principal |
|---|---|---|
| João Pedro Ferreira | 22 | Transcrições, demandas, 5W2H, brainstorm |
| Enzo Trotto | 22 | README, estrutura, Doc de Visão, atas (SM) |
| Bernardo Nemirovsky | 17 | 5W2H, brainstorm, protótipo |
| Alexia Schmid | 14 | AHT, painel, fluxo de agendamento |
| Gabriel Góis | 12 | AHT, ajustes e versão final |
| Bernardo Gomes | 11 | Mapa mental, AHT2 |
| Guilherme Macedo | 5 | AHT inicial, PNGs, organização de pastas |

> Número de commits não mede contribuição. Guilherme, por exemplo, tem poucos commits, mas fez mudanças estruturais grandes.

---

## Retrospectiva

### O que foi bem
- Todos os 7 entregáveis do README foram concluídos.
- Todo o time contribuiu e as tarefas se distribuíram entre as pessoas.
- O trabalho por versões (V01, V02...) e o AHT "teste" evitaram perder versões antigas.

### O que pode melhorar
- **Trabalho concentrado no fim:** 23 dos 30 commits do Sprint 3 foram em 27 e 28/09, e houve um vazio de 16 a 19/09.
- **Etapas fora de ordem:** brainstorm e mapa mental vieram depois do 5W2H e do Doc de Visão, como a própria ata reconhece.
- **Retrabalho de estrutura:** as pastas foram renomeadas 4 vezes (03/09, 15/09 duas vezes e 20/09), e o AHT teve versões duplicadas.
- **Commits pouco descritivos:** há vários "testando o erro", "Commit #3" e "aht".
- **Autores fragmentados:** 16 nomes para 7 pessoas. Vale configurar `git config user.name` e `user.email` no início de cada projeto.

---

## Próximo sprint (Sprint 4: implementação AP2)

- [ ] Apresentar o projeto e anotar o feedback do professor.
- [ ] Criar a estrutura HTML/CSS no VS Code (a ata de 10/09 já sugeria começar cedo).
- [ ] Implementar a landing page e as telas do protótipo, incluindo o agendamento de aula experimental.
- [ ] Definir a Definition of Done, por exemplo "revisado por outra pessoa e com commit descritivo".
- [ ] Distribuir as tarefas desde o início do sprint, para não deixar tudo para os últimos dias.
