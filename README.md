# Шпаргалка markdown

## Выделение текста

Вы можете выделять текст в markdown с помощью символов `_` или `*`. Например:

Пример _курсива_ и **жирного** текста.

## Заголовки

Заголовки можно создавать с помощью символа `#`. Чем больше `#`, тем меньше заголовок. Например:

# Заголовок первого уровня
## Заголовок второго уровня
### Заголовок третьего уровня

## Выделение кода

Чтобы выделить текст как код, поместите его в тройные кавычки `````. 


```

mkdir my_project
cd my_project
git init

```
Это лишь некоторые функции markdown. 


# Шпаргалка - Основная инф/ из уроков по "ХЕШ", статусов файлов и оформления сообщений к Коммит.

## "Хеш"

```
### _Хеш_ - это *идентификатор* коммита в простонародье _"Хеш коммита"_


_Информация о коммите_ - это набор данных, когда был сделан коммит, содержание файлов репозитория на момент коммита и ссылка на предыдущий или родительский коммит.

_Хеширование_ - это способ преобразовать набор данных и получить их "отпечаток".

_.git_ - хеширует информацию о коммите с помощью алгоритма *SHA-1* и получения для каждого коммита своего уникального _хеш_ - результата *хеширование*. 

_Обычно хеш_ - это короткая (40 символов в случае с SHA-1) строка, которая состоит из цифр 0-9 и латинских букв A - F (Неважно в каком регистре).

_Хеш_ - основной идентификатор коммита и позволяет узнать его автора, дату и содержание закоммиченных файлов.

_Хеш_ - хранится в скрытой папке _*.git*_. 

```