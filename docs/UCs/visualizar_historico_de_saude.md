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
A2. Sistema deve apresentar uma lista com os sintomas selecionados pelo usuário no dia selecionado. ([RN01](#rn01), [RN03](#rn03)) <br>
A3. Usuário verifica seu histórico de sintomas baseado no dia específico selecionado. ([RN03](#rn03))

# Fluxos de Exceção

## FE01

A partir do passo 2 no [Fluxo Base](#fluxo-base), caso o usuário selecione uma opção indisponível:

E1. Usuário seleciona um dia marcado como estado de saúde "bem". ([RN01](#rn01), [RN02](#rn02)) <br>
E2. Sistema deve demonstrar de forma responsiva que é uma opção indisponível para selecionar. <br>
            
## FE02

A partir do passo 2 no [Fluxo Base](#fluxo-base), caso o usuário selecione uma opção indisponível:

E1. Usuário seleciona um dia que não foi marcado um estado de saúde. <br>
E2. Sistema deve demonstrar de forma responsiva que é uma opção indisponível para selecionar. <br>

# Regras de Negócio

## RN01

As marcações devem aparecer no calendário apenas se o usuário tiver realizado alguma anteriormente.

## RN02

As marcações de estado de saúde como "bem" devem estar indicadas na cor verde e como "mal" na cor laranja.

## RN03

Lista com sintomas disponíveis:

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
