## HP Vertica
___
### Banco de Dados Analítico para DW
---
### O Que é Vertica
Enquanto um banco de dados relacional é otimizado para armazenar linhas de dados, geralmente para aplicativos transacionais, um banco de dados colunar é otimizado para recuperação rápida de colunas de dados, normalmente em aplicativos analíticos. O armazenamento orientado a colunas para tabelas do banco de dados é um fator importante para a performance de consulta analítica, pois ele reduz expressivamente os requisitos gerais de E/S de disco e diminui a quantidade de dados que você precisa carregar do disco.

by: [Aws - What is a Columnar Database?](https://aws.amazon.com/nosql/columnar/?nc1=h_ls)

---
### Requisitos
- Red Hat 5,6/ Suse 11
- Oracle Linux 6
- Debian 6 /Ubuntu 12
- CentOS 5 e 6

---
### Manutenção  
Usuário padrão : dbadmin

---
### Otimize Tabelas e Não Consultas
 - Projeções
 - Seguimentações
 - Partições
 
 @fa[arrow-down]
+++
### Exemplo CREATE
```sql
create table schema.tab1
(
id int not null,
campo varchar(2) 
),
create projection schema.tab1_p 
(
id ENCODING RLE,
campo
)
as 
select *
from schema.tab1
order by 1 
UNSEGMENTED ALL NODES
```

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

[Requirements Hp Vertica ](https://my.vertica.com/docs/7.0.x/HTML/index.htm#Authoring/InstallationGuide/PlatformRequirementsAndRecommendations.htm%3FTocPath%3DInstallation%2520Guide%7CBefore%2520You%2520Install%2520Vertica%7CPlatform%2520Requirements%2520and%2520Recommendations%7C_____0)


