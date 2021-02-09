### Задание по React

Нужно сделать одностраничное приложение, которое помогает найти ревьюера.

Функционал:
- кнопка настроек, по клику на нее можно переключать видимость настроек.
- в настройках 3 поля:

    1. login для ввода логина текущего юзера
    2. repo для указания репозитория для которого ищем ревьюера
    3. blacklist для указания списка login-ов, кто не должен быть ревьюером
- состояние настроек сохранять в localStorage
- для генерации ревьюера нужна кнопка поиска ревьюера, по клику на которую должен быть выбран рандомный ревьюер из списка контрибьютеров репзитория указанный в пункте 2 настроек, учитывая blacklist пункта 3.
- при генерации ревьюера показываем текущего пользователя и перебираемые вами пользователи для ревью.

Дока по API https://docs.github.com/en/rest.
[Пример, как может выглядеть блок с ревьюером](https://github.com/AndreyGladkov/hh-school-react-2021/blob/main/review.png).

Макетов нет, можно делать на ваш вкус и цвет, включайте фантазию).
Оцениваться будет реализация, а не визуальная часть.
При написании используем только функциональные компоненты, класс компоненты запрещены.


### Задание по Redux

Добавить redux в приложение для управления состоянием приложения. Добавить кастомную middleware для асинхронных походов в API. Сохранять в store сущности ответов от API.


### `yarn`

Устанавливает зависимости

### `yarn start`

Запускает `watch` сборки, что бы при разработке. Не запускать билд после изменений кода.
Так же запускает сервер для разрабоки доступен в браузере по URL [http://localhost:3000](http://localhost:3000).
Он поддерживает hot reload.

### Дока по сборке
Проект сделан с помощью: [Create React App](https://github.com/facebook/create-react-app).
