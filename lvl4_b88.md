## **Warte auf Verstärkung**
## Level 4.b88

#### Neu Gelerntes:
<b>-</b>

[comment]: <> (Was wurde gelernt und wie funktioniert die Technik?)

#### JavaScript-Code:
```js
while(true) {
    var flag = hero.findFlag();
    var enemy = hero.findNearestEnemy();
    if (flag) {
        hero.pickUpFlag(flag);
    }
    else if (enemy) {
        if (hero.isReady("cleave")) {
            hero.cleave(enemy);            
        }
        else {
            hero.attack(enemy);
        }
    }
}
```
![image](lvl4_b88.png)