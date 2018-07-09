# CSS style guide

## class или id
Всегда используем class, даже если элемент один на странице.

## Отступы
Для отступов используем двойной пробел. Если пользуетесь табуляцией — настройте правильно свой текстовый редактор.

## Имена классов
Имена классов в lowercase, через «-».

Неправильно:
```
.Item {}
.item_info {}
.itemInfo {}
```

Правильно:
```
.item {}
.item-info {}
```

## Как много классов нужно?
Как можно меньше, если есть элемент-контейнер, то внутренние элементы имеют класс, только по необходимости.

Неправильно:
```
<nav class="menu">
  <a class="menu-item" href=""></a>
  <a class="menu-item menu-item-selected" href=""></a>
  …
</nav>  
```

Правильно:
```
<nav class="menu">
  <a href=""></>
  <a class="selected" href=""></>
  …
</nav>  
```

## Таблицы или div
Мы используем div, до тех пор пока это целесообразно.

## Float, flexbox
И то и то другое.

## CDN
Мы не используем CDN, все внешние классы должны быть включены в проект.

## CSS фреймворк
Мы используем [http://npmjs.com/sega3](SEGA3).

## Препроцессоры
Мы используем less (пока).







