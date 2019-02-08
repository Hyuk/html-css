# CSS GRID

* [Website - A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)
* [Youtube - CSS Grid Layout Crash Course](https://www.youtube.com/watch?v=jV8B24rSN5o)
* [Example]()

## Properties

* 하위 엘레멘트를 그리드 형식으로 표현한다.
```css
div {
    display: grid;
}
```

* 하위 엘레멘트를 비율에 따라 나눈다.
```css
div {
    grid-template-columns: 70% 30%;
}
```

* 하위 엘레멘트의 열 간격을 조정한다.
```css
div {
    grid-column-gap: 1em;
}
```

* 하위 엘레멘트의 행 간격을 조정한다.
```css
div {
    grid-row-gap: 1em;
}
```

* 하위 엘레멘트의 행열 간격을 조정한다.
```css
div {
    grid-gap: 1em;
}
```

* 하위 엘레멘트를 비율에 따라 나눈다.
```css
div {
    grid-template-columns: 1fr 2fr 1fr;
}
```

* 하위 엘레멘트를 반복된 비율에 따라 나눈다.
```css
div {
    grid-template-columns: repeat(4, 1fr 2fr);
}
```

* 하위 엘레멘트의 세로값을 지정한다.
```css
div {
    grid-auto-rows:100px;
}
```

* 하위 엘레멘트 세로값의 최소값을 지정한다.
```css
div {
    grid-auto-rows: minmax(100px, auto);
}
```

* 하위 엘레멘트의 좌우 정렬을 지정한다.
```css
div {
    justify-items: start;
}

div {
    justify-items: center;
}

div {
    justify-items: end;
}

div {
    justify-items: stretch;
}
```

* 하위 엘레멘트의 상하 정렬을 지정한다.
```css
div {
    align-items: start;
}

div {
    align-items: center;
}

div {
    align-items: end;
}

div {
    align-items: stretch;
}
```

* 해당 엘레멘트의 좌우 정렬을 지정한다.
```css
div {
    justify-self: start;
}

div {
    justify-self: center;
}

div {
    justify-self: end;
}

div {
    justify-self: stretch;
}
```

* 해당 엘레멘트의 상하 정렬을 지정한다.
```css
div {
    align-self: start;
}

div {
    align-self: center;
}

div {
    align-self: end;
}

div {
    align-self: stretch;
}
```

* 해당 엘레멘트의 가로영역을 지정한다.
```css
div {
    grid-column: 1/3
}
```

* 해당 엘레멘트의 세로영역을 지정한다.
```css
div {
    grid-row: 1/3
}
```