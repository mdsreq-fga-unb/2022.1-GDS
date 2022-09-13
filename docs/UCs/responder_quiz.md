# Responder quiz

Nesse documento será documentado o caso de uso de Responder quiz, resumidamente consiste em o usuário do aplicativo poder acessar o o quiz e o responder.

## Descrição Numerada

### Fluxo Base

1. O usuário entra com sua conta no aplicativo.
2. O usuário seleciona a opção de Módulos na barra lateral.
3. Visualiza os módulos disponíveis no momento. ([RN02](#rn02))
4. O usuário seleciona o módulo.
5. O usuário seleciona a opção de ver os quizzes disponíveis.
6. O usuário acessa o quiz selecionado.
7. O usuário responde o quiz. ([RN01](#rn01), [RN03](#rn03), [RN04](#rn04))

# Fluxo Alternativo

## FA01

A partir do passo 6 no [Fluxo Base](#fluxo-base) é gerado o fluxo alternativo 01 a seguir clicando na opção para entrar no quiz desejado:

A1. O usuario pode ver a nota do quiz já respondido. ([RN02](#rn02))<br>
A2. O caso de uso é encerrado com o usuário voltando para o passo 5. ([RN02](#rn02))<br>
# Fluxos de Exceção

## FE01

A partir do passo 4 no [Fluxo Base](#fluxo-base), caso o usuário não tenha módulos disponiveis:

E1. O usuário não possui módulos disponíveis. ([RN02](#rn02))<br>
E2.O sistema retorna ao passo 2 no [Fluxo Base](#fluxo-base).

## FE02

A partir do passo 5 no [Fluxo Base](#fluxo-base) ou no A1 no [Fluxo Alternativo 01](#fa01), caso o usuário não tenha quizzes disponiveis:

E1. O usuário não possui quiz disponíveis no módulo ([RN02](#rn02))<br>
E2.O sistema retorna ao passo 4 no [Fluxo Base](#fluxo-base).<br>

## FE03

A partir do passo 4 no [Fluxo Base](#fluxo-base) , caso o usuário não tenha a nota mínima nos quizzes:

E3. O usuário não tirou nota minima para liberar o proximo módulo. ([RN02](#rn02))<br>
E2.O sistema retorna ao passo 3 no [Fluxo Base](#fluxo-base).<br>

# Regras de negócio

## RN01 
Visualizar o curso não é obrigatório para fazer o quiz.
## RN02 
Para liberar um próximo módulo o usuário deve tirar no minimo 50% da nota.
## RN03 
Cada questão do quiz deve receber apenas uma reposta.
## RN04 
O usuário deve poder realizar o quiz quantas vezes quiser.

# Documento dos Casos de Uso

O documento com os casos de uso está disponível [aqui](https://lucid.app/lucidchart/2177ac08-1b4a-401c-9047-ee3df682c233/edit?invitationId=inv_31318015-e18b-4767-9aa8-2501d5bbfde3&page=0_0#).

