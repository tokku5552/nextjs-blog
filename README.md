## docker の起動関連

- 起動してエミュレータを起動するとき

```
docker-compose up
docker-compose run -p 4000:4000 -p 5000:5000 -p 5001:5001 -p 8080:8080 -p 9005:9005 node-container /bin/bash
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
