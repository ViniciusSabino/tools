## Principais comandos do NPM

**Exibe um miniquestionario para auxiliar na criação e descrição do package.json em seu projeto.**

```
Npm init
```

**Instala um modulo em seu projeto**

```
Npm install nome_do_modulo
```

**Instala um modulo global**

```
Npm install -g nome_do_modulo
```

**Instala o módulo e adiciona-o no arquivo package.json, dentro do atributo "dependencies"**

```
npm install nome_do_modulo --save
```

**Instala o modulo e adiciona-o no arquivo package.json, dentro do atributo "devDependencies"**

```
npm install nome_do_modulo --save-dev
```

**Lista todos os módulos que foram instalados em seu projeto**

```
npm list
```

**Lista todos os módulos globais que foram instalados**

```
npm list -g
```

**Desinstala um modulo do projeto**

```
npm remove nome_do_modulo
```

**Desinstala um modulo global**

```
npm remove -g nome-do_modulo
```

**Desinstala um modulo do projeto, removendo também do atributo "dependencies" do package.json**

```
npm remove nome_do_modulo --save
```

**Desinstala um modulo do projeto, removendo também do atributo "devDependencies" do package.json**

```
npm remove nome_do_modulo --save-dev
```

**Atualiza a versão de um modulo do projeto**

```
npm update nome_do_modulo
```

**Atualiza a versão de um modulo global**

```
npm update -g nome_do_modulo
```

**Cria um usuário no site https://npmjs.org**

```
npm adduser nome_do_usuario
```

**Exibe detalhes do seu perfil público NPM do usuário (é necessário criar um usuário utilizando o comando anterior)**

```
npm whoami
```

**Publica um módulo no https://npmjs.org (É necessário ter uma conta ativa primeiro)**

```
npm publish
```

**Exibe detalhes de todos os comandos**

```
npm help
```
