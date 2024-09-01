# Iniciando com ASP.NET Web API

Este projeto tem como objetivo fornecer uma introdu��o pr�tica ao desenvolvimento de APIs RESTful utilizando 
o **ASP.NET Core Web API**. Nele, voc� aprender� a criar uma API do zero, configurar rotas, manipular dados, 
e implementar as melhores pr�ticas para construir aplica��es web robustas e escal�veis.

## �ndice

- [Pr�-requisitos](#pr�-requisitos)
- [Instala��o](#instala��o)
- [Primeiros Passos](#primeiros-passos)
- [Construindo a API](#construindo-a-api)
- [Testando a API](#testando-a-api)

<br>

![Execu��o1](imgs/mostra1.png)

<br>

## Pr�-requisitos

Antes de come�ar, certifique-se de ter o seguinte instalado em sua m�quina:

- [Visual Studio Community](https://visualstudio.microsoft.com/pt-br/vs/community/) (ou uma IDE compat�vel)
- [.NET SDK](https://dotnet.microsoft.com/download)
- Conhecimento b�sico de C# e conceitos de API REST

## Instala��o

Siga os passos abaixo para configurar e executar o projeto localmente:

1. Clone o reposit�rio para a sua m�quina local:

    ```bash
    git clone https://github.com/seu-usuario/seu-repositorio.git
    ```

2. Navegue at� o diret�rio do projeto:

    ```bash
    cd DemoWebAPI
    ```

3. Abra o projeto no Visual Studio Community.

4. Restaure as depend�ncias e compile o projeto:

    ```bash
    dotnet restore
    dotnet build
    ```

5. Execute o projeto:

    ```bash
    dotnet run
    ```

## Primeiros Passos
Este projeto foi projetado para ser simples de entender, mas poderoso o suficiente para demonstrar
os principais conceitos do ASP.NET Web API. Voc� come�ar� criando modelos e controladores b�sicos, e 
depois adicionar� camadas de servi�o e reposit�rio para uma melhor organiza��o do c�digo.

## Construindo a API
A constru��o da API envolve as seguintes etapas:

1. Criando Modelos: Definindo as entidades que ser�o manipuladas pela API.
2. Configurando Controladores: Criando os endpoints para expor as funcionalidades da API.
3. Implementando Servi�os: Criando a l�gica de neg�cio.
4. Cada etapa � detalhada em tutoriais dentro do pr�prio c�digo do projeto, ajudando voc� a entender cada 
conceito � medida que o implementa.

## Testando a API
Para testar a API, voc� pode utilizar ferramentas como o Postman ou o Swagger, que est� integrado ao projeto. 
Com essas ferramentas, voc� pode simular requisi��es HTTP e verificar se a API est� respondendo conforme o 
esperado.

<br>

![Execu��o1](imgs/mostra2.png)
