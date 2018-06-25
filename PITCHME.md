## HP Vertica
___
### Banco de Dados Analítico para DW
---
### O Que é Vertica
Enquanto um banco de dados relacional é otimizado para armazenar linhas de dados, geralmente para aplicativos transacionais, um banco de dados colunar é otimizado para recuperação rápida de colunas de dados, normalmente em aplicativos analíticos. O armazenamento orientado a colunas para tabelas do banco de dados é um fator importante para a performance de consulta analítica, pois ele reduz expressivamente os requisitos gerais de E/S de disco e diminui a quantidade de dados que você precisa carregar do disco.

by: [Aws - What is a Columnar Database?](https://aws.amazon.com/nosql/columnar/?nc1=h_ls)


---?image=https://upstatebusinessjournal.com/wp-content/uploads/2018/03/business-intelligence-696x464.jpg&opacity=60
### Business Intelligence

De maneira bem resumida pode-se afirmar que o Business Intelligence consiste na coleta dos dados presentes nas diversas fontes disponíveis, organização, análise , conversão em conhecimento e compartilhamento provendo suporte as decisões importantes para a organização.

---
### Pentaho 

Pentaho é uma suite de BI que oferece soluções para as etapas de um projeto de BI/Big Data provendo suporte a fase de ETL, Analises Olap, Relatorios, Datamining e Dashboards.  Entre os softwares da suite estão :

- Pentaho Data-Integration(ETL)
- Pentaho Schema Workbench(Criacao cubos)
- Pentaho Report Designer(Relatorios)
- Pentaho BI Server(Plataforma web)
- Weka (Mineração de dados)
- Ctools(Criação de Dashboards)
- Hadoop Shims
- App Builder
- Dentre outros.

---
### Conhecendo nosso projeto
@div[left-50]
<br>
![BI](https://pragmaticworks.com/portals/1/Consulting/Consulting-Laptop-Icons-Business-Intelligence.png)
@divend
@div[right-50]
@ul[brighten]
- Criar fluxo de ETL e popular um DataMart
- Modelar o cubo OLAP 
- Instalar e criar analises no Servidor de BI
- Criar um relatorio e publica-lo no servidor
- Criar um Dashboard de vendas
@ulend
@divend

---
### Primeiros passos
- Instalar a JDK 1.8 e configurar as variaveis de ambiente.
- Baixar os executaveis no [Source Forge](sourceforge.net/projects/pentaho)
- Baixar jar's dos SGBD's

---
### Pentaho Data Integration

Extracao transformacao e carga 

@fa[arrow-down]

+++
### To-do List

@ul[brighten]
- Criar nossa dimensao Temporal
- Extrair e limpar os dados da sample.
- Carregar dimensoes para o SGBD
@ulend

---
### Pentaho Schema Workbench

Criando e modelando cubos para OLAP

@fa[arrow-down]

+++
### To-do List

@ul[brighten]
- Definindo extrutura Analitica (Star schema)
- Modelando cubo de vendas
- Publicando no BI Server
@ulend

---
### Pentaho Business Analytics Server

Onde a magica acontece ;)

@fa[arrow-down]

+++
### To-do List

@ul[brighten]
- Visualizando o Cubo publicado
- Melhorando as analises com plugins da communidade.
- Dando um tapa no visual.
@ulend

---
### CTOOLS

Criando Dashboards de maneira altamentes customizavel.

@fa[arrow-down]

+++
### To-do List

@ul[brighten]
- Conhecendo o CDE
- Criando um grafico de barras 
- Adicionando filtros ao Painel
@ulend

---
### Pentaho Report Designer

Relatorios analiticos no servidor.

@fa[arrow-down]

+++
### To-do List

@ul[brighten]
- Escolhendo um tema
- Carregando os dados 
- Adicionando filtros ao relatorio
@ulend

---
### Onde Encontrar Ajuda

Lista Pentaho Brasil Yahoo(2.063 Membros)
https://br.groups.yahoo.com/neo/groups/pentahobr/info

Telegram 
https://t.me/pentaho

Forum Oficial
https://forums.pentaho.com/

---
### Contato
@fa[envelope-square] - alexssandroos@yahoo.com.br
<br>
@fa[linkedin] | @fa[github] | @fa[twitter-square] /alexssandroos

---
### Muito Obrigado :)

---
### Referências

[HP Vertica Doc 7.1](http://my.vertica.com/docs/Ecosystem/Amazon/HP_Vertica_7.1.x_Vertica_AWS.pdf)


