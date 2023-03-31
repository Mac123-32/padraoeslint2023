Estou salvando este tpo de padrão para não mais ter qe passar maior parte do meu tempo e ter quue
fazer cada alteração então vamos lá

temos uma pasta que se chama setting.json nela ha as alterações para este caminho onde são sslavas
emcertos prefixos , um padrão meu

havera uma outra pasta que se chama padrao, nela contem os arquivos necessarios para copiar e colar
no seu prjeto

Lembre de intalar o eslint o typescript nodemon sucrase prettier , pois ao copiar e colar sem antes
ter feito estas modificcações você vera varios erros no seu codigo

- Vamosiniciar um pequeno tutorial
  npm init
  npm i -D typescript sucrase
  npm i -D nodemon
  npm i -D eslint @typescript-eslint/parser @typescript-eslint/eslint-pluguin
  npx eslint --init
  - To check syntax, find problems, and enforce code style
  - Javascript modules (import/export)
  - None of these
  - Node
  - Use a popular style guide
  - Standard......
  - javascript
    (Pronto agora podeesperar ele baixar todas as dependencias);

Agora vamos fazer a instalação e organização do prittier
npm i -D prettier eslint-config-prettier eslint-plugin-prettier
