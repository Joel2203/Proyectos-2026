Tema

flex wrap & flow

🎯 Idea clave (3-5 líneas)

¿Qué hace y cuándo usarlo?

el wrap es para evitar desbordamientos o que las cajas pierdan si wwidht al tener que ponerlas todas en una sola fila por el flex, y el flow es para poner ambas propiedades en una sola linea flex flow: (1.direction 2.wrap)

nowrap: metes todos los libros a la fuerza en un solo estante, aunque se aprieten.
wrap: cuando el estante se llena, agregas un estante nuevo abajo.
wrap-reverse: cuando el estante se llena, agregas el estante nuevo arriba en vez de abajo.

⚙️ Sintaxis básica

flex-wrap: (nowrap,wrap,wrap-reverse)
flex-flow: (1.direction 2.wrap)

🧪 Ejemplo rápido

.flexbox{
    display: flex;
    flex-direction: row-reverse;
    flex-wrap: wrap;
}

.flexbox2{
    display: flex;
    flex-flow: column wrap;
}

❌ Error que cometí

me confundia conceptualmente

✅ Solución

practicar