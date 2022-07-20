# Visão Do Produto e Projeto

## Sumário

- 1 Visão Geral do Produto
  - 1.1 Declaração de Posição do Produto
  - 1.2 Objetivos do Produto
  - 1.3 Tecnologias a serem Utilizadas
- 2 Visão Geral do Projeto
  - 2.1 Organização do Projeto
  - 2.2 Planejamento das Fases e/ou Iterações
  - 2.3 Matriz de Comunicação
  - 2.4 Gerenciamento de Riscos
  - 2.5 Critérios de Replanejamento
- 3 Processo de Desenvolvimento de Software
  - 3.1 Atividade 1
  - 3.2 Atividade 2
  - 3.3 Atividade 3
  - 3.4 Atividade "N"
- 4 Processo de Engenharia de Requisitos
  - 4.1 Elicitação de Requisitos
  - 4.2 Análise de Requisitos
  - 4.3 Documetação de Requisitos
  - 4.4 Verificação e Validação de requisitos
  - 4.5 Gerenciamento de Requisitos
- 5 Lições Aprendidas
  - 5.1 Unidade 1
    - 5.1.1 MDS
    - 5.1.2 Requisitos
    - 5.1.3 MDS e Requisitos
- 6 Referências Bibliográficas

## Visão do Produto e Projeto

O guardiões da saúde é uma solução que foi desenvolvida graças a uma parceria entre Skoll Global Threats Found (SGTF), o Ministério da Saúde, a startup Epitrack e a ProEpi, com intuito de realizar vigilância participatiiva.

## 1 Visão Geral do Produto

### 1.1 Declaração de Posição do Produto

  Ao utilizar desse produto, as instituições poderão realizar QUIZ semanais para avaliar                             	os usuários cadastrados.

| Para | As instituições que utilizam o GDS |
|--|--|
| Quem |População no geral |
| O (nome do produto) |Quizes |
| Que |Conscientizar o usuário sobre um assunto qualquer relacionado aos cursos e verificar se estes foram realmente vistos |
| Ao contrário |O GDS é uma solução muito específica, portanto não há conhecimento sobre um concorrente até o momento |
| Nosso produto |O GDS é uma solução muito específica, portanto não há uma diferenciação primária no produto |

### 1.2 Objetivos do Produto

Reengenharia de features presentes no Guardiões da Saúde, alteração da necessidade diária de realizar o reporte para semanal. Desenvolvimento do QUIZ,  nova feature para o aplicativo com objetivo de testar o conhecimento do usuário em diversos módulos e desenvolvimento de ferramenta para criação de QUIZ pelas instituições.

### 1.3 Tecnologias a Serem Utilizadas

Para comunicação, utilizamos Whatsapp, Telegram e Discord. A api do Guardiões da Saúde é em Ruby, utilzaremos JavaScript para o desenvolvimento das features. Figma será utilizado para a prototipação e Docker para testes.


## 2 Visao Geral do Projeto

### 2.1 Organizacao do Projeto

|Papel|Atribuicoes|Responsavel|Participantes|
|-----|-----------|-----------|-------------|
|Desenvolvedor Front-End|Codificar o produto, codificar testes unitários, realizar refatoração|MDS|Marcus Martins, Igor Tiago, Juan Mangueira, Tiago Vivan, Iago |
|Desenvolvedor Back-End|Codificar funcionalidades e fluxo de controle da aplicação|MDS|Marcus Martins, Igor Tiago, Juan Mangueira, Tiago Vivan, Iago|
Engenharia de Requsitos|Atualizar o escopo do produto, organizar o escopo das sprints, definir product backlog|Requisitos|Caio César, Hian Praxedes, Matheus Pimentel, Luiz Pettengill, Taynara Cristina|
Tech Lead|Validar as entregas de desenvolvimento|Ítalo|Marcus Martins, Igor Tiago, Juan Mangueira, Tiago Vivan, Iago, Ítalo|
Cliente|Definir necessidades de melhoria no produto e novas ferramentas a serem desenvolvidas|Maria Vitória, Marcela, George Marsicano|Caio César, Hian Praxedes, Matheus Pimentel, Luiz Pettengill, Taynara Cristina, Maria Vitória, Marcela, George Marsicano|

