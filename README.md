# Анализ кода JavaScript

Перед выполнением задания склонируй себе данный репозиторий. Ответы присылай в виде pull request.

## Задачи

После клонирования открой файл `index.html` и проверь как работает скрипт. Затем приступай к выполнению следующих задач.

### Комментарии
Прокоментируй каждую строку JavaScript-кода. Пиши комментарии как можно подробнее.

### querySelector
Загугли что за метод `querySelector()`. Разберись чем он отличается от `getElementById()`. Как думаешь какой из этих методов лучше использовать при разработке и почему?

### Математика
Объясни принцип работы этого участка кода
```
positionPercent += Math.ceil(Math.random() * 3)
```

1) Что означает `Math.random()`?
2) В каких ситуациях он бывает полезен?
3) Почему его результат умножается на 3? (три лишь для примера, на практике может быть любое нужное число)
4) Что означает `Math.ceil()`? Почему он использован в данном коде?

### setInterval
Объясни почему в данном коде использован `setInterval()` вместо `setTimeout()`?

Что будет, если в качестве второго параметра передать значение `0`?

### Доработки

У этого кода два очевидных бага:

1) машина выезжает вправо за край трассы
2) время гонки показывается в миллисекундах, а не секундах

Исправь оба этих бага. Для исправления первого читай про функцию в CSS [_calc()_](https://developer.mozilla.org/ru/docs/Web/CSS/calc())

### Настоящая гонка

Добавь на страницу еще одну машину. Обе машины должны быть на ходу.

Приглядись в свой код. Много ли в нём повторяющихся строчек? 

Прочитай про принцип программирования [DRY](https://www.google.com/search?q=dry+%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5&newwindow=1&ei=5ap8YI-vNPCprgSb0LTIAw&oq=dry+%D0%BF%D1%80%D0%BE%D0%B3&gs_lcp=Cgdnd3Mtd2l6EAMYADICCAAyBggAEBYQHjIGCAAQFhAeMgYIABAWEB46BwgAEEcQsANQsAVYsAVgzA1oAXACeACAAZ4BiAHwAZIBAzEuMZgBAKABAaoBB2d3cy13aXrIAQjAAQE&sclient=gws-wiz).

- Соответствует ли твой код этому принципу?
- Как можно улучшить код, чтобы он не повторялся?