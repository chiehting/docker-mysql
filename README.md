# docker-mysql

使用docker執行mysql服務,開發環境使用.

## Getting Started

使用docker啟動mysql工具.

* [mysql image](https://hub.docker.com/_/mysql)

### Prerequisites

* [docker](https://docs.docker.com/install/)
* [docker-compose](https://docs.docker.com/compose/install/)

## Running

### start mysql service

編輯docker-compose.yml, 調整MYSQL\_ROOT\_PASSWOR變數來變更root密碼.

```bash
docker-compose up -d
```

