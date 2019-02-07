# Fstrk.io email templates

Powered by [mjml](https://mjml.io/) responsive email framework.

### Установка

```
$ git clone git@github.com:fstrk-io/fstrk-emails.git
$ cd fstrk-emails && npm i
```

### Режим для разработки (hot reload)

```
$ MJML_FILE=<NAME> npm run watch
```

Где `<NAME>` — это название редактируемого шаблона в `./src/templates`.

### Пересобрать шаблон

```
$ MJML_FILE=<NAME> npm run build
```