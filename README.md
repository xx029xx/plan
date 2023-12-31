## Перечень автоматизируемых сценариев
### Переход с главной страницы сайта на страницу с профессией:
_**Предусловие:** Переход по введённому в строку браузера адресу сайта https://netology.ru._


#### №1
1. Кликнуть на кнопку "Каталог курсов".
2. Ввести название профессии в поле поиска.
3. Выбрать профессию из предложенных.
#### Ожидаемый результат: Переход на страницу с профессией.
#### №2
1. Кликнуть на кнопку "Каталог курсов".
2. Ввести название профессии в поле поиска.
3. Нажать на кнопку "Найти курс".
4. Выбрать профессию из списка найденных.
#### Ожидаемый результат: Переход на страницу с профессией.
#### №3
1. Кликнуть на кнопку "Каталог курсов".
2. Кликнуть на раздел "Программирование".
3. Выбрать профессию из списка предложенных.
#### Ожидаемый результат: Переход на страницу с профессией.
#### №4
1. Кликнуть на кнопку "Каталог курсов" на главной странице.
2. Кликнуть на раздел "Все курсы".
3. Выбрать профессию из списка предложенных.
#### Ожидаемый результат: Переход на страницу с профессией.
#### №5
1. Кликнуть на раздел "Программирование" на главной странице.
2. Выбрать профессию из списка предложенных.
#### Ожидаемый результат: Переход на страницу с профессией.
#### №6
1. Прокрутить главную страницу вниз до подвала.
2. Кликнуть на раздел "Каталог курсов".
3. Выбрать профессию из списка предложенных.
#### Ожидаемый результат: Переход на страницу с профессией.
#### №7
1. Прокрутить главную страницу вниз до подвала.
2. Кликнуть на раздел "Популярные курсы".
3. Выбрать профессию из списка предложенных.
#### Ожидаемый результат: Переход на страницу с профессией.
#### №8
1. Прокрутить главную страницу вниз до подвала.
2. Кликнуть на раздел "Программирование".
3. Выбрать профессию из списка предложенных.
#### Ожидаемый результат: Переход на страницу с профессией.


### Переход к анкете для заявки на странице профессии через кнопку "Записаться":
_**Предусловие:** Переход на страницу с профессией._
#### №9
1. Кликнуть на кнопку "Записаться" на странице с профессией.
#### Ожидаемый результат: Переход к анкете для заявки на странице с профессией.
#### №10
1. Прокрутить страницу с профессией вниз, пока наверху не появится кнока "Записаться"
2. Кликнуть на кнопку "Записаться".
#### Ожидаемый результат: Переход к анкете для заявки на странице с профессией.

### Позитивный сценарий
#### Заполнение анкеты для заявки валидными пользовательскими данными:
_**Предусловие:** Переход к анкете для заявки на странице с профессией._  
_**Входные данные:**_  
_**Имя:** Написано на кириллице или латинице и состоит из более 2-х букв, может содержать дефис и пробел._  
_**Номер телефона:** Формат +7 (999) 999-99-99, от 9-ти до 14-ти цифр._  
_**Электронный адрес:** Написан на латинице, указан верный почтовый домен (пример: @mail.ru, @gmail.com)._
#### №11
1. Заполнить поле ввода "Имя".
2. Заполнить поле ввода "Номер телефона".
3. Заполнить поле ввода "Электронная почта".
4. Клинуть на кнопку "Записаться".
#### Ожидаемый результат: Сообщение об успешной записи.

