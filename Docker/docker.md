## Alguns comandos importantes do docker

**Executando o comando docker buil, utilizando um dockerfile especifico.**

```
docker build -t [IMAGE_NAME]:[IMAGE_TAG] -f [DOCKERFILE_NAME] .
```

**Executando o mongodb localmente utilizando uma imagem oficial do mongodb**

**MONGODB**

```
docker run --name mongoname -p 27017:27017 -d -t mongo
```

-p 27017:27017 : O Container irá utilizar a mesma porta 27017 que a minha maquina(aplicação) irá utilizar
para se conectar nesse mongo

-d : Irá executar o container em modo background

-t : para especificar o nome da imagem que será utilizada (no exemplo a imagem é 'mongo')

**Removendo imagens desnecessárias para uso **

```
docker image prune
```
