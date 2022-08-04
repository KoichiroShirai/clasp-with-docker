# clasp in docker

## dependency

- [docker](https://www.docker.com/)
- [node.js](https://nodejs.org/en/)
  - ver >=10.3.0.
- [Clasp](https://www.npmjs.com/package/@google/clasp)

## Setup

- Dockerをインストール

## Usage

- 当該フォルダで

```shell
docker compose up
```

- コンテナが起動したら コンテナに入る
- コンテナの中で claspを使えるようにする

```shell
clasp login --no-localhost
```

- 出てきたurlにアクセス
- 権限を許可する

- 既存のスクリプトを持ってくるには

```shell
clasp clone <scliptID>
```

## Licence

## Authors

## Reference

- [Qiita](https://qiita.com/dd0125/items/47b5edbbd8f11dd4f317)
