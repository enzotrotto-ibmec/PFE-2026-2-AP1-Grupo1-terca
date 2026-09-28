# Documento de Visão
## Projeto PKZ Lab & Studio One to One

### *Disciplina: Projeto Front-end (turma de terça-feira)*

### Professor Thiago Marcondes Santos

---
**Equipe 1:**
- Alexia Schmidt
- Bernardo Gomes
- Bernardo Nemirovsky
- Enzo Trotto (SM)
- Gabriel Góis
- Guilherme Macedo
- João Pedro Ferreira

---

## 1. Introdução

Este documento descreve o problema enfrentado pelas empresas **PKZ Lab (PlayMakerz)** & **Studio One to One**, as necessidades levantadas junto ao cliente nas duas reuniões realizadas, os públicos a serem atendidos e a visão geral da solução proposta pela equipe no projeto de avaliação da disciplina Projeto Front-end.

Ele serve como base de alinhamento entre a Equipe 1 e o cliente sobre **o que será construído e por quê**. Nesta etapa, o trabalho é de **planejamento e prototipação**: nenhuma alteração é feita no site real do cliente.

---

## 2. Descrição do Problema

| | |
|---|---|
| **O problema:** | ausência de um canal digital próprio e profissional para a PKZ Lab e para o Studio One to One |
| **Afeta:** | as duas empresas e seus potenciais clientes: atletas infantojuvenis e seus responsáveis (PKZ) e adultos em busca de treino individualizado (One to One) |
| **Tem como impacto:** | baixo alcance digital, baixa visibilidade em buscadores (SEO), dificuldade de qualificar novos clientes, comunicação incompleta do valor de cada marca e dependência de atendimento manual no funil de aquisição |
| **Uma boa solução seria:** | um site institucional único, com um portal de entrada comum e uma landing page para cada marca, que apresente serviços, metodologia, equipe e diferenciais e conduza o visitante ao agendamento de uma aula experimental |

**Contexto atual:** a aquisição de clientes das duas marcas depende principalmente de indicações e de um funil digital informal: Instagram (@playmakerz_pkz / @studioonetoone) → página de links na bio → atendimento manual via WhatsApp. Esse fluxo gera atrito, exige que uma atendente responda a dúvidas básicas e recorrentes (como funciona a metodologia, horário de funcionamento e valores) e não comunica adequadamente os diferenciais do Centro de Treinamento, em especial as avaliações físicas com validação acadêmica e o suporte multidisciplinar (treino físico, nutrição e fisioterapia).

Como consequência, potenciais clientes não conseguem conhecer os serviços de forma autônoma antes do primeiro contato. Para marcas que trabalham com um serviço premium e de maior valor, a falta de presença digital própria também compromete a credibilidade percebida e limita o crescimento ao raio de indicações dos clientes atuais.

---

## 3. Contexto das Marcas

A PKZ Lab e o Studio One to One são **empresas juridicamente independentes**, geridas pela mesma equipe e instaladas em espaços vizinhos na mesma galeria, na Barra da Tijuca (RJ). O One to One surgiu primeiro; a PKZ Lab, cerca de 6 a 7 meses depois.

As duas marcas compartilham a mesma base de identidade visual (paleta azul e branco) e o mesmo objetivo final, mas aplicam **métodos diferentes para públicos diferentes**. O cliente pediu que o site deixe clara essa identidade dupla e, ao mesmo tempo, unificada.

| | **PKZ Lab (PlayMakerz)** | **Studio One to One** |
|---|---|---|
| **Público** | Crianças e adolescentes de 7 a 15 anos, atletas de qualquer modalidade | Adultos de 17 a 90 anos, atletas amadores e público geral |
| **Proposta** | Treinamento esportivo de alto rendimento, com ciência do esporte e avaliações físicas com validação acadêmica | Musculação com treinamento individualizado e acompanhamento exclusivo de personal trainer |
| **Frase de posicionamento (fornecida pelo cliente)** | "Ciência, tecnologia e metodologia para transformar potencial em performance." | "Treinamentos individualizados para potencializar o que você é de melhor." |

---

## 4. Posicionamento do Produto

