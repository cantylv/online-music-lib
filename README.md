# Сервис получения текста песен

## Технические требования к использованию 
+ Наличие установленного Docker Desktop
+ Golang 1.23.4

### Необходимые действия для запуска проекта (по порядку)
1) Перейти в корень проекта 
2) Запустить команду `make docker-infra`
3) Запустить команду `make pipeline`

После выполнения команд, можно делать запросы к сервису. API сервиса появится в директории docs.