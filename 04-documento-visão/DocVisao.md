# Documento de Visão
## Projeto PKZ Lab & One to One — Site Institucional

**Disciplina:** Projeto Frontend (turma de terça-feira)
**Professor:** Thiago Marcondes Santos
**Instituição:** IBMEC
**Semestre:** 2026.2
**Equipe:** Alexia Schmid, Bernardo Gomes, Bernardo Nemirovsky, Enzo Trotto, Gabriel Góis, Guilherme Macedo, João Pedro Ferreira

---

## 1. Introdução

Este documento tem como objetivo descrever, em alto nível, o problema enfrentado pela **PKZ Lab & One to One** (marca PlayMakerz), as necessidades levantadas junto ao cliente, o público a ser atendido pela solução e a visão geral da proposta a ser desenvolvida pela equipe ao longo do projeto de avaliação da disciplina Projeto Frontend.

Ele serve como base de alinhamento entre a equipe e o cliente sobre **o que será construído e por quê**, antes do início da fase de arquitetura de informação (AHT) e prototipação da interface. Nesta etapa do projeto, o trabalho é de **planejamento** — não há alteração no site real do cliente.

---

## 2. Descrição do Problema

| | |
|---|---|
| **O problema de** | falta de um canal digital próprio e profissional da PKZ |
| **afeta** | a PKZ/PlayMakerz e seus potenciais clientes (atletas de alto rendimento e praticantes de todos os esportes) |
| **e tem como impacto** | baixo alcance digital, dificuldade de qualificar novos clientes, comunicação incompleta do valor do CT e dependência de intermediários no funil de aquisição |
| **uma boa solução seria** | um site institucional próprio, que centralize informações sobre os serviços, a equipe, os diferenciais e os canais de contato da PKZ |

**Contexto atual:** a aquisição de clientes da PKZ é hoje concentrada em indicações e em um funil digital informal (Instagram → landing page em bio → atendimento via assistente no WhatsApp). Esse fluxo gera atrito, depende de intermediação humana para qualificar o interesse do cliente e não comunica adequadamente os diferenciais técnicos do CT — em especial as avaliações físicas com validação acadêmica e o suporte multidisciplinar (treino físico, nutrição e fisioterapia).

Como consequência, potenciais clientes não conseguem explorar os serviços de forma autônoma antes do primeiro contato, e a ausência de presença digital própria compromete a credibilidade e o profissionalismo percebido da marca, limitando o crescimento ao raio de indicações dos clientes atuais.

---

## 3. Posicionamento do Produto

> Para a **PKZ Lab & One to One**, que atende atletas de alto rendimento e praticantes de todos os esportes no seu Centro de Treinamento na Barra da Tijuca (RJ), o **site institucional PKZ** é um canal digital próprio que centraliza serviços, equipe, diferenciais e contato. Diferentemente da situação atual — dependente de Instagram, uma landing page genérica e atendimento manual via WhatsApp — o novo site apresenta a marca de forma coesa, profissional e autônoma, reduzindo o atrito no primeiro contato do potencial cliente com o CT.

---

## 4. Stakeholders e Usuários

| Stakeholder / Usuário | Papel no projeto |
|---|---|
| **PKZ Lab & One to One (PlayMakerz)** | Cliente contratante; validador das demandas e do protótipo final |
| **Treinadores físicos, nutricionistas e fisioterapeutas do CT** | Equipe cujos serviços e diferenciais precisam ser comunicados no site |
| **Atletas de alto rendimento e praticantes de esportes (leads/potenciais clientes)** | Público-alvo do site; usuários que buscarão informações e o primeiro contato |
| **Pais/responsáveis de atletas** | Público secundário, interessado em credibilidade, resultados e formas de contato |
| **Equipe do projeto (alunos de Engenharia da Computação — IBMEC)** | Responsável por planejar e prototipar a solução |
| **Professor Thiago Marcondes Santos** | Avaliador acadêmico do entregável |

---

## 5. Visão Geral da Solução (escopo desta etapa)

O produto desta etapa é um **protótipo de site institucional** para a PKZ, cobrindo as demandas do cliente diretamente relacionadas ao canal web. Com base nas demandas levantadas na reunião com o cliente, o site deve contemplar:

- **Apresentação institucional:** serviços oferecidos no CT (treinamento, nutrição, fisioterapia e avaliações físicas com validação acadêmica), equipe e diferenciais da PKZ e do One to One.
- **Portfólio:** fotos e vídeos dos treinos, tanto da PKZ quanto do One to One.
- **Identidade visual coesa:** apresentação mais profissional e "com mais glamour" das duas marcas, hoje descrita como carente de acabamento.
- **Canal de contato:** opção de contato via WhatsApp diretamente pelo site.
- **Cadastro do aluno:** possibilidade de o aluno se cadastrar pelo próprio site, gerando login e senha.
- **Ponte site ↔ aplicativo:** link/integração entre o site e o aplicativo do CT, facilitando o download do app e a inscrição do aluno.

### Fora do escopo desta etapa

O cliente manifestou diversas demandas que dizem respeito ao **sistema/aplicativo de gestão do CT** (agendamento, créditos semanais, relatórios e dashboards, gráficos de evolução, duplo relatório, cobrança, notificações via WhatsApp, análise de desempenho/scout, etc.). Essas demandas são relevantes para o negócio da PKZ como um todo, mas **não fazem parte do escopo do site institucional** desta entrega — ficam registradas aqui como contexto e como possíveis direcionamentos para etapas futuras do relacionamento entre a PKZ e a equipe de desenvolvimento.

---

## 6. Premissas

- O cliente (PKZ) está disponível para validar entregas e esclarecer dúvidas ao longo do semestre.
- As informações levantadas na reunião com o cliente (demandas tratadas) refletem fielmente as necessidades reais do negócio.
- O projeto é viabilizado como parceria extensionista entre a PKZ e a equipe de alunos de Engenharia da Computação do IBMEC, sem custo direto para o cliente nesta fase.
- Não haverá, nesta etapa, integração real com sistemas de terceiros (WhatsApp Business, gateways de pagamento, aplicativo do CT) — eventuais integrações citadas pelo cliente serão representadas apenas no nível de protótipo/planejamento.

## 7. Restrições

- **Escopo:** nenhuma alteração é feita no site real da PKZ; o entregável é um protótipo (planejamento + interface), não uma implementação em produção.
- **Prazo:** protótipo interativo e documentos devem estar prontos em **29/09/2026**; entrega final do projeto em **17/11/2026**.
- **Início do projeto:** 03/08/2026.
- **Ferramentas definidas para o projeto:** Visual Studio Code, Figma, GitHub, Git, WhatsApp e Discord (comunicação de equipe); HTML, CSS, JavaScript e React como stack de referência para a solução proposta.
- **Local de desenvolvimento:** IBMEC (Rio de Janeiro), com reuniões remotas complementares entre os membros da equipe.

---

## 8. Referências

- `07-reuniao-cliente/02-demandas-cliente.md` — demandas do cliente organizadas por tópico
- `03-5w2h/5w2h.md` — plano de ação (What, Why, Where, When, Who, How, How much)