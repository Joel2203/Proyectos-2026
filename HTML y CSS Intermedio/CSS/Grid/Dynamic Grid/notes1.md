Tema

Dynamic Grid

🎯 Idea clave (3-5 líneas)

¿Qué hace y cuándo usarlo?

principalmente auto-fit loq ue haces esque si el tamaño de la pantalla crece enves de crear una nueva columna usa el espacio que sobra y los reparte en partes iguales entres sus elementos, mientras que auto fill lo que hara esque si la ptanlla crece mantiene su tamaño pero crea el espacio de columna o row donde iria ese elemento por mas que no estee creado

⚙️ Sintaxis básica

auto-fit
aout-fill

grid-template-columns: repeat(auto-fit , minmax(250px, 1fr));

🧪 Ejemplo rápido

.grid{
    display: grid;
    grid-template-columns: repeat(auto-fit , minmax(250px, 1fr));<!-- aca se pone la propiedad y le decimos que no peude achicarse mas de 250px pero que puede estirarse 1 fr (osea que tomara lo que haya de espacio sobrante y repartira equitativamente entre todos sus elementos) -->
    grid-template-rows: repeat(3, 200px);
    grid-auto-rows: 200px;
    grid-auto-flow: column;
    grid-auto-columns: 250px;
    gap: 20px 5px;
    margin: auto;
    margin-top: 30px;
    padding: 15px;
}


❌ Error que cometí

errores conceptuales

✅ Solución

poner en practica