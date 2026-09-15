#  **Demandas do cliente PKZLAB & One to One**

## Requerimentos

### Visão Geral do Negócio

One to One e PKZ Lab são **empresas juridicamente independentes**, geridas pela mesma pessoa/equipe, e que hoje, nas palavras do próprio cliente, são tratadas como uma coisa só ("hoje a gente trata tudo como PKZ e One to One, então é uma coisa só"). A One to One nasceu primeiro; a PKZ Lab nasceu de 6 a 7 meses depois. Fisicamente, ficam em espaços um de frente para o outro, dentro da mesma galeria, na Barra da Tijuca.

As duas marcas compartilham a mesma base de identidade visual ("a mesma camisa") — paleta de cores azul e branco — mas cada uma tem metodologia, público-alvo e posicionamento de mercado próprios.

**Frases de definição fornecidas pelo cliente (para uso literal no site):**

> **One to One:** "Treinamento individualizado para potencializar o que torna você único." *(posteriormente refinada para: "Treinamentos individualizados para potencializar o que você é de melhor.")*

> **PKZ Lab:** "Ciência, tecnologia e metodologia para transformar potencial em performance."

O cliente foi enfático ao dizer que o site precisa comunicar que as duas marcas são "duas juntas se torna o que nós somos" — a mesma metodologia central, aplicada de duas formas diferentes para dois públicos diferentes.

---

### Públicos-Alvo

| | **One to One** | **PKZ Lab** |
|---|---|---|
| **Faixa etária** | Adultos, de 17 a 90 anos | Crianças/adolescentes, de 7 a 15 anos (atletas infantojuvenis) |
| **Perfil** | Atletas amadores, público geral em busca de treinamento convencional | Atletas em busca de treinamento esportivo de alto rendimento e especializado |
| **Metodologia** | Treino de academia convencional; trabalho isolado por grupo muscular (ex: aparelho específico de puxada para fortalecer o dorsal) | "Sistema complexo" — treina as complexidades do movimento de forma integrada (ex: movimentos complexos sentado, exigindo estabilização simultânea de tronco e pescoço) |
| **Posicionamento** | Musculação / treino individualizado para adultos | Ciência do esporte, treinamento de alto rendimento infantojuvenil |

O cliente destacou que as duas abordagens buscam **o mesmo objetivo final**, mas aplicam **métodos diferentes** — essa identidade dupla e, ao mesmo tempo, unificada precisa ficar clara visual e textualmente em todo o site.

---

### Arquitetura e Fluxo do Site

O cliente aprovou um modelo de **hub com páginas específicas** ("hub-and-spoke"), citando os sites da Nubank e da Apple como referência (navegação por rolagem, dividida em sessões, com transições animadas).

**Fluxo:**
1. **Hub / Página inicial** — um ponto de entrada único e compartilhado, apresentando as duas marcas juntas, sem entrar a fundo em ferramentas específicas de nenhuma delas (sem números de telefone, sem dados de cliente logado aqui).
2. **Seleção de marca** — o usuário clica em "One to One" ou "PKZ" (os botões funcionam como um toggle, com transição/mudança de cor ao clicar).
3. **Landing Pages dedicadas** — cada clique leva a uma landing page específica da marca:
   - **Landing Page One to One:** identidade visual e imagens totalmente da One to One, explica a metodologia, traz o WhatsApp próprio da marca, login/cadastro para o portal do cliente adulto.
   - **Landing Page PKZ:** identidade visual e imagens totalmente da PKZ, explica sua metodologia, traz o WhatsApp próprio da marca, login/cadastro para o portal do atleta/responsável.
4. **Área de Login / Cliente** ("área de associado") — fica *dentro* da landing page de cada marca (não no hub compartilhado). É essa área que dá acesso a agendamento, relatórios de evolução e demais ferramentas exclusivas de cliente. Visitantes não logados veem apenas conteúdo informativo/institucional, voltado a despertar interesse.

**Menu de navegação superior (conforme esboçado pelo cliente):** One to One | PKZ | Planos | Agendar | Cadastre-se

**Distinção importante pedida pelo cliente:** precisam existir claramente duas experiências separadas —
- uma **área para o público geral** (informativa, persuasiva, sem necessidade de login), e
- uma **área para clientes já ativos** (atrás de login, funcional, baseada em dados).

---

### Requisitos Funcionais

#### Área Pública

- **Seção de Perguntas Frequentes (FAQ)** cobrindo as duas dúvidas mais recorrentes recebidas via WhatsApp:
  - Como funciona o treinamento/metodologia (com observação de que é adaptável a qualquer esporte, usando o exemplo do "piloto de kart" dado pelo cliente — a metodologia é flexível conforme a demanda física de cada esporte).
  - Horário de funcionamento.
