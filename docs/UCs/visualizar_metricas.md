# Visualizar Métricas

Nesse documento será documentado o caso de uso de *Visualizar métricas*, resumidamente consiste em uma funcionalidade disponível apenas para o administrador do sistema, sendo bem descritiva, representando justamente a visualização das métricas referentes aos módulos, dentro da aplicação.

## Descrição Numerada

### Fluxo Base (Visualiza métricas dos quizzes)

1. Administrador seleciona a opção de visualizar métricas de módulos na área de gerenciamento do sistema.
2. Sistema apresenta a solicitação de escolha de um módulo.
3. Administrador seleciona o módulo de uma lista.
4. Sistema exibe a tela com as diferentes métricas para o módulo e um menu para filtragem dos dados de um quiz específico.
5. Administrador seleciona um quiz do menu de filtragem.
6. Sistema exibe as métricas referentes apenas ao quiz selecionado.

### Fluxo Alternativo

A1. Administrador seleciona a opção de visualizar métricas de reportes de usuários da instituição na área de gerenciamento do sistema. <br>
A2. Sistema exibe a tela com métricas relevantes aos reportes gerais dos usuários cadastrados na instituição do Administrador. <br>
A3. Administrador escolhe um usuário específico no menu de seleção.<br>
A4. Sistema exibe a tela com as métricas de reportes do usuário selecionado.<br>


### Fluxos de Exceção

E1. Administrador seleciona a opção de visualizar métricas de módulos na área de gerenciamento do sistema.<br>
E2. Sistema apresenta a solicitação de escolha de um módulo.<br>
E3. Administrador não escolhe o módulo e tenta avançar.<br>
E4. Sistema informa que é necessário selecionar um módulo para avançar.<br>