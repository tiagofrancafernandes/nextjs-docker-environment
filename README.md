## NextJS Docker environment

* 1- Crie uma pasta chamada `next-app` e na raiz desta, coloque seu projeto **NextJS**

* 2- Conforme seu ambiente (dev ou prod), renomeie os arquivos adequados para tal
    > ### Se **Dev**:
    > 1. Renomeie o arquivo `Dockerfile.dev` para `Dockerfile`
    > 2. Renomeie o arquivo `docker-compose.yml.dev` para `docker-compose.yml`
    >
    > ----
    >
    > ### Se **Prod**:
    > 1. Renomeie o arquivo `Dockerfile.prod` para `Dockerfile`
    > 2.  Renomeie o arquivo `docker-compose.yml.prod` para `docker-compose.yml`

* 3- Execute o comando `docker-compose up`


----

**Testest on**

```
--
Ubuntu 20.04.4 LTS
Docker version 20.10.12, build
docker-compose version 1.29.2, build 5becea4c

--
Ubuntu 20.04.2 LTS
Docker version 20.10.12, build e91ed57
Docker Compose version v2.3.3


```

----

## [Change log](changelog.md)

----

## TODO

- Receber parâmetros por arquivo `.env` (porta, etc)
