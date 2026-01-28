# Funciones de texto en Excel

## Unir textos

### CONCAT
- Une contenido de varias celdas.
- Permite agregar texto fijo usando comillas.
- Reemplaza a CONCATENAR (en desuso).
- Ejemplo:
  - `=CONCAT(A1," ",B1)`

### Operador &
- Alternativa rápida para unir textos.
- Funciona como “pegamento” entre valores.
- Ejemplo:
  - `=A1 & " - " & B1`

## Extraer partes de un texto

### IZQUIERDA
- Obtiene caracteres desde el inicio del texto.
- Útil para códigos o prefijos.
- Ejemplo:
  - `=IZQUIERDA(A1,3)`

### EXTRAER
- Obtiene texto desde una posición específica.
- Requiere:
  - Posición inicial
  - Cantidad de caracteres
- Ejemplo:
  - `=EXTRAER(A1,5,3)`

### DERECHA
- Obtiene caracteres desde el final del texto.
- Útil para fechas o códigos finales.
- Ejemplo:
  - `=DERECHA(A1,4)`

## Limpieza de texto

### ESPACIOS
- Elimina espacios sobrantes:
  - Al inicio
  - Al final
  - Espacios múltiples entre palabras

### LIMPIAR
- Elimina caracteres no imprimibles.
- Quita saltos de línea u otros símbolos ocultos.

### Limpieza combinada
- Se pueden anidar funciones para mejor resultado:
  - `=LIMPIAR(ESPACIOS(A1))`
- Verificar siempre el cierre correcto de paréntesis.

## Convertir fórmulas en valores
- Copiar con **Ctrl + C**.
- Usar **Pegar como valores**.
- Permite mover datos limpios sin depender de fórmulas.
