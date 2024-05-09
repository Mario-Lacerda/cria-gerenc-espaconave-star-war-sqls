# Desafio Dio - Gerenciador de Espaçonaves Star Wars com SQL Server e C#**



Neste desafio, você será desafiado a criar um gerenciador de espaçonaves do Star Wars modelando um banco de dados em SQL Server. Sua missão será entregar os scripts de criação das tabelas, assim como um programa em C# (.NET) que permita a interação com o banco de dados, utilizando o Entity Framework.

objetivo fornecer um guia passo a passo sobre como criar um gerenciador de espaçonaves Star Wars usando SQL Server e C#. O guia cobre todos os aspectos do processo, desde a criação do banco de dados até a implementação do programa em C#.

## **Etapas**

Para concluir este desafio, você deverá seguir as seguintes etapas:

1. Criar o banco de dados no SQL Server.
2. Criar as tabelas necessárias no banco de dados.
3. Implementar o programa em C# (.NET) que permita a interação com o banco de dados.
4. Testar o programa.

## **Pré-requisitos**

Para concluir este guia, você precisará dos seguintes pré-requisitos:

- Uma conta do Microsoft Azure
- O Microsoft SQL Server instalado
- O Visual Studio instalado
- Uma aplicação C#



**Documentação do projeto "Gerenciador de Espaçonaves Star Wars com SQL Server e C#"**

**Estruturando o Projeto**

O projeto é estruturado em três camadas:

- A camada de apresentação é responsável por lidar com a interação do usuário. Ela é responsável por exibir a interface do usuário e lidar com as requisições do usuário.

- A camada de negócio é responsável por lidar com a lógica de negócio do aplicativo. Ela é responsável por validar as requisições do usuário e executar as operações necessárias.

- A camada de dados é responsável por lidar com o armazenamento e recuperação de dados. Ela é responsável por acessar o banco de dados e recuperar os dados necessários para atender às requisições do usuário.

  

  **Estrutura do guia**

  O guia está dividido nas seguintes seções:

  1. **Introdução ao SQL Server**

  2. **Criando um banco de dados no SQL Server**

  3. **Criando um modelo de dados no Entity Framework**

  4. **Implementando o programa em C#**

  5. **Testando o programa**

  6. **Conclusão**

     

  ## Documentando o Projeto

O projeto é documentado usando comentários XML. Os comentários XML são usados para documentar as classes, métodos e propriedades do projeto. Os comentários XML são usados para gerar a documentação do projeto.

## **Definindo Modelos**

Os modelos são usados para representar os dados do aplicativo. Os modelos são definidos usando o Entity Framework. O Entity Framework é um ORM (Object-Relational Mapping) que facilita o mapeamento de objetos para tabelas de banco de dados.

### **Definindo Serviços**

Os serviços são usados para implementar a lógica de negócio do aplicativo. Os serviços são definidos usando interfaces. As interfaces são usadas para definir os contratos dos serviços.

### **Definindo Lógica de Negócios**

A lógica de negócio do aplicativo é implementada nas classes de serviço. As classes de serviço são responsáveis por validar as requisições do usuário e executar as operações necessárias.

### **Integrando as Camadas**

As camadas do aplicativo são integradas usando injeção de dependência. A injeção de dependência é um padrão de design que permite que as classes dependam umas das outras sem criar referências diretas.

## **Testando o Projeto**

O projeto é testado usando testes unitários e de integração. Os testes unitários são usados para testar as classes individuais do projeto. Os testes de integração são usados para testar a integração das diferentes camadas do projeto.



## **Apêndice**

O apêndice contém informações adicionais sobre os seguintes tópicos:

- Recursos do SQL Server
- Comandos do SQL
- Sintaxe C#
- Ferramentas de teste



### **Desenvolvimento**

Para criar o banco de dados, você pode utilizar o SQL Server Management Studio. Depois de criar o banco de dados, você deverá criar as tabelas necessárias. Para isso, você pode utilizar o seguinte script SQL:

```plaintext
CREATE TABLE Spaceship
(
  ID INT IDENTITY NOT NULL,
  Name NVARCHAR(MAX) NOT NULL,
  Class NVARCHAR(MAX) NOT NULL,
  Manufacturer NVARCHAR(MAX) NOT NULL,
  Hyperdrive NVARCHAR(MAX) NOT NULL,
  Crew NVARCHAR(MAX) NOT NULL,
  Passengers NVARCHAR(MAX) NOT NULL,
  Cargo NVARCHAR(MAX) NOT NULL,
  Shields NVARCHAR(MAX) NOT NULL,
  Weapons NVARCHAR(MAX) NOT NULL
);
```



Depois de criar as tabelas, você deverá implementar o programa em C# (.NET) que permita a interação com o banco de dados. Para isso, você pode utilizar o Entity Framework. O Entity Framework é um framework que permite a criação de objetos .NET que representam objetos no banco de dados. Para utilizar o Entity Framework, você deverá criar um modelo de dados que represente as tabelas no banco de dados. Depois, você poderá criar um controlador que permita a interação com o banco de dados.

## **Teste**

Depois de implementar o programa, você deverá testá-lo. Você pode testar o programa utilizando o Visual Studio ou outro ambiente de desenvolvimento integrado.

## **Conclusão**

Este desafio foi uma introdução à criação de um gerenciador de espaçonaves do Star Wars com SQL Server e C#. Você pode aprender mais sobre o assunto consultando a documentação do SQL Server e do Entity Framework.Neste desafio o expert cria um gerenciador de espaço naves do Star Wars modelando um banco de dados em SQL Server. 

Sua missão será entregar os scripts de criação das tabelas que compõem a estrutura desse banco de dados. 

Fornece um guia passo a passo abrangente sobre como criar um gerenciador de espaçonaves Star Wars usando SQL Server e C#. Ao seguir as etapas descritas neste guia, você poderá criar um gerenciador de banco de dados funcional e confiável.
