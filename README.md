# Projeto Java - Demonstração de Recuperação de Dados pelo JDBC

Este é um projeto Java que demonstra a funcionalidade de recuperação de dados usando o JDBC (Java Database Connectivity). O JDBC é uma API Java que permite que os desenvolvedores interajam com bancos de dados relacionais.

Neste projeto, a aplicação se conecta a um banco de dados, executa uma consulta SQL para recuperar os dados de uma tabela chamada "department" e exibe os resultados no console.

## Pré-requisitos

Antes de executar este projeto, certifique-se de ter o seguinte instalado em sua máquina:

- Java Development Kit (JDK) versão 8 ou superior.
- Um banco de dados relacional (por exemplo, MySQL, Oracle, PostgreSQL) com a tabela "department" criada e dados inseridos.

## Configuração do Banco de Dados

Certifique-se de ter um banco de dados configurado com a tabela "department" e dados inseridos antes de executar o projeto. 

## Configuração do Projeto

1. Clone este repositório para sua máquina local:

   ```bash
   git clone https://github.com/Marcus-Vinicius-Oliveira/jdbc-recuperar-dados.git
   ```

2. Abra o projeto em sua IDE Java preferida.

3. Certifique-se de ter o driver JDBC necessário para o seu banco de dados incluído no classpath do projeto. Você pode baixar o driver do site do banco de dados correspondente ou usar uma ferramenta de gerenciamento de dependências, como o Maven ou Gradle, para importar a dependência do driver.

4. Abra o arquivo `src/application/Program.java` e verifique se as informações de conexão com o banco de dados estão corretas. Certifique-se de ajustar a URL do banco de dados, nome de usuário e senha, se necessário.

   ```java
   conn = DB.getConnection();
   ```

## Executando o Projeto

Após configurar o banco de dados e o projeto, você pode executar a aplicação de demonstração de recuperação de dados usando o JDBC.

1. Compile e execute o arquivo `Program.java` a partir de sua IDE ou utilize o seguinte comando no terminal:

   ```bash
   javac src/application/Program.java
   java -cp src application.Program
   ```

2. A aplicação irá se conectar ao banco de dados, executar a consulta SQL definida no código e exibir os resultados no console.

## Contribuição

Sinta-se à vontade para contribuir com melhorias para este projeto. Se você encontrar algum problema ou tiver alguma sugestão, abra uma nova issue neste repositório.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).
