# json-server
JSON server

## Установка и запуск

```bash
# установить npm пакеты
npm i

# запуск сервера
npm run start

# после успешного запуска сервер доступен по 3000 порту
```

## Endpoints

### Посты

```bash
# cписок всех постов
GET	/posts

# получение поста по ID
GET	/posts/1

# получение всех комментариев к посту
GET	/posts/1/comments

# получение всех комментариев к посту
GET	/comments?postId=1

# добавление поста
POST	/posts

# удаление поста
DELETE	/posts/1
```

### Resources

```bash
/posts	100 posts
/comments	500 comments
/albums	100 albums
/photos	5000 photos
/todos	200 todos
/users	10 users
```