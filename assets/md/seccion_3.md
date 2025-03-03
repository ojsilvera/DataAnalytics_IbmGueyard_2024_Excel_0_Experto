# fijacion y primeras operaciones

## Primeras formulas

Aquí tienes un resumen estructurado para facilitar su comprensión:

---

## **Operaciones Básicas en Excel**

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
