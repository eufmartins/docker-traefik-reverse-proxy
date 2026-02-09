# Docker Traefik Reverse Proxy

Projeto de estudo para criar um proxy reverso com Traefik gerenciando múltiplos serviços web. Essa aplicação expõe dois sites através de um único endpoint com roteamento inteligente.

## Sobre

Desenvolvido por **Felipe Martins** — estudante DevOps apaixonado por tecnologia.

LinkedIn: [Felipe Martins](https://linkedin.com/in/eufmartins)

## Como rodar o projeto

1. Clone o repositório:

```
git clone https://github.com/eufmartins/docker-traefik-reverse-proxy.git
```
```
cd docker-traefik-reverse-proxy
```


2. Rode os containers com Docker Compose:

```
docker compose up --build
```

3. Acesse no navegador:
- Site 1: http://localhost/site1
- Site 2: http://localhost/site2
- Dashboard Traefik: http://localhost:8080

## Tecnologias usadas

- Docker
- Docker Compose
- Traefik
- Nginx
- Let's Encrypt

## O que aprendi aqui

- Configurar um proxy reverso com Traefik
- Roteamento baseado em paths (/site1, /site2)
- Configurar HTTPS automático com Let's Encrypt
- Usar middlewares para manipulação de URLs
- Monitorar serviços através do dashboard do Traefik
