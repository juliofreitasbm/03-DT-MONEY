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

+ `npm i json-server -D`: Permite criar uma API através de um arquivo JSON.
+ `npx json-server server.json`: Sobe um servidor local através do arquivo server.json
  > **_OBS1:_** Executar após criar um arquivo `server.json` na pasta raíz do projeto.
  > **_OBS2:_** O parâmetro `-p 3333` sobe o servidor na porta 3333
  > **_OBS3:_** O parâmetro `-w` sobe o servidor no modo watch (atualiza de acordo com as mudanças no server.json)
  > **_OBS4:_** Criar alias `"dev:server": "json-server server.json -p 3333 -w -d 500"` nos scripts do arquivo `package.json`



## Autoria e Créditos:

+ Documentação criada com carinho e dedicação por [Júlio César Freitas](https://github.com/juliofreitasbm) a serviço do [CREA-GO](https://www.creago.org.br/).