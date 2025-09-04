## Финальный проект 6 спринта
<hr>

## Студент: Агата Ничипорчик

## <h>Когорта: #28</h>
<hr>

## <h>Project: Яндекс.Самокат</h>

## <h>Инструкция по запуску:</h>

### <h>1. Установите зависимости:</h>

> pip install -r requirements.txt</h>

### <h>2. Запустить все тесты и записать отчет:</h>

> pytest --alluredir=./allure-results

### <h>3. Посмотреть отчет по прогону html</h>

> allure serve ./allure-results


<hr>

<h3 align="left" style="color:green">Project files and description:</h3>

| Название файла     | Содержание файла             |
|--------------------|------------------------------|
| Tests dir          | Директория с тестами         |
| conftest.py        | Фикстуры                     |
| test_faq.py        | Тесты для «Вопросы о важном» |
| test_logo.py       | Тесты для кликов на лого     |
| test_order.py      | Тесты для оформления заказа  |
| data.py            | Файл с URL и данными тестов  |
| requirements.txt   | Файл с зависимостями         |
| allure_results.dir | Папка с отчетами Allure      |
| locators.dir       | Директория с локаторами      |
| pages.dir          | Директория с PageObject      |
| README.md          |                              |

