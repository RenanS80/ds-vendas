<h1 align="center">DS Vendas</h1>

## 📃 Sobre
Aplicação: <br>
<a href="https://ds-vendas-renan.netlify.app/" target="_new">
    https://ds-vendas-renan.netlify.app/
</a> <br>

DS Deliver é uma aplicação full stack desenvolvida durante a 4ª edição da Semana Spring-React <a href="https://devsuperior.com.br/">DevSuperior</a> – evento ministrado pelo professor Nélio Alves. <br>
Este projeto exibe um dashboard de vendas a partir de dados fornecidos por um back-end construído com Spring Boot. <br>
Durante o desenvolvimento foi criada uma API com os seguintes endpoints:
<ul>
    <li><strong>/sellers:</strong> retorna todos os vendedores cadastrados.</li>
    <li><strong>/sales?page=0&size=10&sort=date,desc:</strong> Retorno pageado, contendo informações de todas as vendas realizadas, ordenadas por data, de forma decrescente.</li>
    <li><strong>/sales/amount-by-seller:</strong> retorna o nome de cada vendedor e o valor total de suas respectivas vendas.</li>
    <li><strong>/sales/success-by-seller:</strong> retorna o nome de cada vendedor, quantidade de visitas e total de vendas efetivadas.</li>
</ul>

---

## 💻 Frameworks, bibliotecas e ferramentas  
O projeto foi desenvolvido com as seguintes tecnologias: <br>

<h3>Ferramentas</h3>
<ul>
    <li>Spring Tool Suit</li>
    <li>VS Code</li>
    <li>Postman</li>
</ul>


<h3>Back-end</h3>
<ul>
    <li>Spring Boot com Maven (Java)</li>
    <li>JPA e ORM</li>
</ul>

<h3>Front-end</h3>
<ul>
    <li>React + Router DOM</li>
    <li>Typescript</li>
    <li>Date-fns (Formatação de datas)
    <li>Axios</li>
    <li>Bootstrap</li>
    <li>Apex Charts (Gráficos)</li>
</ul>

<h3>Implantação</h3>
<ul>
    <li>Back-end: Heroku</li>
    <li>Banco de dados: PostgreSQL</li>
    <li>Front-end: Netlify</li>
</ul>

---

## 🎬 Interface
<strong>Home</strong>
<img src="https://ik.imagekit.io/zqxyh6u3ylz/DS_Vendas/1_c7MaEFHlM.jpg?updatedAt=1631486549830">

<strong>Dashboard</strong>
<img src="https://ik.imagekit.io/zqxyh6u3ylz/DS_Vendas/2_e5c_ZkLRcBL.jpg?updatedAt=1631486549888">

---

## 📁 Como baixar o repositório
```bash
# Clonar o repositório
git clone https://github.com/RenanS80/ds-vendas

# Acessar a pasta ds-vendas
cd ds-vendas
```
---

## ✅ Como executar a aplicação
<h2>Back-end</h2>
<small>Pré-requisito: Java 11</small>

```bash
# Entrar na pasta backend do projeto clonado
cd backend

#Executar o projeto
mvn spring-boot:run
```

<h2>Front-end</h2>
<small>Pré-requisito: Yarn</small>

```bash
# Entrar na pasta frontend do projeto clonado
cd frontend

# Instalar as dependências
yarn install

# Executar a aplicação
yarn start

# Acessar http://localhost:3000 no seu navegador.
```
