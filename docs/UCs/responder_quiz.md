# Responder quiz

Nesse documento será documentado o caso de uso de Responder quiz, resumidamente consiste em o usuário do aplicativo poder acessar o o quiz e o responder.

## Descrição Numerada

### Fluxo Base

1. O usuário entra com sua conta no aplicativo.
2. O usuário seleciona a opção de Módulos na barra lateral.
3. Visualiza os módulos disponíveis no momento.(RN-02)
4. O usuário seleciona o módulo.
5. O usuário seleciona a opção de ver os quizzes disponíveis.
6. O usuário acessa o quiz selecionado.
7. O usuário responde o quiz.(RN-01, RN-03, RN-04)

#### Regras de negócio

* (RN-01) Visualizar o curso não é obrigatório para fazer o quiz.
* (RN-02) Para liberar um próximo módulo o usuário deve tirar no minimo 50% da nota.
* (RN-03) Cada questão do quiz deve receber apenas uma reposta.
* (RN-04) O usuário deve poder realizar o quiz quantas vezes quiser.


### Fluxo Alternativo

A1. O usuario pode ver a nota do quiz já respondido. (FB-06 -> FB-05)

### Fluxos de Exceção

E1. O usuário não possui módulos disponíveis. (FB-03 -> FB-02)<br>

# 

E2. O usuário não possui quiz disponíveis no módulo. (FB-05 -> FB-04)<br>

#

E3. O usuário não tirou nota minima para liberar o proximo módulo. (FB-04 -> Fb-03)<br>

# Documento dos Casos de Uso

O documento com os casos de uso está disponível [aqui](https://lucid.app/lucidchart/2177ac08-1b4a-401c-9047-ee3df682c233/edit?invitationId=inv_31318015-e18b-4767-9aa8-2501d5bbfde3&page=0_0#).