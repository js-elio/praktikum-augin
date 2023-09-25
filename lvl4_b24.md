## **Backwoods Standoff A**
## Level 4.b24

#### Neu Gelerntes:
<b>-</b>

[comment]: <> (Was wurde gelernt und wie funktioniert die Technik?)

#### JavaScript-Code:
```js
while(true) {
    var enemy = hero.findNearestEnemy();
    // Use an if-statement with isReady to check "cleave":
    if (hero.isReady("cleave")) {
        hero.cleave(enemy);        
    }
        // Cleave!
        else {
            hero.attack(enemy);
        }
}
```
![image](lvl4_b24.png)