<b>Смешные команды</b>
<p><b>1. Ветка и коммит</b></p>

```
git checkout -b wip
```
```
git add .
```
```
git commit -m "{Что делали}"
```
```
git push -u origin dev
```

<b><p>2. Удаленный сервер типо хз</p></b>

```
npm install -g live-server
```
```
live-server
```
<b><p>3. Виртуальная среда</p></b>

```
python -m venv "{название виртуальной среды}"
```
<p>В названии виртуальной среды как правило используется "env"</p>

<b><p>3. Пр 5 текст</p></b>
```
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    display: grid;
    grid-template-areas:
        'header header header'
        'nav main sidebar'
        'footer footer footer';
    grid-template-columns: 1fr 2fr 1fr;
    grid-template-rows: 80px 1fr 60px;
    height: 100vh;
    gap: 15px;
    padding: 15px;
    background: #f5f5f5;
}
header {
    grid-area: header;
    background: #3498db;
    color: white;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 1.5em;
    font-weight: bold;
}
nav {
    grid-area: nav;
    background: #2ecc71;
    padding: 15px;
}
main {
    grid-area: main;
    background: #ecf0f1;
    padding: 15px;
    display: flex;
    flex-direction: column;
    gap: 15px;
}
.article {
    background: white;
    padding: 10px;
    border-radius: 5px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}
.masonry {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-auto-rows: minmax(100px, auto);
    gap: 10px;
}
.masonry .grid-item {
    background: white;
    padding: 10px;
    border-radius: 5px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}
.masonry .wide {
    grid-column: span 2;
}
.masonry .tall {
    grid-row: span 2;
}
.masonry .large {
    grid-column: span 2;
    grid-row: span 2;
}
.masonry .small {
    grid-column: span 1;
    grid-row: span 1;
}
aside {
    grid-area: sidebar;
    background: #f39c12;
    padding: 15px;
    color: white;
}
footer {
    grid-area: footer;
    background: #e74c3c;
    color: white;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 1.2em;
}
```
