# Diagrama de Atividade – PKZ Lab e One to One

## 1. Objetivo

Este documento apresenta a explicação do diagrama de atividade desenvolvido em **PlantUML**.

O diagrama representa o fluxo de navegação de um usuário ao acessar o site, permitindo que ele escolha entre as empresas **PKZ Lab** e **One to One**.

O objetivo é demonstrar, de forma visual, as principais ações que o usuário pode realizar dentro do site.

---

## 2. Fluxo inicial

O fluxo começa quando o usuário acessa o site.

A sequência inicial é:

1. **Acessar o site;**
2. **Carregar a página inicial;**
3. **Exibir as opções PKZ Lab e One to One.**

Após essas etapas, o sistema aguarda a escolha do usuário sobre qual empresa deseja conhecer.

---

## 3. Escolha da empresa

O diagrama possui uma estrutura de decisão para identificar qual empresa foi selecionada.

### PKZ Lab

Caso o usuário escolha **PKZ Lab**, o sistema realiza as seguintes ações:

1. Clicar em **"PKZ Lab"**;
2. Redirecionar o usuário para a página da PKZ Lab;
3. Exibir as informações da PKZ Lab.

Depois disso, o usuário pode escolher entre três ações:

- **Conhecer serviços:** visualizar os serviços oferecidos pela PKZ Lab;
- **Entrar em contato:** acessar a área de contato e visualizar as informações de contato;
- **Voltar:** retornar para a página inicial.

### One to One

Caso o usuário escolha **One to One**, o processo é semelhante:

1. Clicar em **"One to One"**;
2. Redirecionar o usuário para a página da One to One;
3. Exibir as informações da One to One.

Depois disso, o usuário pode:

- **Conhecer serviços:** visualizar os serviços oferecidos pela One to One;
- **Entrar em contato:** acessar a área de contato;
- **Voltar:** retornar para a página inicial.

---

## 4. Decisões do usuário

O diagrama utiliza estruturas de decisão `if`, que representam os momentos em que o usuário precisa escolher um caminho.

A primeira decisão é:

> **Qual empresa foi selecionada?**

As opções são:

- PKZ Lab;
- One to One.

Depois que a empresa é selecionada, existe uma segunda decisão:

> **Qual ação o usuário deseja realizar?**

As opções são:

- Conhecer serviços;
- Entrar em contato;
- Voltar.

Essas decisões permitem representar os diferentes caminhos que o usuário pode seguir durante a navegação pelo site.

---

## 5. Retorno para a página inicial

Caso o usuário escolha a opção **Voltar**, o sistema retorna para a página inicial.

Esse retorno permite que o usuário escolha novamente entre **PKZ Lab** e **One to One**.

O fluxo é encerrado quando não há mais nenhuma ação a ser realizada.
