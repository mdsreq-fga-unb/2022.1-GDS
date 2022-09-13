# Registrar reporte semanal

Documento de criação do caso de uso Registrar Reporte Semanal, uma feature 
disponível para todos usuários, sendo bem descritiva, representando literalmente
o registro semanal do estado atual do usuário.

## Descrição Numerada

### Fluxo Base

1. Usuário seleciona a opção de registrar reporte no estado Good. ([RN01](#rn01))
2. O sistema apresenta opções para uso do GPS para que a funcionalidade do HealthMap possa usufruir do reporte.
3. O sistema apresenta uma mensagem indicando que o reporte foi registrado.

### Fluxo Alternativo

A1. Usuário seleciona a opção de registrar reporte no estado Bad. ([RN01](#rn01)) <br> 
A2. O sistema apresenta uma tela perguntando a o usuário o período dos sintomas e quais os sintomas que o usuário está sentindo. <br>
A3. O sistema pede para o usuário responder algumas perguntas. <br>
A4. O sistema apresenta uma mensagem de acordo com os sintomas do usuário. <br>
A5. O sistema disponibiliza um link para o Ministério da Saúde para que o usuário obtenha mais informações sobre seu estado atual. <br>
A6. Mensagem disponibilizada para mostrar o HealthMap <br>

### Fluxo de Exceção

## FE01

E1. Usuário seleciona a opção de registrar reporte no estado Good pela segunda vez no dia. ([RN01](#rn01)) <br>
E2. O sistema responde com uma mensagem informando que o reporte já foi registrado no dia atual <br>

## FE02

E1. Usuário seleciona a opção de registrar reporte no estado Bad pela segunda vez no dia. ([RN01](#rn01)) <br>
E2. O sistema apresenta uma tela perguntando a o usuário o período dos sintomas e quais os sintomas que o usuário está sentindo. <br>
E3. O sistema pede para o usuário responder algumas perguntas. <br>
E4. O sistema apresenta uma mensagem de acordo com os sintomas do usuário. <br>
E5. O sistema responde com uma mensagem informando que o reporte já foi registrado no dia atual. <br>
E6. Mensagem disponibilizada para mostrar o HealthMap. <br>

# Regras de Negócio

## RN01

O sistema não deve permitir que o usuário realize o reporte mais de uma vez em um mesmo dia.

# Documento dos Casos de Uso

O documento com os casos de uso está disponível [aqui](https://lucid.app/lucidchart/2177ac08-1b4a-401c-9047-ee3df682c233/edit?viewport_loc=-61%2C-203%2C2130%2C996%2C0_0&invitationId=inv_31318015-e18b-4767-9aa8-2501d5bbfde3#).
