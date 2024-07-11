Este é um projeto de API Spring Boot para catalogar livros, permitindo que você pesquise livros, liste-os por vários critérios e gerencie autores e suas informações.
Funcionalidades

    Pesquisar e adicionar livros de uma API externa.
    Listar todos os livros.
    Listar todos os autores.
    Listar todos os autores vivos em um ano específico.
    Listar todos os livros em um idioma específico.
    Pesquisar autores por nome.

Pré-requisitos

    Java JDK 17 instalado na máquina.
    IDE Java (recomendado: IntelliJ IDEA, Eclipse, NetBeans).
    Banco de dados PostgreSQL.
    Dependências: Spring Boot, Spring Data JPA, driver PostgreSQL, Jackson Databind.

Configuração

    Configure seu arquivo application.properties com as seguintes configurações:

    spring.application.name=LiterAlura-Challenge
    spring.datasource.url=jdbc:postgresql://${postgresDBHost}/${DBNAME1}
    spring.datasource.username=${postgresUSER}
    spring.datasource.password=${postgresPASSWORD}
    spring.datasource.driver-class-name=org.postgresql.Driver
    hibernate.dialect=org.hibernate.dialect.HSQLDialect
    spring.jpa.hibernate.ddl-auto=update
    #spring.jpa.show-sql=true
    #spring.jpa.format-sql=true

Como Usar

    Clone ou faça o download deste repositório para sua máquina local.
    Abra o projeto em sua IDE Java.
    Configure seu banco de dados PostgreSQL e atualize o arquivo application.properties com suas credenciais do banco de dados.
    Execute a aplicação usando sua IDE ou gere um arquivo JAR com dependências e execute-o usando o comando:


    java -jar liter-alura-challenge.jar

    Use o menu fornecido para interagir com a aplicação:


                    1 - Pesquisar livro na API e adicionar ao banco de dados;
                    2 - Listar todos os livros;
                    3 - Listar todos os autores;
                    4 - Listar todos os autores vivos em um ano específico;
                    5 - Listar todos os livros em um idioma específico;
                    6 - Listar autor por nome;
                    9 - Sair.

            

Consumo de API

A API externa usada para obter informações dos livros é a Gutendex API.

Este README.md fornece instruções sobre como usar a aplicação LiterAlura-Challenge Spring Boot API, incluindo pré-requisitos, funcionalidades e etapas de uso.
