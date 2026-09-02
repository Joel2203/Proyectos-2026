Tema

srcset & sizes

🎯 Idea clave (3-5 líneas)

¿Qué hace y cuándo usarlo?

es para pone imagenes de acuerdo al dispositivo donde se visualice el contenido asi evitamos que una imagen grande y pesada se muestre en un movil cuando podemos optimizar los recursos para que se evite el lag o cargas absurdas, aca para llamar a las img en html y darles su tamaño en src usaremos w luego ya para sizes el px de siempre

⚙️ Sintaxis básica

<!-- <img src=(imagen con la que vamos a comenzar)
    srcset="todas las iamgenes que pondremos a disposicion para que se use la mas adecuada"
    sizes="como un if-else de los tamaños que debe cumplir cada imagen sino pasamos al siguiente tamaño"> -->

🧪 Ejemplo rápido

<!-- <img src="img/joel.jpg"
    srcset="img/joel.jpg 300w, img/bmwmedium.jpg 600w, img/batmanLarge.jpg 1000w"
    sizes="(max-width: 400px) 300px, (max-width: 600px) 500px, 900px"> -->

❌ Error que cometí

primero mi error por nombre a una carpeta con un & segundo tenia mal configurado el devtools

✅ Solución

estar atento a mi entorno