> Para a **PKZ Lab** e o **Studio One to One**, que atendem, respectivamente, atletas infantojuvenis de alto rendimento e adultos em busca de treino individualizado no Centro de Treinamento da Barra da Tijuca (RJ), o **Portal PKZ & One to One** é um site institucional próprio que apresenta as duas marcas em um ponto de entrada comum e dedica a cada uma sua própria landing page, com serviços, metodologia, equipe, diferenciais e contato. Diferentemente da situação atual, que depende do Instagram, de páginas de links genéricas e de atendimento manual via WhatsApp, o novo site comunica as marcas de forma coesa e profissional, responde às dúvidas mais frequentes de forma autônoma e conduz o visitante diretamente ao agendamento de uma aula experimental.

---

## 5. Stakeholders e Usuários

**Disciplina:** Projeto Front-end (turma de terça-feira) — Prof. Thiago Marcondes Santos

| Stakeholder / Usuário | Papel no projeto |
|---|---|
| **PKZ Lab & One to One (PlayMakerz)** | Cliente contratante; validador das demandas e do protótipo final |
| **Treinadores físicos, nutricionistas e fisioterapeutas do CT** | Equipe cujos serviços e diferenciais precisam ser comunicados no site |
| **Atletas de alto rendimento e praticantes de esportes (leads/potenciais clientes)** | Público-alvo do site; usuários que buscarão informações e o primeiro contato |
| **Pais/responsáveis de atletas** | Público secundário, interessado em credibilidade, resultados e formas de contato |
| **Equipe do projeto (alunos de Engenharia da Computação - IBMEC)** | Responsável por planejar e prototipar a solução |

---

## 6. Visão Geral da Solução

### 6.1. Arquitetura do site

O site segue o modelo **hub com páginas específicas** aprovado pelo cliente na segunda reunião, com navegação por rolagem dividida em seções (referências citadas pelo cliente: sites da Nubank e da Apple):

1. **Portal / página inicial (hub):** apresenta as duas marcas juntas, de forma neutra, sem números de telefone e sem preços. O visitante escolhe entre PKZ e One to One por meio de um seletor interativo com transição visual.
2. **Landing page de cada marca:** identidade visual, imagens, tom e contato próprios de cada empresa, com navegação por âncoras entre as seções da página.
3. **Fluxo de contato e agendamento:** comum às duas marcas, leva o visitante do botão de contato até o agendamento de uma aula experimental.

### 6.2. Funcionalidades contempladas

- **Portal de escolha da marca:** tela inicial com apresentação conjunta e acesso às duas landing pages; troca rápida entre as marcas pelo cabeçalho.
- **Apresentação institucional de cada marca:** sobre a empresa, metodologia, serviços (treinamento, nutrição, fisioterapia e avaliações físicas com validação acadêmica) e diferenciais.
- **Seção para pais e responsáveis (PKZ):** segurança, supervisão, qualificação da equipe e comunicação com a família.
- **Equipe e profissionais:** foto e anos de experiência de cada profissional, em posição introdutória na página.
- **Portfólio e galeria:** fotos e vídeos dos treinos e do espaço (aparelhos e ambiente), usando preferencialmente imagens conceituais em vez de rostos identificáveis; fotos de alunos somente com autorização.
- **Depoimentos e breve história da empresa.**
- **Perguntas frequentes (FAQ):** como funciona a metodologia (adaptável a qualquer esporte) e horário de funcionamento.
- **Contato via WhatsApp:** um número próprio em cada landing page, nunca no portal comum.
- **Agendamento de aula experimental:** escolha de dia e horário em uma grade semanal e preenchimento de dados pessoais (nome, telefone, CPF e observação opcional). A aula experimental é o principal ponto de conversão do site.
- **Localização:** endereço e mapa do CT nas duas landing pages.
- **Redes sociais:** links para o Instagram de cada marca.
- **Identidade visual coesa:** paleta azul e branco comum às duas marcas, com acabamento mais profissional e identidades distintas, porém harmônicas.

### 6.3. Diretrizes definidas pelo cliente

