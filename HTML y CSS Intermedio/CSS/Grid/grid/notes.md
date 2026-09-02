Tema

grid

🎯 Idea clave (3-5 líneas)

¿Qué hace y cuándo usarlo?

para poder darle "width y heigth" con columns y row.

⚙️ Sintaxis básica

display: grid
grid-template-columns: (aca pones el tamaño y la cantidad de columnas que vas a poner)
grid-template-row: (aca pones el tamaño y la cantidad de filas que vas a poner)

🧪 Ejemplo rápido

.grid{
    display: grid;
    grid-template-columns: 100px 300px;
    grid-template-rows: 100px 150px 200px;
}

.grid-item{
    background-color: #48e;
    color: #fff;
    font-size: 30px;
    margin: 10px;
    padding: 10px;
}

❌ Error que cometí

confundi el columns == alto y row == ancho, cuando es al reves columns == ancho y row == alto

✅ Solución

practicar hasta que me salga natural