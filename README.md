# Prática de Desenvolvimento de Software

* Curso de graduação: Prática de Desenvolvimento de Software
* Prof. Marco Tulio Valente - mtov [at] dcc.ufmg.br

## Objetivo

Complementar a formação dos alunos na área de Engenharia de Software, por meio do desenvolvimento de um projeto real, usando técnicas e práticas modernas de desenvolvimento de software. Mas especificamente, os alunos vão desenvolver um sistema:

* real, isto é, um sistema que inclusive tenha usuários reais
* usado práticas modernas de Engenharia de Software

## Livro Texto 

Engenharia de Software Moderna ([link](https://engsoftmoderna.info/))

## Práticas Usadas no Curso (pré-requisito)

* Práticas de processo: histórias de usuários, backlog do produto, backlog do sprint, sprint planning, sprint review e retrosperctiva
* Programação: testes de unidade, testes de integração, testes de interface (opcional), bons princípios e padrões de projeto, refactoring, revisão de código (pull requests), code style
* Deployment: controle de versões (GitHub), integração contínua, trunk-based development, feature flags, deployment contínuo (opcional), looging e analytics.

## Avaliação

* 3 sprints de 3 semanas cada um (9 semanas): 60 pontos, isto é, 20 pontos por sprint
* Ajustes, feedback e monitoramento do sistema em produção (3 semanas): 10 pontos
* 1 seminário (por grupo) sobre tecnologia: 15 pontos
* 1 seminário (por grupo) sobre prática/conceito: 15 pontos
* Observação: devido às características da disciplina, ela não possuirá exame especial

## Pontos Extra

* 0.25 pontos para cada "typo" (erro de ortografia, gramatical, etc) encontrado no livro texto
* 1.0 ponto para qualquer outro tipo de erro 
* Limitado a 3 pontos por aluno
* Para garantir o ponto: enviar mail para o professor (apenas o aluno que achar primeiro o erro será contemplado)

## Grupos

* Essa é uma disciplina de trabalho em grupo, com 4 ou 5 alunos. Todos os trabalhos serão em grupos.
* O professor vai procurar atuar como um PO, Scrum Master/Agile Coach.

## Seminário de Tecnologia

* Possíveis temas: algum framework, biblioteca ou ferramenta (Angular, React, Flutter, Apache Kafka, Kubernettes, Docker, etc)
* Não pode ser sobre uma linguagem de programação
* Duração: 75 minutos
* 1a tarefa: enviar tema por e-mail para professor (para aprovação e marcação da data do seminário de tecnologia)

## Seminário sobre Prática/Conceito

* Possíveis temas: um novo "processo" (exemplo: Design Thinking, Design Sprint, Shape Up, etc), um livro de Engenharia de Software (exemplo: A Philosophy of Software Design, Pragmatic Programmer, etc)
* Duração: 75 minutos
* 1a tarefa: enviar tema por e-mail para professor (para aprovação e marcação da data do seminário de prática/conceito)

## Aulas

* Acompanhamento do andamento do projeto (3 grupos por aula)
* Seminários (presença obrigatória)

## Critérios para Escolha do Sistema

* Escopo (~12 semanas)
* Interesse da equipe no sistema
* Afinidade entre os membros da equipe
* Capacidade técnica da equipe
* Disponibilidade de uma plataforma para colocar o sistema em produção
* Capacidade de atrair usuários reais
* Observação: não pode ser um sistema que já está em andamento.

## Primeira Tarefa

* Primeira tarefa: abrir uma [issue](https://github.com/aserg-ufmg/CursoPraticaDesenvolvimentoSoftware/issues) neste mesmo repositório da seguinte forma:
  * Título da issue: nome do sistema e breve descrição (exemplo: ABC: Um sistema para XYZ)
  * Corpo da issue: nome dos membros da equipe; breve descrição das principais funcionalidades do sistema; breve descrição da tecnologia a ser usada (linguagem, frameworks e bancos de dados) e link para o repositório GitHub onde o projeto será desenvolvido.
  * Prazo: 09/03 (2a feira)
  * Aula de 2a feira: 09/03 - cada grupo deve explicar seu sistema em 8 minutos
  
## Sprint #1 (20 pontos)

* Sprint planning (prazo: 13/03 - Valor 2 pontos)
  * Escrever de 5-10 estórias
  * Quebrar as estórias em tarefas; alocar as tarefas para membros do time.
  * Documentar estórias, tarefas e responsáveis no README do projeto, em uma uma seção chamada Sprint Planning.
  * Criar um diagrama de pacotes UML do sistema, descrevendo sua arquitetura em alto nível. Mais detalhes sobre diagramas de       pacotes no Capítulo 4, Seção 4.4 do livro texto. Adicionar esse diagrama no README do repositório, em uma seção chamada       Arquitetura
* Sprint Review
  * Datas: 23 e 26/03 (em sala de aula)

### Práticas de Implementação

* Testes de unidade
* Desenvolvimento baseado no Trunk e feature flags
* Seguir um layout de código. Veja um exemplo para [Java](https://google.github.io/styleguide/javaguide.html).

### Orientações para as Sprint Reviews (Sprints #1, #2 e #3)

* Em sala de aula, 30 minutos (a definir), incluindo uma demonstração funcional do sistema.
odos membros do grupo devem estar presentes; mas, para otimizar, a apresentação pode ser realizada por 1-2 membros. Quem não puder estar presente, favor justificar por mail.
* Chegar com tudo preparado para a apresentação, incluindo laptop, dados de teste, roteiro do que será apresentado etc. Não conte que o WiFi da sala estará funcionando.
* Caso alguém não tenha um laptop para demonstração, favor entrar em contato com o professor.