- **Valores não serão publicados no site.** Os preços são negociáveis conforme o pacote, e o cliente prefere que o visitante conheça o serviço na aula experimental antes de discutir valores.
- **Sem personificação da marca:** o site não deve girar em torno da imagem de uma única pessoa.
- **Hierarquia de informação:** primeiro despertar curiosidade (seção principal com vídeo ou imagem), depois contato de fácil acesso, divisão das marcas, profissionais, depoimentos e, mais abaixo, o conteúdo informativo detalhado.

### 6.4. Fora do escopo do protótipo desta etapa

As demandas abaixo foram registradas nas reuniões com o cliente e são relevantes para o negócio, mas dizem respeito à **área logada do cliente** ou ao **sistema de gestão do CT**. Ficam documentadas como direcionamento para etapas futuras:

- Cadastro e login de alunos, com portal separado por marca (portal adulto no One to One e portal do atleta/responsável na PKZ).
- Integração entre o site e o aplicativo do CT (download do app e inscrição).
- Agendamento de clientes ativos com créditos semanais, limite de 6 atletas por horário, fila de espera e janela de cancelamento/reagendamento.
- Relatórios, dashboards e gráficos de evolução com histórico completo, notas contextuais e resumos gerados por IA.
- Duplo relatório (professor e aluno) e observações do treino anterior na agenda do professor.
- Controle de retestes físicos e parametrização de testes por idade e modalidade.
- Área de cobrança e pagamentos.
- Notificações via WhatsApp.
- Análise de desempenho e scout por vídeo.

---

## 7. Premissas

- O cliente está disponível para validar entregas e esclarecer dúvidas ao longo do semestre.
- As demandas registradas nas duas reuniões com o cliente refletem as necessidades reais do negócio.
- O cliente fornecerá os arquivos de logo, os códigos das cores e o material de fotos e vídeos necessários; novas fotos profissionais podem ser antecipadas, se necessário.
- O projeto é viabilizado como parceria extensionista entre o cliente e a equipe de alunos de Engenharia da Computação e de Software do IBMEC, sem custo direto para o cliente nesta fase.
- Não haverá, nesta etapa, integração real com sistemas de terceiros (WhatsApp Business, gateways de pagamento, aplicativo do CT). Integrações citadas pelo cliente são representadas apenas no nível de protótipo e planejamento.

---

## 8. Restrições

- **Escopo:** nenhuma alteração é feita no site real do cliente; o entregável desta etapa é um protótipo (planejamento e interface), não uma implementação em produção.
- **Prazos:** início em **03/08/2026**; protótipo interativo e documentos até **29/09/2026**; entrega final do projeto em **17/11/2026**.
- **Ferramentas:** Visual Studio Code, Figma, GitHub, Git, WhatsApp e Discord (comunicação da equipe).
- **Tecnologias de referência:** HTML, CSS, JavaScript e React.
- **Local de desenvolvimento:** IBMEC (Rio de Janeiro), com reuniões remotas complementares entre os membros da equipe.

---

## 9. Referências

- `01 - brainstorm/brainstorm.md`: levantamento de ideias e matriz de priorização
- `02 - Mapa-mental/Mapa mental.png`: mapa mental do projeto
- `03 - 5w2h/5w2h_PKZ.md` e `03 - 5w2h/5w2h_OneToOne.md`: planos de ação de cada marca
- `05 - AHT/AHT.md` e `05 - AHT/AHT Versão Final.puml`: fluxo de navegação do site
- `06 - Protótipo da interface/`: telas do protótipo e link para o [protótipo interativo no Figma](https://www.figma.com/design/p9MEkL4mP9m6SogMw3rMru/PrototipoPFE?node-id=0-1&t=TJD0jx6o964L1fip-1)
- `07 - Demandas-cliente/Reunião-Cliente1/demandas-cliente.md`: demandas da primeira reunião com o cliente
- `07 - Demandas-cliente/Reunião-Cliente2/demandas-cliente.md`: demandas da segunda reunião com o cliente
- `Ata-das-reuniões/10/10Sep.md` e `Ata-das-reuniões/10/27Sep.md`: atas das reuniões internas da equipe