---
sidebar_position: 2
title: Introdução
---

### Como Iniciar um Projeto no Angular ?
>
> Este guia irá orientá-lo a começar um projeto Angular, desde a instalação até a execução do seu primeiro servidor local.

### Passo 1: Instalar o Node.js

Antes de começar com o Angular, é necessário ter o **Node.js** instalado. O Angular utiliza o Node.js para gerenciar pacotes e executar o servidor de desenvolvimento.

1. **Baixe o Node.js**: Acesse o [site oficial do Node.js](https://nodejs.org) e baixe a versão recomendada para a maioria dos usuários.


> ### Passo 2: Instalar o Angular CLI
> 
> O Angular CLI (Command Line Interface) é uma ferramenta de linha de comando que ajuda a criar e gerenciar projetos Angular de forma eficiente.
> 
> 1. **Instale o Angular CLI globalmente**:
>    Execute o seguinte comando no terminal:
>    ```bash
>    npm install -g @angular/cli
>    ```
> 
> 2. **Verifique a instalação**: Para verificar se o Angular CLI foi instalado corretamente, execute:
>    ```bash
>    ng --version
>    ```

> ### Passo 3: Criar um Novo Projeto Angular
> 
> Agora que o Angular CLI está instalado, você pode criar um novo projeto Angular.
> 
> 1. **Crie o projeto**:
>    No terminal, execute o comando:
>    ```bash
>    ng new meu-projeto-angular
>    ```
>    O Angular CLI irá perguntar algumas configurações para o projeto (como usar CSS, SCSS, etc.). Escolha as opções desejadas.
> 
> 2. **Acesse o diretório do projeto**:
>    Navegue até o diretório do seu projeto recém-criado:
>    ```bash
>    cd meu-projeto-angular
>    ```

> ### Passo 4: Executar o Servidor de Desenvolvimento
> 
> Com o projeto criado, é hora de rodá-lo localmente para ver o que foi gerado.
> 
> 1. **Inicie o servidor de desenvolvimento**:
>    Execute o comando:
>    ```bash
>    ng serve
>    ```
> 
> 2. **Acesse o projeto no navegador**:
>    Abra o navegador e vá até [http://localhost:4200](http://localhost:4200). Você verá a página inicial do seu novo projeto Angular.

> ### Passo 5: Próximos Passos
> 
> Agora que o projeto está em funcionamento, você pode começar a modificar e expandir a aplicação. Alguns próximos passos incluem:
> 
> - **Criar componentes**: Use o comando `ng generate component nome-do-componente` para criar novos componentes.
> - **Adicionar roteamento**: Configure o roteamento de páginas no seu projeto.
> - **Conectar com APIs**: Use o Angular HTTP Client para se comunicar com APIs externas.
> 
> > Para mais informações, consulte a documentação oficial do Angular [aqui](https://angular.io/docs).
   
2. **Verifique a instalação**: Após a instalação, abra o terminal ou prompt de comando e execute o seguinte comando para verificar se o Node.js foi instalado corretamente:
   ```bash
   node --version
