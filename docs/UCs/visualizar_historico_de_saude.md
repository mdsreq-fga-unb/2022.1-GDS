# Visualizar histórico de saúde 

Nesse documento será documentado o caso de uso de objetivo visualizar histórico de saúde, resumidamente consiste em uma funcionalidade bem descritiva, representando justamente a visualização do histórico de saúde pelo calendário no aplicativo.

## Descrição Numerada

# Fluxo Base

1. Usuário acessa a área de calendário do sistema.
2. Sistema deve apresentar calendário com marcações do seu histórico de saúde. ([RN01](#rn01), [RN02](#rn02))
3. Usuário verifica seu histórico de saúde baseado no mês que estiver visualizando.

# Fluxos Alternativos

## FA01

A partir do passo 2 no [Fluxo Base](#fluxo-base) é gerado o fluxo alternativo 01 a seguir:

A1. Usuário seleciona um dia marcado como estado de saúde "mal". ([RN01](#rn01)) <br>
A2. Sistema deve apresentar uma lista com os sintomas selecionados pelo usuário no dia selecionado. ([RN01](#rn01)) <br>
A3. Usuário verifica seu histórico de sintomas baseado no dia específico selecionado. ([RN03](#rn03))

## FA02

A partir do passo 2 no [Fluxo Base](#fluxo-base) é gerado o fluxo alternativo 02 a seguir clicando na opção de editar cursos criados: 

A1. Administrador seleciona a opção de editar cursos criados na área de gerenciamento do sistema. ([RN01](#rn01))<br>
A2. Sistema deve apresentar opções de cursos criados para edição. <br>
A3. Administrador seleciona um curso. <br>
A4. Sistema deve apresentar opções para alterar os dados nos campos ou deletar o curso. ([RN02](#rn02)) <br>
A5. Administrador seleciona a opção de deletar o curso. <br>
A6. Sistema envia uma mensagem perguntando se o administrador tem certeza da opção selecionada. ([FE04](#fe04))<br>
A7. Administrador confirma a opção. <br>
A8. Sistema deleta o curso. <br>
A9. O caso de uso é encerrado com o curso deletado. ([RN04](#rn04)) <br>


# Fluxos de Exceção

## FE01

A partir do passo 6 no [Fluxo Base](#fluxo-base) ou passo A6 no [Fluxo Alternativo 01](#fa01), caso o administrador insira uma descrição com mais de 150 caracteres:

E1. Sistema informa que a descrição é obrigatória e deve ter menos de 150 caracteres. ([RN03](#rn03)) <br>
E2. Administrador fecha janela informativa.<br>
E3. Sistema retorna administrador para o passo 5 no [Fluxo Base](#fluxo-base).<br>
            
## FE02

A partir do passo 6 no [Fluxo Base](#fluxo-base) ou passo A6 no [Fluxo Alternativo 01](#fa01), caso o administrador insira um link com mais de 200 caracteres:

E1. Sistema informa que o link inserido deve ter menos de 200 caracteres. ([RN03](#rn03)) <br>
E2. Administrador fecha janela informativa.<br>
E3. Sistema retorna administrador para o passo 5 no [Fluxo Base](#fluxo-base).<br>

## FE03

A partir do passo 6 no [Fluxo Base](#fluxo-base) ou passo A6 no [Fluxo Alternativo 01](#fa01), caso o administrador não insira nenhum link:

E1. Sistema informa que deve ser inserido ao menos um link. ([RN03](#rn03)) <br>
E2. Administrador fecha janela informativa.<br>
E3. Sistema retorna administrador para o passo 5 no [Fluxo Base](#fluxo-base).<br>

## FE04 

A partir do passo A6 no [Fluxo Alternativo 02](#fa02), caso o administrador selecione a opção de não ter certeza:

E1. Administrador seleciona a opção de não ter certeza. <br>
E3. Sistema retorna administrador para o passo A4 no [Fluxo Alternativo 02](#fa02).<br>

## FE05

A partir do passo 6 no [Fluxo Base](#fluxo-base) ou passo A6 no [Fluxo Alternativo 01](#fa01), caso o administrador não insira uma descrição:

E1. Sistema informa que a descrição é obrigatória e deve ter menos de 150 caracteres. ([RN03](#rn03)) <br>
E2. Administrador fecha janela informativa.<br>
E3. Sistema retorna administrador para o passo 5 no [Fluxo Base](#fluxo-base).<br>

## FE06

A partir do passo 6 no [Fluxo Base](#fluxo-base) ou passo A6 no [Fluxo Alternativo 01](#fa01), caso o administrador não insira um título:

E1. Sistema informa que o título é obrigatória e deve ter menos de 70 caracteres. ([RN03](#rn03)) <br>
E2. Administrador fecha janela informativa.<br>
E3. Sistema retorna administrador para o passo 5 no [Fluxo Base](#fluxo-base).<br>

## FE07

A partir do passo 6 no [Fluxo Base](#fluxo-base) ou passo A6 no [Fluxo Alternativo 01](#fa01), caso o administrador insira um título com mais de 70 caracteres:

E1. Sistema informa que o título é obrigatória e deve ter menos de 70 caracteres. ([RN03](#rn03)) <br>
E2. Administrador fecha janela informativa.<br>
E3. Sistema retorna administrador para o passo 5 no [Fluxo Base](#fluxo-base).<br>

# Regras de Negócio

## RN01

As marcações devem aparecer no calendário apenas se o usuário tiver realizado alguma anteriormente.

## RN02

As marcações de estado de saúde como "bem" devem estar indicadas na cor verde e como "mal" na cor laranja.

## RN03

A lista de sintomas disponíveis é:

* Alteração de paladar e olfato.
* Bolhas na Pele.
* Calafrios.
* Cansaço.
* Coceira.
* Congestão Nasal.
* Conjuntivite.
* Diarreia.
* Dificuldade para Respirar.
* Dor atrás dos olhos.
* Dor de Cabeça.
* Dor de Estômago.
* Dor de Garganta.
* Dor nas Articulações.
* Dor no corpo.
* Dor nos Músculos.
* Dor nos Olhos.
* Exantema.
* Fadiga.
* Febre.
* Língua ou Gânglios Inflamados.
* Mal-estar
* Manchas Roxas pelo Corpo.
* Náusea ou Vômito.
* Pele e Olhos Amarelados.
* Sangramento.
* Tosse.

## RN04

O sistema deve ser responsivo e retornar pro usuário uma mensagem informando que sua ação foi salva.

# Documento dos Casos de Uso

O documento com os casos de uso está disponível [aqui](https://lucid.app/lucidchart/2177ac08-1b4a-401c-9047-ee3df682c233/edit?viewport_loc=-61%2C-203%2C2130%2C996%2C0_0&invitationId=inv_31318015-e18b-4767-9aa8-2501d5bbfde3#).
