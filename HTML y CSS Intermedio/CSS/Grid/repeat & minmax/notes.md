Tema

repeat & minmax

🎯 Idea clave (3-5 líneas)

¿Qué hace y cuándo usarlo?

para hacer que un tamaño en el grid se repita sin necesidad de poner a todo un tamaño, es para utomatizarlo.

⚙️ Sintaxis básica

repeat([aca la cantidad de veces que se va a repetir], [unidad de medida a usar eje: 1fr, 200px])
minmax([aca pones el hasta ekl minimo que se achica el componente], [aca los maximo que puede crecer un componenete])

🧪 Ejemplo rápido

.grid{
    display: grid;
    height: 100vh;
    grid-template-columns: repeat(4, minmax(200px, 400px));
    grid-template-rows: repeat(2, 200px) 1fr;
}

❌ Error que cometí

ahi me amreba un poco con los repeat

✅ Solución

ponerlo en practica