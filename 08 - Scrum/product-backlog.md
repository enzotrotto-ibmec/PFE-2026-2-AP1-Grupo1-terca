# Product Backlog

Backlog do produto da Equipe 1, priorizado pelo método **MoSCoW** (Must / Should / Could / Won't). Os itens foram derivados das demandas do cliente (`07 - Demandas-cliente/`), dos entregáveis exigidos pela disciplina e do Documento de Visão.

---

## Épico A: Descoberta e requisitos

| ID | História de usuário / tarefa | Critério de aceitação | Prioridade | Sprint | Status |
|---|---|---|---|---|---|
| PB-01 | Como equipe, quero ter a transcrição completa da 1ª reunião com o cliente, para não perder nenhuma informação. | Transcrição em Markdown no repositório. | Must | 1 | Concluído |
| PB-02 | Como equipe, quero uma versão tratada da 1ª reunião só com as demandas do cliente, para usar como base do planejamento. | Demandas organizadas por tópico, sem falas soltas. | Must | 1 | Concluído |
| PB-03 | Como equipe, quero transcrever e tratar a 2ª reunião com o cliente, para refinar arquitetura, públicos e diretrizes visuais. | Transcrição + demandas com checklist de ações. | Must | 3 | Concluído |

## Épico B: Planejamento

| ID | História de usuário / tarefa | Critério de aceitação | Prioridade | Sprint | Status |
|---|---|---|---|---|---|
| PB-04 | Como equipe, quero um 5W2H da PKZ Lab, para ter um plano de ação claro para a marca. | As 7 perguntas respondidas com base nas demandas. | Must | 2 | Concluído |
| PB-05 | Como equipe, quero um 5W2H do Studio One to One, pelo mesmo motivo. | Idem PB-04. | Must | 2 | Concluído |
| PB-06 | Como equipe, quero um brainstorm sobre dores e melhorias do site, para levantar ideias sem filtro. | Documento com diagnóstico, ideias e priorização. | Must | 3 | Concluído |
| PB-07 | Como equipe, quero um mapa mental das ideias, para visualizar a relação entre os temas. | Imagem do mapa mental no repositório. | Must | 3 | Concluído |
| PB-08 | Como cliente, quero um Documento de Visão, para ter alinhado o que será construído e por quê. | Problema, stakeholders, solução, premissas, restrições e escopo. | Must | 1 a 5 | Concluído |

## Épico C: Arquitetura e navegação

| ID | História de usuário / tarefa | Critério de aceitação | Prioridade | Sprint | Status |
|---|---|---|---|---|---|
| PB-09 | Como visitante, quero um caminho claro da Home até o agendamento, para conseguir marcar uma aula experimental sem ajuda. | AHT em PlantUML (.puml + .png) e hierarquia de tarefas em Markdown, cobrindo Home, One to One, PKZ e contato/agendamento. | Must | 3 a 5 | Concluído |

## Épico D: Protótipo de interface

| ID | História de usuário / tarefa | Critério de aceitação | Prioridade | Sprint | Status |
|---|---|---|---|---|---|
| PB-10 | Como visitante, quero uma página inicial que apresente as duas marcas e me deixe escolher uma, para ir direto ao que me interessa. | Telas da Home, One to One e PKZ no Figma. | Must | 2 | Concluído |
| PB-11 | Como visitante, quero agendar uma aula experimental escolhendo dia e horário, para conhecer o serviço antes de falar de preço. | Telas de contato, grade de horários e formulário (nome, telefone, CPF, observação) no Figma, para as duas marcas. | Must | 5 | Concluído |
| PB-12 | Como avaliador, quero acessar o protótipo e ver as telas no repositório. | Link do Figma + PNGs das telas em `06 - Protótipo da interface/`. | Must | 5 | Concluído |

## Épico E: Gestão do projeto

| ID | História de usuário / tarefa | Critério de aceitação | Prioridade | Sprint | Status |
|---|---|---|---|---|---|
| PB-13 | Como equipe, quero o repositório organizado em pastas numeradas com um README, para encontrar tudo facilmente. | Pastas `01` a `07` + README com status dos entregáveis. | Must | 1 a 4 | Concluído |
| PB-14 | Como equipe, quero registrar nossas reuniões internas em atas, para ter histórico das decisões. | Atas em `Ata-das-reuniões/`. | Should | 3, 5 | Concluído |
| PB-15 | Como equipe, quero ensaiar e apresentar o projeto, para entregar a AP1. | Ordem de falas definida e apresentação realizada. | Must | 5 | Concluído |
| PB-16 | Como professor, quero ver evidências do uso de Scrum, para avaliar a metodologia. | Pasta `08 - Scrum/` com papéis, backlog e sprints. | Must | 5 | Concluído |

## Épico F: Desenvolvimento do site (AP2)

| ID | História de usuário / tarefa | Critério de aceitação | Prioridade | Sprint | Status |
|---|---|---|---|---|---|
| PB-17 | Incorporar o feedback do professor da apresentação da AP1 ao backlog. | Itens novos/ajustados registrados aqui. | Must | 6 | A fazer |
| PB-18 | Como visitante, quero um hub com seletor PKZ / One to One com transição de cor, para escolher a marca. | Hub em HTML/CSS, sem telefone e sem preços. | Must | 6+ | A fazer |
| PB-19 | Como visitante adulto, quero a landing page do One to One com metodologia, serviços e contato. | Página com identidade e WhatsApp próprios. | Must | 6+ | A fazer |
| PB-20 | Como pai/responsável, quero a landing page da PKZ com uma seção "Para Pais", para confiar na segurança e na equipe. | Página com seção para pais e WhatsApp próprio. | Must | 6+ | A fazer |
| PB-21 | Como visitante, quero agendar a aula experimental pelo site. | Grade semanal + formulário com validação. | Must | 6+ | A fazer |
| PB-22 | Como visitante, quero ver profissionais, depoimentos, galeria, FAQ e localização. | Seções comuns implementadas nas duas landing pages. | Should | 6+ | A fazer |
| PB-23 | Como visitante, quero links "saiba mais" que rolam até a seção, sem trocar de página. | Navegação por âncoras com rolagem suave. | Should | 6+ | A fazer |
| PB-24 | Como visitante, quero acessar o site pelo celular. | Layout responsivo e acessível (contraste, textos alternativos). | Should | 6+ | A fazer |
| PB-25 | Como visitante, quero um hero com vídeos de treino em camadas de baixa opacidade (referência: abertura da Marvel). | Seção principal com vídeo de fundo. | Could | 6+ | A fazer |

## Fora do escopo atual (Won't: por enquanto)

Demandas registradas nas reuniões com o cliente, mas que dependem de área logada ou de sistema de gestão (ver seção 6.4 do Documento de Visão):

| ID | Item | Status |
|---|---|---|
| PB-26 | Cadastro/login de alunos com portal por marca | Fora do escopo |
| PB-27 | Agendamento de alunos ativos com créditos semanais, 6 vagas por horário e fila de espera | Fora do escopo |
| PB-28 | Gráficos de evolução com histórico completo, notas contextuais e resumos por IA | Fora do escopo |
| PB-29 | Duplo relatório (professor/aluno) e observações do treino anterior na agenda | Fora do escopo |
| PB-30 | Controle de retestes e parametrização de testes por idade/modalidade | Fora do escopo |
| PB-31 | Área de cobrança e pagamentos | Fora do escopo |
| PB-32 | Notificações via WhatsApp | Fora do escopo |
| PB-33 | Análise de desempenho / scout por vídeo | Fora do escopo |
