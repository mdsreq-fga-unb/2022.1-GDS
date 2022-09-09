# Gerenciar Curso

Nesse documento será documentado o caso de uso de objetivo Gerenciar Curso, resumidamente consiste em uma funcionalidade disponível apenas para o administrador do sistema, sendo bem descritiva, representando justamente a criação de um curso e edição do mesmo dentro da aplicação web.

## Descrição Numerada

# Fluxo Base

1. Administrador acessa a área de gerenciamento do sistema.
2. Sistema deve apresentar opções de criar um curso ou editar cursos criados. ([RN01](#rn01), [FA01](#fa01))
3. Administrador seleciona a opção de criar um curso na área de gerenciamento do sistema.
4. Sistema apresenta a solicitação dos campos para criar um curso. ([RN02](#rn02))
5. Administrador preenche os campos e solicita a criação de curso. ([RN02](#rn02))
6. Sistema valida os dados inseridos. ([RN03](#rn03))
7. O caso de uso é encerrado com o curso criado. ([RN04](#rn04))

# Fluxos Alternativos

## FA01

A1. Sistema deve apresentar opções de criar um curso ou editar cursos criados. <br>
A2. Sistema apresenta a solicitação de nome para o módulo. <br>
A3. Administrador insere o nome do módulo.<br>
A4. Sistema exibe a opção de criar quiz e criar curso.<br>
A5. Administrador seleciona a opção de criar curso.<br>
A6. Sistema exibe campos para inserir link(s) para acessar o curso e descrição sobre o curso.<br>
A7. Administrador insere seu(s) respectivo(s) link(s) desejados.<br>
A8. Administrador conclui a criação do curso e finaliza tarefa.<br>
A9. Sistema apresenta uma mensagem indicando que foi salvo a criação.<br>

* Campos presentes na funcionalidade: campo para inserir um link para acessar o curso.
* Regras de Negócio: o curso deve ter um link válido, a descrição não pode estar vazia.

### Fluxos de Exceção

E1. Administrador seleciona a opção de criar um módulo na área de gerenciamento do sistema.<br>
E2. Sistema apresenta a solicitação de nome para o módulo.<br>
E3. Administrador não insere o nome do módulo e tenta avançar.<br>
E4. Sistema informa que é necessário um nome para o módulo para avançar.<br>

# 

E1. Administrador seleciona a opção de criar um módulo na área de gerenciamento do sistema.<br>
E2. Sistema apresenta a solicitação de nome para o módulo.<br>
E3. Administrador insere o nome do módulo.<br>
E4. Sistema exibe a opção de criar quiz e criar curso.<br>
E5. Administrador seleciona a opção de criar quiz.<br>
E6. Sistema exibe campos para inserir perguntas e alternativas para formar um questionário.<br>
E7. Administrador tenta avançar sem inserir nenhuma pergunta.<br>
E8. Sistema informa que é necessário perguntas com alternativas para a criação de um quiz.<br>

# 

E1. Administrador seleciona a opção de criar um módulo na área de gerenciamento do sistema.<br>
E2. Sistema apresenta a solicitação de nome para o módulo.<br>
E3. Administrador insere o nome do módulo.<br>
E4. Sistema exibe a opção de criar quiz e criar curso.<br>
E5. Administrador seleciona a opção de criar quiz.<br>
E6. Sistema exibe campos para inserir perguntas e alternativas para formar um questionário.<br>
E7. Administrador tenta avançar deixando uma pergunta sem alternativas.<br>
E8. Sistema informa que é necessário perguntas com alternativas para a criação de um quiz.<br>

# 

E1. Administrador seleciona a opção de criar um módulo na área de gerenciamento do sistema.<br>
E2. Sistema apresenta a solicitação de nome para o módulo.<br>
E3. Administrador insere o nome do módulo.<br>
E4. Sistema exibe a opção de criar quiz e criar curso.<br>
E5. Administrador seleciona a opção de criar curso.<br>
E6. Sistema exibe campos para inserir link(s) para acessar o curso e descrição sobre o curso.<br>
E7. Administrador tenta avançar sem inserir um link para acessar o curso.<br>
E8. Sistema informa que é necessário ao menos um link para criar o curso.<br>

# 

E1. Administrador seleciona a opção de criar um módulo na área de gerenciamento do sistema.<br>
E2. Sistema apresenta a solicitação de nome para o módulo.<br>
E3. Administrador insere o nome do módulo.<br>
E4. Sistema exibe a opção de criar quiz e criar curso.<br>
E5. Administrador seleciona a opção de criar curso.<br>
E6. Sistema exibe campos para inserir link(s) para acessar o curso e descrição sobre o curso.<br>
E7. Administrador tenta avançar sem inserir uma descrição para o curso.<br>
E8. Sistema informa que é obrigatório a descrição para criar o curso.<br>

# Regras de Negócio

## RN01

O sistema não deve permitir que seja selecionado a opção de editar curso caso não exista um curso criado. 

## RN02

Os campos serão:
* Campo para inserir link(s) para acessar o curso: campo obrigatório separando os links por quebra de linha com capacidade de até 200 caracteres por link e máximo de 10 linhas (10 links).
* Campo para inserir a descrição do curso: campo opcional com capacidade de até 150 caracteres.

## RN03

No passo 4 do [Fluxo Base](#fluxo-base) o administrador deve ter inserido ao menos um link para um curso com no máximo 200 caracteres por link e opcionalmente uma breve descrição sobre o curso de no máximo 150 caracteres.

## RN04

O sistema deve ser responsivo e retornar pro usuário uma mensagem informando que o curso foi criado.

# Documento dos Casos de Uso

O documento com os casos de uso está disponível [aqui](https://lucid.app/lucidchart/2177ac08-1b4a-401c-9047-ee3df682c233/edit?viewport_loc=-61%2C-203%2C2130%2C996%2C0_0&invitationId=inv_31318015-e18b-4767-9aa8-2501d5bbfde3#).
