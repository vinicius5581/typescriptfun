# TypeScript 101

## Setup

### Initiate a project

```
yarn init -y
```

### Install Typescript:

```
yarn add typescript --dev
```

### Configuring the typescript compiler

```
yarn tsc --init
```

- open tsconfig.json


#### Changes to tsconfig.json

- Create a `/src` folder and add a `index.ts` to it. => `/src/index.ts`.
- on `tsconfig.json` change the `rootDir` to `./src`.
- Create a `/dist` folder.
- on `tsconfig.json` change the `outDir` to `./dist`.
- on `tsconfig.json` enable `removeComments` (set it to true `"removeComments": true`)
- on `tsconfig.json` enable `noEmitOnError` (set it to true `"noEmitOnError": true`)

## Compiling files:

```
yarn tsc index.ts
```

### anottating or explaning a variable:

```
let age: number = 20
```




