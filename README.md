# Lab4: currencycalc (own package + docs + GitHub packages)

## Структура
- cmd/app/main.go — пример использования + обработка ошибок + fmt.Printf
- pkg/currencycalc/currencycalc.go — пакет currencycalc с экспортируемыми функциями и doc-комментариями

## Используемые GitHub пакеты
- github.com/dustin/go-humanize — форматирование чисел
- github.com/google/uuid — генерация UUID (пример вызова чужого пакета)

## Запуск
```bash
go mod tidy
go run ./cmd/app
