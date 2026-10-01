# prova-pratica1-computacao-nuvem

nome:vinicius hay mussi becalito
RA:c5b508a0b02f8a18e82f

## O que eu fiz?
Executei uma página web em um contêiner Docker chamado loja.
Usei a imagem nginx:alpine e a porta 8081 do ambiente.

## verificação do contêiner
CONTAINER ID   IMAGE          COMMAND                  CREATED              STATUS              PORTS                                     NAMES
0881215e482c   nginx:alpine   "/docker-entrypoint.…"   About a minute ago   Up About a minute   0.0.0.0:8081->80/tcp, [::]:8081->80/tcp   loja

## Teste da página
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Loja</title>
</head>
<body>
  <h1>Loja no ar</h1>
</body>
</html>

## Explicação
o contêiner loja armazena a imagem, já o nginx:alpine é a base.
o mapeamento da porta 8081:80 server pra ligar a porta ambiente á porta do contêiner
