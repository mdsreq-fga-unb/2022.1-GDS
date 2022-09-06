# Visualizar lista de módulos disponíveis
Nesse documento será documentado o caso de uso de Visualizar lista de módulos disponíveis Visualizar lista de módulos disponíveis, resumidamente consite em o usuário do aplicativo poder ver os módulos disponíveis para ele no momento.

## Descrição Numerada

### Fluxo Base

1. O usuário entra com sua conta no aplicativo.
2. O usuário seleciona a opção de Módulos na barra lateral.
3. Visualiza os módulos disponíveis no momento.
4. O usuário seleciona o módulo.
5. O usuário seleciona opção de ver quizzes disponíveis.
6. Realiza o quiz.
7. Visualiza a nota do quiz.

* Regras de Negócio: Os módulos mais avançados só podem ser liberados caso os anteriores tenham uma nota minima de 50%.

### Fluxo Alternativo

A1. O usuário entra com sua conta no aplicativo.<br>
A2. O usuário seleciona a opção de Módulos na barra lateral.<br>
A3. Visualiza os módulos disponíveis no momento.<br>
A4. O usuário seleciona o módulo.<br>
A5. O usuário seleciona a opção de ver os cursos disponíveis.<br>
A6. O usuário acessa o conteúdo do curso selecionado.<br>

### Fluxos de Exceção

E1. O usuário entra com sua conta no aplicativo.<br>
E2. O usuário seleciona a opção de Módulos na barra lateral.<br>
E3. Visualiza os módulos disponíveis no momento.<br>
E4. O usuário seleciona um módulo que ainda não foi liberado.<br>
E5. O sistema informa que esse módulo ainda não foi liberado.<br>