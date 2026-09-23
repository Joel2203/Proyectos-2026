Tema

transitions

🎯 Idea clave (3-5 líneas)

¿Qué hace y cuándo usarlo?

basicamente cuando hacemos algun moviento sobrea la web podemos predefinir un comportamiento llamada animacion ya sea cambio de colores tamaños o formas.

⚙️ Sintaxis básica

 transition: width 4s steps(6), background-color .6s, steps(6);
             (como se desplaza), cuanto dura, pasos de animacion, fondo de color lo que cambara, duracion, pasos de la duracion
  
tenemos cvarios tipos como duration, delay, property, time-function y style

🧪 Ejemplo rápido

.barra{
    padding: 40px;
    background-color: #48e;
    border-radius: 36px;
    width: 10%;
    transition: width 4s steps(6);
}

.barra:active{
    width: 100%;
    transition: 1s linear;
}

.barra2{
    padding: 40px;
    background-color: #48e;
    border-radius: 36px;
    width: 10%;
    transition: width 4s steps(6), background-color .6s, steps(6);
}

.barra2:active{
    width: 100%;
    transition: 1s linear;
    background-color: #f00;
}

.box2:has(.barra2:active) {
    border: 4px solid #f00;
    transition-duration: 3s;
}

❌ Error que cometí

ninguno

✅ Solución

practicar