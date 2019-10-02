# ru.reactjs.org

Этот репозиторий содержит исходный код и содержимое сайта [ru.reactjs.org](https://ru.reactjs.org/).

## Начало

### Предварительные требования

1. Git
1. Node: любая версия 8.x, начиная с 8.4.0 или выше
1. Yarn: Смотрите [сайт Yarn с инструкциями по установке](https://yarnpkg.com/lang/en/docs/install/)
1. Сделать форк этого репозитория (для предложения изменений)
1. Копия [репозитория ru.reactjs.org](https://github.com/reactjs/ru.reactjs.org) на вашем компьютере

### Установка

1. `cd ru.reactjs.org` для перехода в директорию проекта
1. `yarn` для установки npm-зависимостей проекта

### Запуск проекта локально

1. `yarn dev` для старта сервера в режиме разработки с поддержкой перезагрузки на лету (на основе [Gatsby](https://www.gatsbyjs.org))
1. `open http://localhost:8000` откроет сайт в вашем браузере по умолчанию

## Помощь проекту

### Рекомендации

Документация разделена на несколько частей, с разными характером и целями. Если вы планируете написать больше, чем несколько фраз, вам может быть полезно ознакомиться с [рекомендациями для участия](https://github.com/reactjs/ru.reactjs.org/blob/master/CONTRIBUTING.md#guidelines-for-text) и его конкретными разделами.

### Создание ветки

1. `git checkout master` из любой папки в вашей локальной копии репозитория `ru.reactjs.org`
1. `git pull origin master`, чтобы убедиться, что у вас самая последняя версия кода
1. `git checkout -b the-name-of-my-branch` (замените `the-name-of-my-branch` на подходящее имя) для создания ветки

### Внесение изменений

1. Следуйте инструкциям из раздела «Запуск проекта локально»
1. Сохраните файлы и проверьте в вашем браузере
  1. Изменения в React-компонентах внутри `src` применяются на лету
  1. Изменения в markdown-файлах внутри `content` применяются на лету
  1. При работе с плагинами может понадобится удаление папки `.cache` и перезапуск сервера

### Проверка изменений

1. По возможности проверьте визуальные изменения во всех последних версиях распространённых браузеров: и настольных, и мобильных.
1. Запустите `yarn check-all` из корня проекта. (Это запустит Prettier, ESLint и Flow.)

### Отправка изменений

1. `git add -A && git commit -m "Мой текст"` (замените `Мой текст` на подходящее сообщение, например `Fix header logo on Android`) для сохранения ваших изменений
1. `git push my-fork-name the-name-of-my-branch`
1. Перейдите на [страницу репозитория ru.reactjs.org](https://github.com/reactjs/ru.reactjs.org) — вы должны увидеть вашу веткy.
1. Следуйте инструкциям на GitHub.
1. По возможности добавьте скриншот с наглядными изменениями. Как только вы сделаете PR, автоматически будет создан Netlify-билд, так что люди смогут посмотреть ваши изменения.

## Перевод

Если вы заинтересованы в переводе `reactjs.org`, ознакомьтесь с текущим прогрессом перевода на [isreacttranslatedyet.com](https://www.isreacttranslatedyet.com/).

## Решение проблем

- `yarn reset` для очистки локального кеша

## Лицензия

Контент на [ru.reactjs.org](https://ru.reactjs.org/) распространяется по лицензии CC-BY-4.0, как указано в файле [LICENSE-DOCS.md](https://github.com/open-source-explorer/reactjs.org/blob/master/LICENSE-DOCS.md).
