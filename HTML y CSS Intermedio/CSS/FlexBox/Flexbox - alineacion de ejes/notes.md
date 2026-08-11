Tema

flexbox - alineacion de ejes

🎯 Idea clave (3-5 líneas)

¿Qué hace y cuándo usarlo?

tiene diversus usos por ejemplo el justify-content es para navs o alinear elmentos en una sola linea del eje X luego estan el align-item que tambien sirven para ordener elementos que esten dentro de una sola fila trabaja solo en el eje y y por ultimo tenemos el align-content igual trabaja solo en el eje Y pero esta ves trabaja con diversas filas o columnas.


⚙️ Sintaxis básica
justify-content: (start,denter,end,space-bewteen,space-evenly)
align-item:(start,denter,end,space-bewteen,space-evenly)
align-content:(start,denter,end,space-bewteen,space-evenly)

🧪 Ejemplo rápido

.flexbox{
    display: flex;
    flex-flow: row wrap;
    justify-content: space-evenly;
}

.flex-item{
    width: 200px;
    height: 50px;
    background-color: #f00;
    color: #fff;
    margin: 10px;
    text-align: center;
}

.flexbox2{
    display: flex;
    flex-flow: row wrap;
    border: 2px solid #000;
    margin: 20px;
    justify-content: center;
    align-content: space-between;
    height: 400px;
}

.flex-item2{
    width: 200px;
    background-color: #f00;
    color: #fff;
    text-align: center;
}

.flexbox3{
    display: flex;
    flex-flow: row wrap;
    justify-content: center;
    align-content: center;
    margin-top: 150px;
    border: 2px solid #000;
    padding: 20px;
    height: 100px;
}

❌ Error que cometí

errores conceptuales por ejemp´lo para que le align-content sirva debo definir un height para que la propiedad trabaje

✅ Solución

practicar