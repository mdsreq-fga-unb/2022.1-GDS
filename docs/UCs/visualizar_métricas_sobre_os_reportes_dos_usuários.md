# Visualizar Métricas Sobre os Reportes dos Usuários

Nesse documento será documentado o caso de uso de *Visualizar métricas sobre os reportes dos usuários*, resumidamente consiste em uma funcionalidade disponível apenas para o administrador do sistema, sendo bem detalhada, representando justamente a visualização das métricas referentes aos reportes dos usuários da aplicação.

## Descrição Numerada

# Fluxo Base

1. Administrador acessa a área de gerenciamento do sistema.
2. Sistema deve apresentar a opção de visualizar as métricas dos reportes dos usuários. ([FA01](#fa01), [FA02](#fa02))
3. Administrador seleciona a opção de visualizar métricas na área de gerenciamento do sistema.
4. Administrador digita nos campos o nome do usuário ou cidade que deseja ver as métricas de forma detalhada. ([RN01](#rn01))
5. Sistema apresenta as métricas de cada cidade e usuário. ([RN02](#rn02))
6. O caso de uso é encerrado com as métricas visualizadas.

# Fluxos Alternativos

## FA01

A partir do passo 2 no [Fluxo Base](#fluxo-base) é gerado o fluxo alternativo 01 a seguir clicando na opção de visualizar métricas dos reportes dos usuários:

A1. Administrador seleciona a opção de visualizar métricas na área de gerenciamento do sistema.
A2. Sistema deve apresentar opções de visualizar os dados por cidade ou por usuário.
A3. Administrador seleciona visualizar dados por cidade.
A4. Administrador digita nos campos a cidade que deseja visualizar os dados. ([RN01](#rn01))
A5. Sistema deve apresentar número de reportes marcados como bem e número de reportes marcados como mal, assim como seus respectivos sintomas.([RN02](#rn02))
A6. Administrador visualiza dados relativos aos reportes.([RN02](#rn02))
A7. O caso de uso é encerrado com as métricas visualizadas.

## FA02

A partir do passo 2 no [Fluxo Base](#fluxo-base) é gerado o fluxo alternativo 01 a seguir clicando na opção de visualizar métricas dos reportes dos usuários:

A1. Administrador seleciona a opção de visualizar métricas na área de gerenciamento do sistema.
A2. Sistema deve apresentar opções de visualizar os dados por cidade ou por usuário.
A3. Administrador seleciona visualizar dados por usuário.
A4. Administrador digita nos campos o nome do usuário que deseja visualizar os dados. ([RN01](#rn01))
A5. Sistema deve apresentar o nome, local e informações sobre o reporte deste usuário. ([RN02](#rn02))
A6. Administrador visualiza dados relativos ao reporte. ([RN02](#rn02))
A7. O caso de uso é encerrado com as métricas visualizadas. 

# Fluxos de Exceção

## FE01

A partir do passo 3 no [Fluxo Base](#fluxo-base), caso o administrador insira um nome de usuário sem nenhum caracter:

E1. Sistema informa que o nome inserido deve ter ao menos um caracter. ([RN03](#rn03))([RN01](#rn01))
E2. Administrador fecha janela informativa.
E3. Sistema retorna administrador para o passo 3 no [Fluxo Base](#fluxo-base).

## FE02

A partir do passo 3 no [Fluxo Base](#fluxo-base), caso o administrador insira um nome de cidade sem nenhum caracter:

E1. Sistema informa que o nome da cidade inserida deve ter ao menos um caracter. ([RN03](#rn03))([RN01](#rn01))
E2. Administrador fecha janela informativa.
E3. Sistema retorna administrador para o passo 3 no [Fluxo Base](#fluxo-base).

## FE03

A partir do passo 3 no [Fluxo Base](#fluxo-base), caso o administrador insira um nome de usuário com mais de 50 caracteres:

E1. Sistema informa que o nome inserido deve ter no máximo 50 caracteres. ([RN01](#rn01))
E2. Administrador fecha janela informativa.
E3. Sistema retorna administrador para o passo 3 no [Fluxo Base](#fluxo-base).

## FE04

A partir do passo 3 no [Fluxo Base](#fluxo-base), caso o administrador insira um nome de cidade com mais de 50 caracteres:

E1. Sistema informa que o nome inserido deve ter no máximo 50 caracteres. ([RN01](#rn01))
E2. Administrador fecha janela informativa.
E3. Sistema retorna administrador para o passo 3 no [Fluxo Base](#fluxo-base).

# Regras de Negócio

## RN01

Os campos serão:

* Campo para inserir nome de usuário: campo optativo com capacidade de até 50 caracteres.
* Campo para inserir nome de cidade: campo optativo com capacidade de até 50 caracteres.
* Campo para inserir nome de usuário: campo optativo com no mínimo um caracter.
* Campo para inserir nome de cidade: campo optativo com no mínimo um caracter.

## RN02

* O sistema deve ser responsivo e retornar pro administrador as métricas das cidades informadas.
* O sistema deve ser responsivo e retornar pro administrador as métricas do usuário informado.

# Documento dos Casos de Uso

O documento com os casos de uso está disponível [aqui](https://lucid.app/lucidchart/2177ac08-1b4a-401c-9047-ee3df682c233/edit?viewport_loc=-61%2C-203%2C2130%2C996%2C0_0&invitationId=inv_31318015-e18b-4767-9aa8-2501d5bbfde3#).