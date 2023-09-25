## **Animania**
## Level 6.b10

#### Neu Gelerntes:
Animationen mit animation:

[comment]: <> (Was wurde gelernt und wie funktioniert die Technik?)

#### HTML-Code:
```
<style>
    #imageA {  
        animation:slide 5s 99;
    }
    #imageB {
        animation:myAnim 0.1s 10;
    }
    /* keyframes is a special CSS "at-rule"! */
    /* It tells the browser this is not just CSS */
    @keyframes slide {
        from {
            transform: translateX(300%);
            background-color:rgb(0, 255, 0);
        }
        to {
            transform: translateX(-300%);
            background-color:rgb(255, 0, 0);
        }
    }
    @keyframes myAnim {
        from {
            /* Add properties for the start. */
            transform: scale(0.5);
        }
        to {
            /* Add properties for the end result. */
            transform: scale(5);
        }
    }
</style>
<img id="imageA" src="/file/db/thang.type/529ab1a24b67a988ad000002/portrait.png">
<img id="imageB" src="/file/db/thang.type/52cee45a76ebd5196b00003a/portrait.png">
```
![image](lvl6_b10.png)