### 2.2 Planejamento das Fases e/ou Iterações do Projeto
|Sprint|Produto(Entrega)|Data Inicio|Data Fim|
|------|----------------|-----------|--------|
|Sprint 1|Definicao do Produto|13/06/22|19/06/22|
|Sprint 2|Backlog do Produto|20/06/22|26/06/22|
|Sprint 3|MVP e Planejamento do Projeto|27/06/22|03/07/22|
|Sprint 4|Protótipo de tela, ajustar ambiente de desenvolvimento|04/07/22|10/07/22|
|Sprint 5|Reportar semanalmente o estado do usuário (US-01)|11/07/22|17/07/22|
|Sprint 6|Notificar usuário até o reporte ser realizado (US-02), garantir que para ganhar crédito o usuário tenha respondido todas as semanas, ao menos uma vez (US-03)|18/07/22|24/07/22|
|Sprint 7|Facilitar ao usuário a visualização de que não enviou um reporte (US-04), criar quiz semanais (US-05)|25/07/22|31/07/22|
|Sprint 8|Criar tela de cadastro de quiz com número de questões definidas pela instituição até dado limite (US-06)|01/08/22|07/08/22|
|Sprint 9|Garantir que o usuário terá acesso ao quis equivalente ao nível que se encontra (US-07)|08/08/22|14/08/22|
|Sprint 10|Criar banco de dados contendo informações do usuário referente ao módulo que ele se encontra (US-08)|15/08/22|21/08/22|
|Sprint 11|Criar ícone na barra de tarefas que direcionará para tela de quis (US-09), criar tela do quiz contendo botões que direcionarão para página de curso ou página de quis (US-10)|22/08/22|28/08/22|
|Sprint 12|Criar campos para inserção de links do conteúdo e vídeo aulas de cada módulo (US-11) |29/08/22|04/09/22|
|Sprint 13|Garantir que o usuário possa realizar o quiz sem necessariamente ter estudado material proposto (US-12)|05/09/22|11/09/22|
|Sprint 14|Realizar Testes|12/09/22|15/09/22|

### 2.3
|Descricao|Area/Envolvidos|Periodicidade|Produtos Gerados|
|---------|---------------|-------------|----------------|
| Acompanhamento das Atividades em Andamento<br/> Acompanhamento dos Riscos, Compromissos, Ações Pendentes, Indicadores| Equipe de MDS e Equipe de Requisitos | Semanal - MDS, Quinzenal-REQ| Ata de Reunião, Relatório de Situação do Projeto|
|Comunicar Situacao do Projeto|Equipe de MDS, Equipe de Requisitos, Professor|Semanal|Ata de reuniao, Relatorio de Situacao de Projeto|
|Reunião diária para alinhamento da equipe e levantar dúvidas para que se possa seguir com a sprint| Equipe de MDS, Equipe de Requisitos| Diario (Segunda a Sexta)| Ata de Reuniao|
|Reunião semanal de acompanhamento da sprint|Equipe de MDS, Equipe de Requisitos|Semanal|Funcionalidades da Aplicacao|Apresentação do progresso da equipe|Equipe de MDS, Equipe de Requisitos|Ao fim de cada módulo|Produto e projeto, funcionalidades desenvolvidas

### 2.4 Gerenciamento de Riscos

  - Não conseguir entregar o Backlog da sprint.
    - Ver quais foram os responsáveis pelas partes não entregues e fornecer apoio necessário para que consiga realizar suas tarefas na próxima sprint.
  - Membro da equipe trancar a matéria.
    - Comunicação constante entre todos os membros da equipe para que todos os membros sejam informados com antecedência.
  - Baixa produtividade em semana de prova.
    - Aumentar produtividade na semana anterior e posterior
  - Dificuldades de comunicação entre as equipes de MDS e Requisitos
    - Manter contato ao menos uma vez na semana, na reunião semanal de acompanhamento da sprint.

### 2.5 Critérios de Replanejamento

