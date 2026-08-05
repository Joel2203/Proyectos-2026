Tema

Trancisiones

🎯 Idea clave (3-5 líneas)

¿Qué hace y cuándo usarlo?

nos da posibilidad de animar objetos o elementos dentro de nuestra web

⚙️ Sintaxis básica

1: transition-(property,duration,delay,timing-function) puede ir cualquiera de estos. pero hay mas

2:transition: left 1s cubic-bezier(1,0,.83,.82) 2s; esto es un todo en uno 1re: de donde parte, 2do: duracion de la trancision, 3ro:curva, 4to: delay

3:transition-property:color,background,margin. es como meter las propiedas que van a trancisionar

🧪 Ejemplo rápido

```css
body{
    margin: 0;
    font-family: sans-serif;
    height: 100vh;
}

.box{
    width: 200px;
    height: 200px;
    background-color: #f00;
    margin-top: 50px;
    position: relative;
    transition-property:left ;
    transition-duration:2s ;
    transition-delay: 3s;
    transition-timing-function:ease-in ;
    left: 0;
}

body:hover .box{
    left: 800px;
}

.box--color{
    width: 200px;
    height: 200px;
    background-color: #f00;
    margin: auto;
    margin-top: 50px;
    text-align: center;
    transition-property:color,background ;
    transition-duration:2s ;
    transition-delay: 4s;
    color: #000;
}

body:hover .box--color{
    color: #fff;
    background-color: #00f;
}

.box--curva{
    width: 200px;
    height: 200px;
    background-color: #0f0;
    margin-top: 50px;
    position: relative;
    transition: left 1s cubic-bezier(1,0,.83,.82) 2s;
    left: 0;
}

body:hover .box--curva{
    left: 800px;
}
```

❌ Error que cometí

me equivocaba en cuanto a cosas en las propiedad, errores teoricos

✅ Solución

practicar