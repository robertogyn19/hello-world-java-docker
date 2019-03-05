# Readme

## Build da imagem

Execute o comando abaixo para construir a imagem do docker.

```
docker build -t robertogyn19/hello-world:0.0.1 -f ./devops/Dockerfile .
```

## Execução da imagem

Para executar a imagem, rode o comando abaixo.

```
docker run --rm robertogyn19/hello-world:0.0.1
```