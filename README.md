# Workshop-Docker

Este projeto é um exemplo para demonstrações de uso do Docker. Siga as instruções abaixo para clonar o projeto e rodar a aplicação usando Docker.

## Pré-requisitos

Certifique-se de que você tem os seguintes softwares instalados:

- [Git](https://git-scm.com/)
- [Docker](https://www.docker.com/)

## Clonando o Projeto

1. Abra seu terminal ou prompt de comando.
2. Clone este repositório executando o seguinte comando:

    ```bash
    git clone https://github.com/seu-usuario/Workshop-Docker.git
    ```

3. Navegue até o diretório do projeto:

    ```bash
    cd Workshop-Docker
    ```

## Construindo a Imagem Docker

Dentro do diretório do projeto, construa a imagem Docker usando o seguinte comando:

```bash
docker build -t imagem-docker .
```
## Executando o Contêiner
Após a construção da imagem, você pode executar o contêiner com o seguinte comando:
```
docker run -d -p 8080:80 imagem-docker
```
Este comando executará o contêiner em segundo plano e mapeará a porta 8080 do seu host para a porta 80 do contêiner.

## Acessando a Aplicação
Abra o seu navegador e acesse a aplicação em http://localhost:8080.



