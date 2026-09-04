Tema

sub grid

🎯 Idea clave (3-5 líneas)

¿Qué hace y cuándo usarlo?

cuandoo querramos poner un grid dentro de otro grid y tratarlo como un grid aparte, pero esto puede repercutir en el grid principal como en sus tamaños.

⚙️ Sintaxis básica

    grid-area: (aca pones en que columna o fila emepzara el sub grid y pones tambien los espacios que tomara);
    grid-template-columns: subgrid;
    grid-template-rows: subgrid;

🧪 Ejemplo rápido

.grid-item:first-child{
    grid-area: 2/2/span 2/span 2;
    display: grid;
    grid-template-columns: subgrid;
    grid-template-rows: subgrid;
    gap: 10px;
    padding: 5px;
}

.subgrid-item {
    background-color: #f6e;
    padding: 20px;
    border-radius: 16px;
    text-align: center;
    width: 350px;
}

❌ Error que cometí

ninguno

✅ Solución

NA