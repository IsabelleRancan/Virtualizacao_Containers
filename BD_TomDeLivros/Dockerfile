# Usando a imagem oficial do PostgreSQL
FROM postgres:latest

# Copiar o dump SQL para o diretório de inicialização do PostgreSQL
COPY ./Tom_De_Livros.sql /docker-entrypoint-initdb.d/

# Expor a porta 5432 para acessar o banco de dados
EXPOSE 5432
