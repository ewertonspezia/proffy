# Configurações Iniciais

## React Project Start
`yarn create react-app NOMEPROJETO --template typescript`

## NodeJS Server Start
mkdir server

`yarn init -y`

Criar pasta src

Criar arquivo server.ts dentro de src

`yarn add typescript -D`

Criar arquivo de configurações do typescript

`yarn tsc --init`

Dentro do arquivo tsconfig.json alterar target para es2017 (devido a compatibilidades com os navegadores)

Instalar a dependência abaixo para observar as alterações no servidor e reestartar o server automaticamente

`yarn add ts-node-dev -D`

Criar dentro de package.json para conseguir iniciar o server com o comando `yarn start`

`"scripts": {
    "start": "tsnd --transpile-only --ignore-watch node_modules --respawn src/server.ts"
  }`
