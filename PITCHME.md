## Oficina Pentaho
___
### Mergulhando no BI com Software Livre

---
### Quem sou eu 
<div class="left">
---?image=assets/img/alexssandroos_1505174890_893.jpg&position=left&size=35% 65%
</div>
<div class="right">
<p><b>Entusiasta resolvedor de problemas! :) </b></p>
<p>Formado em Analise de Sistemas, MBA em BI, Especialização em Data Science em andamento.</p> 
<p>Casado, pai da Esther, Nerd por natureza, apaixonado por ficção cientifica, tecnologia... enfim mais coisas do que tenho horas no dia pra fazer.</p>
</div>

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
### CTOOLS | Dashboards 

![Painel CTOOLS](https://3.bp.blogspot.com/-TzWIshmKCIs/VRlnJv1y61I/AAAAAAAAAig/SbDofijnyuQ/s1600/ctoo.jpg&size=80% 80%) 

--- 
### Configurando o ambiente


--- 
### Instalando o Pentaho

---
### Onde Encontrar Ajuda

Lista Pentaho Brasil Yahoo(2.063 Membros)
https://br.groups.yahoo.com/neo/groups/pentahobr/info

Telegram 
https://t.me/pentaho

Forum Oficial
https://forums.pentaho.com/


---
### Referências

https://help.pentaho.com/Documentation/7.1/Installation

https://alexssandroos.github.io/blog/install-jdk-jre-oracle
