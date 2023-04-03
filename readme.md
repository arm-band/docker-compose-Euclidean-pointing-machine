# エウクレイデスの星取り機 (Euclidean pointing machine)

## Abstract

diagrams.net (旧 draw.io) をローカル(仮想)で実行できる環境をさっと作るための Dockerfile と Docker Compose。

Powered by [jgraph/docker-drawio](https://github.com/jgraph/docker-drawio).

## Usage

```
git clone https://github.com/arm-band/docker-compose-Euclidean-pointing-machine.git
```

### Usage

1. Copy `sample.env` and rename `.env`
2. Change parameters in `.env`
3. `docker-compose up -d`
4. `docker-compose exec epm /bin/bash`

### Finish

1. `docker-compose down`