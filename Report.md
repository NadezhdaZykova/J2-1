# Отчёт о тестировании приложения "Money Transfer"

## Краткое описание

При пополнении счёта клиента, текущий баланс которого составил 2_000_000_000 (два миллиарда рублей), на сумму 500_000_000 (пятьсот миллионов рублей) возникла ошибка.


## Описание тестов

Проведено позитивное, функциональное тестирование с тестируемых функции пополнения счёта клиента.

## Результаты

1. При пополнении счёта клиента возникли проблемы при выходе за границы типа int.
2. Ссылка на баг-репорт https://github.com/NadezhdaZykova/J2-1/issues/1

## Общие рекомендации

Необходимо исправить ситуацию, возникшую при выходе за границы типа int.