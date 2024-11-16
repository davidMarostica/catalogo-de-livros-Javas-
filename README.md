# LiterAlura

LiterAlura é um projeto Spring Boot que conecta você ao vasto mundo da literatura através da API do Project Gutenberg. Descubra, explore e salve seus livros e autores favoritos para criar sua própria biblioteca digital personalizada.

## Recursos Principais

- **Busca de Livros**: Encontre livros por título e explore detalhes como autores, gênero e data de publicação.
- **Salvar Livros e Autores**: Salve seus achados literários para fácil acesso e referência futura.
- **Listar Livros e Autores**: Navegue por sua biblioteca digital organizada.
- **Busca de Autores**: Encontre autores por nome e visualize os livros que eles escreveram.
- **Autores Vivos em Determinado Ano**: Descubra quais autores da sua biblioteca estavam vivos em um ano específico.

## Como Usar

### Configure o PostgreSQL

1. Instale o PostgreSQL em seu sistema.
2. Crie um banco de dados para o LiterAlura.
3. Atualize as configurações de conexão no arquivo `application.properties`:

```properties
spring.datasource.url=jdbc:postgresql://127.0.0.1:5432/db
spring.datasource.username=postgres
spring.datasource.password=postgres
