# Scrum: Equipe 1 (PKZ Lab & One to One)

Esta pasta documenta como a Equipe 1 aplicou o **Scrum** para organizar o trabalho da AP1 da disciplina Projeto Front-end (IBMEC 2026.2). Os registros foram montados com base no histórico de commits do repositório e nas atas de reunião da equipe (`Ata-das-reuniões/`).

## Conteúdo da pasta

```
08 - Scrum/
├── README.md            - papéis, eventos, artefatos e acordos do time
├── product-backlog.md   - backlog do produto priorizado (AP1 + AP2)
└── sprints/
    ├── sprint-01.md     - 25/08 a 31/08 - Descoberta
    ├── sprint-02.md     - 01/09 a 07/09 - Planejamento (5W2H) e 1º protótipo
    ├── sprint-03.md     - 08/09 a 14/09 - Visão, ideação e AHT
    ├── sprint-04.md     - 15/09 a 21/09 - Organização e refinamento
    └── sprint-05.md     - 22/09 a 29/09 - Fechamento e apresentação
```

---

## 1. Papéis (Scrum Team)

| Papel | Quem | Responsabilidades no projeto |
|---|---|---|
| **Product Owner** | Prof. Thiago Marcondes Santos | Define os entregáveis e os prazos, prioriza o que deve ser feito em cada etapa, aceita ou pede correções nas entregas e dá o feedback da apresentação. |
| **Scrum Master** | Enzo Trotto | Conduz as reuniões, remove impedimentos, mantém o repositório organizado (README, estrutura de pastas) e registra as atas. |
| **Time de Desenvolvimento** | Alexia Schmid, Bernardo Gomes, Bernardo Nemirovsky, Gabriel Góis, Guilherme Macedo, João Pedro Ferreira | Produzem os entregáveis (transcrições, 5W2H, brainstorm, mapa mental, AHT, protótipo) e se auto-organizam na divisão das tarefas. |

**Cliente / stakeholder:** PKZ Lab & One to One - fonte das demandas levantadas nas reuniões com o cliente, que a equipe transformou em itens do Product Backlog.

---

## 2. Eventos

| Evento | Como fizemos | Duração |
|---|---|---|
| **Sprint** | Sprints de **1 semana** (segunda a domingo), alinhadas às aulas de terça-feira. | 1 semana |
| **Sprint Planning** | No início da semana, após a aula, o time escolhe os itens do Product Backlog para a sprint e divide as tarefas entre os membros. | ~30 min |
| **Daily Scrum** | Reunião rápida no Discord: cada membro informa o que fez, o que vai fazer e se tem algum impedimento. | ~15 min |
| **Sprint Review** | Revisão dos entregáveis no repositório (commits) e, quando possível, validação com o cliente/professor. | ~30 min |
| **Sprint Retrospective** | Ao fim da sprint, o time lista o que funcionou, o que não funcionou e define ações de melhoria para a próxima. | ~15 min |

As dailies e as demais reuniões acontecem no **Discord** (com compartilhamento de tela); as reuniões mais longas estão registradas em `Ata-das-reuniões/`. Fora das reuniões, a comunicação por mensagem é feita pelo WhatsApp e pelo Discord.

---

## 3. Artefatos

| Artefato | Onde está |
|---|---|
| **Product Backlog** | [`product-backlog.md`](product-backlog.md) |
| **Sprint Backlog** | Seção "Sprint Backlog" de cada arquivo em [`sprints/`](sprints/) |
| **Incremento** | Os próprios entregáveis versionados no repositório (pastas `01` a `07`) |

### Meta do Produto (Product Goal)

> Entregar o planejamento completo e o protótipo interativo de um site institucional único para a PKZ Lab e o Studio One to One - com portal de entrada comum e uma landing page por marca - que leve o visitante a agendar uma aula experimental (AP1), e depois implementá-lo em HTML/CSS (AP2).

---

## 4. Acordos do time

### Definition of Ready (DoR): um item pode entrar na sprint quando:
- Está escrito como história de usuário ou tarefa clara, com critério de aceitação.
- Está ligado a uma demanda do cliente ou a um entregável exigido pela disciplina.
- Tem um responsável definido na Sprint Planning.

### Definition of Done (DoD): um item só está pronto quando:
- O arquivo está no repositório, na pasta numerada correta.
- Foi revisado por pelo menos mais um membro da equipe.
- Está consistente com as demandas do cliente (`07 - Demandas-cliente/`) e com o Documento de Visão.
- Imagens/diagramas têm a versão final exportada (PNG) junto do arquivo-fonte (ex.: `.puml`).
- O status do entregável foi atualizado no `README.md` principal.

### Convenções de trabalho
- **Git:** commits pequenos e descritivos em português, direto na `main`; sempre dar `git pull` antes de começar para evitar conflitos de merge.
- **Versões:** versões antigas são mantidas com o sufixo "(VERSÃO ANTIGA)" / "(desatualizado)" até a versão nova ser aprovada.
- **Comunicação:** Discord para as dailies e reuniões, WhatsApp e Discord para mensagens, Figma para o protótipo, GitHub para os entregáveis.

---

## 5. Contribuição por pessoa (AP1)

Commits de 29/08 a 29/09/2026 (108 no total), com os nomes de autor unificados (o repositório tem 16 nomes de autor para 7 pessoas).

| Pessoa | Commits | Foco principal |
|---|---|---|
| João Pedro Ferreira | 22 | Transcrições, demandas, 5W2H, brainstorm |
| Enzo Trotto | 22 | README, estrutura, Documento de Visão, atas (SM) |
| Bernardo Nemirovsky | 17 | 5W2H, brainstorm, protótipo |
| Alexia Schmid | 16 | AHT, painel, fluxo de agendamento |
| Gabriel Góis | 12 | AHT, ajustes e versão final |
| Bernardo Gomes | 11 | SCRUM, Mapa mental e AHT |
| Guilherme Macedo | 5 | AHT inicial, PNGs, organização de pastas |

> Número de commits não mede contribuição: Guilherme, por exemplo, tem poucos commits, mas fez mudanças estruturais grandes.

---

## 6. Roadmap

| Sprint | Período | Objetivo | Status |
|---|---|---|---|
| [Sprint 1](sprints/sprint-01.md) | 25/08 - 31/08 | Entender o cliente e estruturar o repositório | Concluída |
| [Sprint 2](sprints/sprint-02.md) | 01/09 - 07/09 | Planos 5W2H das duas marcas e primeiras telas do protótipo | Concluída |
| [Sprint 3](sprints/sprint-03.md) | 08/09 - 14/09 | Documento de Visão, brainstorm, mapa mental, AHT e 2ª reunião com o cliente | Concluída |
| [Sprint 4](sprints/sprint-04.md) | 15/09 - 21/09 | Organizar o repositório e refinar a AHT | Concluída |
| [Sprint 5](sprints/sprint-05.md) | 22/09 - 29/09 | AHT final, fluxo de agendamento no protótipo e apresentação | Concluída |
| Sprints 6+ | 30/09 - 17/11 | AP2: implementação em HTML/CSS com base no feedback do professor | Planejada |
