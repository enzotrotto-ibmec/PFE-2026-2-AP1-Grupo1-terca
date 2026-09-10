# Sessão de Brainstorming – PKZ Lab & Studio One to One

> **Disciplina:** Projeto Frontend (Turma de Terça-feira) – IBMEC 2026.2  
> **Professor:** Thiago Marcondes Santos  
> **Equipe 1:** Alexia Schmidt, Bernardo Gomes, Bernardo Nemirovsky, Enzo Trotto (SM), Gabriel Góis, Guilherme Macedo, João Pedro Ferreira  
> **Objetivo:** Levantamento livre de ideias, análise de dores, ideação de funcionalidades, arquitetura e propostas de valor para guiar a reestruturação da presença digital e a criação do protótipo de interface das marcas **PKZ Lab** e **Studio One to One**.

---

## 1. Contexto & Diagnóstico Atual

### 1.1. Cenário Encontrado

- **Dualidade de Marcas:** O Centro de Treinamento (localizado na Av. Armando Lombardi, 949, Barra da Tijuca - RJ) abriga duas operações com propostas distintas:
  - **PKZ Lab (PlayMakerz):** Treinamento físico voltado para atletas de alto rendimento de diversos esportes, com forte validação acadêmica, fisiologia e preparação esportiva avançada.
  - **Studio One to One:** Treinamento individualizado com acompanhamento exclusivo de personal trainers, com foco em reabilitação física, longevidade e bem-estar em um espaço reservado e premium.
- **Funil Atual Fragmentado:** A captação de novos clientes depende quase que exclusivamente de indicações ("boca a boca") e de um fluxo digital informal:
  $$\text{Instagram (@playmakerz\_pkz / @studioonetoone)} \longrightarrow \text{Linktree/Bio.site} \longrightarrow \text{Atendente manual no WhatsApp}$$
- **Dores Principais Identificadas:**
  - Inexistência de um site próprio que centralize a identidade institucional de ambas as marcas.
  - Dependência excessiva de triagem humana no WhatsApp para esclarecimento de dúvidas básicas sobre modalidades, estrutura e equipe.
  - Falta de autoridade visual no ambiente digital que reflita o alto padrão do CT e justifique o valor dos serviços.
  - Baixa visibilidade nos mecanismos de busca (SEO) para pessoas que buscam ativamente por treino de alta performance ou personal trainer na Barra da Tijuca.
  - Comunicação dispersa do suporte multidisciplinar oferecido no espaço (treinamento físico, fisioterapia e nutrição).

---

## 2. Levantamento de Ideias e Oportunidades (Tempestade de Ideias)

### 2.1. Arquitetura da Solução & Divisão de Marcas

- **Landing Page Splash / Portal Unificado:**
  - Criar uma tela inicial com divisão conceitual e visual, permitindo ao visitante escolher seu objetivo logo no primeiro contato:
    - _“Quero alta performance esportiva e avaliação física”_ $\rightarrow$ **PKZ Lab**
    - _“Quero acompanhamento individualizado e exclusivo com personal”_ $\rightarrow$ **One to One**
- **Navegação Híbrida / Troca Rápida:**
  - Manter um seletor sutil no cabeçalho (_header_) para alternar facilmente entre os dois universos sem precisar retornar à tela inicial.
- **Identidades Visuais Distintas, porém Harmônicas:**
  - **PKZ Lab:** Design dinâmico, moderno, esportivo, focado em dados, ciência do esporte e superação.
  - **One to One:** Design minimalista, sofisticado, acolhedor, transmitindo exclusividade, saúde e atenção individual.

### 2.2. Ideias para o Website Institucional (Escopo Principal AP1)

- **Apresentação de Estrutura e Instalações:**
  - Galeria em carrossel e lightbox com fotos de alta resolução do CT, maquinário e áreas de convivência.
  - Vídeos curtos em loop mostrando os treinos em execução e o ambiente dinâmico do centro.
- **Corpo Técnico & Equipe Multidisciplinar:**
  - Cards detalhados de apresentação dos treinadores, nutricionistas e fisioterapeutas com qualificações acadêmicas e especialidades.
- **Metodologia & Validação Acadêmica:**
  - Seção explicativa e infográficos descomplicando como funcionam os testes físicos de alta tecnologia e o acompanhamento fisiológico contínuo.
