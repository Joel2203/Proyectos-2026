Tema

scrol animation

🎯 Idea clave (3-5 líneas)

¿Qué hace y cuándo usarlo?

es para estilizar cuando hacemos uso del scrol y el scroll puede  tener otro scroll

⚙️ Sintaxis básica

.container{
    scroll-timeline: --containerScroll block;
    overflow-y: scroll;
    height: 50vh;
}
se hace el segundo scroll aparte se define como trabjara

🧪 Ejemplo rápido

.crecedor{
    height: 200vh;
}

.container{
    scroll-timeline: --containerScroll block;
    overflow-y: scroll;
    height: 50vh;
}

.box{
    background-color: #fff;
    border: 8px solid #48e;
    padding: 6px;
    border-radius: 39px;
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
}

.barra{
    padding: 40px;
    background-color: #48e;
    border-radius: 36px;
    width: 10%;
    animation-name: llenar-barra;
    animation-fill-mode: both;
    animation-timing-function: linear;
    animation-timeline: --containerScroll;
}

❌ Error que cometí

nada

✅ Solución

practicar