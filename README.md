# Proyecto: Buenas Prácticas en R

## Descripción
Este proyecto tiene como objetivo explorar y aplicar buenas prácticas al momento de codificar en R. A través de un caso práctico, se busca identificar cómo un código subóptimo puede mejorarse para garantizar:

- Legibilidad.
- Eficiencia.
- Mantenimiento.
- Correctitud de los resultados.

Se incluye un archivo llamado **`bad_script.R`**, que contiene un ejemplo de código que no sigue buenas prácticas, y su correspondiente solución mejorada en otro archivo. Además, se proporciona una guía de buenas prácticas y la data utilizada para la actividad.

## Estructura del Proyecto

- **`bad_script.R`**: Código inicial que contiene errores comunes, falta de organización y problemas de eficiencia.
- **`solution_script.R`**: Versión mejorada del código original, implementando las buenas prácticas aprendidas.
- **`guia_buenas_practicas.pdf`**: Documento que detalla principios y ejemplos de buenas prácticas al programar en R.
- **`data.csv`**: Archivo de datos utilizado en los ejemplos y actividades.
- **`README.md`**: Este archivo, que explica el propósito del proyecto y cómo utilizar los scripts proporcionados.

## Buenas Prácticas Aplicadas

1. **Nombres descriptivos**:
   - Variables, funciones y columnas con nombres claros y específicos.
   - Uso de nombres en inglés si se planea colaborar en proyectos internacionales.

2. **Formato y consistencia**:
   - Uso de indentación consistente (2 o 4 espacios).
   - Líneas de código que no excedan 80 caracteres.

3. **Comentarios claros**:
   - Explicación de bloques de código complejos.
   - Uso de comentarios inline para aclarar operaciones específicas.

4. **Evitación de hardcoding**:
   - Uso de variables y constantes para valores reutilizables.
   - Lectura de datos desde archivos o bases de datos en lugar de codificar valores directamente en el código.
   - Parametrización de funciones para que sean más flexibles y reutilizables.

5. **Control de errores y advertencias**:
   - Uso de funciones como `tryCatch` o `stopifnot` para manejar errores.

6. **Estructura modular**:
   - División del código en funciones reutilizables.

## Instrucciones de Uso

1. Clona o descarga este repositorio.
2. Revisa el archivo **`bad_script.R`** para identificar los problemas.
3. Compara con la versión mejorada en **`solution_script.R`**.
4. Consulta la guía de buenas prácticas en **`guia_buenas_practicas.pdf`** para más información y ejemplos.
5. Analiza las diferencias y reflexiona sobre cómo las buenas prácticas mejoran el código.

## Propósito Educativo
Este proyecto está diseñado como una actividad práctica para aprender y reflexionar sobre las buenas prácticas en programación con R. No solo se busca mejorar la calidad del código, sino también fomentar hábitos que sean útiles en entornos de trabajo reales y colaborativos.

## Contribuciones
Si deseas contribuir con sugerencias o mejoras, eres bienvenido a enviar un pull request o abrir un issue en el repositorio.

---

**Autor**: Luis Vásquez  
**Fecha**: Enero 2025

