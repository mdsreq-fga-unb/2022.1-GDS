# Editar Módulo

Nesse documento será registrado o caso de uso de Editar módulo, resumidamente consiste em uma funcionalidade disponível apenas para o administrador do sistema, sendo bem descritiva, representando justamente a edição de um módulo dentro da aplicação.

## Descrição Numerada

### Fluxo Base

1. Administrador seleciona a opção de editar um módulo na área de gerenciamento do sistema.
2. Sistema apresenta a solicitação de nome para o módulo.
3. Administrador edita nome do módulo.
4. Sistema exibe a opção de editar quiz e editar curso.
5. Administrador seleciona a opção de editar quiz.
6. Sistema exibe campos para inserir perguntas e alternativas para formar um questionário.
7. Administrador edita as perguntas e suas respectivas alternativas desejadas.
8. Administrador edita/altera o gabarito desejado.
9. Administrador conclui a edição do quiz e finaliza tarefa.
10. Sistema apresenta uma mensagem indicando que foi salvo a edição.

* Campos presentes na funcionalidade: campo para inserir/editar uma pergunta dentro do questionário, campo para inserir/editar alternativas dentro de cada pergunta, campo para alterar gabarito dentro da pergunta.
* Regras de Negócio: o quiz deve conter o gabarito atualizado, o quiz deve ter questões atualizadas, cada questão deve ter apenas uma alternativa correta.

### Fluxo Alternativo

A1. Administrador seleciona a opção de editar um módulo na área de gerenciamento do sistema. <br>
A2. Sistema apresenta a solicitação de nome para o módulo. <br>
A3. Administrador edita o nome do módulo.<br>
A4. Sistema exibe a opção de editar quiz e editar curso.<br>
A5. Administrador seleciona a opção de editar curso.<br>
A6. Sistema exibe campos para inserir link(s) para acessar o curso e descrição sobre o curso.<br>
A7. Sistema exibe campos para editar link(s) já existentes para acessar o curso e descrição sobre o curso.<br>
A8. Administrador insere/edita seu(s) respectivo(s) link(s) desejados.<br>
A9. Administrador conclui a edição do curso e finaliza tarefa.<br>
A10. Sistema apresenta uma mensagem indicando que foi salvo a edição.<br>

* Campos presentes na funcionalidade: campo para inserir um link para acessar o curso, campo para editar link existente, campo para inserir nome do curso, campo para inserir descrição do curso.
* Regras de Negócio: o curso deve ter um link válido, a descrição não pode estar vazia, o nome do curso não deve estar vazio.

### Fluxos de Exceção

E1. Administrador seleciona a opção de editar um módulo na área de gerenciamento do sistema.<br>
E2. Sistema apresenta a solicitação de novo nome para o módulo.<br>
E3. Administrador não insere o nome do módulo e tenta avançar.<br>
E4. Sistema informa que é necessário um nome para o módulo para avançar.<br>

# 

E1. Administrador seleciona a opção de editar um módulo na área de gerenciamento do sistema.<br>
E2. Sistema apresenta a solicitação de novo nome para o módulo.<br>
E3. Administrador insere o nome atualizado do módulo.<br>
E4. Sistema exibe a opção de editar quiz e editar curso.<br>
E5. Administrador seleciona a opção de editar quiz.<br>
E6. Sistema exibe campos para inserir perguntas e alternativas para formar um novo questionário.<br>
E7. Administrador tenta avançar sem inserir nenhuma pergunta.<br>
E8. Sistema informa que é necessário realizar alguma alteração para atualizar o quiz ou cancelar a ação.<br>

# 

E1. Administrador seleciona a opção de editar um módulo na área de gerenciamento do sistema.<br>
E2. Sistema apresenta a solicitação de novo nome para o módulo.<br>
E3. Administrador insere o nome atualizado do módulo.<br>
E4. Sistema exibe a opção de editar quiz e editar curso.<br>
E5. Administrador seleciona a opção de editar quiz.<br>
E6. Sistema exibe campos para inserir perguntas e alternativas para formar um novo questionário.<br>
E7. Administrador tenta avançar sem inserir nenhuma pergunta.<br>
E8. Sistema informa que é necessário perguntas com alternativas para a edição de um quiz.<br>

# 

E1. Administrador seleciona a opção de editar um módulo na área de gerenciamento do sistema.<br>
E2. Sistema apresenta a solicitação de nome para o módulo.<br>
E3. Administrador insere atualiza o nome do módulo.<br>
E4. Sistema exibe a opção de editar quiz e editar curso.<br>
E5. Administrador seleciona a opção de editar quiz.<br>
E6. Sistema exibe campos para inserir perguntas e alternativas para formar um questionário.<br>
E7. Administrador tenta avançar deixando uma pergunta sem alternativas.<br>
E8. Sistema informa que é necessário perguntas com alternativas para a edição de um quiz.<br>

# 

E1. Administrador seleciona a opção de editar um módulo na área de gerenciamento do sistema.<br>
E2. Sistema apresenta a solicitação de nome para o módulo.<br>
E3. Administrador insere atualiza o nome do módulo.<br>
E4. Sistema exibe a opção de editar quiz e editar curso.<br>
E5. Administrador seleciona a opção de editar quiz.<br>
E6. Sistema exibe campos para editar perguntas e alternativas para atualizar um questionário.<br>
E7. Administrador tenta avançar deixando uma pergunta sem gabarito.<br>
E8. Sistema informa que é necessário perguntas com gabaritos para a edição de um quiz.<br>

# 

E1. Administrador seleciona a opção de editar um módulo na área de gerenciamento do sistema.<br>
E2. Sistema apresenta a solicitação de novo nome para o módulo.<br>
E3. Administrador insere o nome do módulo.<br>
E4. Sistema exibe a opção de editar quiz e editar curso.<br>
E5. Administrador seleciona a opção de editar curso.<br>
E6. Sistema exibe campos para editar link(s) para acessar o curso e descrição sobre o curso.<br>
E7. Administrador apaga o link existente e tenta avançar sem inserir um novo link para acessar o curso.<br>
E8. Sistema informa que é necessário ao menos um link para atualizar o curso corretamente.<br>

# 

E1. Administrador seleciona a opção de editar um módulo na área de gerenciamento do sistema.<br>
E2. Sistema apresenta a solicitação de atualização do nome para o módulo.<br>
E3. Administrador insere o novo nome do módulo.<br>
E4. Sistema exibe a opção de editar quiz e editar curso.<br>
E5. Administrador seleciona a opção de editar curso.<br>
E6. Sistema exibe campos para inserir link(s) para acessar o curso e descrição sobre o curso.<br>
E7. Administrador tenta avançar sem inserir uma descrição para o curso.<br>
E8. Sistema informa que é obrigatório a descrição para atualizar o curso.<br>
