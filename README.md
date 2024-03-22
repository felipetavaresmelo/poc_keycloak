# poc_keycloak

POC de uma aplicação Spring Boot utilizando o keycloak para autenticação e autorização.


## Instalação do docker

https://docs.docker.com/desktop/install/windows-install/

## Instalação do keycloak via docker

[Getting Started](https://www.keycloak.org/getting-started/getting-started-docker)


```sh
docker run -p 8080:8080 -e KEYCLOAK_ADMIN=admin -e KEYCLOAK_ADMIN_PASSWORD=admin quay.io/keycloak/keycloak:24.0.1 start-dev
```

## Acesso ao keycloak local

http://localhost:8080/admin/master/console/


## JWT

http://www.jwt.io


## Projeto Spring

### Criar projeto

https://start.spring.io

#### Dependências

- Spring Web
- Lombok
- Spring Security

## Referencias:

- https://www.youtube.com/watch?v=wgdo5I53GQo&t=2456s