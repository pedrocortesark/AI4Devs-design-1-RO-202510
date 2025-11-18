# Reglas de uso de GitHub Copilot en este proyecto

Este proyecto utiliza GitHub Copilot como "motor de pensamiento" asistido. Para mantener trazabilidad y poder reutilizar el contexto, seguiremos estas reglas:

1. **Registro de prompts**
   - Todos los prompts importantes que el usuario envíe a Copilot para avanzar en el proyecto se registrarán en un archivo de log de prompts. Como incio del prompt tendremos un pequeño encabezado:

   ```markdown
    # REGISTRO DE PROMPTS UTILIZADOS

    **Autor**:   

    **Fecha**:   

    **Proyecto**: 

    **Descripción**: 
    ---
   ```

   - Cada prompt se guardará con un identificador incremental y siguiendo este snippet: 



   - El contenido del prompt se copiará de forma íntegra (salvo información sensible, que podrá resumirse).

2. **Archivo de log de prompts**
   - El archivo de log se llamará `prompts-log.md` y se ubicará en la carpeta `LTI-PCN` que se encuentra en la raíz del repositorio.
   - La estructura de cada entrada será:
     - Título breve del objetivo del prompt.
     - Fecha y hora (opcional).
     - Contenido completo del prompt del usuario.
     - Resumen
   - Este es el snippet:

3. **Responsabilidad de actualización**
   - Cada vez que el usuario cree un nuevo prompt relevante para el proyecto, Copilot añadirá una nueva entrada al final de `prompts-log.md` con el siguiente identificador incremental.
   - El usuario no necesita mantener el contador; Copilot se asegurará de incrementar el índice correctamente.

4. **Uso posterior en prompts**
   - Cuando sea útil, Copilot podrá leer `prompts-log.md` para recuperar contexto histórico, decisiones previas y vocabulario del proyecto.

5. **Alcance**
   - Estas reglas aplican a todas las fases del proyecto de diseño de la LTI descrito en este repositorio.

---

Esta versión inicial define la regla general. A medida que avancemos, podremos extender este archivo con convenciones adicionales (nombres de ramas, estructura de entregables, etc.).
