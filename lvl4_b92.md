## **Lichtung des Unheils**
## Level 4.b92

#### Neu Gelerntes:
<b>-</b>

[comment]: <> (Was wurde gelernt und wie funktioniert die Technik?)

#### JavaScript-Code:
```js
while (true) {
    var flag = hero.findFlag("green");
    var fla = hero.findFlag("black");
    if (flag) {
        hero.pickUpFlag(flag);       
        var enemy = hero.findNearestEnemy();
        if (enemy) {
            if (hero.isReady("cleave")) {
                hero.cleave(enemy);       
            }
        } 
    }
    if (fla) {
        hero.pickUpFlag(fla);
        if (hero.isReady("warcry")) {
            hero.warcry();
        }
    }
    else {
        var enemy = hero.findNearestEnemy();
        if (enemy) {
            hero.attack(enemy);
        }        
    }
}
```
![image](lvl4_b92.png)