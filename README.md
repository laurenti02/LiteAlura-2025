# LiteAlura-2025
📚 Desafio Literalura 2025
Java Bota de mola PostgreSQL Licença

🔹 Descrição
Literalura Challenge 2025 é um aplicativo Java com Spring Boot que permite:

Consulte livros da API Gutendex .
Registrar livros e autores em PostgreSQL usando Spring Data JPA.
Realize pesquisas interativas de livros e autores a partir do console.
Listar livros por idioma e buscar autores por ano de nascimento.
O projeto foi desenvolvido como parte do projeto LiterAlura 2025.

🛠 Requisitos
Java JDK 17 ou superior
Maven 4 o superior
Spring Boot 3.5.4
PostgreSQL 16 ou superior
IDE recomendado: IntelliJ IDEA ou Visual Studio Code
⚙️ Configuração
Crie a base de dados PostgreSQL :
CREATE DATABASE literalura;
Configurar variáveis de ambiente :
DB_HOST=localhost
DB_USER=tu_usuario
DB_PASSWORD=tu_contraseña
Verificarapplication.properties :
spring.datasource.url=jdbc:postgresql://${DB_HOST}/literalura
spring.datasource.username=${DB_USER}
spring.datasource.password=${DB_PASSWORD}
spring.jpa.hibernate.ddl-auto=update
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.PostgreSQLDialect
🚀 Como executar
Execute a classe principal do seu IDE ou terminal

Interaja com o menu no console:

Buscar livro por título
Listar livros registrados
Ver autores
Pesquisar autor por ano
Listar livros por idioma
🎯 Funcionalidades principais
Procurar por título.
Registro de livros e autores na base de dados.
Listado de livros por idioma.
Pesquisa de autores por ano de nascimento.
Menú seguro que maneja entradas inválidas e evita travamentos.
👨‍💻 Autor
LAURENTI – Projeto desenvolvido para o desafio LiterAlura Challenge 2025. 🔗 GitHub

📄 Licença
Este projeto está abaixo da licença MIT :

MIT License

Copyright (c) 2025 LAURENTI

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRIN
