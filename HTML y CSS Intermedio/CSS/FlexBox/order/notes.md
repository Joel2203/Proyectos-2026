Tema

order flex

🎯 Idea clave (3-5 líneas)

¿Qué hace y cuándo usarlo?

es para darle un orden especificao a un elemeto, se puede usar para diseños repsonsive

⚙️ Sintaxis básica

order: (el numero que se le vaya a poner, tambien sirve con numero negativos)

🧪 Ejemplo rápido

.flexbox{
    display: flex;
    flex-flow: row wrap;
    border: 2px solid #000;
    margin: auto;
    margin-top: 150px;
    justify-content: space-evenly;
    width: 800px;
    padding: 40px;
    background-color: #fff;
}

.flex-item{
    width: 120px;
    font-size: 50px;
    background-color: #f00;
    text-align: center;
    color: #fff;
    order: 2;
}

.flex-item:first-child{
    background-color: #00f;
    order: 1;
}

.flex{
    background-color: #0f0;
    order: 3;
}

.flex-item:last-child{
    background-color: #000;
    order: -1;
}

❌ Error que cometí

ninguno

✅ Solución

practicar