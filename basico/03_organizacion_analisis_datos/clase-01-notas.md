# Ordenar y filtrar datos en Excel

## Ordenamiento de datos
- Acceso desde Inicio → **Ordenar y filtrar**.
- Permite ordenar:
  - Texto (A → Z / Z → A)
  - Números (menor → mayor / mayor → menor)
- **Orden personalizado**:
  - Permite agregar múltiples niveles.
  - Ejemplo: primero por subcategoría y luego por monto.
- Verificar siempre que las **cabeceras estén correctamente seleccionadas**.

## Activar y usar filtros
- Atajo clave: **Ctrl + Shift + L** (activar / desactivar filtros).
- Los filtros permiten analizar subconjuntos sin modificar la tabla original.

## Atajos útiles para análisis
- **Ctrl + E / Ctrl + A**: seleccionar todo el rango.
- **Ctrl + Z**: deshacer cambios.
- **Ctrl + X / Ctrl + V**: mover información sin perder fórmulas.
- **Ctrl + Shift + 4**: formato de moneda o número.

## Tipos de filtros según el dato

### Filtros por fecha
- Agrupación por:
  - Año
  - Mes
  - Día
- Útil para validar formatos correctos y analizar periodos.

### Filtros por texto
- Filtrado por palabras clave.
- Uso de condiciones:
  - **Y**
  - **O**
- Ideal para categorías o descripciones.

### Filtros por número
- Mayor que / menor que.
- Entre rangos.
- Top 10 (valores más altos o bajos).

### Filtros por color
- Filtrar por:
  - Color de celda
  - Color de fuente
  - Íconos (formato condicional)
- Útil para identificar alertas o estados.

## Subtotales dinámicos

### SUBTOTALES
- Suma solo los valores **visibles** tras aplicar filtros.
- Sintaxis común:
  - `=SUBTOTALES(9, rango)`
- Se actualiza automáticamente al cambiar el filtro.
- Aplicar formato con **Ctrl + Shift + 4** para mejor visualización.

## Buenas prácticas
- Separar información crítica antes de filtrar si afecta otras fórmulas.
- Usar SUBTOTALES en lugar de SUMA cuando se trabaja con filtros.
- Mantener una tabla limpia y continua para evitar errores.