- **Valores NÃO devem ser publicados no site.** O cliente foi bem claro: os preços são altamente negociáveis (pacote base de aproximadamente R$1.800, reduzido ao remover serviços como acompanhamento de psicólogo ou diminuir a frequência semanal), e mostrar um número de cara pode "espantar" o possível cliente — principalmente quem vem de fora da Barra. Em vez disso, o site deve direcionar o visitante para agendar uma **aula experimental**, onde o valor do serviço é demonstrado pessoalmente antes de qualquer discussão de preço.
- **CTA de "Fale conosco"** — botão de fácil acesso, idealmente um botão direto para o WhatsApp. Atenção: One to One e PKZ usam **dois números de WhatsApp diferentes** (o mesmo atendente responde por ambos) — cada número deve ficar na landing page da respectiva marca, não no hub compartilhado.
- **Navegação por âncora "saiba mais"** — ao clicar em um tópico (ex: "segurança"), a página deve rolar suavemente até a seção correspondente mais abaixo, em vez de abrir uma nova página.
- **Seção de Professores/Profissionais** — uma foto de cada professor mais os anos de experiência, posicionada como seção introdutória (não deve ser a primeira coisa que aparece na tela).
- **Seção de Depoimentos/Avaliações** e uma breve seção de história da empresa.
- **Galeria de interior/equipamentos** ("visual de interior") — mostrando os aparelhos e o ambiente de treino.
- **Lógica de agendamento e lista de espera:**
  - Cada horário comporta **6 atletas simultâneos**.
  - Incluir uma **fila de espera** para horários lotados.
  - Incluir um **tempo de antecedência para notificação/chegada** configurável (o cliente sugeriu de 10 a 20 minutos), considerando o tempo de deslocamento (o cliente citou como exemplo alguém vindo do Recreio, que não consegue chegar em 10 minutos).
  - Essa mesma lógica de antecedência deve reger também a **janela de reagendamento/cancelamento**.

#### Área Logada / Cliente

- **Fluxo de login/cadastro separado por marca** (portal adulto da One to One vs. portal de atleta/responsável da PKZ).
- **Portal do cliente One to One:** seleção de professor, agendamento de aulas, visualização de aulas anteriores e observações da sessão, informações gerais da marca.
- **Portal do cliente PKZ (visão do atleta/responsável):** gráficos de evolução/desempenho, aulas agendadas, mais informações.
- **Gráficos de evolução com histórico completo, não apenas comparação de dois pontos.** A ferramenta atual do cliente ("Lovable") só compara dois testes selecionados (ex: Teste 1 vs. Teste 4), perdendo os dados dos testes intermediários. O cliente quer que **todo o histórico de testes seja exibido como uma linha de tendência contínua** (por exemplo, a evolução da distância de salto ao longo de todas as sessões registradas).
- **Notas de observação contextual atreladas aos gráficos.** Números brutos podem parecer uma regressão quando, na verdade, representam uma melhora (exemplo real dado pelo cliente: um atleta que saltava 4,50m com uma perna e 3,58m com a outra — uma assimetria grande — passou a saltar 2,80m igualmente com as duas pernas; o número parece menor, mas a assimetria foi corrigida). A interface precisa permitir anexar notas/pop-ups explicativos a pontos ou intervalos específicos do gráfico, para que os pais não interpretem a tendência de forma equivocada.
- **Resumos narrativos gerados por IA para os gráficos.** O cliente já usa IA para gerar textos de análise de um único teste (ex: "o atleta demonstra boa capacidade de salto..."). Eles querem estender isso para sintetizar **vários testes juntos** em uma única narrativa (por exemplo, explicando uma tendência de correção ao longo de 3 a 4 sessões), com um **campo editável** para que a equipe possa corrigir erros da IA antes de publicar para o cliente.
- **Notas de agendamento voltadas ao professor.** A agenda de agendamento atual mostra apenas o nome do atleta. O cliente quer que cada sessão agendada exiba **as observações da sessão anterior daquele atleta** (ex: "sentiu dor no ombro", "treino de ontem teve ênfase em salto"), para que um professor diferente, ao atender no dia seguinte, saiba o que foi feito e possa ajustar o foco do treino em vez de repetir sem saber.
- **(Exploratório/ainda não decidido) Visualização resumida de atributos** — o cliente cogitou a ideia de um gráfico simplificado ao estilo "de videogame" (referenciando os atributos de jogadores do FIFA, ex: "94 de pace") para dar aos pais/equipe uma leitura intuitiva e rápida da média de atributos de um atleta. O próprio cliente sinalizou que essa ideia ainda está em discussão interna, não sendo um requisito fechado ainda — vale prototipar como algo desejável, mas não prioritário.

---

### Diretrizes Visuais e de UI

