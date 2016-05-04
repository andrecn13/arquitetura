# Arquitetura Microservi�os Odontoweb

Este projeto foi construido para armazenar as configura��es da arquitetura para os microservi�os do projeto odontoweb. Todos os microservi�os precisam possuir esta biblioteca no classpath.

### Oque est� send configurado neste projeto?

	* Authorization Filter
	* Generic Dependencies
	* Multi-tenancy

### Instala��o

Para compilar o projeto rode o seguinte comando:


`gradle clean build`

Para publicar o projeto como uma biblioteca no reposit�rio local do maven rode o seguinte comando:

`gradle publishToMavenLocal`
