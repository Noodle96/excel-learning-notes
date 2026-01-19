# Operadores básicos y referencias en Excel

## Inicio de fórmulas
- Toda fórmula en Excel comienza con **=**.
- Indica a Excel que se realizará un cálculo y no solo texto.

## Operadores básicos
- **Suma (+)**: suma valores o celdas.
- **Resta (-)**: resta valores.
- **Multiplicación (*)**: operador para multiplicar.
- **División (/)**: operador para dividir.
- **Porcentaje (%)**:
  - Puede usarse directamente en una fórmula.
  - Es recomendable usar celdas con formato porcentaje para evitar errores.
- Atajo útil:
  - **Alt + Shift + =** → inserta automáticamente la función **SUMA**.

## Referencias en Excel
Las referencias determinan cómo se comporta una fórmula al copiarla.

### Referencias relativas
- Cambian automáticamente al copiar o arrastrar la fórmula.
- Son las referencias por defecto.
- Ideales cuando el cálculo debe adaptarse a cada fila o columna.

### Referencias absolutas
- Se fijan con **F4** (o **Fn + F4**).
- Usan signos de dólar: **$C$24**.
- La fila y la columna no cambian al copiar la fórmula.
- Útiles para valores constantes (tasas, precios base, impuestos).

### Referencias mixtas
- Fijan solo una parte:
  - **$C24** → fija la columna.
  - **C$24** → fija la fila.
- Se usan cuando se necesita control parcial al copiar fórmulas.

## Uso práctico de referencias mixtas
- Ideales para:
  - Tablas de simulación
  - Cálculos cruzados
  - Escenarios con múltiples combinaciones
- Permiten copiar una fórmula a muchas celdas manteniendo coherencia.
- Reducen errores y aceleran tareas repetitivas.

## Buenas prácticas
- Revisar siempre los colores de las referencias en las fórmulas.
- Usar referencias absolutas solo cuando el valor **no debe cambiar**.
- Probar la fórmula en una celda antes de copiarla al resto del rango.
