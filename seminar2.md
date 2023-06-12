## Туториал Git
1. Инициализируем репозиторий командой 
```
git init
```
2. Добавляем файл к отслеживанию командой 
```
git add "namefile"
```
3. Добавляем файл к отслеживанию ``` "-a" ``` и Сохраняем изменения с сообщением ``` "-m" ``` командой 
```
git commit -am "massage"
```
4. Чтобы посмотреть историю записей используем 
```
git log
```
5. Чтобы посмотреть различия мужду последней записью и файлом используем 
```
git diff
```
6. 
```
git add .
```
 используется для автоматического отслеживания файлов
7. чтобы посмотреть статус отслеживания используем 
```
git status
```
8. Для перемещения между фиксациями используем
```
git checkout number
```



# Туториал по MarkDown





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



