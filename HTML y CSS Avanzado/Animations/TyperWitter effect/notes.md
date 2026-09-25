Tema

TyperWritter

🎯 Idea clave (3-5 líneas)

¿Qué hace y cuándo usarlo?

es una animacion que "hace ver" que se esta escribiendo el texto en vivo. tambien podemos usar un filter: drop-shadow para ponerle capas de color y hacerlo ver como un color neon.

⚙️ Sintaxis básica

animation: titilart .40s infinite alternate;

filter: drop-shadow(0px 0px 15px #fff9)
    drop-shadow(0px 0px 2px #fff9) drop-shadow(0px 0px 12px #fff9)
    drop-shadow(0px 0px 1px #fff9);

🧪 Ejemplo rápido

.text-container{
    display: flex;
    flex-direction: column;
    height: 50vh;
    justify-content: space-evenly;
    align-items: center;
    margin: auto;
    filter: drop-shadow(0px 0px 15px #fff9)
    drop-shadow(0px 0px 2px #fff9) drop-shadow(0px 0px 12px #fff9)
    drop-shadow(0px 0px 1px #fff9);
}

.text{
    color: #fff;
    letter-spacing: 4px;
    animation: grow 2s both steps(7);
    overflow: hidden;
    position: relative;
}

.text::selection{
    background-color: transparent;
}

.text::before{
    content: '';
    width: 1px;
    height: 100%;
    background-color: #fff;
    position: absolute;
    right: 0;
    border-radius: 4px;
    animation: titilart .40s infinite alternate;
}

@keyframes grow{
    from{
        width: 0%;
    }

    to{
        width: 100%;
    }
}

@keyframes titilar{
    from{
        opacity: 0;
    }

    to{
        opacity: 1;
    }
}

❌ Error que cometí

ninguno

✅ Solución

repasar