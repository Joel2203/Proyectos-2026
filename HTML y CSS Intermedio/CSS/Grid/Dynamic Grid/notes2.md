Tema

Dynamic Grid

🎯 Idea clave (3-5 líneas)

¿Qué hace y cuándo usarlo?

lo mismo que en notes1. pero aca trabajaremos con fill osea que el mantendra su tamaño pero reservara una posciion para un elementos por mas que este no exista en el html.

⚙️ Sintaxis básica

grid-template-columns: repeat(auto-fill , minmax(250px, 1fr));

🧪 Ejemplo rápido

.grid{
    display: grid;
    grid-template-columns: repeat(auto-fill , minmax(250px, 1fr));<!-- mas que nada aca se pone 1fr para que todo sea equitativo y tipo responsive en moviles -->
    grid-auto-rows: 1fr;
    grid-auto-flow: row;
    grid-auto-columns: 1fr;
    gap: 10px;
    padding: 10px;
    margin: auto;
}


❌ Error que cometí

confusion de conceptos

✅ Solución

afianzarlo