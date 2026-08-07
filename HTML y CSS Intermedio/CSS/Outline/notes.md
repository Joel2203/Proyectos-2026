Tema
Outline

🎯 Idea clave (3-5 líneas)

¿Qué hace y cuándo usarlo?

es como poner un segundo margen pero este no va a alterar el tamaño ni nada del elemento

⚙️ Sintaxis básica

outline- (with,color,style,offset)
outline: 1px solid #000

🧪 Ejemplo rápido

.box{
    width: 200px;
    height: 200px;
    background-color: #f00;
    border: 2px solid #000;
    margin: auto;
    margin-top: 50px;
    outline: 5px double #00f;
    white-space: normal;
    word-break: break-word;
}

.box:hover{
    outline-width: 10px;
    outline-color: #0f0;
    outline-style: solid;
}

❌ Error que cometí

me confundi un poco con que hacia el offset

✅ Solución
investigue y sirve para separar el outline del borde o elemento 