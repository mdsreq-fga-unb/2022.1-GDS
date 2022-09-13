# Gerenciar Curso

Nesse documento será documentado o caso de uso de objetivo Notificação sobre um quiz novo disponível.

## Descrição Numerada

# Fluxo Base

1. Asignal gera a Notificação de Novo Quiz.
2. O Guardiões da Saúde envia a notificaçao para o usuário.
3. O usuário recebe a notificação.

# Fluxos de Exceção

## FE01

A partir do passo 1 no [Fluxo Base](#fluxo-base), caso o usuário já tenha realizado o Quiz novo:

E1. O Guardiões não envia a notificação para o usuário.
            

# Regras de Negócio

## RN01

O sistema não deve permitir o envio de notificação para usuários que ja tenham realizado o Quiz novo apresentado. 


# Documento dos Casos de Uso

O documento com os casos de uso está disponível [aqui](https://lucid.app/lucidchart/2177ac08-1b4a-401c-9047-ee3df682c233/edit?viewport_loc=-61%2C-203%2C2130%2C996%2C0_0&invitationId=inv_31318015-e18b-4767-9aa8-2501d5bbfde3#).