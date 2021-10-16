
> npx --package typescript tsc --help

// compila o ficheiro typescript com o nome index.ts para a pasta dist
> npx --package typescript tsc --outDir dist index.ts

tsc significa typescript compiler

<em>cria ficheiro package.json</em>
> npm init -y

> npm i typescript --save-dev

package.json -> scripts: {"tsc": "tsc"}

> npm run tsc -- --init

caniuse.com parar ver que js/ts comandos várias versões do browser suportam

tsconfig.json -> { "sourceMap": true, "outDir": "./dist", "moduleResolution": "node"} 





