# Módulo 1 de ReactJS Rocket-Seat

Esse módulo é um projeto de Controle Financeiro chamado DT-Money focado em performance no React.
___
### Palavras chave:
>ReactJS

## Conteúdo Programático do Módulo 1

<details style="font-size: 16px">
<summary><strong style="font-size: 18px">1. Estrutura visual</strong></summary>

  ---

  + Introdução
  + Setup do projeto
  ---
</details>

## Atalhos do VSCode:

>Clique para visualizar os [Atalhos do VSCode](https://silicon-chips-f58.notion.site/VsCode-Shortcuts-Atalhos-4ced0388660c4f1c93b410765c0a44cd) no Notion.

## Principais comandos:

### Aula "Setup do Projeto"

+ `npm create vite@latest`: Cria o projeto Vite.
  > **_OBS:_** Aqui você pode encontrar a documentação do [Vite](https://vitejs.dev/guide/)
+ `npm i`: Instala as dependências para rodar o projeto.
+ `npm run dev`: Roda o projeto na porta configurada no arquivo vite.config.js. Nesse projeto está na localhost:3001.
+ `npm i styled-componentes`: Biblioteca que permite trabalhar com estilos usando componentes.
+ `npm i @types/styled-components -D`: Tipagem da biblioteca styled-components.

### Recurso "Figma"

+ Protótipo de Alta Fidelidade no [Figma](https://www.figma.com/community/file/1138814493269096792)

### Aula "Componente: Summary"

+ `npm i phosphor-react`: Biblioteca de ícones.

### Aula "Criando um modal acessível"

+ Aria: Regras de [Acessibilidade](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA)
+ AriaKit: Biblioteca de acessibilidade [Ariakit](https://github.com/ariakit/ariakit)
+ Headless UI: Biblioteca de acessibilidade [Headless UI](https://headlessui.com/)
+ Chakra UI: Biblioteca de componentes acessíveis [Chakra UI](https://v2.chakra-ui.com/getting-started)
+ Radix UI: Biblioteca de componentes acessíveis [Radix UI](https://www.radix-ui.com/)

+ `npm install @radix-ui/react-dialog`: Instala o modal (dialog) do radix.

### Aula "Criando radio button acessível"

+ `npm install @radix-ui/react-radio-group`: Instala o radio button do radix.

### Aula "Configurando JSON Server"

+ `npm i json-server@0.17.0 -D`: Permite criar uma API através de um arquivo JSON.
  > **_OBS:_** Algumas funcionalidades utilizadas no projeto só funcionam nessa versão antiga do json-server.
+ `npx json-server server.json`: Sobe um servidor local através do arquivo server.json
  > **_OBS1:_** Executar após criar um arquivo `server.json` na pasta raíz do projeto.
  > **_OBS2:_** O parâmetro `-p 3333` sobe o servidor na porta 3333
  > **_OBS3:_** O parâmetro `-w` sobe o servidor no modo watch (atualiza de acordo com as mudanças no server.json)
  > **_OBS4:_** Criar alias `"dev:server": "json-server server.json -p 3333 -w -d 500"` nos scripts do arquivo `package.json`

### Aula "Aplicando React Hook Form"

+ `npm i react-hook-form zod`: Biblioteca para lidar com formulários no React. Instala junto o zod para validação de dados e definição do schema do formulário.
+ `npm i @hookform/resolvers`: Biblioteca para utilizar o zodResolver.

### Aula "Configurando Axios"

+ `npm i axios`: Biblioteca para requisições.

### Aula "Corrigindo erros de linting"

+ `npm i eslint @rocketseat/eslint-config -D`: Instala o ESLint e a configuração da RocketSeat.

### **Passo a Passo para Configuração do ESLint do Crea-GO:**

1. Excluir a pasta `node_modules`.
2. Dentro do arquivo `package.json`, excluir todas as `devDependencies` que tenham "eslint" no nome.
3. Rodar `npm i`
4. Rodar o comando: `npm install eslint@8.22.0 @typescript-eslint/eslint-plugin@5.45.0 @typescript-eslint/parser@5.45.0 eslint-plugin-prettier@4.2.1 prettier@2.7.1 --save-dev`
5. Rodar o comando: `npm i -D eslint-config-creago`
6. Exclua o arquivo `.eslint.config.js` e, se não existir, crie o arquivo ´.eslintrc.json´ e coloque no seu conteúdo:
    >
    ```
    {
      "extends": "eslint-config-creago/react"
    }
    ```
7. Alterar as configurações de usuário no `settings.json`, acrescentando:
    >
    ```
    {
      "editor.codeActionsOnSave": {
          "source.fixAll": "explicit",
          "source.fixAll.eslint": "explicit"
      },
      "eslint.format.enable": true,
      "editor.formatOnSave": true
    }
    ```
8. Instalar a extensão ESLint da Microsoft no VSCode
9. Rodar `npm run lint` para mostrar os erros.
10. Testar se `Ctrl + S` num arquivo .ts ou .tsx aplica formatação do ESLint


## Autoria e Créditos:

+ Documentação criada com carinho e dedicação por [Júlio César Freitas](https://github.com/juliofreitasbm) a serviço do [CREA-GO](https://www.creago.org.br/).