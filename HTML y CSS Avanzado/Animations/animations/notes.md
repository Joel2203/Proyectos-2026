Tema

animations

🎯 Idea clave (3-5 líneas)

¿Qué hace y cuándo usarlo?

es lo mismo que la trancision pero aca seremos mas detallados y especificos, podremos como un apartado llamada @kerframes donde ahi pondremos como se ejecutara la animacion y arriba en el elemento solo definimos delay, time, direction & count

⚙️ Sintaxis básica

.elemento a animar{
    animation-name: nombre que le dimos al keyframes;
    animation-duration: 3s;
    animation-delay: 2s;
    animation-fill-mode: both[aca significa que empieza desde from], forward inicia desde lo que  definio el elemento;
    animation-iteration-count: (infinite, o ponemos el nro de veces que queremo que se repita);
    animation-direction: (alternate-reverse:esto para que temrine y vuelva al inciio automaticamente, alternate: para que haga la animacion al reves);
}

@keyframes nombre de la animacion {
    from{
        lo que hara al empezar
    }

    to{
        lo que ghara al terminar
    }
}

🧪 Ejemplo rápido

.barra{
    padding: 40px;
    background-color: #48e;
    border-radius: 36px;
    width: 10%;
    transition: width 4s steps(6);
    animation-name: llenar-barra;
    animation-duration: 3s;
    animation-delay: 2s;
    animation-fill-mode: both;
    animation-iteration-count: infinite;
    animation-direction: alternate-reverse;
}

.barra:active{
    animation-play-state: paused;
}

@keyframes llenar-barra {
    from{
        width: 30%;
        background-color: #95a;
    }

    to{
        width: 100%;
        background-color: #f00;
    }
}

❌ Error que cometí

ninguno

✅ Solución

practicar