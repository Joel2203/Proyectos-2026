Tema

Container Queries

🎯 Idea clave (3-5 líneas)

¿Qué hace y cuándo usarlo?

principalmente cuando necesitemos trabajar con un elmento especifico en cierto tamaño del contenido, es decir supongamos que queremos dar una estilo a un div en diferentes tamaños, un estilo para 1024px y otro para 600px, es ahi donde usamos los Container Queries.

⚙️ Sintaxis básica

(se pone la clase o elemento que queremos estilizar){
    container-type: (inline-size, inline, normal);
    container-name: (el nombre que querramos, podemos tener una clase con el mismo nombre pero aca se enfatisa cual exactamente queremos cambiar);
}

@(aca llamamos a la clase) (aca usamos el nombre que pusimos arriba) (aca el tamaño en el que se hara el estilo){

}

🧪 Ejemplo rápido

.container{
    container-type: inline-size;
    container-name: principal;
}


@container principal (max-width: 600px){
    p{
        font-size: 30px;
        color: #4f1;
        background-color: #f90;
        transition-property: color,background;
        transition-delay: 0.4s;
        transition-duration: 0.2s;
    }
    p:hover{
        color: #f00;
        background-color: #666;
    }
}

❌ Error que cometí

ninguno

✅ Solución

practicar