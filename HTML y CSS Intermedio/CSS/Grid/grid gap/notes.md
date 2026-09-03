Tema

grid gap

🎯 Idea clave (3-5 líneas)

¿Qué hace y cuándo usarlo?

viene a sustituir el margin, para poder separar a los elementos entre si solamente, lo que evita poner un espacio a un borde que no tonga un elemeto a su lado o arriba o abajo.

⚙️ Sintaxis básica

column-gap:
row-gap:
gap: (aca haces ambas columns & row)

🧪 Ejemplo rápido

.grid{
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-template-rows: repeat(3, 200px);
    grid-auto-rows: 200px;
    grid-auto-flow: column;
    grid-auto-columns: 250px;
    gap: 20px 5px;
    width: 80vw;
    margin: auto;
    margin-top: 30px;
}


❌ Error que cometí

ninguno

✅ Solución

poner en practica