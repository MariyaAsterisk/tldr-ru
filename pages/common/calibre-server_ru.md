# calibre-server

> Серверное приложение, используемое для распространения электронных книг.
> Сначала книги нужно импортировать в библиотеку с помощью графического интерфейса или calibredb.
> Часть электронной библиотеки Calibre.

- Запускает сервер распространения книг. Доступен по адресу http://localhost:8080:

`calibre-server`

- Запускает сервер на другом порту. Доступен по адресу http://localhost:port:

`calibre-server --port {{port}}`

- Защищает сервер паролем:

`calibre-server --username {{username}} --password {{password}}`
