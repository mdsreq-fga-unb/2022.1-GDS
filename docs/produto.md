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
  - 3.1 Metodologia Adotada
  - 3.2 Atividades
    - 3.2.1 Atividade 1
    - 3.2.2 Atividade 2
    - 3.2.3 Atividade 3
    - 3.2.4 Atividade 4
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



### 2.3 Matriz de Comunicação
|Descricao|Area/Envolvidos|Periodicidade|Produtos Gerados|
|---------|---------------|-------------|----------------|
| Acompanhamento das Atividades em Andamento<br/> Acompanhamento dos Riscos, Compromissos, Ações Pendentes, Indicadores| Equipe de MDS e Equipe de Requisitos | Semanal - MDS, Quinzenal-REQ| Sem produtos gerados|
|Comunicar Situacao do Projeto|Equipe de MDS, Equipe de Requisitos, Professor|Semanal|Sem produtos gerados|
|Reunião diária para alinhamento da equipe e levantar dúvidas para que se possa seguir com a sprint| Equipe de MDS, Equipe de Requisitos| Diario (Segunda a Sexta)| Sem produtos gerados|
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
  - Dificuldades de comunicação entre as equipes de MDS e o Ítalo
    - Manter contato constante ao fim de cada sprint, e marcar reuniões com certa frequência
  - Dificuldades de comunicação entre as equipes de Requisitos e as Clientes
    - Manter contato constante com as clientes encontrando o melhor horário para pelo menos uma delas, ou tirando dúvidas pelo whatsapp

### 2.5 Critérios de Replanejamento

O produto será replanejado caso entenda-se que o escopo está inadequado, isto é, grande ou pequeno demais para o tempo da matéria e tamanho da equipe. Também poderá ocorrer seu replanejamento caso as clientes necessitem de uma nova funcionalidade, sendo necessário um backlog atualizado e uma revisão das sprints.

## 3 Processo de desenvolvimento de software

### 3.1 Metodologia Adotada

Pensamos em uma metodologia para se trabalhar, porém não conseguimos nos identificar com nenhuma, no entanto, a partir da abordagem Gupta, percebemos que era melhor um ciclo de vida evolutivo devido ao pouco conhecimento da tecnologia pelos participantes, portanto escolhemos a metodologia XP, seguindo seus valores de comunicação, simplicidade, feedback, coragem e respeito.

### 3.2 Atividades de Desenvolvimento

Utilizaremos para a gestão de tarefas as Sprints, da metodologia Scrum, tendo intervalos de uma semana entre as entregas, e a tabela vinda da metodologia KanBan

Dentre as atividades das sprints, serão desempenhadas:

### 3.2.1 Atividade 1

|Atividade | Método | Ferramenta | Entrega | Feedback |
|-|-|-|-|-|
| Design do prototipo | Prototipagem em pares | Figma | Protótipo pronto para análise | Segundos |

### 3.2.2 Atividade 2

|Atividade | Método | Ferramenta | Entrega | Feedback |
|-|-|-|-|-|
| Validação do protótipo. | Esclarecimentos entre equipe e cliente e aceitação do protótipo | Whatsapp para conversas informais e Discord para reuniões | Protótipo pronto para implementação | Dias |

### 3.2.3 Atividade 3

|Atividade | Método | Ferramenta | Entrega | Feedback |
|-|-|-|-|-|
| Construção do Código | Pair Programming, Refatoração, Sprint, Dailies, Baby Steps | VS Code para a construção, Discord para comunicação durante a programação em pares e WhatsApp para conversas pontuais |Código pronto para testagem | Segundos |

### 3.2.4 Atividade 4

|Atividade | Método | Ferramenta | Entrega | Feedback |
|-|-|-|-|-|
| Testagem do Código | Testes unitários automatizados e containerização | Docker |Funcionalidades devidamente testadas. | Minutos |

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
  | Documentação dos requisitos | Criação de Épicos, features e Histórias de usuários a partir dos requisitos | Quadro Kanban do ZenHub | Product backlog |

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
  | Criação de itens do product backlog | Criar os itens do product backlog com base requisitos funcionais e não-funcionais do projeto | Reuniões da equipe de requisitos com as clientes para a criação de itens no quadro Kanban (ZenHub) do projeto | Product Backlog |

  | Atividade | Método | Ferramenta | Entrega |
  |--|--|--|--|
  | Manutenção do product backlog | Fazer o manejo do product backlog com base nos requisitos funcionais e não-funcionais do projeto. | Alinhamentos com as clientes por meio de reuniões, gerenciamento pela equipe de Engenharia de Requisitos dos itens do product backlog | Refinamento do Product Backlog |

  | Atividade | Método | Ferramenta | Entrega |
  |--|--|--|--|
  | Definição das tarefas da sprint | Definição das tarefas a serem executadas na sprint com base nos itens do product backlog | Reuniões de sprint planning | Sprint Backlog |
 
