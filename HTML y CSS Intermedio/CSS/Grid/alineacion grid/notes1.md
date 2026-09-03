Tema

alinecacion grid (horizontal)

🎯 Idea clave (3-5 líneas)

¿Qué hace y cuándo usarlo?

aca lo mismo que flex para alinear en el eje horizontal solo ocuparemos todos los justify ya sea es items, content, self. items = solo a los elementos, content = a toda el grid y sus celdas, self = a un solo elemento

⚙️ Sintaxis básica

justify-items: (aca puede ir start,strech,center, end);
justify-content: (aca puede ir start,strech,center, end);
justify-self: (aca puede ir start,strech,center, end);

🧪 Ejemplo rápido

.grid{
    display: grid;
    grid-template-columns: repeat(3 , 250px);
    grid-template-rows: repeat(3 , 250px);
    gap: 10px;
    padding: 10px;
    justify-items: end;
    justify-content: center;
}

.grid-item:first-child{
    justify-self: start;
    background-color: #6e0;
}

❌ Error que cometí

ninguno mas bien entendi por fin la diferencia de justify y aling

✅ Solución

poner en practica