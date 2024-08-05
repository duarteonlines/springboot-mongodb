# Rede Social Simplificada

Bem-vindo ao projeto de Rede Social Simplificada! Este é um projeto que simula uma rede social básica onde usuários podem criar posts e cada post pode ter vários comentários. O projeto é construído com Java, Spring Framework e MongoDB.

## Estrutura do Projeto

O projeto é estruturado de acordo com uma arquitetura em camadas, o que facilita a manutenção e a escalabilidade do código. A estrutura básica é a seguinte:

- **Modelo (Model):** Contém as entidades do sistema, como `Usuário`, `Post` e `Comentário`.
- **Repositório (Repository):** Interfaces que definem os métodos para acessar e manipular os dados no banco de dados.
- **Serviço (Service):** Contém a lógica de negócios da aplicação.
- **Controlador (Controller):** Gerencia as requisições HTTP e interage com os serviços para fornecer respostas adequadas.

## Tecnologias Utilizadas

- **Java:** Linguagem de programação principal.
- **Spring Framework:** Para criar e gerenciar a aplicação.
- **MongoDB:** Banco de dados NoSQL utilizado para armazenar dados.
- **Spring Data MongoDB:** Integra o MongoDB com o Spring Framework.

## Requisitos

Antes de rodar o projeto, certifique-se de ter os seguintes softwares instalados:

- Java 11 ou superior
- Maven (para gerenciamento de dependências)
- MongoDB
- IDE (como IntelliJ IDEA ou Eclipse)

## Configuração do Projeto

1. **Clone o repositório:**

   ```bash
   git clone https://github.com/oliveiraordep/springboot-mongodb.git
   ```

   ```
   cd springboot-mongodb
   ```

2. **Configurando Base de Dados:**
   
   Configure o MongoDB:

   Certifique-se de que o MongoDB está em execução. Por padrão, o MongoDB estará ouvindo na porta 27017.

2.1 **Configure as propriedades do MongoDB**

   Edite o arquivo src/main/resources/application.properties e ajuste a URL de conexão do MongoDB se necessário.


## Buildando e rodando o projeto

```bash
mvn clean install
```

```bash
mvn spring-boot:run
```
