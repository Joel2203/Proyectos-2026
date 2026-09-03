Tema

grid start & end

🎯 Idea clave (3-5 líneas)

¿Qué hace y cuándo usarlo?

cuando querramos darle un posicion a un grid determinado, podemos usar span para poner como que ejemplo: span 2 quiere decir que siempre ocupara 2

⚙️ Sintaxis básica

    grid-column-start: (aca se pone donde vamos a iniciar, aca se tiene en cuenta los bordes);
    grid-row-start: (aca se pone donde vamos a iniciar, aca se tiene en cuenta los bordes);
    grid-column-end: (aca pones hasta donde va abarcar);
    grid-row-end: (aca pones hasta donde va abarcar);

    grid-column: (aca se pone donde inicia)/(aca donde acaba);
    grid-row: (aca se pone donde inicia)/(aca donde acaba);

🧪 Ejemplo rápido

.grid-item:first-child{
    grid-column-start: 1;
    grid-row-start: 1;
    grid-column-end: 3;
    grid-row-end: 4;
}

.grid-item:last-child{
    grid-column: 4/span 2;
    grid-row: 4/span 2;
}

❌ Error que cometí

ninguno, solo algo del height en el .grid

✅ Solución

poner en practica