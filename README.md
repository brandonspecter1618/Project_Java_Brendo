# Project_Java_Brendo

Aqui algumas informações para poder executar o projeto.

***Tomcat 9.0

Estou usando o Tomcat 9.0, e utilizando o Apache NetBeans IDE 15 para iniciar 
o servidor a partir dentro do próprio IDE.

***Conversão entre HTML para JSP

Com relação ao projeto, criei o mesmo em cima do Maven, e feito a migração do meu index.html para index.jsp.

*** DB + Servlet

Criei um arquivo com os dados de conexão para o banco somente com um Connection simples. E em seguida
criei meu Servlet, fiz a importação do método de conexão para dentro do mesmo e criei três If's
separados, sendo que estes foram responsáveis por controlarem quais serão os tipos de códigos 
a serem executados pelo banco de dados. 

***Tomcat + Index.jsp

Das opções na page web, temos as opção: "nome", "email", "age"


/*Selecionar todos os dados do DB*/

Para selecionar todos os dados do DB, é só clicar no botão "Clique Aqui", sem preencher nada nos campos 
"ID", "nome", "email", "age"



/*Inserir dados no DB*/

Para Inserir dados no banco de dados podemos usar os três campos "nome", "email", "age", já que o DB

tem as colunas correspondentes à esses nomes e ainda o ID com auto_increment. 



/* Deletar dados no DB*/

Já na opção Delete temos a opção de selecionar o campo "ID" e digitar o número de ID
que deseja excluir. 

