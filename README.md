📅 Sistema de Agenda de Consultas
API Java para estudo de Spring Boot

🚀 Instalação

🔹 Passo 1: Criar o Build do Projeto

Antes de rodar a aplicação, é recomendável limpar e criar a pasta /target:

mvn clean package

🔹 Passo 2: Configuração do Swagger

O Swagger é utilizado para documentar a API. Para mais informações, consulte:🔗 SpringDoc - Configuração de Propriedades

🔹 Passo 3: Configuração do Banco de Dados (H2)

Edite o arquivo application.properties para definir os parâmetros de conexão:

springdoc.swagger-ui.path=/
springdoc.swagger-ui.disable-swagger-default-url=true

spring.datasource.url=jdbc:h2:mem:pacientesdb
spring.datasource.driverClassName=org.h2.Driver
spring.datasource.username=sa
spring.datasource.password=

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true

🌍 Navegação

▶️ Executar a API

Para iniciar o servidor Spring Boot, execute o seguinte comando:

mvn spring-boot:run

📑 Documentação da API (Swagger)

Acesse a interface interativa do Swagger clicando no link abaixo:🔗 Swagger UI - API Documentation

📚 Referências

🔗 SpringDoc - Documentação Oficial