- **Paleta de cores:** azul e branco, idêntica nas duas marcas ("a mesma camisa, então a paleta é branco e azul, pra tudo"). O cliente possui os códigos exatos das cores e os arquivos de logo salvos no Google Drive e vai compartilhar/baixar para a equipe.
- **Fotografia:** as fotos atuais estão desatualizadas. Uma fotógrafa profissional está agendada para fazer novo material; o cliente se ofereceu para **antecipar essa sessão de fotos** caso a equipe precise de imagens atualizadas com urgência — vale confirmar esse ponto com ele.
- **Sem personificação da marca.** O cliente não quer que o site gire em torno do rosto/identidade de uma única pessoa. Preferências indicadas:
  - Imagens conceituais — mostrando o uniforme/identidade visual da marca, em vez de rostos identificáveis.
  - Caso se use foto de algum aluno, é necessário **obter autorização explícita dele antes.**
  - **Efeito preferido:** um fundo em camadas, com baixa opacidade, mostrando cenas de treino sobrepostas — o cliente citou como referência a abertura dos filmes da Marvel (várias cenas de treino simultâneas, com opacidade baixa, ao fundo). **Vídeo é preferível a foto estática** para esse efeito, se for viável.
  - O cliente já possui vídeos institucionais prontos (formatos vertical e diagonal) que podem ser atualizados/reaproveitados para isso.
- **Hierarquia de informação (de cima para baixo), inspirada na navegação por rolagem da Nubank/Apple:**
  1. **Seção principal (hero):** um vídeo ou imagem curta que desperte curiosidade sobre "quem somos", sem explicar demais de cara — como o site da Nubank faz ao instigar antes de explicar.
  2. **CTA de contato de fácil acesso** (botão de WhatsApp) posicionado próximo ao topo.
  3. **Links de âncora "saiba mais"** que rolam até a seção relevante.
  4. **Divisão de marcas** — One to One vs. PKZ, apresentada como dois botões/toggles interativos, com transição de cor ao passar o mouse/clicar.
  5. **Seção de Professores/Profissionais** — tom introdutório, posicionada depois da divisão de marcas, não antes.
  6. **Depoimentos e breve história da empresa.**
  7. Conteúdo informativo/funcional mais aprofundado (detalhes próximos ao FAQ, ferramentas específicas de cliente) posicionado **mais abaixo**, já que a maioria dos primeiros visitantes ainda não é cliente e busca informações gerais primeiro; clientes recorrentes conseguem rolar a página até encontrar o que precisam.
- **Landing pages** (One to One / PKZ) devem trazer o número de telefone, as imagens e o tom específicos de cada marca — o hub compartilhado deve permanecer neutro e sem números de telefone.

---

### Checklist de Ações

- [ ] Construir o **Hub/Página inicial** compartilhado, com vídeo/imagem de destaque, CTA de contato e seção de seleção de marca (sem preços, sem números de telefone aqui).
- [ ] Construir duas **Landing Pages** separadas (One to One, PKZ), cada uma com sua própria identidade visual, número de WhatsApp e ponto de entrada para login/cadastro.
- [ ] Implementar a **animação de transição de cor** ao clicar/passar o mouse nos botões de seleção One to One / PKZ.
- [ ] Adicionar uma **seção de FAQ** (metodologia + horário) — excluir explicitamente valores; adicionar um CTA de "Agende sua aula experimental" em vez disso.
- [ ] Adicionar **navegação por links de âncora** (estilo "saiba mais").
- [ ] Desenhar a seção de **Professores/Profissionais** (foto + anos de experiência), posicionada no meio da página, com tom introdutório.
- [ ] Desenhar a seção de **Depoimentos + história da empresa**.
- [ ] Desenhar a seção de **galeria de equipamentos/interior**.
- [ ] Solicitar ao cliente os **arquivos de logo e os códigos da paleta de cores** salvos no Drive.
- [ ] Confirmar com o cliente a possibilidade de **antecipar a sessão de fotos profissionais**, caso a equipe precise de imagens novas em breve.
- [ ] Prototipar o **efeito de fundo em vídeo com baixa opacidade** (estilo abertura da Marvel) para a seção principal — verificar viabilidade com os vídeos institucionais já existentes.
- [ ] Desenhar a **área exclusiva de cliente** (atrás de login), separada das páginas públicas institucionais.
- [ ] Especificar o **sistema de agendamento**: 6 vagas simultâneas por horário, fila de espera, tempo de antecedência configurável (10 a 20 min) e janela correspondente de cancelamento/reagendamento.
- [ ] Especificar o **componente de gráfico de evolução**: linha do tempo com histórico completo (não apenas comparação de dois pontos), com painel de observações/notas atrelado a cada gráfico.
- [ ] Especificar o **campo de resumo gerado por IA** para análise de múltiplos testes, com opção editável/de correção para a equipe.
- [ ] Especificar a **visão de agendamento do professor**: cada sessão marcada deve exibir as observações da sessão anterior daquele atleta.
- [ ] (Opcional/exploratório) Prototipar um **gráfico resumido de atributos** (estilo FIFA) para a evolução do atleta — confirmar com o cliente antes de investir tempo de desenvolvimento nisso.
- [ ] Confirmar a estrutura do menu superior: One to One | PKZ | Planos | Agendar | Cadastre-se.
