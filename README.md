# DS Vendas 
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/PToledoCESJF/projeto_sds4/blob/master/LICENSE) 


# O projeto
DS Vendas trata-se de uma aplicação que exibe um dashboard com 2 gráfico e uma tabela paginada apresentando a taxa de sucesso e as vendas realizadas por cada vendedor.
Trata-se de uma aplicação com front-end desenvolvido em ReactJs, hospedado na plataforma Netlify e que utiliza dados 
fornecidos por uma API hospedada no Heroku com back-end desenvolvida em Java com Spring Boot.
Esta aplicação full stack (back-end e front-end) foi desenvolvida durante a 4ª edição da **Semana DevSuperior** (#sds4), evento organizado pela [DevSuperior](https://devsuperior.com "Site da DevSuperior").
## Layout da aplicação
### Welcome
Ao acessar o sistema, a primeira tela a ser exibida faz uma breve apresentação o da aplicação.
O botão Dashboard direciona para a página principal da aplicação.
##
![Welcome](https://github.com/PToledoCESJF/projeto_sds4/blob/master/assets/welcome.png)
##
### Dashboard
A tela Dashboard exibe 2 gráficos e uma tabela paginada que mostar o resultado das vendas realizadas por cada vendedor.
##
![Dashboard](https://github.com/PToledoCESJF/projeto_sds4/blob/master/assets/Dashboard.png)
##
### Taxa de sucesso
O primeiro gráfico exibe a taxa de sucesso nas visitas realizadas por cada vendedor.
![TaxaSucesso](https://github.com/PToledoCESJF/projeto_sds4/blob/master/assets/chart1.png)
##
### Todas as vendas
O segundo gráfico mosta o percentual de vendas realizadas pelos vendedores.
![TaxaSucesso](https://github.com/PToledoCESJF/projeto_sds4/blob/master/assets/chart2.png)
## Tecnologias utilizadas
### Back-end 
***Pré-requisitos: Java 11***
- Java
- Spring Boot
- JPA / Hibernate
- Maven
- Banco de dados: Postgresql
##
### Front-end
***Pré-requisitos: NodeJs 13+ / npm e/ou yarn***
- HTML / CSS / JS / TypeScript
- ReactJS
- Apex Charts
##
## Implantação em produção
- Back-end: Heroku
- Front-end web: Netlify
## 
## Para obter este projeto:
- Abra um terminal e execute:
```bash
git clone https://github.com/PToledoCESJF/projeto_sds4
```
##
### Back-end
- Entre na pasta do projeto back end
```bash
cd backend
```
- Execute o projeto
```java
mvnw spring-boot:run
```
##
### Front end web
- Entre na pasta do projeto front end web
```bash
cd frontend
```
- Instale as dependências
```bash
yarn install
```
**ou**
```bash
npm install
```

- Executar o projeto
```bash
yarn start
```
É possível ver a aplicação no ar acessando:
https://dsvendas-ptoledo.netlify.app
##
## Autor
***
Paulo Donizete Alves de Toledo
##### CONTATO:
- (32)99838-9166
- ptoledo.bsices@gmail.com
- paulodat.902522195@uniacademia.edu.br
- https://www.linkedin.com/in/paulo-toledo-0488b1174/
***

