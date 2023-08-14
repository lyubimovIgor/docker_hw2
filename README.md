# Склады и товары (Docker)


## Созданём образ: 
### docker build . --tag stocks_products_image


## Созданём и запуск контейнера (с именем) на основе образа stocks_products_image : 
### docker run -d --name stocks_products_container -p 8000:6060 stocks_products_image


## Остановка контейнера: 
### docker stop stocks_products_container


## Проверка 'curl':
### curl localhost:8000/test


## Проверяем логи: 
### docker logs stocks_products_container


