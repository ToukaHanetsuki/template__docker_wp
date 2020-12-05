# Environment
- Docker version 19.03.12

# Set up

## .envファイルの作成
```
echo -n -e \
WORDPRESS_DB_NAME=wordpress"\n"\
WORDPRESS_DB_USER=wp_user"\n"\
WORDPRESS_DB_PASSWORD=password"\n"\
MYSQL_RANDOM_ROOT_PASSWORD=yes"\n"\
MYSQL_DATABASE=wordpress"\n"\
MYSQL_USER=wp_user"\n"\
MYSQL_PASSWORD=password\
>> .env
```

## コンテナの作成・起動
```
docker-compose up
```

# Other Commands

## コンテナの起動
```
docker-compose up

# or

docker-compose start
```

## コンテナの停止
```
docker-compose stop
```

## コンテナの停止・削除
```
docker-compose down
```

# 参考になるリンク集
- [WordPress のフォルダ構成](https://www.webdesignleaves.com/pr/wp/wp_folder_structure.html)