## 5 Escopo do Produto

### 5.1 Requisitos funcionais

#### Lista de Requisitos Funcionais (Reengenharia)

- RF01: Realizar cadastro de uma nova conta (APP)
- RF02: Recuperar a senha do usuário pelo e-mail cadastrado (APP)
- RF03: Cadastrar dados da universidade (APP)
- RF04: Reportar diariamente estado (APP)
- RF05: Enviar notificações de report (APP)
- RF06: Cadastrar vacinas (APP)
- RF07: Mostrar dias que os reports foram feitos (APP)
- RF08: Mostrar gráfico com porcentagem dos reports feitos (APP)
- RF09: Informar localização de onde o report foi feito (APP)
- RF10: Visualizar opções de dicas de saúde e higiene (APP)
- RF11: Visualizar notícias do Twitter da Proepi (APP)
- RF12: Cancelar participação no aplicativo (APP)
- RF13: EEditar dados cadastrais do usuário (APP)
- RF14: Visualizar número de reports seguidos marcados como bem (APP)
- RF15: Adicionar mais contas conectadas ao aplicativo (APP)
- RF16: Trocar de conta do usuário (APP)
- RF17: Visualizar mapa hospitais/unidades de saúde (APP)
- RF18: Acessar dados de reportes de saúde (APP)

### Lista de Requisitos Funcionais (Clientes)

- RF19: Reportar semanalmente o estado do usuário (APP)
- RF20: Notificar o usuário até o reporte ser realizado (APP)
- RF21: Criar quiz (WEB)
- RF22: Editar quiz (WEB)
- RF23: Remover quiz (WEB)
- RF24: Visualizar dados sobre o quiz (WEB)
- RF25: Criar curso (WEB)
- RF26: Editar curso (WEB)
- RF27: Remover curso (WEB)

# Requisitos Funcionais - SAFE

<table style="width:100%">
<thead>
  <tr>
    <th>ÉPICO</th>
    <th>FEATURE</th>
    <th>ID</th>
    <th>HISTÓRIA</th>
    <th>PRIORIDADE</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="3">Reporte Semanal (mobile)</td>
    <td rowspan="3">Reporte semanal</td>
    <td>US - 01</td>
    <td>Eu, como instituição, quero receber pelo menos um reporte por semana de cada usuário, para registrar a taxa de contaminação</td>
    <td align="center"></td>
  </tr>
  <tr>
    <td>US - 02</td>
    <td>Eu, como usuário do produto, quero ser notificado do reporte, para que eu lembre de fazer o reporte semanal</td>
    <td align="center"></td>
  </tr>
  <tr>
    <td>US - 03</td>
    <td>Eu, como usuário do produto, quero não ser mais notificado caso já tenha realizado o reporte, para que não seja incomodado já tendo feito o reporte</td>
    <td align="center"></td>
  </tr>
  <tr>
    <td rowspan="12">Quizes</td>
    <td rowspan="3">Criar um curso por módulo</td>
    <td>US - 04</td>
    <td>Eu, como instituição, quero inserir informações sobre o conteúdo que será estudado, para que os usuários tenham um material para se informarem sobre os assuntos dos quizzes</td>
    <td align="center"></td>
  </tr>
  <tr>
    <td>US - 05</td>
    <td>Eu, como instituição, quero editar as informações inseridas no curso, para que eu consiga editar as informações caso necessário</td>
    <td align="center"></td>
  </tr>
  <tr>
    <td>US - 06</td>
    <td>Eu, como instituição, quero poder excluir um curso, para que eu consiga remover um curso que não é mais necessário</td>
    <td align="center"></td>
  </tr>
  <tr>
    <td rowspan="3">Criar quiz semanal</td>
    <td>US - 07</td>
    <td>Eu, como instituição, quero criar quiz para avaliar o conhecimento dos estudantes, para dar um estímulo para ser um conhecimento básico sobre saúde</td>
    <td align="center"></td>
  </tr>
  <tr>
    <td>US - 08</td>
    <td>Eu, como instituição, quero poder editar o quiz, para que esteja sempre atualizado</td>
    <td align="center"></td>
  </tr>
  <tr>
    <td>US - 09</td>
    <td>Eu, como instituição, quero poder excluir um quiz caso. Para que esteja sempre atualizado.</td>
    <td align="center"></td>
  </tr>
  <tr>
    <td rowspan="5">Dados do quiz</td>
    <td>US - 10</td>
    <td>Eu, como usuário do produto, quero saber qual foi minha nota no quiz para saber se fui aprovado e avaliar meus conhecimentos</td>
    <td align="center"></td>
  </tr>
  <tr>
    <td>US - 11</td>
    <td>Eu, como usuário do produto, quero saber se passei no quiz ou se preciso fazer novamente para não perder nenhuma avaliação</td>
    <td align="center"></td>
  </tr>
  <tr>
    <td>US - 12</td>
    <td>Eu, como usuário do produto, quero poder fazer o quiz novamente caso queira para aumentar minha nota ou não tenha obtido nota suficiente</td>
    <td align="center"></td>
  </tr>
  <tr>
    <td>US - 13</td>
    <td>Eu, como instituição, quero visualizar como os estudantes se saíram no quiz para avaliar seus conhecimentos</td>
    <td align="center"></td>
  </tr>
  <tr>
    <td>US - 14</td>
    <td>Eu, como usuário do produto, quero saber se já completei o quiz para avaliar meus conhecimentos</td>
  <td align="center"></td>
  </tr>
  
 


