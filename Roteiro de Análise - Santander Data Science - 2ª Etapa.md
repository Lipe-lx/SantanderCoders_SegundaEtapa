# :notebook: Roteiro de Análise: 

## Metodologia de Base para Ciência de Dados

#### Definido por: Jhon Rollins - Data Scientist, IBM Analytics, (Fonte: IBM)

![image-20210721100740504](C:\Users\myhouse\AppData\Roaming\Typora\typora-user-images\image-20210721100740504.png)

## :bulb: Entendimento do Negócio: 

#### Santander Data Science - 2ª Etapa:

Case: **Quantas pastas dentais são vendidas por mês no Brasil?**

Abordagem **“top-down”**, onde primeiro define-se o problema de negócios e, em seguida, os dados são analisados para encontrar uma solução.

## :question: 10 Perguntas a serem respondidas:

#### Do Problema á abordagem:

##### 01 - Qual é o problema que você está tentando resolver?

Quantas pastas dentais são vendidas por mês no Brasil.

##### 02 - Como você pode usar dados para responder á pergunta? (definir a abordagem)

Através de um modelo estatístico.

#### Trabalhando com os Dados: Organização dos dados necessários

##### 03 - De quais dados você precisa para responder a pergunta?

Consumo de pasta dental no Brasil;

Peso médio dos tubos de pasta de dente com a quantidade média por utilização.

Balanço de fabricação/vendas de pasta dental;

População Brasileira divida por classe social e índices de saneamento;

População com acesso a água;

Índice de Escolaridade e Educação .

##### 04 - De onde vêm os dados (identifique todas as fontes) e como você os obterá?

Instituto Brasileiro de Geografia e Estatística (IBGE). Pesquisa Nacional de Saúde:

| [4960](https://sidra.ibge.gov.br/tabela/4960) | [Domicílios com água canalizada em pelo menos um cômodo, por situação do domicílio](https://sidra.ibge.gov.br/tabela/4960) |
| --------------------------------------------- | ------------------------------------------------------------ |
| [7556](https://sidra.ibge.gov.br/tabela/7556) | [Domicílios com existência de banheiro de uso exclusivo e esgotamento sanitário por rede geral de esgoto ou fossa sépitica ligada à rede geral, por situação do domicílio](https://sidra.ibge.gov.br/tabela/7556) |
| [4950](https://sidra.ibge.gov.br/tabela/4950) | [Pessoas que tinham algum plano de saúde (médico ou odontológico), por nível de instrução e situação do domicílio](https://sidra.ibge.gov.br/tabela/4950) |
| [4953](https://sidra.ibge.gov.br/tabela/4953) | [Pessoas que tinham algum plano de saúde (médico ou odontológico), por rendimento mensal domiciliar per capita e situação do domicílio](https://sidra.ibge.gov.br/tabela/4953) |

Instituto Brasileiro de Geografia e Estatística (IBGE). Mapa de pobreza e desigualdade:

| [228](https://sidra.ibge.gov.br/tabela/228) | [Famílias residentes em domicílios particulares por situação do domicílio e número de componentes das famílias](https://sidra.ibge.gov.br/tabela/228) |
| ------------------------------------------- | ------------------------------------------------------------ |
| [156](https://sidra.ibge.gov.br/tabela/156) | [Domicílios particulares ocupados, moradores em domicílios particulares ocupados e média de moradores em domicílios particulares ocupados](https://sidra.ibge.gov.br/tabela/156) |
| [146](https://sidra.ibge.gov.br/tabela/146) | [Pessoas de 10 anos ou mais de idade por grupos de anos de estudo](https://sidra.ibge.gov.br/tabela/146) |

###### Artigos Científicos:

Faculdade de Odontologia da UFMG: http://revodonto.bvsalud.org/scielo.php?script=sci_arttext&pid=S1516-09392014000200005&lng=pt&nrm=iso&tlng=pt  - Acessado em 21/07/21 - 13:26

![image-20210721194207033](C:\Users\myhouse\AppData\Roaming\Typora\typora-user-images\image-20210721194207033.png)

Universidade Federal do Rio Grande do Sul: https://www.scielo.br/j/csp/a/b5wxN8JjNrKMVV9pr4v9GFh/?lang=pt# - Acessado em 21/07/21 - 14:26

![image-20210721194043940](C:\Users\myhouse\AppData\Roaming\Typora\typora-user-images\image-20210721194043940.png)

Universidade Federal da Paraíba - Parâmetros morfológicos de escovas dentais comercializadas em João Pessoa-PB: http://revodonto.bvsalud.org/scielo.php?pid=S1806-146X2010000400001&script=sci_arttext  Acessado em 21/07/21 - 22:26
![](C:\Users\myhouse\AppData\Roaming\Typora\typora-user-images\image-20210721222906188.png)

Ficha Técnica Creme Dental: https://biancooralcare.com.br/wp-content/uploads/2020/01/CD-Protefresh-FT-BIANCO.pdf - Acessado em 21/07/21 - 23:32

##### 05 - Os dados que você coletou são representativos do problema a ser resolvido?

Sim

##### 06 - Que trabalho adicional é necessário para manipular e trabalhar com os dados?

Limpeza de dados não desejados

Estruturação dos dados

Visualização dos dados via gráficos

#### Derivando a Resposta: Validando os dados e a abordagem projetada

##### 07 - De que forma os dados podem ser visualizados para se chegar à resposta necessária?

Através de um modelo estatístico.

##### 08 - O modelo usado realmente responde à pergunta inicial ou precisa ser ajustado?

Responde a pergunta inicial

##### 09 - Você pode colocar o modelo em prática?

Sim

##### 10 - Você pode obter um feedback construtivo para a resposta à pergunta?

Sim

## :notebook: Abordagem Analítica: 

### :pencil: Identificar os tipos de padrões que serão necessários para resolver a questão de modo mais eficaz: Abordagens de Associação de Grupos: Aprender sobre comportamento humano

#### Para determinar probabilidades:

 Modelo Preditivo

#### Para determinar relações:

Modelo Descritivo

#### Problemas que requerem contagem:

Modelo Estatístico

#### Problemas booleanos (true/false) ou (sim/não):

Modelo de Classificação

## :notebook:Requerimentos de dados

 A abordagem analítica escolhida determina os requisitos de dados. Especificamente, os métodos analíticos a serem usados requerem determinados  conteúdos, formatos e representações de dados, orientados pelo conhecimento de domínio.

## :notebook:Coleta de Dados

04 - De onde vêm os dados (identifique todas as fontes) e como você os obterá?

## :notebook:Entendimento dos dados

03 - De quais dados você precisa para responder a pergunta?

## :notebook:Preparação de Dados

06 - Que trabalho adicional é necessário para manipular e trabalhar com os dados?

## :notebook:Modelagem

08 - O modelo usado realmente responde à pergunta inicial ou precisa ser ajustado?

## :notebook:Avaliação

07 - De que forma os dados podem ser visualizados para se chegar à resposta necessária?

## :notebook:Implementação

09 - Você pode colocar o modelo em prática?

## :notebook:Feedback

10 - Você pode obter um feedback construtivo para a resposta à pergunta?