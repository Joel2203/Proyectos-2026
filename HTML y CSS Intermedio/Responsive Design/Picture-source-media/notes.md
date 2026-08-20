Tema

Picture-source-media

🎯 Idea clave (3-5 líneas)

¿Qué hace y cuándo usarlo?

es una forma distinta de decir que imagen se dbe usar en cada tamaño de resolucion que hay pero a la vez tambien hay la forma de cambiar los formatos de la imagen poniendo type=""

⚙️ Sintaxis básica

<!-- <picture>
<source media = (la reoslucion de la imagen que se pondra cuando haya el tamaño) srcset=(la iamgen)>
<img (imagen la primera en salir)>
</picture> -->

🧪 Ejemplo rápido

<!-- <body>
    <picture>
        <source media="(max-width: 400px)" srcset="img/joel.jpg">
        <source media="(max-width: 600px)" srcset="img/bmwmedium.jpg">
        <img src="img/batmanLarge.jpg">
    </picture>
</body> -->

❌ Error que cometí

ninguno

✅ Solución

practicar