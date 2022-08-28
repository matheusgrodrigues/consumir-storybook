# Instalação

Baixe o repositório
> git clone https://github.com/matheusgrodrigues/consumir-storybook.git

Execute o projeto
> yarn start ou npm start

## Dependencias

Adicionei o suporte a sass e a instalação do repositório do storybook customizado criado por mim no package.json, portando ele será baixado automaticamente, e ficará disponível como devDependencies na pasta node_modules para uso.

## Importando estilos do storybook

Após a instalação do projeto, será necessário importar os estilos globais do storybook para que os componentes do react-boostrap sejam estilizados.

No repositório do storybook que criei, foi criado variaveis customizadas que sobrescreveram as originais do bootstrap, portando deve importa-as para utilizar os estilos customizados do storybook criado.

`File: index.tsx`

`import "storybook-docs/src/styles/custom.scss";`

## Instanciando o component

`File: App.tsx`

`import Button from "storybook-docs/src/stories/MButton/MButton";`

`<Button variant="primary">Botão test</Button>`

## Storybook customizado

- [Demo online](https://630ba585e462553a7ef93d70-iksemgvage.chromatic.com/?path=/story/matheus-buttons-storybook--page) 
- [Repositório](https://github.com/matheusgrodrigues/storybook)