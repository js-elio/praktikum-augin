## **Agrippas Refaktoriert**
## Level 4.b58

#### Neu Gelerntes:
<b>-</b>

[comment]: <> (Was wurde gelernt und wie funktioniert die Technik?)

#### JavaScript-Code:
```js
function cleaveOrAttack(enemy) {
    if (hero.isReady("cleave")) {
        hero.cleave(enemy);        
    }
    else {
        hero.attack(enemy);
    }
}
while(true) {
    var enemy = hero.findNearestEnemy();
    if(enemy) {
        var distance = hero.distanceTo(enemy);
        if(distance < 5) {
            cleaveOrAttack(enemy);
        }
    }
}
```
![image](lvl4_b58.png)