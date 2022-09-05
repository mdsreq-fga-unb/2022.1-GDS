# Criar Módulo

Nesse documento será documentado o caso de uso de Criar módulo, resumidamente consiste em uma funcionalidade disponível apenas para o administrador do sistema, sendo bem descritiva, representando justamente a criação de um módulo dentro da aplicação.

## Descrição Numerada

### Fluxo Base

1. Administrador seleciona a opção de criar um módulo na área de gerenciamento do sistema.
2. Sistema apresenta a solicitação de nome para o módulo.
3. Administrador insere o nome do módulo.
4. Sistema exibe a opção de criar quiz e criar curso.
5. Administrador seleciona a opção de criar quiz.
6. Sistema exibe campos para inserir perguntas e alternativas para formar um questionário.
7. Administrador insere as perguntas e suas respectivas alternativas desejadas.
8. Administrador conclui a criação do quiz e finaliza tarefa.
9. Sistema apresenta uma mensagem indicando que foi salvo a criação.

* Campos presentes na funcionalidade: campo para inserir uma pergunta dentro do questionário, campo para inserir alternativas dentro de cada pergunta.
* Regras de Negócio: o quiz deve conter o gabarito, deve existir ao menos uma questão no quiz.

### Fluxo Alternativo

A1. Administrador seleciona a opção de criar um módulo na área de gerenciamento do sistema. <br>
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