### Негативные сценарии
#### Оставление незаполненными полей анкеты для заявки пользовательскими данными:
_**Предусловие:** Переход к анкете для заявки на странице с профессией._  
_**Входные данные:** Валидные пользовательские данные._
#### №12
1. Заполнить поле ввода "Имя".
2. Заполнить поле ввода "Номер телефона".
3. Оставить пустым поле ввода "Электронная почта".
4. Клинуть на кнопку "Записаться".
#### Ожидаемый результат: Сообщение о необходимости заполнить поле "электронная почта" данными.
#### №13
1. Заполнить поле ввода "Имя".
2. Оставить пустым ввода "Номер телефона".
3. Заполнить поле поле ввода "Электронная почта".
4. Клинуть на кнопку "Записаться".
#### Ожидаемый результат: Сообщение о необходимости заполнить поле "номер телефона" данными.
#### №14
1. Оставить пустым ввода "Имя".
2. Заполнить поле ввода "Номер телефона".
3. Заполнить поле поле ввода "Электронная почта".
4. Клинуть на кнопку "Записаться".
#### Ожидаемый результат: Сообщение о необходимости заполнить поле "имя" данными.
### Заполнение анкеты для заявки невалидными пользовательскими данными: ####
_**Предусловие:** Переход к анкете для заявки на странице с профессией._  
_**Входные данные:** Невалидные и валидные пользовательские данные._
#### №15
1. В поле ввода "Имя" ввести меньше 2-х букв на кириллице или латинице.
2. В поле ввода "Номер телефона" ввести валидные данные.
3. В поле ввода "Электронная почта" ввести валидные данные.
4. Кликнуть на кнопку "Записаться".
#### Ожидаемый результат: Некоторые поля заполнены неверно.
#### №16
1. В поле ввода "Имя" ввести букв больше допустимого количества.
2. В поле ввода "Номер телефона" ввести валидные данные.
3. В поле ввода "Электронная почта" ввести валидные данные.
4. Кликнуть на кнопку "Записаться".
#### Ожидаемый результат: Некоторые поля заполнены неверно.
#### №17
1. В поле ввода "Имя" ввести цифры.
2. В поле ввода "Номер телефона" ввести валидные данные.
3. В поле ввода "Электронная почта" ввести валидные данные.
4. Кликнуть на кнопку "Записаться".
#### Ожидаемый результат: Некоторые поля заполнены неверно.
#### №18
1. В поле ввода "Имя" ввести спецсимволы (например: №\$\*).
2. В поле ввода "Номер телефона" ввести валидные данные.
3. В поле ввода "Электронная почта" ввести валидные данные.
4. Кликнуть на кнопку "Записаться".
#### Ожидаемый результат: Некоторые поля заполнены неверно.
#### №19
1. В поле ввода "Имя" ввести буквы экзотического языка (например: японского или арабского).
2. В поле ввода "Номер телефона" ввести валидные данные.
3. В поле ввода "Электронная почта" ввести валидные данные.
4. Кликнуть на кнопку "Записаться".
#### Ожидаемый результат: Некоторые поля заполнены неверно.
#### №20
1. В поле ввода "Имя" ввести валидные данные.
2. В поле ввода "Номер телефона" ввести менее 9-ти цифр.
3. В поле ввода "Электронная почта" ввести валидные данные.
4. Кликнуть на кнопку "Записаться".
#### Ожидаемый результат: Некоторые поля заполнены неверно.
#### №21
1. В поле ввода "Имя" ввести валидные данные.
2. В поле ввода "Номер телефона" ввести более 14-ти цифр.
3. В поле ввода "Электронная почта" ввести валидные данные.
4. Кликнуть на кнопку "Записаться".
#### Ожидаемый результат: Некоторые поля заполнены неверно.
#### №22
1. В поле ввода "Имя" ввести валидные данные.
2. В поле ввода "Номер телефона" ввести буквы.
3. В поле ввода "Электронная почта" ввести валидные данные.
4. Кликнуть на кнопку "Записаться".
#### Ожидаемый результат: Некоторые поля заполнены неверно.
#### №23
1. В поле ввода "Имя" ввести валидные данные.
2. В поле ввода "Номер телефона" ввести спецсимволы.
3. В поле ввода "Электронная почта" ввести валидные данные.
4. Кликнуть на кнопку "Записаться".
#### Ожидаемый результат: Некоторые поля заполнены неверно.
#### №24
1. В поле ввода "Имя" ввести валидные данные.
2. В поле ввода "Номер телефона" валидные данные.
3. В поле ввода "Электронная почта" ввести общее количество символов больше допустимого.
4. Кликнуть на кнопку "Записаться".
#### Ожидаемый результат: Некоторые поля заполнены неверно.
#### №25
1. В поле ввода "Имя" ввести валидные данные.
2. В поле ввода "Номер телефона" валидные данные.
3. В поле ввода "Электронная почта" ввести данные на кириллице.
4. Кликнуть на кнопку "Записаться".
#### Ожидаемый результат: Некоторые поля заполнены неверно.
#### №26
1. В поле ввода "Имя" ввести валидные данные.
2. В поле ввода "Номер телефона" валидные данные.
3. В поле ввода "Электронная почта" ввести менее одного символа, не считая доменного адреса.
4. Кликнуть на кнопку "Записаться".
#### Ожидаемый результат: Некоторые поля заполнены неверно.
#### №27
1. В поле ввода "Имя" ввести валидные данные.
2. В поле ввода "Номер телефона" валидные данные.
3. В поле ввода "Электронная почта" ввести адрес почты без символа @.
4. Кликнуть на кнопку "Записаться".
#### Ожидаемый результат: Некоторые поля заполнены неверно.

## Перечень используемых инструментов ##
- IntelliJ IDEA - среда для работы с программным кодом при написании автотестов.
- Java 11 - автотесты будут написаны на этом языке программирования.
- Gradle - для сборки проекта на языке Java и управления зависимостями.
- Lombok (опционально) - библиотека для сокращения написания программного кода.
- Selenide - фреймворк для автотестирования GUI.
- Rest Assured - библиотека для автотестирования REST API.
- Faker - библиотека для генерации пользовательских данных.
- Docker - (опционально) среда для изолированного развёртывания тестовых баз данных и работы с окружением.
- Allure - фреймворк для создания лаконичных и информативных отчётов о тестировании.
- Git и GitHub - для управления версиями тестируемой среды и предоставления удалённого доступа.

## Перечень необходимых разрешений, данных и доступов ##
1. Резрешение на тестирование сайта от владельца.
2. Доступ к технической документации сайта.
3. Доступ к API для проверки успешности запросов на сервер.
4. Доступ к базе данных для проверки успешной реализации тестов.

## Перечень и описание возможных рисков при автоматизации ##
- Отсутствие технической документации.
- Падение тестов из-за изменения структуры сайта.
- Сложность поиска локаторов элементов.
- Автотесты не могут проверить графический интерфейс тестируемой среды.
- Автотесты могут утратить актуальность и потребовать доработки при внесении изменений в тестируемую среду.
- Ложные срабатывания по отправке форм.

## Перечень необходимых специалистов для автоматизации ##
Один Инженер по тестированию.

## Интервальная оценка с учётом рисков в часах ##
50 часов