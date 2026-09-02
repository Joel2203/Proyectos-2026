Tema

fixed queries

🎯 Idea clave (3-5 líneas)

¿Qué hace y cuándo usarlo?

es cuando una propiedad para css es muy nueva y no se sabe si el navegador lo soportara entonces se pone un supports en caso que si lo soporte para aplicar la funcionalidad

⚙️ Sintaxis básica

@supports

@supports not

🧪 Ejemplo rápido

@supports (display: grid){
    body{
        display: grid;
    }
}

@supports not (display: flex){
    body{
        display: flex;
    }
}

❌ Error que cometí

ninguno

✅ Solución

practicarlo y verlo en un caso real de uso