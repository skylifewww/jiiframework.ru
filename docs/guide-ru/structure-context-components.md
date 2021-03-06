# Компоненты контекста

Набор компонентов контекста зависит от того, где он применяется. Самый распространённый вариант - это запрос пользователя,
для него мы и рассмотрим встроенный набор компонентов.

Как и у компонентов приложения, каждый компонент приложения имеет свой уникальный ID, который позволяет идентифицировать
его среди других различных компонентов в одном и том же контексте. Вы можете получить доступ к компоненту следующим образом:

```js
    actionIndex: function(context) {
        context.ComponentID
    }
```

## Встроенные компоненты запроса

Ниже представлен список встроенных компонентов запроса. Вы можете конфигурировать их также как и другие компоненты в
секции `context` в конфигурационном файле.

* [[Jii.base.Response|response]]: представляет собой данные от сервера, которые будет направлены пользователю.
  Более детальная информация представлена в разделе [Ответы](runtime-responses);
* [[Jii.base.Request|request]]: представляет собой запрос, полученный от конечных пользователей.
  Более детальная информация представлена в разделе [Запросы](runtime-requests);
* [[Jii.user.WebUser|user]]: представляет собой информацию аутентифицированного пользователя. 
  Более детальная информация представлена в разделе [Аутентификация](security-authentication);
