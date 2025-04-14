# AVITO QA Internship — Весенняя волна 2025

В этом репозитории содержится выполненное тестовое задание для стажёра QA-направления (весенняя волна 2025).

---

## Задание 1 - Поиск багов на странице

Задание 1 находится в папке с соответствующим названием:  
`Задание 1.md`

---

## Задание 2.1 — Тестирование API микросервиса 

Задание выполнено с использованием **Postman** и **JavaScript** для написания тестов по всем доступным ручкам API.
- Тест-кейсы находятся в файле `TESTCASES.md`
- Баг-репорт находится в файле `BUGS.md`


## Как использовать Postman-коллекцию:

### 1. Установите [Postman](https://www.postman.com/downloads/), если он ещё не установлен.

### 2. Скачайте коллекцию
Сохраните Postman-коллекцию по ссылке:  
📁 [Postman_collection.json](https://github.com/AlexVKh/AVITO_qa-internship/blob/main/Postman_collection.json)

### 3. Импортируйте коллекцию в Postman:
- Откройте Postman → **Import**
- Перейдите во вкладку **Files**
- Выберите скачанный файл `Postman_collection.json`
- Нажмите **Import**

### 4. Убедитесь, что переменная `{{baseUrl}}` установлена:
```text
https://qa-internship.avito.com