</tbody>
</table>

|         Legenda (prioridades)  |Definição 	                                                  |
| :----------------------------: | :------------------------------------------------------------------------------------ |
| Alta                           |  Requisitos sem os quais a aplicação é considerada incompleta |
| Média                          |  Requisitos importantes que podem ser postergados      |
| Baixa                          |  Requisitos sem os quais o Sistema funciona de maneira satisfatória   |


# Requisitos não funcionais

<table>
<thead>
  <tr>
    <th>Requisitos Não Funcionais (Classificação)</th>
    <th>RNf</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="4">Requisitos de Implementação</td>
    <td>O backend do produto deve ser desenvolvido em JavaScript</td>
  </tr>
  <tr>
    <td>O frontend do produto será desenvolvido em React Native</td>
  </tr>
  <tr>
    <td>O protótipo do front end será feito no Figma</td>
  </tr>
  <tr>
    <td>A responsidade do produto será feita utilizando a aplicação PWA</td>
  </tr>
  <tr>
    <td>Requisitos Legislativos</td>
    <td>O produto esteja de acordo com a LGPD (Lei geral de proteção de dados)</td>
  </tr>
  <tr>
    <td rowspan="9">Requisitos de Usabilidade</td>
    <td>O produto deve funcionar em android e ios</td>
  </tr>
  <tr>
    <td>O produto deve deixar destacado caso o usuário termine o curso</td>
  </tr>
  <tr>
    <td>O produto deve deixar destacado caso o usuário termine o quiz com nota maior que 50%</td>
  </tr>
  <tr>
    <td>O produto deve mostrar a nota do quiz, referente ao módulo que o usuário está</td>
  </tr>
  <tr>
    <td>O produto deve funcionar apenas com acesso à internet</td>
  </tr>
  <tr>
    <td>O produto deve dar a opção entre refazer quiz ou passar para o próximo módulo</td>
  </tr>
  <tr>
    <td>O produto deve fazer uso de pop-ups</td>
  </tr>
  <tr>
    <td>Deve ser possível ver seu histórico de reports tanto no formato de calendário quanto de estatística (gráfico de pizza)</td>
  </tr>
  <tr>
    <td>O aplicativo não deve exigir muito do aparelho em que está sendo usado</td>
  </tr>
  <tr>
    <td rowspan="2">Requisito de Portabilidade</td>
    <td>O produto deve ser acessível via mobile</td>
  </tr>
  <tr>
    <td>As instituições contratantes devem acessar as funcionalidades por meio de dashboards web</td>
  </tr>
</tbody>
</table>

# 6 Canvas MVP

