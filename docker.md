## Alguns comandos importantes do docker

**Executando o comando docker buil, utilizando um dockerfile especifico.**

```
docker build -t [IMAGE_NAME]:[IMAGE_TAG] -f [DOCKERFILE_NAME] .
```

**Removendo imagens pendentes (imagens que não completaram seu processo de build) e que não possuem mais utilidades**

- Listando essas imagens

```
docker images -f dangling=true
```

- Excluindo imagens com base no retorno de uma busca (listagem)

        -q: Passando o id da imagem no comando docker rmi
        rmi: Comando para remover uma ou mais imagens
        -f: Irá realizar um filtro com base nas condições fornecidas após o -f

```
 docker images rmi --force $(docker images -f dangling=true -q)
```
