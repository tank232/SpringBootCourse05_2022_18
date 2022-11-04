Домашнее задание
Обернуть приложение в docker-контейнер

Цель:
Цель: деплоить приложение в современном DevOps-стеке
Результат: обёртка приложения в Docker


Описание/Пошаговая инструкция выполнения домашнего задания:
Внимание! Задание выполняется на основе любого сделанного Web-приложения

Обернуть приложение в docker-контейнер. Dockerfile принято располагать в корне репозитория. В image должна попадать JAR-приложения. Сборка в контейнере рекомендуется, но не обязательна.
БД в собственный контейнер оборачивать не нужно (если только Вы не используете кастомные плагины)
Настроить связь между контейнерами, с помощью docker-compose
Опционально: сделать это в локальном кубе.
Приложение желательно реализовать с помощью всех Best Practices Docker (логгирование в stdout и т.д.)
Данное задание НЕ засчитывает предыдущие!

Критерии оценки:
Факт сдачи:

0 - задание не сдано
1 - задание сдано
Степень выполнения (количество работающего функционала, что примет заказчик, что будет проверять тестировщик):
0 - ничего не работает или отсутствует основной функционал
1 - не работает или отсутствует большая часть критического функционала
2 - основной функционал есть, возможны небольшие косяки
3 - основной функционал есть, всё хорошо работает
4 - основной функционал есть, всё хорошо работает, тесты и/или задание перевыполнено
Способ выполнения (качество выполнения, стиль кода, как ревью перед мержем):
0 - нужно править, мержить нельзя (нарушение соглашений, публичные поля)
1 - лучше исправить в рамках этого ДЗ для повышения оценки
2 - можно мержить, но в следующих ДЗ нужно поправить.
3 - можно мержить, мелкие недочёты
4 - отличная работа!
5 - экстра балл за особо красивый кусочек кода/решение целиком (ставится только после отличной работы, отдельно не ставится)
Статус "Принято" ставится от 6 и выше баллов.
Ниже 6, задание не принимается.
Идеальное, но не работающее, решение = 1 + 0 + 4 (+4 а не 5) = 5 - не принимается.
Если всё работает, но стилю не соответствует (публичные поля, классы капсом) = 1 + 4 + 0 = 5 - не принимается

Рекомендуем сдать до: 10.10.2022