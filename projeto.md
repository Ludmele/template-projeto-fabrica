<img src='/img/logo.png' alt='logo da empresa' width='50px' heidth='50px'/>

# *FIBONACCI MANAGEMENT SYSTEM*

# PROJETO DE SOFTWARE

## *Stakeholders*
|NOME|CARGO|E-MAIL|
|:---|:---|:---|
|Ana Clara Bertando Gonçalves|Programador|anaclarabertando@gmail.com|
|Anthony Pohlmann Rodrigues|Líder de planejamento|pohlmann.anthony@gmail.com|
|Ingrid Victória de Souza Silva|Programador|ingrid.aluna2024@gmail.com|
|Kamyly Lopes Gouveia|Programador|kamylylopes141@gmail.com|
|Ludmele Figueiredo da Silva|Programador|ludmelefigueiredo@gmail.com|
|Pamela Alves|Programador|alves.pamela@estudante.ifro.edu.br|


# Sumário

* [RESUMO DO PROJETO](#resumo-do-projeto)
* [INTRODUÇÃO](#introdução)
  * [PROPÓSITO DESTE DOCUMENTO](#propósito-deste-documento)
* [DESCRIÇÃO GERAL](Em nosso site, -----, será apresentado instruções passo a passo de receitas de diversas culturas, para que, os usuários possam explorar novas experiências culinárias e interagir em uma comunidade ativa — compartilhamento das ideias)
  * [USUÁRIOS DO SISTEMA](#usuários-do-sistema)
  * [ABRANGÊNCIA E SISTEMAS SIMILARES](#abrangência-e-sistemas-similares)
  * [SUPOSIÇÕES E DEPENDÊNCIAS](#suposições-e-dependências)
* [METODOLOGIA ADOTADA NO DESENVOLVIMENTO](#metodologia-adotada-no-desenvolvimento)
* [REQUISITOS DO SOFTWARE](#requisitos-do-software)
  * [REQUISITOS FUNCIONAIS](#requisitos-funcionais)
  * [REQUISITOS NÃO FUNCIONAIS](#requisitos-não-funcionais)
* [PROTOTIPAGEM](#prototipagem)
* [DIAGRAMA DE CLASSES](#diagrama-de-classes)
* [REFERÊNCIAS](#referências)


# RESUMO DO PROJETO
| ITEM | Um site de receitas interativo e prático. Os usuários poderão compartilhar receitas de diversas culturas, dicas, criar e entrar em comunidades específicas e participar de fóruns de discussão.|
|:---|:---|
| NOME DO PROJETO |Sabores&Culturas|
| GERENTE DO PROJETO |Ludmele Figuereido da Silva|
| PRINCIPAL OBJETIVO |Desenvolver uma solução para buscas de receitas (torná-las rápidas e práticas)|
| BENEFÍCIOS ESPERADOS |* Ter várias variedades de receitas;<br/>* Facilidade para encontrar as receitas em um único site;<br/>* Incentivar a interação das pessoas na comunidade;<br/>* Praticidade e acessibilidade;<br/>* Criar uma comunidade colaborativa e participativa|
| INÍCIO E TÉRMINO PREVISTOS | 14/03/2025 - 07/12/2025 |

[ [INÍCIO](Sabores&Culturas) ]

# INTRODUÇÃO

## PROPÓSITO DESTE DOCUMENTO

Este documento destina-se aos clientes, engenheiros, gerentes e demais stakeholders deste projeto. O propósito deste documento é apresentar a descrição dos serviços e funções que o sistema **_Fibonacci Management System_** deve prover, bem como as suas restrições de operação e propriedades gerais, a fim de ilustrar uma descrição detalhada do sistema para um auxílio durante as etapas de análise, projeto e testes. O documento especifica todos os requisitos funcionais e não funcionais do sistema e contém a prototipagem, além de diagramas UML que foram construídos levando-se em conta as funcionalidades identificadas durante a fase de concepção do sistema.

[ [INÍCIO](#fibonacci-management-system) ]

# DESCRIÇÃO GERAL

## Usuários do sistema
|USUÁRIO|DESCRIÇÃO|
|:---|:---|
|**Usuário Padrão:**|Realizam as tarefas comuns a todos os usuários, tal como: logar e enviar mensagens. Todos demais usuários estendem as funcionalidades do UsuárioPadrão|
|**Administrador:**|Responsáveis pelo gerenciamento das entidades pertinentes à instituição e pela alocação de outros administradores|
|**Coordenador:**|Responsáveis pela aprovação de disciplinas, turmas e matrículas realizadas pela secretaria do curso, além de ser responsável pela alocação da secretaria|
|**Secretaria:**|Responsáveis pelo cadastramento de disciplinas e turmas, pela alocação de professores e monitores de um curso e matrículas dos alunos|
|**Professor:**|Responsáveis pela criação do programa da disciplina através de ferramentas de planejamento e criação de atividades|
|**Aluno:**|Seguem o programa da disciplina criada pelo professor, tendo como apoio ferramentas de comunicação, tal como: chat e fórum|


[ [INÍCIO](#fibonacci-management-system) ]

# Metodologia Adotada no Desenvolvimento

[ [INÍCIO](#fibonacci-management-system) ]

# Requisitos do Software

A especificação dos requisitos deste documento deve seguir as recomendações da norma IEEE Std-830-1998, levando em conta as recomentações do documento de [características dos requisitos](caracteristicas_requisitos.md).

## Requisitos Funcionais

A tabela a seguir contém a relação dos Requisitos Funcionais elicitados, com as colunas: identificador, nome, descrição e prioridade:

| IDENTIFICADOR | NOME | DESCRIÇÃO |
|:---|:---|:---|

|RNF-001 |Segurança| S999erá um site seguro. Garante a segurança dos dados dos usuários, não os disponibilizando para terceiros.|
|RNF-002 |Portabilidade| Permite que o site seja acessado em diversas plataformas, exemplo: mobile, pc, etc.|
|RNF-003 |Desempenho| O site será leve, PROVAVELMENTE não terá travamentos|
|RNF-004 |Acessibilidade| Tornará o site acessivel ao grupo de pessoas portadoras de deficiência auditiva e visual|
|RNF-005 |navagabilidade| O site não será muito complexo, então será relativamente fácil de navegar|



## Requisitos Não Funcionais
A tabela a seguir contém a relação com os Requisitos Não Funcionais identificados, contendo identificador, nome, descrição e prioridade:

| IDENTIFICADOR | NOME | DESCRIÇÃO |
|:---|:---|:---|
|RNF-001 |Segurança| Será um site seguro. Garante a segurança dos dados dos usuários, não os disponibilizando para terceiros.|
|RNF-002 |Portabilidade| Permite que o site seja acessado em diversas plataformas, exemplo: mobile, pc, etc.|
|RNF-003 |Desempenho| O site será leve, PROVAVELMENTE não terá travamentos|
|RNF-004 |Acessibilidade| Tornará o site acessivel ao grupo de pessoas portadoras de deficiência auditiva e visual|
|RNF-005 |navagabilidade| O site não será muito complexo, então será relativamente fácil de navegar|

[ [INÍCIO](#fibonacci-management-system) ]


# Prototipagem

[Protótipo criado no FIGMA em 2025 por estudantes](https://www.figma.com/file/iNC7wyX9zP7Kmn3BhiCFGf/Fals6Hood-(Prot%C3%B3tipo-criado-por-estudantes-em-2022)?node-id=0%3A1&t=B16hgeZP3MSURCCa-1)

![Imagem do Protótipo](/img/home.png)

[ [INÍCIO](#fibonacci-management-system) ]


# Diagrama de Classes

![Diagrama de Classes](/img/CDModelo.png)

[ [INÍCIO](#fibonacci-management-system) ]


# REFERÊNCIAS

Esta subseção apresenta as referências aos documentos que utilizamos no auxílio à construção deste documento.
* [UML](https://www.omg.org/spec/UML/2.5/About-UML/)
* [Práticas para Especificação de Requisitos IEEE-830](https://ieeexplore.ieee.org/document/720574)