![](https://raw.githubusercontent.com/mdsreq-fga-unb/2022.1-GDS/ff06dafb8a6f4d2d8896457556084a261359f04a/assets/Canvas_MVP.png)

## 7 Lições aprendidas
### 7.1 Unidade 1
#### 7.1.1 MDS

Nessa primeira unidade tivemos um pouco de dificuldade em situar toda a dinâmica de trabalho em grupo que a disciplina propõe. Todos os conteúdos foram mais do que achávamos que seria e isso acabou prejudicando não só o individual, mas também toda minha equipe, onde por muitas vezes estávamos perdidos. No entanto, na semana da entrega foi quando conseguimos nos sintonizar melhor e decidir de vez tudo aquilo que iríamos fazer, e isso acabou esclarecendo muitas coisas e fazendo com que muitos de nós estudássemos mais e fossemos mais atrás das coisas, sendo sincero com o que sabíamos ou não. Portanto, aprendi muito sobre diálogo, sobre como devemos agir como equipe e como precisamos também ir atrás das coisas individualmente para assim fazer um trabalho melhor em conjunto.

#### 7.1.2 Requisitos

Na equipe de requisitos antes de tudo tivemos que aperfeiçoar nossa comunicação, tendo em vista que alguns membros não se conheciam. Após esse obstáculo trabalhamos nossa organização para conseguirmos um horário bom para a maioria do time conseguir se reunir e aprender mais sobre o Guardiões da Saúde, onde todos já haviam tido contato, mas não conhecíamos o background da aplicação, entendendo melhor como funciona suas funcionalidades, como a equipe que desenvolveu trabalhou e fazendo um trabalho de análise e adaptação para passar informações de forma mais clara para a equipe de MDS.

Além disso, nos colocamos no lugar do cliente para entender o que e como exatamente ele gostaria das suas requisições. Com todas essas informações, tivemos que pensar de forma crítica para formular perguntas que surgiram a partir das explicações do cliente, ou aspectos que não foram tão bem explicados para a equipe. Contudo, tivemos que aprender melhor sobre o produto, justamente para conseguir fazer um processo de reengenharia e formular os requisitos do que já foi construído até o momento. Portanto, tivemos várias lições aprendidas, dentre elas, comunicação, organização, compreensão e criticidade.

#### 7.1.3 MDS-Requisitos

A maior lição aprendida nessa unidade com certeza foi a comunicação, as equipes não se conheciam totalmente ainda, então foram gerados encontros para esse obstáculo ser ultrapassado, além do que as informações devem ser passadas de forma clara entre os times para não acontecer confusões ou trabalhos extras. Outra questão que foi gerada com isso foi a empatia, já que as equipes são interdependentes em algumas tarefas, então não é tão simples pedir que uma atividade seja feita, existe todo uma forma de se comunicar para não causar sentimentos ruins entre as equipes.

### 7.2 Unidade 2
#### 7.2.1 MDS
Nesta unidade 2, aprendemos, em primeiro lugar, a importância de uma sala invertida para o compartilhamento de conhecimentos plurais e acessíveis, numa linguagem que todos compartilham. Assim, conseguimos também desenvolver softskills relacionadas à comunicação e resiliência para solução dos problemas durante a apresentação. Dessa forma, aprendemos sobre as tecnologias de testes de sistemas Cypress, testes unitários com Jpress, Linguagem de programação TypeScript, React com typescript, Git, entre outros conhecimentos adicionais compartilhados durante os momentos de ensino.

#### 7.2.2 Requisitos

Na equipe de requisitos tivemos alguns problemas para definirmos os requisitos onde aconteceu um equivoco quando foram definidos alguns requisitos funcionais e não funcionais. Com isso foram colocadas algumas regras de negócio e atividades que seriam realizadas no processo de desenvolvimento como requisitos funcionais, fazendo com que tivéssemos que revisar e planejar novamente os requisitos do projeto, mas dessa vez de forma correta.

#### 7.2.1 MDS-Requisitos

As duas equipes aprenderam a melhorar a comunicação de ambas as partes, para seja comunicado o que ambas as equipes estão fazendo para que não aja confusões ou questionamento das atividades das equipes, assim não atrasando as entregas e facitando a organização das tarefas.

### 7.3 Unidade 3
#### 7.3.1 MDS
#### 7.3.2 Requisitos
#### 7.3.3 MDS-Requisitos

### 7.4 Unidade 4
#### 7.4.1 MDS
#### 7.4.2 Requisitos
#### 7.4.3 MDS-Requisitos

## 8 Referências bibliográficas
