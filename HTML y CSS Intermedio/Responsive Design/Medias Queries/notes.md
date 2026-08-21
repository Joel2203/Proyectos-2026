Tema

medias queries

🎯 Idea clave (3-5 líneas)

¿Qué hace y cuándo usarlo?

es la forma en la que se estrctura la progamacion para distintos tipos de dispositivos en una mismas clase

⚙️ Sintaxis básica
1
@media (elemento a llamar) {
    (element en especifico){
        (lo que hara el elemento)
    }
}
2
@media (elemento a llamar) and (condicion para que ejecute la orden de abajo. es como un if) {
    (element en especifico){
        (lo que hara el elemento)
    }
}

🧪 Ejemplo rápido

.flexbox{
    display: flex;
}

.flex-item{
    background-color: #666;
    color: #fff;
    padding: 30px;
    border: 1px solid #f00;
    flex-grow: 1;
}

@media screen and (max-width:600px) {
    .flexbox{
        flex-direction: column;
    }
}

❌ Error que cometí

me mareaba mucho y en html para trabajr con moviles se debe poner esto:
<!-- <meta name="viewport" content="width=device-width,initial-scale=1.0"> -->

✅ Solución

practicar