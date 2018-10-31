# Desafio cadastro de funcionários da empresa

## Oportunidade

Olá! Temos uma oportunidade para testador pleno na Novio e gostaríamos que você participasse do nosso processo seletivo. Ao fim do processo, você receberá um feedback do nosso time com o resultado do processo 😃.

## Detalhamento do desafio

O desafio será focado em criar testes de aceitação e de integração para o sistema ManterFuncionarios. Os testes de aceitação deverão ser automatizados e integrados ao build do projeto. Propositalmente o projeto tem erros que devem ser cobertos nos testes demonstrando quais cenários apresentam as falhas.

## Pré-requisitos para executar o projeto e logar no sistema

 - JDK 8+;
 - Maven 3.3+;
 - Dependências já estão declaradas no pom.xml (Driver H2, Spring Boot, Swagger)

O banco de dados é o h2, portanto não será necessário baixar e configurar um banco (Verificar o application.yml para mais detalhes).
Para iniciar o projeto basta executar ‘mvn spring-boot:run’ na raiz. A API está disponível através do ‘localhost:8080’.

## Serviços e funcionalidades a serem testadas

 - Manter usuário (Campos: nome, login e senha);
 - Manter funcionário (Campos: nome completo, matrícula, ocupação e setor);

## Regras específicas:

 - Todas as deleções são lógicas gerenciados por uma flag no código.
 - A senha será armazenada como um Hash;

## Tecnologias para os testes:

 - Java 8+;
 - Maven 3.3+;
 - Junit 5 e Rest assured (ou outros frameworks para automação);

## Instruções

1. Após o envio do desafio você terá 3 dias para desenvolver. Seja criativo! Utilize as ferramentas e frameworks ao seu favor.
2. Atualize o README.MD do projeto e detalhe as etapas para que os testes sejam executados.
3. Após finalizado envie o projeto zipado para o e-mail dangellys@novio.com.br.
