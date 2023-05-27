# Как сделать пул-реквест
Пул-реквест — способ предложить свои правки в чужой проект на Гитхабе. Обычно для этого используют специальные программы, например, гит или Гитхаб КЛИ. Но простые пул-реквесты можно сделать из браузера. Этот способ подойдёт, чтобы предложить свой текст в Open Prompting.

Допустим, вы хотите предложить новый рецепт. Для этого:
1. Сделайте копию нашего проекта.
2. Добавьте рецепт в свою копию.
3. Отправьте пул-реквест.

Тогда мы скопируем новую статью в нашу базу знаний.

Теперь подробнее.

### Шаг 1. Создайте копию репозитория Open Prompting

https://github.com/kkhrv/Knowledge-Base/assets/25165356/32e20e72-6e07-4020-bae8-6f099ae92ed6

1. Сделайте форк — копию базы знаний Open Promting. Для этого нажмите кнопку Fork в верхнем правом углу или перейдите по ссылке:<br>[скопировать базу знаний](https://github.com/Open-Prompting/Knowledge-Base/fork)

2. В открывшемся окне нажмите Create fork.

Гитхаб попросит подождать, а потом покажет страницу с вашей копией репозитория.

### Шаг 2. Добавьте рецепт
https://github.com/kkhrv/Knowledge-Base/assets/25165356/3b5bcbdc-1532-43eb-85c9-524a177b56d8

1. В скопированном репозитории откройте папку с рецептами: content → recipes.

2. Создайте папку и файл для нового рецепта. Нажмите Add file → Create new file. В появившемся окне наберите `название-рецепта/readme.md`. Название рецепта мы пишем на английском. Например, если рецепт о поиске синонима, назовите рецепт «synonym». Изменить название можно позже.

3. В поле ввода вставьте шаблон рецепта:

````
# Название рецепта
[ситуация]

## Что сделать
1. [Шаг первый]
2. [Шаг второй]
```
[Промт]
```
Результат:
[ссылка на скриншот]()
[Трудности и опасности]
````

Добавлять скриншоты в рецепт не обязательно. Иллюстрации мы сделаем за вас. Если скриншот всё же нужен, его проще добавить на следующем этапе.

4. Отредактируйте рецепт и нажмите кнопку Commit changes. В поле Commit message можно написать пару слов о рецепте — но это не обязательно.

### Шаг 3. Отправить пул-реквест

https://github.com/kkhrv/Knowledge-Base/assets/25165356/4e8586bc-0498-4f61-9732-60cc94ad3474

1. На странице с вашей копией репозитория откройте выкладку Pull requests и нажмите New pull request.
2. Вы увидите меню с двумя выпадающими списками. Проверьте:
   * В левом меню должен быть выбран репозиторий Open-Prompting / Knowledge-Base.
   * В правом — ваша копия. Её название начинается с имени вашего аккаунта.
3. Нажмите кнопку Create pull request.
4. В появившемся окне опишите материал, который предлагаете. В это же окно можно перетянуть файл со скриншотом — если считаете, что он необходим.

Это всё.

Мы увидим ваш запрос и ответим: предложим правки или сразу опубликуем материал. В любом случае вы получите уведомление на Гитхабе.