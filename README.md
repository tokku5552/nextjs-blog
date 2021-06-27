## docker の起動関連

- 起動してエミュレータを起動するとき

```
docker-compose up
docker-compose run -p 3000:3000 node-container /bin/bash
```

- 起動済みのコンテナに接続するとき

```
docker ps
docker exec -i -t <CONTAINER ID> /bin/bash
```

- コンテナを停止するとき

```
docker-compose down
```

This is a starter template for [Learn Next.js](https://nextjs.org/learn).
