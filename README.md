# Оформление README.md
*Запомни, чтобы не забыть*

---

1. ###Оформление заголовков
```md
# H1 — заголовок первого уровня, самый большой
## H2 — заголовок второго уровня, поменьше
### H3
#### H4
##### H5
###### H6 — заголовок шестого уровня, самый маленький 
```

---

###2. Создание черты
```md
#### Заголовок 4

Текст над чертой

---

Текст под чертой
```

---

###3. Перенос строк
```md
Текст до переноса⋅⋅  
Текст после переноса <br>
Текст после второго переноса
```
Чтобы начать новый параграф, в конце предыдущей строки должно стоять два символа переноса. Для этого нужно нажать Enter два раза.

---

###4. Выделение текста
```md
Курсив — это *звёздочки* или _подчёркивания_.
Полужирный шрифт — двойные **звёздочки** или двойные __подчёркивания__.
Можно совместить выделение **звёздочки и _подчёркивания_**.
~~Зачёркнутый текст.~~
```

---

###5. Списки
```md
1. Первый пункт нумерованного списка.
2. Второй пункт.

* первый пункт ненумерованного списка;
* второй пункт ненумерованного списка

- первый пункт ненумерованного списка;
- второй пункт ненумерованного списка
```

---

###6. Ссылки
```md
[Яндекс](https://www.yandex.ru)

Также можно добавить ссылке тайтл (от англ title — «название», «заголовок»). Тайтл — это всплывающая подсказка, которая появляется при наведении мыши на ссылку. Тайтл нужно заключить в кавычки и указать внутри скобок после адреса.
[Яндекс](https://www.yandex.ru "Я Yandex!")
```

---

###7. Код
Чтобы оформить текст как код, нужно окружить его тройками косых кавычек — грависов. После первой тройки грависов указывают язык программирования, на котором написан код. В маркдауне есть поддержка синтаксиса почти всех популярных языков и инструментов.
```md
```bash
ls - la
```
```html
<h1>А я просто текст</h1>
``` 
```
