### Com o Dockerfile pronto, precisamos fazer o build da imagem, para isso execute:
```
docker build -t marcosguedes01/simplenodeapp:latest .
```

### Com o build finalizado, temos uma imagem com o nome"‘node-app", para comprovar execute o comando abaixo:
```
docker images
```

### Para rodar o container e executar a aplicação, execute o comando abaixo:
```
docker run -ti -p 3000:3000 marcosguedes01/simplenodeapp:latest
```