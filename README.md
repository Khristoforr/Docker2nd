# 1-й шаг, выполняем сборку образа
`docker build -t stock_products .` 

# 2-й шаг, запускаем контейнер
`docker run --name stock_products1 -d -p 8081:80 stock_products` 


# CRUD

Необходимо выполнить и предоставить на проверку задачу:

[Склады и товары](./stocks_products)

Работа должна соответствовать принятому [стилю оформления кода](https://github.com/netology-code/codestyle/tree/master/python).

Любые вопросы по решению задач задавайте в Slack-чате.
