# Установка зависимостей

Установить в проект следующие пакеты.

```bash
npm install --save-dev prettier husky lint-staged
```

## Интерграция плагинов .huskyrc и .lintstagedrc

Добавить в корень проекта фалы .huskyrc и .lintstagedrc с кодом настроек внутри (скопировать)

Ссылки на документацию по интеграции плагинов в популярные редакторы.
- [Prettier editor integration](https://prettier.io/docs/en/editors.html)
- [ESLint editor integration](https://eslint.org/docs/user-guide/integrations)

## Настройки VSCode

Для комфортной работы, после установки плагинов, нужно добавить несколько
настроек редактора в Settings VSCode для автосохранения и форматирования файлов.

```json
{
  "files.autoSave": "onFocusChange",
  "editor.formatOnSave": true,
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true
  }
}
```

## Нормализация стилей
   https://github.com/Vitamin-JS/React-init-project/blob/main/README.md

