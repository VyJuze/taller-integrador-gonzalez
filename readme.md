# Taller integrador individual

**Nombre completo:** Juan Sebastián González Vecino

## Tabla de hallazgos de la auditoría

| Defecto encontrado | Por qué era un problema | Cómo lo corrigió |
| --- | --- | --- |
| Archivos con nombres con espacios y mayúsculas inconsistentes (`Mi Pagina De Notas.HTML`, `Estilos Del Sitio.CSS`) | Dificulta referenciarlos y no sigue las convenciones estándar de nomenclatura web | Se renombraron a `index.html` y `styles.css` |
| Variables llamadas `data1`, `TempValue2`, `x` | No indican qué almacenan; obliga a leer todo el código para entenderlo | Se renombraron a `notas`, `promedio`, `numeroNotas` |
| Parámetros llamados `a`, `b`, `c` | Mismo problema de legibilidad que las variables genéricas | Se renombraron a `nota1`, `nota2`, `nota3` |
| Función llamada `calc()` | No comunica su propósito dentro del código | Se renombró a `calcularPromedioFn()` |
| IDs de inputs `n1`, `n2`, `n3` | Dificultan relacionar el HTML con la lógica que los usa | Se renombraron a `nota1`, `nota2`, `nota3` |
| IDs de párrafos de salida `r`, `r2` | No indican qué contenido muestran | Se renombraron a `parrafoPromedio` y `parrafoResultado` (reflejado también en `styles.css`) |
| Título de la página `pagina` | No describe el propósito del sitio | Se cambió a `Calculadora de Promedio` |
| Función comentada y sin uso `calcularAntiguo()` | Código muerto que ensucia el archivo | Se eliminó |

## Enlace al sitio publicado

url: vacio