O produto será replanejado caso entenda-se que o escopo está inadequado, isto é, grande ou pequeno demais para o tempo da matéria e tamanho da equipe. Também poderá ocorrer seu replanejamento caso as clientes necessitem de uma nova funcionalidade, sendo necessário um backlog atualizado e uma revisão das sprints.

## 3 Processo de desenvolvimento de software

### 3.1 Atividade 1

   Atividade      | Método        | Ferramenta            |Entrega
---------|-------------|-------------|-----------------
  Definição das User Stories   |Sprint, Dailies e Baby Steps.     | Discord e WhatsApp. |User Stories devidamente definidos.

### 3.2 Atividade 2

   Atividade      | Método        | Ferramenta            |Entrega
---------|-------------|-------------|-----------------
  Modelagem visual.    |Modelagem Visual (casos de uso) e protipagem.   | Figma e Lucidchart.  |Protótipo pronto para análise.

### 3.3 Atividade 3

   Atividade      | Método        | Ferramenta            |Entrega
---------|-------------|-------------|-----------------
  Validação do protótipo.    |Prototipagem.      | Figma e Lucidchart.  |Modelo e protótipo prontos para implementação.

### 3.4 Atividade 4

   Atividade      | Método        | Ferramenta            |Entrega
---------|-------------|-------------|-----------------
  Mapeamento e implementação do código através de classes criadas.    |Pair Programming, Refatoração, Sprint, Dailies, Baby Steps.     | VS. Code, Discord e WhatsApp.  |Código pronto para testes.

### 3.5 Atividade 5

   Atividade      | Método        | Ferramenta            |Entrega
---------|-------------|-------------|-----------------
  Automação de testes unitários utilizando Docker.    |Testes unitários automatizados e Containerização.      | Docker.  |Funcionalidades devidamente testadas.

## 4 PROCESSO DE ENGENHARIA DE REQUISITOS

  O processo de engenharia de requisitos escolhido seguirá o mesmo modelo definido para o desenvolvimento de software, uma vez que as equipes de engenharia de requisitos e de engenharia de software estão trabalhando conjuntamente. Isso tornará mais fácil a integração entre as duas equipes. Com isso em mente, o processo escolhido foi o Extreme Programming, ou XP, e as atividades que serão executadas pela equipe de engenharia de requisitos podem ser vistas detalhadamente nas tabelas presentes nos subtópicos abaixo.

### 4.1 Elicitação de Requisitos

  | Atividade | Método | Ferramenta | Entrega |
  |--|--|--|--|
  | Descoberta e compreensão dos requisitos | Estudo da documentação do produto, observação do produto, entrevistas com as clientes | Reunião com as clientes, leitura da documentação, utilização do produto | Conjunto não estruturado de requisitos |

  | Atividade | Método | Ferramenta | Entrega |
  |--|--|--|--|
  | Classificação e organização dos requisitos | Agrupamento e organização do conjunto não estruturado em grupos correlatos | Reunião da equipe de requisitos | Conjunto organizado de requisitos do projeto |

### 4.2 Análise de Requisitos

  | Atividade | Método | Ferramenta | Entrega |
  |--|--|--|--|
  | Priorização e negociação dos requisitos | Alinhamento com as clientes dos requisitos organizados | Reunião com as clientes e a equipe de egenharia de requisitos | Definição/Redefinição dos requisitos do projeto |

### 4.3 Documentação de Requisitos

  | Atividade | Método | Ferramenta | Entrega |
  |--|--|--|--|
  | Documentação dos requisitos | Criação de Épicos, features e Histórias de usuários a partir dos requisitos | Quadro Kanban do Trello | Product backlog |

### 4.4 Verificação e Validação de Requisitos

  | Atividade | Método | Ferramenta | Entrega |
  |--|--|--|--|
  | Inspeção | Revisão por pares | Reunião da equipe de requisitos (em pares) para inspeção das entregas | Novas tarefas de correção de bugs no product backlog |

  | Atividade | Método | Ferramenta | Entrega |
  |--|--|--|--|
  | Acompanhamento das atividades de desenvolvimento | Comunicação constante entre equipes de Engenharia de Requisitos e Desenvolvimento | Conversas e reuniões informais durante a sprint | Maior alinhamento da equipe com os requisitos definidos |

