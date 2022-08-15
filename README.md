# parser_test

## Build
cd cmd/server && go build -o parser_test

## Run
./parser_test

## Параметры окружения для запуска

| Параметр | Описание             | По умолчанию |
|----------|----------------------|--------------|
| HOST     | Хост запуска сервера | localhost    |
| PORT     | Порт запуска сервера | 8080         |

## Пример ENV для старта сервера
```
HOST=localhost;PORT=8080