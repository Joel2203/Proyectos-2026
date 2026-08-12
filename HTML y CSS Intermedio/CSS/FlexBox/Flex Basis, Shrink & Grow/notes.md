Tema

Flex Basis, Shrink & Grow

🎯 Idea clave (3-5 líneas)

¿Qué hace y cuándo usarlo?

son porpiedades de flex, basis es cuanto medira desde el inicio, grow hasta cuando se va a estirar y shrink hasta cuanto se achicara, es para un diseño repsonsive mas que nada

⚙️ Sintaxis básica
    flex-basis: 150px;
    flex-grow: 1;
    flex-shrink: 1;

    (version simplificada)
    flex: grow shrink basis

🧪 Ejemplo rápido

.flexbox{
    display: flex;
    flex-flow: row wrap;
    border: 2px solid #000;
    margin: auto;
    margin-top: 150px;
    justify-content: space-evenly;
    padding: 40px;
    background-color: #fff;
}

.flex-item{
    font-size: 50px;
    background-color: #f00;
    text-align: center;
    color: #fff;
    flex-flow: row wrap;
    flex-basis: 150px;
    flex-grow: 1;
    flex-shrink: 1;
}

otro ejemplo:
.item {
    flex: 1 1 200px; 
    /* grow: 1, shrink: 1, basis: 200px */
}

❌ Error que cometí

conceptuales ya los tengo resueltos

✅ Solución

practicar, ver en que se puede usar en el desarrollo web