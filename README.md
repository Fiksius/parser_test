# parser_test

## Build

cd cmd/server && go build -o parser_test

## Run

./parser_test

## Параметры окружения для запуска

| Параметр    | Описание             | По умолчанию |
|-------------|----------------------|--------------|
| PARSER_HOST | Хост запуска сервера | localhost    |
| PARSER_PORT | Порт запуска сервера | 8080         |

## Пример ENV для старта сервера
```Bash
export PARSER_HOST=localhost
export PARSER_PORT=8080
```