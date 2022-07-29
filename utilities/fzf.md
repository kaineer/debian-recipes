# fzf

Используется для выбора одного или нескольких элементов из списка.

## Установка

 * Из пакета:

```sh
sudo apt install fzf
```

 * [Релиз на github](https://github.com/junegunn/fzf/releases/tag/0.31.0)

## Пример использования

```sh
ls | fzf                   # Выбрать имя файла из каталога и вывести в stdout
cat package.json | \       # Выбрать имя скрипта из сохранённых в package.json
  jq '.scripts | keys | join("\n") -r'

# TODO add some more
```
