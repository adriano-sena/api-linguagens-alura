<h1 algin="center"> Api Linguagens </h1>

![Api Linguagens logo ](https://user-images.githubusercontent.com/58452965/181083266-564d97b9-436a-4330-a3f4-07d78d7f6ac8.png)

![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge)

## Índice 

* [Índice](#índice)
* [Descrição do Projeto](#descrição-do-projeto)
* [Funcionalidades e Demonstração da Aplicação](#funcionalidades-e-demonstração-da-aplicação)
* [📁 Acesso ao Projeto](#acesso-ao-projeto)
* [Tarefas em aberto](#tarefas-em-aberto)
* [✔️ Tecnologias utilizadas](#tecnologias-utilizadas)
* [Pessoas Desenvolvedoras do Projeto](#pessoas-desenvolvedoras)

# Descrição do projeto

Api desenvolvida durante a imersão Java Alura. O objetivo desta api é a criação de um ranking de linguagens de programação, contendo o ícone da linguagem, titulo e posição no ranking. 
Ela foi desenvolvida em Java, utilizando o Framework SpringBOOT, Cluster do MongoDB para armazenar os dados da API. Atualmente está hospedada no Heroku e pode ser consumida 
Utilizando os endpoints descritos neste documento. 

 ## :hammer: Funcionalidades e Demonstração da aplicação

:heavy_check_mark: Cadastrar uma nova linguagem no ranking
:heavy_check_mark: Atualizar uma linguagem no ranking ( TODO )
:heavy_check_mark: Exibir o ranking em ordem crescente e Decrescente
:heavy_check_mark: Deletar uma linguagem do ranking

![Get Linguagens API](https://user-images.githubusercontent.com/58452965/181091113-07cf2018-8a6d-4b71-8ec4-abd7565184d6.gif)

No exemplo acima foi utilizada a ferramenta Postman para o envio de uma requisição GET da à url https://linguagens-api-nano.herokuapp.com/linguagens que retorna o ranking das linguagens
armazenadas em nosso cluster MongoDB 

## 📁 Acesso ao projeto

Aqui você pode acessar o Código fonte do projeto ou baixá-lo para realizar testes ou modificações, Fique à vontade :) 
https://github.com/adriano-sena/api-linguagens-alura


## 🛠️ Abrir e rodar o projeto

Caso queira rodar o projeto Localmente Basta realizar os seguintes passos:

Clone o projeto (Digite os seguintes comandos)

```
git clone https://github.com/adriano-sena/api-linguagens-alura.git
```

Com o Maven devidamente configurado digite o seguinte comando em seu terminal(na raiz do projeto):

```
mvnw package
```

Acesse os endpoints pelo navegador ou Postman. 

Caso queira somente consumir a api hospedada no Heroku basta utilizar o endpoint abaixo para receber o ranking das linguagens:

https://linguagens-api-nano.herokuapp.com/linguagens

## Tarefas em aberto

:memo: Criar endpoint para atualizar uma linguagem  

:memo: Criar endpoint para exibir ranking em ordem decrescente  

:memo: Criar endoint para deletar uma linguagem do ranking 

## ✔️ Tecnologias utilizadas

- ``Java 18``
- ``Visual Studio Code``
- ``Paradigma de orientação a objetos``
- `MongoDB`
- `Maven`
- `Spring BOOT`

## Pessoas Desenvolvedoras

| [<img src="https://avatars.githubusercontent.com/u/58452965?s=400&u=0444a558c2aab9ced65b4d23ff1307ce12a19b8b&v=4" width=115><br><sub>Adriano Sena</sub>](https://github.com/adriano-sena) |
| :---: | 




