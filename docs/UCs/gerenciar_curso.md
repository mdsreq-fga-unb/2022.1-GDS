# Gerenciar Curso

Nesse documento será documentado o caso de uso de objetivo Gerenciar Curso, resumidamente consiste em uma funcionalidade disponível apenas para o administrador do sistema, sendo bem descritiva, representando justamente a criação de um curso e edição do mesmo dentro da aplicação web.

## Descrição Numerada

# Fluxo Base

1. Administrador acessa a área de gerenciamento do sistema.
2. Sistema deve apresentar opções de criar um curso ou editar cursos criados. ([RN01](#rn01), [FA01](#fa01), [FA02](#fa02))
3. Administrador seleciona a opção de criar um curso na área de gerenciamento do sistema.
4. Sistema apresenta a solicitação dos campos para criar um curso. ([RN02](#rn02))
5. Administrador preenche os campos e solicita a criação do curso. ([RN02](#rn02))
6. Sistema valida os dados inseridos. ([RN03](#rn03), [FE01](#fe01), [FE02](#fe02), [FE03](#fe03))
7. O caso de uso é encerrado com o curso criado. ([RN04](#rn04))

# Fluxos Alternativos

## FA01

A partir do passo 2 no [Fluxo Base](#fluxo-base) é gerado o fluxo alternativo 01 a seguir clicando na opção de editar cursos criados: 

A1. Administrador seleciona a opção de editar cursos criados na área de gerenciamento do sistema. ([RN01](#rn01))<br>
A2. Sistema deve apresentar opções de cursos criados para edição. <br>
A3. Administrador seleciona um curso. <br>
A4. Sistema deve apresentar opções para alterar os dados nos campos ou deletar o curso. ([RN02](#rn02)) <br>
A5. Administrador preenche os campos com novos dados e solicita o salvamento da edição do curso. ([RN02](#rn02)) <br>
A6. Sistema valida os dados inseridos. ([RN03](#rn03), [FE01](#fe01), [FE02](#fe02), [FE03](#fe03), [FE05](#fe05), [FE06](#fe06)) <br>
A7. O caso de uso é encerrado com o curso editado. ([RN04](#rn04)) <br>

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

A partir do passo 6 no [Fluxo Base](#fluxo-base), caso o administrador insira uma descrição com mais de 150 caracteres:

E1. Sistema informa que a descrição é obrigatória e deve ter menos de 150 caracteres. ([RN03](#rn03)) <br>
E2. Administrador fecha janela informativa.<br>
E3. Sistema retorna administrador para o passo 5 no [Fluxo Base](#fluxo-base).<br>
            
## FE02

A partir do passo 6 no [Fluxo Base](#fluxo-base), caso o administrador insira um link com mais de 200 caracteres:

E1. Sistema informa que o link inserido deve ter menos de 200 caracteres. ([RN03](#rn03)) <br>
E2. Administrador fecha janela informativa.<br>
E3. Sistema retorna administrador para o passo 5 no [Fluxo Base](#fluxo-base).<br>

## FE03

A partir do passo 6 no [Fluxo Base](#fluxo-base), caso o administrador não insira nenhum link:

E1. Sistema informa que deve ser inserido ao menos um link. ([RN03](#rn03)) <br>
E2. Administrador fecha janela informativa.<br>
E3. Sistema retorna administrador para o passo 5 no [Fluxo Base](#fluxo-base).<br>

## FE04 

A partir do passo A6 no [Fluxo Alternativo 02](#fa02), caso o administrador selecione a opção de não ter certeza:

E1. Administrador seleciona a opção de não ter certeza. <br>
E3. Sistema retorna administrador para o passo A4 no [Fluxo Alternativo 02](#fa02).<br>

## FE05

A partir do passo 6 no [Fluxo Base](#fluxo-base), caso o administrador não insira uma descrição:

E1. Sistema informa que a descrição é obrigatória e deve ter menos de 150 caracteres. ([RN03](#rn03)) <br>
E2. Administrador fecha janela informativa.<br>
E3. Sistema retorna administrador para o passo 5 no [Fluxo Base](#fluxo-base).<br>

## FE06

A partir do passo 6 no [Fluxo Base](#fluxo-base), caso o administrador não insira um título:

E1. Sistema informa que o título é obrigatória e deve ter menos de 70 caracteres. ([RN03](#rn03)) <br>
E2. Administrador fecha janela informativa.<br>
E3. Sistema retorna administrador para o passo 5 no [Fluxo Base](#fluxo-base).<br>

## FE07

A partir do passo 6 no [Fluxo Base](#fluxo-base), caso o administrador insira um título com mais de 70 caracteres:

E1. Sistema informa que o título é obrigatória e deve ter menos de 70 caracteres. ([RN03](#rn03)) <br>
E2. Administrador fecha janela informativa.<br>
E3. Sistema retorna administrador para o passo 5 no [Fluxo Base](#fluxo-base).<br>

# Regras de Negócio

## RN01

O sistema não deve permitir que seja selecionado a opção de editar curso caso não exista um curso criado. 

## RN02

Os campos serão:
* Título: campo obrigatório com capacidade máxima de até 70 caracteres e mínima de um caractere.
* Campo para inserir link(s) para acessar o curso: campo obrigatório separando os links por quebra de linha com capacidade de até 250 caracteres por link e máximo de 10 linhas (10 links).
* Campo para inserir a descrição do curso: campo obrigatório com capacidade máxima de até 150 caracteres e mínima de um caractere.

## RN03

O administrador deve ter inserido ao menos um link para um curso com no máximo 250 caracteres por link, obrigatoriamente uma breve descrição sobre o curso de no máximo 150 caracteres e obrigatoriamente um título com no máximo 70 caracteres.

## RN04

O sistema deve ser responsivo e retornar pro usuário uma mensagem informando que sua ação foi salva.

# Documento dos Casos de Uso

O documento com os casos de uso está disponível [aqui](https://lucid.app/lucidchart/2177ac08-1b4a-401c-9047-ee3df682c233/edit?viewport_loc=-61%2C-203%2C2130%2C996%2C0_0&invitationId=inv_31318015-e18b-4767-9aa8-2501d5bbfde3#).
