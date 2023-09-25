## **Wonderglade**
## Level 4.b80

#### Neu Gelerntes:
<b>-</b>

[comment]: <> (Was wurde gelernt und wie funktioniert die Technik?)

#### JavaScript-Code:
```js
while (true) {
    var item = hero.findNearestItem();
    if (item) {
        if (item.type !== "gem") {
            hero.moveXY(item.pos.x, item.pos.y);
        }
    }
}
```
![image](lvl4_b80.png)