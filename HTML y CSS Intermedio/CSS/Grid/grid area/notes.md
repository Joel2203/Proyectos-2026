Tema

grid area

🎯 Idea clave (3-5 líneas)

¿Qué hace y cuándo usarlo?

es una forma diferente de colocar un elemento en el grid, pero aca se pondra la estructura padre y luego se llamar a los hijos para asginarle el nombre que le padre les dio.

⚙️ Sintaxis básica

    grid-template-areas:
    "(aca el nombre de los hijos podemos tener mas de una fila)";

luego abajo se declara al hijo con el nombre que le asigno el padre
    (nombre que el padre asigna){
    grid-area: (nombre que el padre asigna);
}

🧪 Ejemplo rápido

.grid{
    flex-grow: 1;
    display: grid;
    grid-template-columns: minmax(200px, 1fr) minmax(300px, 3fr) minmax(200px, 1fr);
    grid-template-rows: 1fr;
    grid-auto-rows: dense;
    margin: auto;
    gap: 10px;
    padding: 10px;
    grid-template-areas:
    "nav main aside";
}

nav{
    grid-area: nav;
}

main{
    grid-area: main;
    min-width: 300px;
}

aside{
    grid-area: aside;
}

❌ Error que cometí

me confundi en que en el .grid puse grid-area y no grid-template-areas.

✅ Solución

poner en practica