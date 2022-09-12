# Gerenciar Quiz

Nesse documento será registrado o caso de uso de Gerenciar Quiz, resumidamente consiste em uma funcionalidade disponível apenas para o administrador do sistema, sendo bem descritiva, representando justamente a criação de um quiz e a sua edição dentro da aplicação.

## Descrição Numerada

# Fluxo Base

1. Administrador acessa a área de gerenciamento do sistema.
2. Sistema deve apresentar opções de criar um quiz ou editar quizzes criados. ([RN01](#rn01), [FA01](#fa01), [FA02](#fa02))
3. Administrador seleciona a opção de criar um quiz na área de gerenciamento do sistema.
4. Sistema apresenta a solicitação dos campos para criar um quiz. ([RN02](#rn02))
5. Administrador preenche os campos e solicita a criação do quiz. ([RN02](#rn02))
6. Sistema valida os dados inseridos. ([RN03](#rn03), [FE01](#fe01), [FE02](#fe02), [FE03](#fe03))
7. O caso de uso é encerrado com o quiz criado. ([RN04](#rn04))

# Fluxos Alternativos

## FA01

A partir do passo 2 no [Fluxo Base](#fluxo-base) é gerado o fluxo alternativo 01 a seguir clicando na opção de editar quizzes criados:

A1. Administrador seleciona a opção de editar quizzes criados na área de gerenciamento do sistema. ([RN01](#rn01))
A2. Sistema deve apresentar opções de quizzes criados para edição.
A3. Administrador seleciona um quiz.
A4. Sistema deve apresentar opções para alterar os dados nos campos ou deletar o quiz. ([RN02](#rn02))
A5. Administrador preenche os campos com novos dados e solicita o salvamento da edição do quiz. ([RN02](#rn02))
A6. Sistema valida os dados inseridos. ([RN03](#rn03), [FE01](#fe01), [FE02](#fe02), [FE03](#fe03))
A7. O caso de uso é encerrado com o quiz editado. ([RN04](#rn04))


## FA02 

A partir do passo 2 no [Fluxo Base](#fluxo-base) é gerado o fluxo alternativo 02 a seguir clicando na opção de editar quizzes criados:

A1. Administrador seleciona a opção de editar quizzes criados na área de gerenciamento do sistema. ([RN01](#rn01))
A2. Sistema deve apresentar opções de quizzes criados para edição.
A3. Administrador seleciona um quiz.
A4. Sistema deve apresentar opções para alterar os dados nos campos ou deletar o quiz. ([RN02](#rn02))
A5. Administrador seleciona a opção de deletar o quiz.
A6. Sistema envia uma mensagem perguntando se o administrador tem certeza da opção selecionada. ([FE04](#fe04))
A7. Administrador confirma a opção.
A8. Sistema deleta o quiz.
A9. O caso de uso é encerrado com o quiz deletado. ([RN04](#rn04))

# Fluxos de Exceção

## FE01

A partir do passo 6 no [Fluxo Base](#fluxo-base), caso o administrador insira uma pergunta sem nenhum caracter:

E1. Sistema informa que a pergunta inserida deve ter ao menos um caracter. ([RN03](#rn03))
E2. Administrador fecha janela informativa.
E3. Sistema retorna administrador para o passo 5 no [Fluxo Base](#fluxo-base).

## FE02

A partir do passo 6 no [Fluxo Base](#fluxo-base), caso o administrador insira uma pergunta com mais de 200 caracteres:

E1. Sistema informa que a pergunta inserida deve ter menos de 200 caracteres. ([RN03](#rn03))
E2. Administrador fecha janela informativa.
E3. Sistema retorna administrador para o passo 5 no [Fluxo Base](#fluxo-base).

## FE03

A partir do passo 6 no [Fluxo Base](#fluxo-base), caso o administrador insira uma alternativa com mais de 200 caracteres:

E1. Sistema informa que a alternativa inserida deve ter menos de 200 caracteres. ([RN03](#rn03))
E2. Administrador fecha janela informativa.
E3. Sistema retorna administrador para o passo 5 no [Fluxo Base](#fluxo-base).

## FE04

A partir do passo 6 no [Fluxo Base](#fluxo-base), caso o administrador não insira nenhuma pergunta:

E1. Sistema informa que deve ser inserido ao menos uma pergunta com suas respectivas alternativas. ([RN03](#rn03))
E2. Administrador fecha janela informativa.
E3. Sistema retorna administrador para o passo 5 no [Fluxo Base](#fluxo-base).

## FE05

A partir do passo 6 no [Fluxo Base](#fluxo-base), caso o administrador insira mais de 5 perguntas:

E1. Sistema informa que devem ser inseridas no máximo 5 perguntas com suas respectivas alternativas. ([RN03](#rn03))
E2. Administrador fecha janela informativa.
E3. Sistema retorna administrador para o passo 5 no [Fluxo Base](#fluxo-base).

## FE06

A partir do passo 6 no [Fluxo Base](#fluxo-base), caso o administrador não insira nenhum gabarito para cada pergunta:

E1. Sistema informa que deve ser inserido um gabarito por questão. ([RN03](#rn03))
E2. Administrador fecha janela informativa.
E3. Sistema retorna administrador para o passo 5 no [Fluxo Base](#fluxo-base).

## FE07

A partir do passo A6 no [Fluxo Alternativo 02](#fa02), caso o administrador selecione a opção de não ter certeza:

E1. Administrador seleciona a opção de não ter certeza.
E3. Sistema retorna administrador para o passo 4 no [Fluxo Alternativo 02](#fa02).

# Regras de Negócio

## RN01

O sistema não deve permitir que seja selecionado a opção de editar quiz caso não exista um quiz criado.

## RN02

Os campos serão:

* Campo para inserir perguntas(s) para criar o quiz: campo obrigatório separando os links por quebra de linha com capacidade de até 200 caracteres por link e máximo de 10 linhas (10 links).
* Campo para inserir as alternativas: campo obrigatório com capacidade de até 150 caracteres por alternativa.
* Campo para inserir as alternativas: campo obrigatório que deve possuir no mínimo duas alternativas e no máximo quatro alternativas por questão.
* Campo para informar (selecionar) gabarito da pergunta: campo obrigatório em que deve ser selecionado apenas uma opção por questão.

## RN03

O administrador deve ter inserido ao menos uma pergunta em um quiz com no máximo 200 caracteres por pergunta e obrigatoriamente suas respectivas alternativas sobre o quiz de no máximo 150 caracteres por alternativa.

## RN04

O sistema deve ser responsivo e retornar pro usuário uma mensagem informando que sua ação foi salva.

# Documento dos Casos de Uso

O documento com os casos de uso está disponível [aqui](https://lucid.app/lucidchart/2177ac08-1b4a-401c-9047-ee3df682c233/edit?viewport_loc=-61%2C-203%2C2130%2C996%2C0_0&invitationId=inv_31318015-e18b-4767-9aa8-2501d5bbfde3#).