### 4.5 Gerenciamento de Requisitos

  | Atividade | Método | Ferramenta | Entrega |
  |--|--|--|--|
  | Criação de itens do product backlog | Criar os itens do product backlog com base requisitos funcionais e não-funcionais do projeto | Reuniões da equipe de requisitos com as clientes para a criação de itens no quadro Kanban (Trello) do projeto | Product Backlog |

  | Atividade | Método | Ferramenta | Entrega |
  |--|--|--|--|
  | Manutenção do product backlog | Fazer o manejo do product backlog com base nos requisitos funcionais e não-funcionais do projeto. | Alinhamentos com as clientes por meio de reuniões, gerenciamento pela equipe de Engenharia de Requisitos dos itens do product backlog | Refinamento do Product Backlog |

  | Atividade | Método | Ferramenta | Entrega |
  |--|--|--|--|
  | Definição das tarefas da sprint | Definição das tarefas a serem executadas na sprint com base nos itens do product backlog | Reuniões de sprint planning | Sprint Backlog |

## 5 Lições aprendidas
### 5.1 Unidade 1
#### 5.1.1 MDS

  Nessa primeira unidade tivemos um pouco de dificuldade em situar toda a dinâmica de trabalho em grupo que a disciplina propõe. Todos os conteúdos foram mais do que achávamos que seria e isso acabou prejudicando não só o individual, mas também toda minha equipe, onde por muitas vezes estávamos perdidos. No entanto, na semana da entrega foi quando conseguimos nos sintonizar melhor e decidir de vez tudo aquilo que iríamos fazer, e isso acabou esclarecendo muitas coisas e fazendo com que muitos de nós estudássemos mais e fossemos mais atrás das coisas, sendo sincero com o que sabíamos ou não. Portanto, aprendi muito sobre diálogo, sobre como devemos agir como equipe e como precisamos também ir atrás das coisas individualmente para assim fazer um trabalho melhor em conjunto.

#### 5.1.2 Requisitos

Na equipe de requisitos antes de tudo tivemos que aperfeiçoar nossa comunicação, tendo em vista que alguns membros não se conheciam. Após esse obstáculo trabalhamos nossa organização para conseguirmos um horário bom para a maioria do time conseguir se reunir e aprender mais sobre o Guardiões da Saúde, onde todos já haviam tido contato, mas não conhecíamos o background da aplicação, entendendo melhor como funciona suas funcionalidades, como a equipe que desenvolveu trabalhou e fazendo um trabalho de análise e adaptação para passar informações de forma mais clara para a equipe de MDS.

Além disso, nos colocamos no lugar do cliente para entender o que e como exatamente ele gostaria das suas requisições. Com todas essas informações, tivemos que pensar de forma crítica para formular perguntas que surgiram a partir das explicações do cliente, ou aspectos que não foram tão bem explicados para a equipe. Contudo, tivemos que aprender melhor sobre o produto, justamente para conseguir fazer um processo de reengenharia e formular os requisitos do que já foi construído até o momento. Portanto, tivemos várias lições aprendidas, dentre elas, comunicação, organização, compreensão e criticidade.

#### 5.1.3 MDS-Requisitos

A maior lição aprendida nessa unidade com certeza foi a comunicação, as equipes não se conheciam totalmente ainda, então foram gerados encontros para esse obstáculo ser ultrapassado, além do que as informações devem ser passadas de forma clara entre os times para não acontecer confusões ou trabalhos extras. Outra questão que foi gerada com isso foi a empatia, já que as equipes são interdependentes em algumas tarefas, então não é tão simples pedir que uma atividade seja feita, existe todo uma forma de se comunicar para não causar sentimentos ruins entre as equipes.

### 5.2 Unidade 2
#### 5.2.1 MDS
#### 5.2.2 Requisitos
#### 5.2.1 MDS-Requisitos

### 5.3 Unidade 3
#### 5.3.1 MDS
#### 5.3.2 Requisitos
#### 5.3.3 MDS-Requisitos

### 5.4 Unidade 4
#### 5.4.1 MDS
#### 5.4.2 Requisitos
#### 5.4.3 MDS-Requisitos

## 6 Referências bibliográficas




