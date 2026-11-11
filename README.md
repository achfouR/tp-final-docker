# TP Final - Docker Compose

Projeto com dois containers: Nginx customizado e servidor HTTP Python.

## Arquivos
- `Dockerfile`: imagem personalizada do Nginx.
- `site/index.html`: primeira pagina.
- `servidor-http/index.html`: segunda pagina.
- `docker-compose.yml`: configuracao dos dois servicos.

## Executar
No terminal, dentro da pasta do projeto:

```bash
docker compose build
docker compose up -d
docker ps
docker compose logs
docker compose exec site sh
```

Para sair do terminal interno do container, digite `exit`.

Abrir no navegador (digitando manualmente, sem parametros adicionais):
- `http://localhost:8080`
- `http://localhost:8081`

## Encerrar
```bash
docker compose down
```

## Entrega
Enviar link do GitHub e PDF com prints dos comandos e dos dois sites.
