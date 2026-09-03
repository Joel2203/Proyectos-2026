Tema

flow dense

🎯 Idea clave (3-5 líneas)

¿Qué hace y cuándo usarlo?

es una propiedad que evita que a la hora de mover un elemento del grid, este haga hueco y se vea mal, en resumen trata de llenar los espacios vacios pero no dejarlos en blanco.

⚙️ Sintaxis básica

grid-auto-flow: dense;

luego puede seleccionar el elemento especifico del grid y determinar cuanto espacio ocupara en el grid.
    grid-column: span 2;
    grid-row: span 2;

🧪 Ejemplo rápido

.grid{
    display: grid;
    height: 80vh;
    grid-template-columns: repeat(auto-fill , minmax(200px, 1fr));
    grid-auto-rows: 1fr;
    grid-auto-flow: dense;
    grid-auto-columns: 1fr;
    gap: 10px;
    padding: 10px;
    margin: auto;
}

.grid-item:nth-child(7){
    grid-column: span 2;
    grid-row: span 2;
}

❌ Error que cometí

ninguno

✅ Solución

poner en practica