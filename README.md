# linthtml-config-htmlacademy
> Это стандартный конфигурационный файл для stylelint от [HTML Academy](https://htmlacademy.ru/).

## Установка

```bash
npm install htmllint-config-htmlacademy -D
```

## Использование

Если вы установили `linthtml-config-htmlacademy` локально в свой проект, jто просто примените его в конфигурационном файле `stylelint` вашего проекта:

```json
{
  "extends": "htmllint-config-htmlacademy"
}
```

### Расширение конфига

Просто добавьте ключ `"rules"` в ваш конфиг после `"extends": "linthtml-config-htmlacademy"`, а затем добавьте туда свои правила.

Например, если вы хотите изменить максимальную длину `line-max-len`, то нужно:

```json
{
  "extends": "stylelint-config-recommended",
  "rules": {
    "line-max-len": [
      true,
      120
    ]
  }
}
```
