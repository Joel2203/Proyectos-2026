Tema

alinecacion grid (vertical)

🎯 Idea clave (3-5 líneas)

¿Qué hace y cuándo usarlo?

aca lo mismo que flex para alinear en el eje vertical solo ocuparemos todos los align ya sea es items, content, self. items = solo a los elementos, content = a toda el grid y sus celdas, self = a un solo elemento. aca si debemos definir un height.

⚙️ Sintaxis básica

align-items: (aca puede ir start,strech,center, end);
align-content: (aca puede ir start,strech,center, end);
align-self: (aca puede ir start,strech,center, end);

🧪 Ejemplo rápido

.grid{
    display: grid;
    grid-template-columns: repeat(1 , 1fr);
    grid-template-rows: repeat(3 , 50px);
    gap: 10px;
    padding: 10px;
    align-items: stretch;
    align-content: space-evenly;
    height: 350px;
    border: 2px solid #000;
    margin: 20px;

}

.grid-item:first-child{
    align-self: start;
    background-color: #6e0;
}

❌ Error que cometí
ninguno

✅ Solución

poner en practica