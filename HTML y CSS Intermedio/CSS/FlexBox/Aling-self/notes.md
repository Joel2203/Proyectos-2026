Tema

aling-self

🎯 Idea clave (3-5 líneas)

¿Qué hace y cuándo usarlo?
align-self sirve para cambiar de posición únicamente a un solo elemento del flex

⚙️ Sintaxis básica

align-self: (center,flex-end, flex-start, baseline)

🧪 Ejemplo rápido
.flexbox{
    display: flex;
    flex-flow: row wrap;
    height: 200px;
    border: 2px solid #000;
    margin: auto;
    margin-top: 150px;
    padding: 40px;
    background-color: #fff;
    justify-content: space-evenly;
    align-items: start;
    gap: 10px;
}

.flex-item{
    background-color: #f00;
    text-align: center;
    color: #fff;
    flex-flow: row wrap;
    width: 100px;
}

.flex-item:first-child{
    background-color: #00f;
    align-self: flex-end;
}

.flex-item:last-child{
    background-color: #000;
    align-self: center;
}

❌ Error que cometí

me confundi mucho por culpa de align-content, porque ponia todo en una sola linea y el align-self no movia nada como se pretende

✅ Solución
fue quitar el align-content o definirle witdh a la caja del flexbox