- **Prova Social (Casos de Sucesso e Parcerias):**
  - Depoimentos de atletas e clientes assíduos destacando evolução real e reabilitação.
  - Exibição de escudos/marcas de modalidades e clubes que frequentam o CT.
- **Pontos de Contato & Conversão Ágil (CTA):**
  - Botão fixo/flutuante de WhatsApp direcionando diretamente para atendimento com mensagem pré-configurada por marca.
  - Formulário intuitivo para agendamento de visita presencial ou avaliação inicial.
  - Ponte de download do aplicativo do CT e link para cadastro/login de alunos.
- **Localização & Acessibilidade:**
  - Mapa interativo (Google Maps), fotos da fachada, facilidades de acesso/estacionamento e horários de funcionamento na Barra da Tijuca.

### 2.3. Ideias para o Sistema Interno e Aplicativo (Escopo Futuro / Longo Prazo)

_(Demandas levantadas na reunião com o cliente, catalogadas para orientação futura do ecossistema)_

- **Gestão de Créditos Semanais:** Sistema onde o aluno controla seus créditos de treino semanais (que renovam sem acumular) e gerencia agendamentos e cancelamentos de forma autônoma.
- **Dashboards Visuais de Evolução:** Relatórios descomplicados (estilo exames laboratoriais) para fácil interpretação dos pais e alunos, com gráficos de evolução temporal.
- **Sistema de Duplo Relatório:** Avaliação do treino preenchida pelo professor + feedback do aluno sobre a aula para a coordenação pedagógica.
- **Alerta de Retestes:** Notificação para a equipe técnica de quando um aluno atingiu o período de reavaliação física.
- **Módulo de Scout e Análise de Vídeo:** Solução para taguear partidas de futebol/esportes sem necessidade de reassistir ao mesmo vídeo para múltiplos atletas.

---

## 3. Matriz de Priorização (Impacto x Facilidade)

| Funcionalidade / Ideia                                 | Impacto no Negócio | Facilidade de Prototipação |      Prioridade para AP1      |
| ------------------------------------------------------ | :----------------: | :------------------------: | :---------------------------: |
| **Tela inicial com escolha PKZ Lab vs. One to One**    |     Altíssimo      |            Alta            |   **Essencial (Must have)**   |
| **Páginas institucionais de serviços e corpo docente** |        Alto        |            Alta            |   **Essencial (Must have)**   |
| **Portfólio com fotos e vídeos reais do CT**           |        Alto        |           Média            |   **Essencial (Must have)**   |
| **Botão de WhatsApp contextualizado para conversão**   |     Altíssimo      |            Alta            |   **Essencial (Must have)**   |
| **Ponte de direcionamento para o App e Cadastro**      |       Médio        |            Alta            |   **Essencial (Must have)**   |
| **Infográficos explicativos de metodologia de testes** |        Alto        |           Média            |  **Desejável (Should have)**  |
| **Formulário de agendamento de visita online**         |       Médio        |           Média            |  **Desejável (Should have)**  |
| **Sistema de créditos, agendamentos e dashboards**     |     Altíssimo      |           Baixa            | _Futuro / Fora do escopo web_ |
| **Módulo de Scout esportivo por vídeo**                |       Médio        |           Baixa            | _Futuro / Fora do escopo web_ |

---

## 4. Conexão com os Demais Entregáveis do Projeto

- **02 - Mapa Mental:** Mapear visualmente os eixos gerados aqui: Eixo Central (Portal CT) $\rightarrow$ Ramos: PKZ Lab, One to One, Institucional/Equipe, Conversão/Contato e Área do Aluno.
- **03 - 5W2H:** Estruturação operacional já validada para as duas marcas em `5w2h_PKZ.md` e `5w2h_OneToOne.md`.
- **04 - Documento de Visão:** Consolidação formal das necessidades de negócio, público-alvo, premissas e escopo de prototipação.
- **05 - AHT (Árvore Hierárquica de Tarefas):** Validação dos fluxos de navegação (Acesso $\rightarrow$ Escolha da marca $\rightarrow$ Serviços / Contato / Retorno).
- **06 - Protótipo da Interface:** Implementação no Figma aplicando sofisticação visual, consistência tipográfica, paleta alinhada ao posicionamento premium e usabilidade responsiva.
