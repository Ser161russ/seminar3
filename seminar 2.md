# Справка (туториал) по основам системы контроля версии GIT



## Как инициализировать GIT
**Чтобы инициализировать репозиторий, необходимо происать в терминале следующую команду:**

```
git init
```
### Как сделать первое сохранение в GIT
***Выполним следующую команду, ее используем чтоб GIT обратил на нее внимание и начал ее отслживать:***
```
git add
```
***Дальше можем проверить начал ли GIT следить за документом. Для этго запустим команду:***
```
git status
```
***Теперь можем создать наше первое сохранение, команда:***
```
git commit -m"init:start new project"
```



# Туториал(справка)для рабты с яыком разметки  MarckDown #


## Заголовки 








## Цитаты








## Исходный код
В чистом Маркдауне блоки кода отбиваются 4 пробелами в начале каждой строки.

Но в GitHub-Flavored Markdown (сокращенно GFM) есть более удобный способ: ставим по три апострофа (на букве Ё) до и после кода. Также можно указать язык исходного кода.

```html
<nav class="nav nav-primary">
  <ul>
    <li class="tab-conversation active">
      <a href="#" data-role="post-count" class="publisher-nav-color" data-nav="conversation">
        <span class="comment-count">0 комментариев</span>
        <span class="comment-count-placeholder">Комментарии</span>
      </a>
    </li>
    <li class="dropdown user-menu" data-role="logout">
      <a href="#" class="dropdown-toggle" data-toggle="dropdown">
        <span class="dropdown-toggle-wrapper">
          <span>
            Войти
          </span>
        </span>
        <span class="caret"></span>
      </a>
    </li>
  </ul>
</nav>
```

Самое приятное, что в коде не нужно заменять угловые скобки `< >` и амперсанд `&` на их html-сущности.






## Таблицы


