## **Transformative Properties**
## Level 6.b9

#### Neu Gelerntes:
Bilder bearbeiten mit transform:

[comment]: <> (Was wurde gelernt und wie funktioniert die Technik?)

#### HTML-Code:
```
<!-- The "transform" CSS is used to modify elements. -->
<!-- Use it to rotate, scale, or translate (move) tags! -->

<style>
    #imgA {
        /* Rotating requires a unit, like "deg". */
        /* "deg" is shorthand for "degrees". */
        transform: rotate(45deg);
    }
    #imgB {
        /* Scaling multiplies the size by a value! */
        transform: scale(0.5);
    }
    #imgC {
        /* Elements can be "translate"d in X and Y. */
        /* "translate" is another word for "move". */
        transform: translateY(100px);
    }
    #imgD {
        /* This is how to do multiple transformations at once. */
        transform: rotate(-45deg) scale(1.5);
    }
    #imgE {
        /* Add a transform property to this element: */
        transform: translateX(350px);
    }
    #imgF {
        /* Add a transform property to this element: */
        transform: scale(0.05);
    }
    #imgG {
        /* Add a transform property to this element: */
        transform: scale(4) translateY(100px);
    }
    #imgH {
        /* Add a transform property to this element: */
        transform: rotate(70deg) scale(2);
    }
    img {
        margin-bottom:20%;
        width:20%;
    }
</style>
<img id="imgA" src="/file/db/thang.type/5466d4f2417c8b48a9811e87/portrait.png">
<img id="imgB" src="/file/db/thang.type/52e95b4222efc8e70900175d/portrait.png">
<img id="imgC" src="/file/db/thang.type/55652fb3b9effa46a1f775fd/portrait.png">
<img id="imgD" src="/file/db/thang.type/55e1a6e876cb0948c96af9f8/portrait.png">
<img id="imgE" src="/file/db/thang.type/575848b522179b2800efbfbf/portrait.png">
<img id="imgF" src="/file/db/thang.type/57588f09046caf2e0012ed41/portrait.png">
<img id="imgG" src="/file/db/thang.type/529ec584c423d4e83b000014/portrait.png">
<img id="imgH" src="/file/db/thang.type/52e9adf7427172ae56002172/portrait.png">
```
![image](lvl6_b9.png)