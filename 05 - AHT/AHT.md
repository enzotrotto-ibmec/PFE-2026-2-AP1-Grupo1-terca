# AHT – Fluxo Completo do Site (Home, One to One e PKZ)

## 1. Objetivo

Esta AHT (Análise Hierárquica de Tarefas) representa como o usuário navega pelo site que reúne as empresas **One to One** (treinamento convencional para adultos, com Personal Training) e **PKZ – Playmakerz** (treinamento esportivo para atletas infantojuvenis).

O objetivo principal do usuário é **conhecer as empresas e agendar uma aula experimental**. O diagrama de atividades, feito em PlantUML, mostra os caminhos possíveis da Página Principal até esse agendamento.

## 2. Estrutura do fluxo

O fluxo é dividido em quatro partes:

- **Página Principal (Home):** ponto de partida e de escolha. O usuário conhece as empresas e decide seguir para a One to One, para a PKZ ou para o Instagram, no rodapé.
- **Página One to One:** voltada a adultos que buscam treinamento convencional, apresenta a empresa, suas soluções exclusivas e a localização das unidades.
- **Página PKZ (Playmakerz):** voltada a atletas infantojuvenis, apresenta a empresa, com uma seção dirigida aos pais/responsáveis e outra sobre a diversidade de esportes, além do mapa de localização.
- **Fluxo de contato e agendamento:** etapa **comum** às duas empresas, acessada pelo menu "Contato" de qualquer uma das páginas.

## 3. Decisões e encerramentos

| Decisão | Onde | Caminhos |
|---|---|---|
| Ação de navegação | Home | One to One · PKZ · Instagram no rodapé |
| Clicar em "Contato"? | One to One e PKZ | Sim → agendamento · Não → verifica o Instagram |
| Clicar no Instagram? | One to One e PKZ | Sim → perfil da empresa · Não → fim |

O fluxo termina em quatro situações: ao ir para o Instagram pelo rodapé da Home, ao ir para o Instagram a partir da One to One, ao ir para o Instagram a partir da PKZ, ou quando a **aula experimental é agendada com sucesso**.

## 4. Hierarquia de tarefas

```text
0. Conhecer as empresas e agendar uma aula experimental
   1. Acessar a Página Principal (Home)
      1.1 Visualizar informações das empresas e fotos dos integrantes
      1.2 Escolher um caminho de navegação
          1.2.1 Ir para a One to One ("arraste para visita" ou "Personal Training - Quero conhecer")
          1.2.2 Ir para a PKZ ("Arraste para visitar PKZ" ou "PKZ - Quero conhecer")
          1.2.3 Acessar o Instagram no rodapé
   2. Navegar na página One to One
      2.1 Acessar o cabeçalho (Sobre | Serviços | Localização | Contato)
      2.2 Visualizar a seção "Sobre a One to One"
      2.3 Explorar soluções exclusivas
      2.4 Visualizar a localização das unidades no rodapé
      2.5 Escolher o próximo passo (Contato ou Instagram)
   3. Navegar na página PKZ
      3.1 Acessar o cabeçalho (Sobre | Para Pais | Serviços | Localização | Contato)
      3.2 Ler o título "Treine como um profissional"
      3.3 Visualizar a seção "Sobre a PKZ"
      3.4 Ler a seção "Para Pais/Responsáveis"
      3.5 Explorar a seção "Sem Limites de Esportes"
      3.6 Visualizar o mapa de localização no rodapé
      3.7 Escolher o próximo passo (Contato ou Instagram)
   4. Realizar contato e agendamento
      4.1 Informar o nome e clicar em "Falar com o consultor"
      4.2 Abrir a agenda de aula experimental
      4.3 Selecionar dia e data
      4.4 Preencher o cadastro (Nome Completo, Telefone, CPF e Observação opcional)
      4.5 Clicar em "Confirmar aula"
      4.6 Receber a confirmação do agendamento
```

**Plano 0:** realizar 1; em seguida, 2 **ou** 3; e, por fim, 4. Se o usuário escolher o Instagram, o fluxo termina sem passar por 4.

**Plano 1:** realizar 1.1 e escolher entre 1.2.1, 1.2.2 ou 1.2.3.

**Planos 2 e 3:** realizar as subtarefas em ordem e, ao final, escolher entre Contato (segue para 4) ou Instagram (fim).

**Plano 4:** realizar 4.1 a 4.6 em ordem.

## 5. Considerações finais

A Home é o ponto central de navegação e direciona públicos distintos (adultos na One to One, atletas infantojuvenis na PKZ), e as duas páginas de empresa convergem para um único fluxo de contato e agendamento, o que mantém a experiência consistente. Depois de escolher a empresa, o usuário chega à aula experimental em poucos passos: clicar em "Contato", informar o nome, escolher a data e preencher o cadastro.