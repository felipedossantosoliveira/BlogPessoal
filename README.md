# **PersonalBlog**

## Project Setup

### With Docker

#### Docker up

```sh
docker compose up -d
```

#### Compile and Hot-Reload for Development

```sh
docker exec -it vitedocker sh -c "npm i && npm run dev"
```

#### Compile and Minify for Production

```sh
docker exec -it vitedocker sh -c "npm i && npm run build"
```
---
### With local node

#### Compile and Hot-Reload for Development
``` sh
npm install
npm run dev
```

### Compile for production in hostinger share hosting

``` sh 
npm install
npm run build
```

>### Shared-hosting
>#### Active npm in hostinger share hosting
>
>```sh
>export NVM_DIR="$HOME/.nvm"
>[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"
>[ -s "$NVM_DIR/bash_completion" ] && \. "$NVM_DIR/bash_completion"
>```

## Agradecimentos

[Artur Ferreto](https://github.com/arturferreto) - Por ser um incrível amigo e companheiro de trabalho 
