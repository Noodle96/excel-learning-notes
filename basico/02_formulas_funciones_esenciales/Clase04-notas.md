# Funciones de fecha en Excel

## Fecha y hora actuales
- **HOY()**:
  - Devuelve la fecha actual.
  - Útil para calcular días restantes o vencidos.
- **AHORA()**:
  - Devuelve fecha y hora actual.
  - Útil para seguimientos con precisión temporal.

## Extraer información de una fecha

### DÍA
- Obtiene el día numérico del mes.
- Ejemplo:
  - `=DÍA(A1)`

### DIASEM
- Devuelve el día de la semana en formato numérico.
- Sintaxis:
  - `=DIASEM(fecha, tipo)`
- Ejemplo común:
  - `tipo = 2` → lunes = 1, domingo = 7

### MES
- Devuelve el número del mes.
- Ejemplo:
  - `=MES(A1)`

### AÑO
- Devuelve el año de una fecha.
- Ejemplo:
  - `=AÑO(A1)`

### TEXTO
- Convierte una fecha en texto personalizado.
- Ejemplos:
  - `=TEXTO(A1,"dddd")` → nombre del día
  - `=TEXTO(A1,"mmm")` → mes abreviado
  - `=TEXTO(A1,"mmmm")` → mes completo

## Cálculo de diferencias entre fechas

### DÍAS
- Calcula días naturales entre dos fechas.
- Sintaxis:
  - `=DÍAS(fecha_final, fecha_inicial)`
- El orden de las fechas afecta el resultado.

### DIAS.LAB.INT
- Calcula días laborables entre dos fechas.
- Sintaxis:
  - `=DIAS.LAB.INT(fecha_inicial, fecha_final, [fin_de_semana], [días_no_laborables])`
- Permite:
  - Personalizar días de fin de semana.
  - Excluir feriados o días de descanso.
- Fijar rangos opcionales con **F4** para evitar desplazamientos.

## Buenas prácticas
- Fijar referencias de fechas clave (HOY, feriados).
- Usar formatos de texto para reportes más claros.
- Verificar siempre el tipo de fecha (no texto).
