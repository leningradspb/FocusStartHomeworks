[![Build Status](https://travis-ci.com/MisnikovRoman/FocusStartHomeworks.svg?branch=test%2FsetupCI)](https://travis-ci.com/MisnikovRoman/FocusStartHomeworks)
# Focus Start iOS (fall 2019)

##### Правила сдачи домашнего задания:

1. Необходимо скачать исходный репозиторий с базовыми файлами для домашнего проекта.
2. Создать свое решение задачи в виде исходного кода.
3. Отправить в виде pull request к данному репозиторию с наименованием ветки surname_name/feature_name (наименование ветки обязательно(!) в lowercase. feature_name будет описано отдельно в каждом домашнем задании).

## Домашнее задание #1

**Название фичи**: test  
**Описание**: Необходимо исправить ошибку в приложении

## Домашнее задание #2

**Название фичи**: string_extension  
**Описание**: Написать расширение для класса String, которое добавляет 2 метода:
* Метод возвращает строку с развернутыми словам
* Метод проверяет номер мобильного телефона на правильность

Шаблон для заполнения есть в файле `String+Extensions.swift`.
Также в проекте есть тесты на правильность реалиазации новых методов. Тесты запускаются комбинацией клавиш `Cmd+U`
В проекте на гитхабе также настроена автоматическая сборка проекта при пул реквесте.

## Домашнее задание #3

**Название фичи**: high_order_funtiones  
**Описание**: Написать расширение для класса Sequence с тремя методами:  
* своя реализация метода '.map(:)'
* своя реализация метода '.reduce(:)'
* своя реализация метода '.compactMap(:)'
Примечание: методы должны быть дженериками и работать с любыми типами

Также необходимо заполнить класс с тестами

## Дополнительная информация
### Как обновить склонированный (forked) репозиторий

Добавить исходный оригинальный репозиторий и назвать его `upstream`
> `git remote add upstream https://github.com/ArtemPrivet/FocusStartHomeworks.git`

Загрузить все изменения в удаленном репозитории
> `git fetch upstream`

Влить все изменения в свой локальный репозиторий
> `git merge upstream/master`

Отправить изменения на свой удаленный репозиторий
> `git push`
