Tema
Text flow control

🎯 Idea clave (3-5 líneas)

¿Qué hace y cuándo usarlo?

/*si a un elemto le pongo text-wrap:balance lo va acomodar para que no se tenga que alargar y recortar luego de una forma fea pero para textos largos podemos usar pretty eso hara que si queda alguna palabra abajo no se vea como la ultima palabra sino que la acompaña con mas plabras para que se vea como una frase*/

/*.box estas van con white-space:nowrap es para no haya saltos de linea automaticos, pre es para yo mismo
ponerle el salto de linea donde quiero que vaya, normal es el que viene por defecto basicamente
hace el salto de linea autimatico,pre-wrap es como el normal hace el salto de linea automatico
pero a la vez cuando yo hago un salto de linea especifico me lo respeta,*/

/*.box2 si se mete un texto largo y no queremos que se desborde podemos usar white-space: nowrap;
    text-overflow: ellipsis; overflow: hidden; eso metera todo el texto dentro de un elmento
    pero el elemento no debe contener alemntos dentro sino no sirve*/

/*.box3 aca vemos la propiedad de word-break donde tenemos (break-all o keep-all) break all puede
    romper una letra en cualquier palabra, mientras que keep-all enves de cortar la palabra la baja
    completa, la mejor es auto-phrase. si ponemor word-wrap:anywhere significa que si la palabra
    la rompe antes que se desborde*/

⚙️ Sintaxis básica
 white-space: (nowrap,pre,pre-wrap,normal)
 text-overflow: (ellipsis, clip)
 overflow: (hidden,scroll,auto)
 word-break: (break-all o keep-all o break-word)
 text-wrap:(balance o pretty)

🧪 Ejemplo rápido

.box{
    width: 240px;
    height: 240px;
    margin: auto;
    margin-top: 50px;
    background-color: #fff;
    border: 2px solid #000;
    white-space: nowrap;
}

.box2{
    width: 240px;
    height: 50px;
    margin: auto;
    margin-top: 50px;
    background-color: #fff;
    border: 2px solid #000;
    white-space: nowrap;
    text-overflow: ellipsis;
    overflow: hidden;
}

.box3{
    width: 240px;
    height: 50px;
    margin: auto;
    margin-top: 50px;
    background-color: #fff;
    border: 2px solid #000;
    white-space: normal;
    word-break: break-all;
}

h1{
    text-wrap: balance;
}

.box4{
    width: 240px;
    height: 110px;
    margin: auto;
    margin-top: 100px;
    background-color: #fff;
    border: 2px solid #000;
    white-space: normal;
    word-wrap: anywhere;
    text-wrap: pretty;
}

❌ Error que cometí

varios conceptuales y que son varios que memorizar

✅ Solución

practicar