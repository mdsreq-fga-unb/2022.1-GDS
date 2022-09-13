# Acessar conteúdo do curso

Nesse documento será documentado o caso de uso de Acessar conteúdo do curso, resumidamente consiste em o usuário do aplicativo poder acessar o conteúdo do curso que está disponível para ele no momento.

## Descrição Numerada

# Fluxo Base

1. O usuário entra com sua conta no aplicativo.
2. O usuário seleciona a opção de Módulos na barra lateral.
3. Visualiza os módulos disponíveis no momento.
4. O usuário seleciona o módulo.
5. O usuário seleciona a opção de ver os cursos disponíveis.
6. O usuário acessa o conteúdo do curso selecionado. ([RN01](#rn01), [RN02](#rn02))

# Fluxo Alternativo

# Fluxos de Exceção

## FE01

A partir do passo 3 no [Fluxo Base](#fluxo-base), caso o usuário entre para ver os módulos:

E1. O usuário não possui módulos disponíveis.<br>
E2. O sistema retorna para o passo 2 do [Fluxo Base](#fluxo-base)<br>

## FE02

A partir do passo 4 no [Fluxo Base](#fluxo-base), caso o usuário siga para ver os cursos:

E1. O usuário não possui cursos disponíveis no módulo.<br>
E2. O sistema retorna para o passo 3 do [Fluxo Base](#fluxo-base)<br>

# Regras de negócio

## RN01
 Visualizar o curso não é obrigatório para fazer o quiz.
## RN02
 O conteúdo do curso deve ser disponibilizado por meio de link externos.

# Documento dos Casos de Uso

O documento com os casos de uso está disponível [aqui](https://lucid.app/lucidchart/2177ac08-1b4a-401c-9047-ee3df682c233/edit?invitationId=inv_31318015-e18b-4767-9aa8-2501d5bbfde3&page=0_0#).