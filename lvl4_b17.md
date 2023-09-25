## **Knochenheiler**
## Level 4.b17

#### Neu Gelerntes:
<b>-</b>

[comment]: <> (Was wurde gelernt und wie funktioniert die Technik?)

#### JavaScript-Code:
```js
while(true) {
    if (hero.canCast("regen")) {
        var bernardDistance = hero.distanceTo("Bernard");
        if(bernardDistance < 10) {
            // Bernard braucht eine Regeneration!
            hero.cast("regen", "Bernard");
        }
        
        // Benutze `if` und `distanceTo` ("Entfernung zu") um" Chandra" zu regenerieren
        // wenn Sie weniger als 10m entfernt ist.
        var chandraDistance = hero.distanceTo("Chandra")
        if (chandraDistance < 10) {
            hero.cast("regen", "Chandra");
        }
        }
    else {
        // Wenn du die Fähigkeit "regen" ("regenerieren") gerade nicht ausführst benutze `if` und `distanceTo` ("Entfernung zu")
        // um Gegner anzugreifen die Näher sind als hero.attackRange.
        var enemy = hero.findNearestEnemy();
        if (enemy) {
            
        
        var distance = hero.distanceTo(enemy);
        if (distance < hero.attackRange) {
            hero.attack(enemy);
        }
        }
    }
}
```
![image](lvl4_b17.png)