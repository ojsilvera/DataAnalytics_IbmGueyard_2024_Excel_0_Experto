# fijacion y primeras operaciones

## Primeras formulas

### **Formas de Realizar Operaciones en Excel**

| **Método** | **Descripción** | **Ventajas** | **Desventajas** |
|------------|---------------|-------------|----------------|
| **Usar Excel como calculadora** | Ingresar manualmente los valores y la operación. Ejemplo: `150 + 100` | Fácil de usar | No se actualiza si cambian los valores |
| **Hacer referencias a celdas** | Usar referencias de celdas en lugar de valores fijos. Ejemplo: `=B6 + C6` | Se actualiza automáticamente al cambiar valores | Puede ser tedioso con muchas celdas |
| **Usar funciones de Excel (SUMA)** | Utilizar la función SUMA. Ejemplo: `=SUMA(B6:C6)` | Más eficiente y flexible | Requiere aprender sintaxis |
| **SUMA con celdas no contiguas** | Utilizar la función SUMA con celdas separadas. Ejemplo: `=SUMA(B6;D6;F6)` | Permite sumar celdas dispersas | Puede ser más difícil de leer si hay muchas celdas |

---

### **Ejemplo Práctico**

#### **Escenario: Sumar Ventas y Comisiones**

Si queremos calcular el total de ventas más comisiones en la celda `D13`, podemos hacerlo de diferentes maneras:

1. **Usando Excel como calculadora:**

   ```excel
   = 150 + 100
   ```

   📌 Resultado: 250, pero **NO recomendado** porque no se actualiza si cambian los datos.

2. **Usando referencias a celdas:**

   ```excel
   = B6 + C6
   ```

   📌 **Recomendado**, ya que si cambian `B6` o `C6`, el resultado se actualiza automáticamente.

3. **Usando la función SUMA:**

   ```excel
   =SUMA(B6:C6)
   ```

   📌 Ideal cuando las celdas son contiguas.

4. **SUMA con celdas separadas:**

   ```excel
   =SUMA(B6;D6;F6)
   ```

   📌 Útil cuando los valores no están en celdas consecutivas.

---

📢 **Conclusión:**

- Evitar usar Excel como una simple calculadora.
- Usar referencias a celdas para mantener la actualización automática.
- Usar la función `SUMA` para mayor eficiencia, especialmente con rangos grandes.
- En caso de celdas dispersas, utilizar `SUMA` con referencias separadas.

## Operaciones basicas

### **Operaciones Matemáticas Básicas**

En Excel, se pueden realizar todas las operaciones matemáticas básicas como en una hoja de papel:

| **Operación** | **Símbolo en Excel** | **Ejemplo** | **Resultado** |
|--------------|---------------------|------------|-------------|
| **Suma** | `+` | `=5+3` | 8 |
| **Resta** | `-` | `=10-4` | 6 |
| **Multiplicación** | `*` | `=6*2` | 12 |
| **División** | `/` | `=9/3` | 3 |
| **Cociente (división entera)** | `COCIENTE` | `=COCIENTE(9;2)` | 4 |
| **Porcentaje** | `%` | `=50%*200` | 100 |

---

### **Concatenación en Excel**

Concatenar significa unir textos o números en una misma celda.

| **Método** | **Fórmula** | **Resultado** |
|-----------|------------|--------------|
| **Usando CONCATENAR** | `=CONCATENAR("Inés";" "; "Pérez")` | `Inés Pérez` |
| **Usando el operador &** | `="Inés" & " " & "Pérez"` | `Inés Pérez` |
| **Unir texto con números** | `="Factura " & A2` | `Factura 358` |

📌 **Nota:** Si se concatenan números con texto, Excel los tratará como texto, lo que puede generar errores en cálculos.

---

### **Identificar si un valor es texto**

Para verificar si una celda tiene formato de texto, se usa la función `ESTEXTO`.

| **Fórmula** | **Resultado** |
|------------|-------------|
| `=ESTEXTO(A1)` | `VERDADERO` (si A1 es texto) |
| `=ESTEXTO(A2)` | `FALSO` (si A2 es número) |

⚠ **Precaución**: Si intentamos sumar un número con un texto, Excel dará error.

---

### **Ejemplo de Cálculo de Porcentaje**

Para calcular un porcentaje de un monto de ventas:

1. **Fórmula básica:**

   ```excel
   =Monto * Porcentaje
   ```

2. **Ejemplo:**

   Si `A2 = 500` y `B2 = 10%`, entonces:

   ```excel
   =A2 * B2
   ```

   📌 **Resultado:** `50` (el 10% de 500).

---

📢 **Conclusión:**

- Excel permite realizar operaciones matemáticas básicas de forma eficiente.
- Se pueden unir textos y números con `CONCATENAR` o `&`, pero los números se convertirán en texto.
- La función `ESTEXTO` ayuda a identificar si un valor es tratado como texto.
- Para calcular porcentajes, se multiplica el monto por el porcentaje deseado.
