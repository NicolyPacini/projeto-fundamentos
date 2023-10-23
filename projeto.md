<img src='/img/logo.png' alt='logo da empresa' width='150px' heidth='150px'/>

# *Euforia Make-up*

# PROJETO DE SOFTWARE

## *Stakeholders*
|NOME|CARGO|E-MAIL|
|:---|:---|:---|
|Nicoly Pacini| Gerente de Projeto|efraimdossantos@icloud.com|
|Uédina Clarice|Gerente de Projeto| uedinaclaricebarros@gmail.com|
|Ana Carolina Leopoldo|Gerente de Projeto|ac4686993@gmail.com|
|Vitória Gonçalves da Silva|Gerente do projeto|Vit0r4a33@gmail.com|

# Sumário

* [RESUMO DO PROJETO](#resumo-do-projeto)
* [INTRODUÇÃO](#introdução)
  * [PROPÓSITO DESTE DOCUMENTO](#propósito-deste-documento)
  * [ESCOPO DO PROJETO](#escopo-do-projeto)
  * [CONCEPÇÃO DO SISTEMA](#concepção-do-sistema)
  * [CONVENÇÕES, TERMOS E ABRIVEAÇÕES](#convenções-termos-e-abreviações)
* [DESCRIÇÃO GERAL](#descrição-geral)
  * [USUÁRIOS DO SISTEMA](#usuários-do-sistema)
  * [ABRANGÊNCIA E SISTEMAS SIMILARES](#abrangência-e-sistemas-similares)
  * [SUPOSIÇÕES E DEPENDÊNCIAS](#suposições-e-dependências)
* [ESTUDO DE VIABILIDADE](#estudo-de-viabilidade)
  * [VIABILIDADE TÉCNICA](#viabilidade-técnica)
  * [VIABILIDADE ECONÔMICA](#viabilidade-econômica)
  * [VIABILIDADE ORGANIZACIONAL](#viabilidade-organizacional)
* [METODOLOGIA ADOTADA NO DESENVOLVIMENTO](#metodologia-adotada-no-desenvolvimento)
* [REQUISITOS DO SOFTWARE](#requisitos-do-software)
  * [REQUISITOS FUNCIONAIS](#requisitos-funcionais)
  * [REQUISITOS NÃO FUNCIONAIS](#requisitos-não-funcionais)
* [PROTOTIPAGEM](#prototipagem)
* [DIAGRAMA DE CASOS DE USO](#diagrama-de-casos-de-uso)
  * [ESPECIFICAÇÃO DOS CASOS DE USO](#descrição--especificação-dos-casos-de-uso)
* [DIAGRAMA DE CLASSES](#diagrama-de-classes)
* [DIAGRAMA DE SEQUÊNCIAS](#diagrama-de-sequências)
* [ DIAGRAMA DE ATIVIDADES](#diagrama-de-atividades)
* [REFERÊNCIAS](#referências)


# RESUMO DO PROJETO
| ITEM | DESCRIÇÃO|
|:---|:---|
| NOME DO PROJETO | Euforia Make-up |
| GERENTE DO PROJETO | Nicoly |
| PRINCIPAL OBJETIVO |  Objetivo do nosso projeto e ajudar você para elevar sua auto-estima com nossos produtos. A empresa make-up é voltada para vendas de maquiagens|
| BENEFÍCIOS ESPERADOS |* Vendas de maquiagens ;<br/>* ajudar o cliente a ter uma relação melhor com o seu rosto;<br/>* Ter mais criações no mercado de trabalho;<br/>* servir de inspiração pra pequenas empresas;<br/>* Ter um preço acessível|
| INÍCIO E TÉRMINO PREVISTOS | 14/03/2023 - 07/12/2023 |

[ [INÍCIO](#fibonacci-management-system) ]

# INTRODUÇÃO

## PROPÓSITO DESTE DOCUMENTO

Este documento destina-se aos clientes, engenheiros, gerentes e demais stakeholders deste projeto. O propósito deste documento é apresentar a descrição dos serviços e funções que o sistema **_Euforia Make-up_** deve prover, bem como as suas restrições de operação e propriedades gerais, a fim de ilustrar uma descrição detalhada do sistema para um auxílio durante as etapas de análise, projeto e testes. O documento especifica todos os requisitos funcionais e não funcionais do sistema e contém a prototipagem, além de diagramas UML que foram construídos levando-se em conta as funcionalidades identificadas durante a fase de concepção do sistema.

## CONCEPÇÃO DO SISTEMA

Foram usados três métodos para que pudessem ser obtidos os requisitos do sistema:
* Entrevista:
  * Entrevista: Discussões com todas as integrantes do grupo, para decidirmos as melhores ideias e maneiras de obter o melhor resultado, para nós (integrantes) e para os nossos usuários.
* Consulta com especialista:
  * Wagner da Silva, professor responsável, graduação sistema de informação.
* Prototipação:
  * Representações das ideias de maquiagem que estará em venda, design da nossa loja, aprovada pelas integrantes do grupo.



## CONVENÇÕES, TERMOS E ABREVIAÇÕES

Para evitar interpretações incorretas deste documento, algumas convenções e termos específicos são descritos a seguir:

* Make-up: Se maquiar; 
*	Euforia: estado caracterizado por alegria, despreocupação, otimismo e bem-estar.


[ [INÍCIO](#fibonacci-management-system) ]

# DESCRIÇÃO GERAL

## ESCOPO DO PROJETO

### NO ESCOPO

O  sistema  Euforia Make-up e voltado diretamente para vendas de maquiagens,dicas, e indicações de produtos voltados a cada tipo de pele, e também auxilia os maquiadores iniciantes ou para quem vai se maquiar pela primeira vez e não sabe que produto utilizar.

### FORA DO ESCOPO

Não fazem parte do escopo do projeto:
* Configurações no aplicativo direto do aparelho do cliente;
* Interferência em quaisquer informações adquiridas do ambiente tecnológico do cliente.


## Usuários do sistema
|USUÁRIO|DESCRIÇÃO|
|:---|:---|
|**Usuário Padrão:**|Realizam as tarefas comuns a todos os usuários, tal como: logar e enviar mensagens. Todos demais usuários estendem as funcionalidades do UsuárioPadrão. |
|**Administrador:**|Responsáveis pelo gerenciamento das entidades pertinentes à loja. |
|**Atendente:**|Responsáveis pelos clientes da loja, auxiliando ao máximo. |
|**Assitente:**|Responsáveis pelo cadastramento e organização dos produtos. |
|**Secretaria:**|Responsáveis pela aprovação e alocação de produtos na loja. |
|**Desing:**|Responsáveis pelo visual do site oficial da loja. |
|**Gerente:**|Responsáveis por manter o controle e organização da loja. |

## Abrangência e sistemas similares

### Abrangência:

 O sistema irá conter ferramentas para construção de uma loja de maquiagens, com produtos de otíma qualidade. As donas da loja através do site oficial, vão disponibilizar os produtos que serão comprados/consumidos pelos clientes. As Donas terão a liberdade de colocar os produtos que quiserem e as dicas de maquiagem que acharem pertinentes para seu púlblico alvo. Serão disponibilidados os produtos escolhidos para a venda, assim que os clientes comprarem será gerado estatisticamente o valor total ganho nas vendas. O sistema também irá prover o gerenciamento das entidades que compõem a loja.

Dentre as ferramentas utilizadas pela loja, a principal será o site oficial "Euforia Make-up", onde serão realizadas as vendas.

Das ferramentas de planejamento podemos citar:

* **Produtos Disponíveis:** Serão disponibilizados produtos para serem vendidos na loja;

* **Anúncios:** Espaço para anunciar promoções de produtos;

* **Organização das vendas:** haverá um diretório onde terá todas as informações sobre as vendas realizadas;

* **Planejamento de Maquiagens:** Planejamento das maquiagens que poderão ser de grande ajuda para os cliente.

### Sistemas similares:

No cenário atual da universidade se encontra um sistema que é responsável por realizar tal tarefa, denominado Virtus, porém o sistema não atende todas as necessidades, não sendo considerado satisfatório pela maioria dos usuários.

No cenário nacional encontram-se três sistemas que se destacam:

**AulaNet:** é um ambiente de software baseado na Web, desenvolvido no Laboratório de Engenharia de Software - LES - do Departamento de Informática da PUC-Rio, para administração, criação, manutenção e participação em cursos à distância.
WebAula: é um produto formado por soluções integradas de gerenciamento de aprendizagem, conhecimento e conteúdos on-line, resultado de uma joint venture entre as empresas Zargon e Poliedro.

**TelEduc:** é um ambiente para a criação, participação e administração de cursos na Web. Ele foi concebido tendo como alvo o processo de formação de professores para informática educativa, baseado na metodologia de formação contextualizada desenvolvida por pesquisadores do Nied (Núcleo de Informática Aplicada à Educação) da Unicamp.

No cenário internacional os sistemas de maior porte são:

**WebCT:** O WebCT é um programa que possibilita a criação de ambientes educacionais na Internet, desenvolvido pela University of British Columbia - Canadá. Ele permite a colocação do conteúdo de um curso na Internet pelo professor e, em seguida, o cadastro os alunos que participarão daquele curso. O objetivo principal é possibilitar a interação entre tais sujeitos através de ferramentas de trabalho em grupo, tais como: fóruns de discussão, chat, palestras on-line, além de facilitar a comunicação professor-aluno, através da publicação de notas e gabaritos de avaliações.

**Blackboard:** é um sistema de autoria extremamente amigável, desenvolvido para ser utilizado por educadores e profissionais interessados em aplicar as novas tecnologias interativas da rede na educação, contribuindo para a metodologia de ensino presencial e potencializando o processo de ensino e aprendizagem a distância.

## Suposições e dependências
O sistema necessita de um servidor web para sua hospedagem.

Os usuários devem utilizar um computador com a seguinte configuração mínima:

* Processador Dual Core 2GHz ou superior
* 2Gb de memória RAM
* 5Gb de armazenamento em disco
* Para uso do sistema é preciso ter instalado o Java SE versão 8 e o MySql versão 8.0.28.

# ESTUDO DE VIABILIDADE

Uma vez definidos a necessidade para o sistema e seus requisitos de negócio, é possível compreender melhor o projeto do sistema proposto para elaborar o estudo de viabilidade com os seguintes destaques:

## Viabilidade Técnica
Sim, a nossa empressa tem em mente a noção da nossa capacidade, tendo ciência que podemos desenvolver sistemas de maneira eficaz e eficiente usando: Mobincube um sistema móvel desenvolvido pela Microsoft, que nos permite criar aplicativos tanto para Android quanto para iOS e até mesmo Windows Phone, trabalhamos com base em sitemas especializados e sistemas de informação com uma taxa de sucesso relevante, além de possuir empregados capacitados com técnicas avançadas para administrar o projeto com sucesso para realização do seu atendimento.

## Viabilidade Econômica
 Sim, este projeto é viavel. Chegamos a esta conclusão, após elaboramos uma reunião para discutir sobre os custos e beneficios do nosso projeto, e também sobre as marcas de maquiagens mais benéficas para todos. Buscando a melhor forma de investir visando obter um bom lucro, tendo um valor de custos menor que o valor de retorno. 
 Após a inauguração, espera-se oferecer um ótimo serviço, com um site bem desenvolvido e moderno, maquigens de qualidade e com alta durabilidade e aprimorar a funcionabilidade do sistema da loja "Euforia Make-up".
 Com um grande avanço economico esperamos expandir nossa empresa, voltando especificamente a sustentabilidade e com a diminuição dos valores dos nossos produtos visando mantermos a qualidade alcançando um publico maior, tendo assim mais lucro.

## Viabilidade Organizacional
Sim, de acordo com nossos dados acreditamos que o nosso aplicativo oferece uma boa qualidade em todos os fatores e da forma mais compreensível possível para o bem estar dos clientes, uma empresa que reflete os seus clientes se mantem focada e sustentável de maneira segura e que possibilite todos de ter uma experiencia interressante seja ela em qualqueer tipo de ambiente possível seja na compra de um produto ou na entrega dele, pensando nisso decidimos aumentar o numero de entregadores para que o tempo de espera seja menor, além de também conseguir acessar lugares isolados e de classe social mais baixa.

[ [INÍCIO](#fibonacci-management-system) ]

# Metodologia Adotada no Desenvolvimento
O Processo Unificado da Rational conhecido como RUP (Rational Unified Process), é um processo de engenharia de software criado para apoiar o desenvolvimento orientado a objetos, fornecendo uma forma sistemática para se obter vantagens no uso da UML. Foi criado pela Rational Software Corporation e adquirido em fevereiro de 2003 pela IBM.
O principal objetivo do RUP é atender as necessidades dos usuários garantindo uma produção de software de alta qualidade que cumpra um cronograma e um orçamento previsíveis.
Escolhemos o RUP pois ele é conhecido pelo seu foco e qualidade de software ajudando até mesmo com futuros riscos para a empresa.



[ [INÍCIO](#fibonacci-management-system) ]

# Requisitos do Software

A especificação dos requisitos deste documento deve seguir as recomendações da norma IEEE Std-830-1998, levando em conta as recomentações do documento de [características dos requisitos](caracteristicas_requisitos.md).

## Requisitos Funcionais

A tabela a seguir contém a relação dos Requisitos Funcionais elicitados, com as colunas: identificador, nome, descrição e prioridade:

| IDENTIFICADOR | NOME | DESCRIÇÃO |
:---|:---|:---|
|RF-001 | Realizar Cadastro de Clientes | O sistema deve possibilitar que os clientes da Euforia Make-upsejam cadastrados, sendo os seguintes campus obrigatórios: nome; sexo; data de nascimento; telefone; e-mail; cpf/cnpj; estado civil; endereço.|
|RF-002 | Realizar as vendas de produtos| O sistema deve possibilitar as vendas dos produtos comercializados. |
|RF-003 | Quantidade de produtos vendidos| O sistema deve possibilitar a quantidades de produtos vendididos para os clientes. |
|RF-004 | Emitir relatório de produtos vendidos | O sistema deve possibilitar a emissão de relátorio de vendas personalizadas. |
|RF-005 | Calcular o valor do pedido | O sistema deve calcular automaticamente o valor do pedido, possibilitando o cliente saber o exato valor da sua compra. |
|RF-006 | Proporcionar dicas de maquiagens | O sistema deve possibilitar dicas de maquiagens para o cliente que tem dificuldade na hora de comprar, possibilitando saber os produtos ideais para cada tipo de pele. |
|RF-007 | Selecionar uma forma de pagamento | O sistema permite que o cliente selecione o modo de pagamento de sua preferencia de acordo com as opções do sistema   |
|RF-008 | Selecionar tipo de produto | Permite ao cliente selecionar qualquer produto dentro do catalogo |
|RF-009 | Calcular o preço final | O sistema realiza internamente a soma de todos os produtos escolhidos pelo cliente |
|RF-010 | Proporcionar cupons de desconto | Assim que disponivel o sistema da ao cliente um cupom |
|RF-011 | Cnacelamento de produtos| O sistema propõe também o cancelamento do pruduto  |
|RF-012 | Categorizar os produtos | O sistema categoriza automaticamente o produto conforme seus dados |
|RF-013 | Notificar a chegada de novos produtos | Assim que possivel o sistema notifica ao cliente em segundo plano a chegada de um novo produto ou qualquer novidade |
|RF-014 | Notificar promoções | Assim como o requisisto acima o sistema notifica em segundo plano as promoções |
|RF-015 | Finalizar a venda | Apos a confirmação da compra o sistema finaliza a compra emitindo assim o comprovante |
|RF-016 | Emitir um comprovante | Apos a compra o sistema emite um comprovante ao cliente para evitar futuros problemas, tanto para o nosso sistema quanto para o usuario |
|RF-017 | Emitir valor do frete | Apos a realização da compra o sistema emite o valor do frete |
|RF-018 | Avisar sobre o prazo de entrega | O sistema calcula o percurso do produto e avisa sobre o prazo e também o percurso do produto antes de chegar ao cliente |
|RF-019 | Selecionar os produtos para o carrinho | O sistema permite que o cliente selecione qualquer produto de sua escolha até o carinho ilimitadas vezes |
|RF-020 | Avaliação do cliente | O sistema possibilita que o usuario avalie nossos produtos e aplicativos|
|RF-021 | feedback | Possibilita que o cliente consiga entrar em contato com os nossos servidores para alguma duvida ou opnião |

## Requisitos Não Funcionais
A tabela a seguir contém a relação com os Requisitos Não Funcionais identificados, contendo identificador, nome, descrição e prioridade:

| IDENTIFICADOR | NOME | DESCRIÇÃO |
|:---|:---|:---|
|RNF-001 | Privacidade dos dados do usuario | A aplicação deve ser segura para o uso protegendo todos os dados do usuário e evitando violações de privacidade.|
|RNF-002 | Suporte  | O sistema deve ter capacidade de suportar varios usuarios e transações sem diminuir seu desempenho. |
|RNF-003 | Personalização | O sistema deve ser personalizavel de acordo acom as preferencias do cliente como foto do usuario e etc. |
|RNF-004 | Acessibilidade | A aplicação deve ser acessivel a todos os usuários. |
|RNF-005 | Manutenção | O sistema deve ser fácil de se manter e atuializar para que posso ser compatível em vários dispositivos. |
|RNF-006 | Organização | O sistema deve ter uma otíma organização, para que tudo ocorra bem e sem problemas. |
|RNF-007 | Facilidade | A insterface do sistema deve ser de fácil entendimento para vários usuários de diferentes idades e dificuldades. |
|RNF-008 | Legal | Tudo relacionado ao sistema deve ser legal, conforme a lei. |
|RNF-009 | Portabilidade  | O sistema deve ter facilidade em ser tranferido de um sistema computacional para outro. |
|RNF-010 | Eficiência | O sistema deve garantir ter eficiência em todos os quesitos necessários. |


[ [INÍCIO](#fibonacci-management-system) ]


# Prototipagem

[Protótipo criado no FIGMA em 2022 por estudantes](https://www.figma.com/file/iNC7wyX9zP7Kmn3BhiCFGf/Fals6Hood-(Prot%C3%B3tipo-criado-por-estudantes-em-2022)?node-id=0%3A1&t=B16hgeZP3MSURCCa-1)

![Imagem do Protótipo](/img/home.png)

[ [INÍCIO](#fibonacci-management-system) ]


# Diagrama de Casos de Uso


![Diagrama de Casos de Uso](/img/Caso_de_Uso_Euforia.png)

## Descrição / Especificação dos Casos de Uso

### UC-01 - Cadastrar Professor

|UC-01 - Cadastrar Professor|           
|:---|
|**Descrição/Objetivo:** Permite a inclusão de novos professores no Sistema|
|**Atores: Administrador**|
|**Pré-condições:** O usuário precisa estar cadastrado e logado|
|**Pós-condições:** Será apresentada uma mensagem confirmando a realização do cadastro|
|**FLUXO PRINCIPAL / BÁSICO:**|
|1. O usuário seleciona a opção cadastrar professor|
|2. Os dados do professor são inseridos|
|3. O usuário clica em salvar|
|4. Um novo ID é gerado |
|5. É apresentada uma mensagem confirmando a realização do cadastro|
|**FLUXOS ALTERNATIVOS / EXCESSÕES:** |
|**A1: Campo obrigatório não preenchido** |
|1. Uma mensagem será apresentada para o usuário, informando que existe(m) campos obrigatórios que não foram preenchidos |
|2. O cursor será posicionado no primeiro campo obrigatório que não foi preenchido |
|**A2: Data de nascimento inválida** |
|1. Uma mensagem será apresentada para o usuário, informando que a data informáda não é válida|
|2. O cursor será posicionado para o campo data|


## Matriz de Rastreabilidade


| REQUISITO |Criar Conta|Realizar Compra|Cancela Compra|Realizar Pagamento|Adicionar item ao carrinho|Notificações e avisos|Realizar fadback|Visualizar Carrinho de Compra|Escolher Forma de Pagamento|Exclui item do Carrinho|     
|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|
|RF-001|X| | | | | | | | | | 
|RF-002| |X| | | | | | | | | 
|RF-003| | | | |X| | | | |X| 
|RF-004| | | |X| | | | | | | 
|RF-005| | | | | | | |X| | | 
|RF-006| | | | | |X| | | | | 
|RF-007| | | | | | | | |X| | 
|RF-008| | | | |X| | | | | | 
|RF-009| | | | | | | |X| | | 
|RF-010| | | | | |X| | | | |
|RF-011| | |X| | | | | | | | 
|RF-012| | | | | |X| | | | | 
|RF-013| | | | | |X| | | | | 
|RF-014| | | | | |X| | | | | 
|RF-015| |X| |X| | | | | | | 
|RF-016| | | |X| | | | | | | 
|RF-017| | | | | |X| | | | | 
|RF-018| | | | | |X| | | | | 
|RF-019| | | | |X| | | | | | 
|RF-020| | | | | | |X| | | | 



[ [INÍCIO](#fibonacci-management-system) ]

# Diagrama de Classes

![Diagrama de Classes](/img/trabalho.png)

[ [INÍCIO](#fibonacci-management-system) ]

# Diagrama de Sequências

![Diagrama de Classes](/img/diagramaCadastro.png)
[ [INÍCIO](#fibonacci-management-system) ]



# Diagrama de Atividades


# REFERÊNCIAS

Esta subseção apresenta as referências aos documentos que utilizamos no auxílio à construção deste documento.
* [UML](https://www.omg.org/spec/UML/2.5/About-UML/)
* [Práticas para Especificação de Requisitos IEEE-830](https://ieeexplore.ieee.org/document/720574)
