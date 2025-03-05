# Tips para trabajar mejor

## Configuraciones iniciales

### **1. Eliminación de Cuadrícula**

- Se accede desde la pestaña **Vista** → Opción **Línea de Cuadrícula**.
- Permite trabajar en un entorno más limpio y visualmente cómodo.

---

### **2. Creación y Edición de Hojas**

| Acción | Método |
|--------|--------|
| **Insertar una hoja nueva** | Clic en el botón **+** o clic derecho → **Insertar** → **Hoja de cálculo**. |
| **Mover una hoja** | Arrastrar la pestaña de la hoja a la posición deseada. |
| **Cambiar color de pestaña** | Clic derecho sobre la pestaña → **Color de pestaña**. |
| **Renombrar hoja** | Clic derecho sobre la pestaña → **Cambiar nombre**. |

---

### **3. Ajuste de Ancho de Columnas**

**Métodos:**

- Arrastrar manualmente desde el encabezado de la columna.
- Doble clic en el borde derecho del encabezado de la columna para **ajuste automático**.
- Seleccionar varias columnas → Doble clic en el borde para **ajustar todas a la vez**.

---

### **4. Inserción y Edición de Comentarios**

| Acción | Método |
|--------|--------|
| **Insertar comentario** | Clic derecho en la celda → **Insertar comentario**. |
| **Editar comentario** | Clic derecho en la celda con comentario → **Editar comentario**. |
| **Eliminar comentario** | Clic derecho en la celda con comentario → **Eliminar comentario**. |

---

### **5. Cálculo del IVA y Ajuste de Decimales**

1. **Fórmula para calcular IVA:**
   \[
   IVA = \text{Monto Total} - \text{Monto Neto}
   \]
2. **Quitar decimales:**
   - Pestaña **Inicio** → Opción **Disminuir decimales**.
3. **Auto-relleno de columna:**
   - Colocar el cursor en la **esquina inferior derecha** de la celda hasta que se convierta en una cruz delgada.
   - **Doble clic** o **arrastrar** hacia abajo para aplicar la fórmula en toda la columna.

---

### **6. Insertar Título Combinando Celdas**

1. Seleccionar el rango de celdas donde se colocará el título (**Ejemplo: H6 hasta K7**).
2. Pestaña **Inicio** → Opción **Combinar y Centrar**.
3. Ajustar alineación:
   - Horizontal: **Izquierda, Centro o Derecha**.
   - Vertical: **Arriba, Medio o Abajo**.
4. Modificar fuente y color si es necesario.

---

### **7. Suma Automática**

| Método | Procedimiento |
|--------|--------------|
| **Manual** | Escribir `=SUMA(RANGO_DE_CELDAS)` y presionar **Enter**. |
| **Automático** | Seleccionar la celda destino → Pestaña **Inicio** → **AutoSuma** (∑) → Enter. |
| **Relleno automático** | Arrastrar la fórmula hacia el costado para aplicarla a otras filas o columnas. |

---

## Inmovilizar vistas

### 🔹 **1. Inmovilizar filas y columnas**

Permite fijar títulos o columnas para facilitar la visualización de datos al desplazarse.

#### **Pasos para inmovilizar filas o columnas**

| Acción | Pasos |
|---|---|
| **Fijar filas** | 1. Selecciona la fila inmediatamente debajo de la que quieres inmovilizar. `<br>` 2. Ve a la pestaña **Vista** → **Inmovilizar paneles** → **Inmovilizar filas**. |
| **Fijar columnas** | 1. Selecciona la columna inmediatamente a la derecha de la que quieres inmovilizar. `<br>` 2. Ve a **Vista** → **Inmovilizar paneles** → **Inmovilizar Columnass**. |
| **Fijar filas y columnas simultáneamente** | 1. Selecciona la celda **inmediatamente siguiente** a la fila y columna que deseas inmovilizar. `<br>` 2. Ve a **Vista** → **Inmovilizar paneles** → **Inmovilizar paneles**. |
| **Desbloquear filas o columnas** | **Vista** → **Inmovilizar paneles** → **Movilizar paneles**. |

---

### 🔹 **2. Ocultar y mostrar celdas**

Permite ocultar datos irrelevantes y mostrar solo la información deseada.

#### **Cómo ocultar filas o columnas**

1. Selecciona las filas o columnas a ocultar.
2. Haz clic derecho y selecciona **Ocultar**.

#### **Cómo mostrar filas o columnas ocultas**

1. Identifica el espacio entre los números de filas o letras de columnas.
2. Haz clic derecho en el espacio y selecciona **Mostrar**.

#### **Cómo copiar solo las celdas visibles**

1. Selecciona los datos visibles.
2. Presiona `F5` → **Especial** → **Solo celdas visibles** → **Aceptar**.
3. Copia (`Ctrl + C`) y pega (`Ctrl + V`) en otro lugar.

---

### 🔹 **3. Transponer tablas (Cambiar orientación de datos)**

Convierte una tabla horizontal en vertical o viceversa.

#### **Pasos para transponer**

1. Copia la tabla (`Ctrl + C`).
2. Selecciona la celda de destino.
3. En opciones de pegado, elige **Transponer**.

---

### 🔹 **4. Copiar y pegar solo valores**

Elimina formatos y fórmulas, dejando solo los datos.

#### **Pasos**

1. Copia (`Ctrl + C`).
2. En opciones de pegado, elige **Pegar solo valores**.

---

### 🔹 **5. Asignar nombres a rangos y tablas**

Facilita la referencia de datos en fórmulas.

#### **Pasos para nombrar un rango**

1. Selecciona el rango de celdas.
2. En el cuadro de nombres, escribe un nombre (ejemplo: `Vendedores`).
3. Presiona **Enter**.

#### **Pasos para nombrar una tabla**

1. Selecciona la tabla.
2. Ve a la pestaña **Diseño**.
3. En el campo **Nombre de tabla**, escribe un nombre (ejemplo: `Ventas`).

#### **Convertir una tabla en rango**

1. Selecciona la tabla.
2. Ve a **Diseño** → **Convertir en rango** → **Aceptar**.

---

## Validacion de datos

### **Resumen del Texto sobre Funciones de Excel**

El texto describe varias funciones útiles de Excel para mejorar la organización, validación y manipulación de datos.

---

## **1. Validación de Datos (Listas Desplegables)**

**¿Qué es?**

Permite restringir los valores ingresados en una celda según una lista predefinida, evitando errores y asegurando la
uniformidad de los datos.

**Ejemplo de Uso:**

- En una columna "Estado" se establecen las opciones: "Pagado", "A pagar", "Rechazado".
- Si alguien intenta ingresar un valor diferente, Excel mostrará un mensaje de error.

**Pasos para crear una lista desplegable:**

1. Seleccionar la columna donde se aplicará la validación.
2. Ir a la pestaña **Datos** → **Validación de datos**.
3. En **Permitir**, elegir la opción **Lista**.
4. En **Origen**, seleccionar las celdas que contienen los valores permitidos.
5. Presionar **Enter** y la lista desplegable quedará lista.

---

## **2. Formato Condicional**

**¿Qué es?**

Permite resaltar celdas que cumplen con ciertos criterios, facilitando la identificación de datos relevantes.

**Ejemplo de Uso:**

- Resaltar en **verde** las celdas que contienen el texto "A depositar".

**Pasos para aplicar formato condicional:**

1. Seleccionar la columna que se desea formatear.
2. Ir a **Inicio** → **Formato Condicional** → **Reglas para resaltar celdas**.
3. Elegir **Texto que contiene**, escribir "A depositar".
4. Aplicar el formato: **Fondo verde y texto blanco**.
5. Presionar **Aceptar** y los datos que cumplen la condición quedarán resaltados.

---

## **3. Eliminación de Duplicados**

**¿Qué es?**

Permite eliminar valores repetidos en una columna, dejando solo valores únicos.

**Ejemplo de Uso:**

- Limpiar una lista de ciudades eliminando los valores duplicados.

**Pasos para eliminar duplicados:**

1. Seleccionar la columna con datos repetidos.
2. Ir a la pestaña **Datos** → **Quitar duplicados**.
3. Si la tabla tiene encabezados, marcar la opción correspondiente.
4. Presionar **Aceptar** y Excel eliminará los duplicados, mostrando la cantidad eliminada y los valores únicos restantes.

---

## **4. Función CONCATENAR**

**¿Qué es?**
Permite unir textos de diferentes celdas en una sola celda.

**Ejemplo de Uso:**

- Unir los valores "Joaquín" y "Pérez" en una celda para formar "Joaquín Pérez".

**Fórmula Básica:**

```excel
=CONCATENAR(A1; " "; B1)
```

- `A1` contiene "Joaquín"
- `B1` contiene "Pérez"
- `" "` agrega un espacio entre ambos nombres.

---

## **5. Relleno Rápido (Excel 2016 en adelante)**

**¿Qué es?**
Permite que Excel detecte patrones y complete automáticamente los datos sin necesidad de usar fórmulas.

**Ejemplo de Uso:**

- Unir nombres sin usar CONCATENAR.

**Pasos:**

1. Escribir un ejemplo de cómo debe quedar el resultado (ej. "Joaquín Pérez Sánchez").
2. Seleccionar las celdas donde se desea aplicar el formato.
3. Ir a **Inicio** → **Relleno rápido**.
4. Excel completará automáticamente el patrón en el resto de las celdas.

---

### **Resumen Visual**

| **Función**                | **Propósito**                                | **Ejemplo**                           | **Pasos Clave** |
|----------------------------|---------------------------------------------|---------------------------------------|----------------|
| **Validación de datos**     | Restringe valores en celdas                 | Lista de "Pagado", "A pagar", etc.   | Datos → Validación de datos → Lista |
| **Formato condicional**     | Resalta datos según condiciones             | Texto "A depositar" en verde         | Inicio → Formato condicional |
| **Eliminar duplicados**     | Elimina valores repetidos                    | Lista de ciudades sin repetidos      | Datos → Quitar duplicados |
| **Concatenar**              | Une textos de diferentes celdas              | "Joaquín Pérez"                      | `=CONCATENAR(A1;" ";B1)` |
| **Relleno rápido**          | Completa datos automáticamente               | Excel predice y rellena patrones     | Inicio → Relleno rápido |

Estas funciones ayudan a mejorar la organización, limpieza y visualización de datos en Excel, optimizando el trabajo y
reduciendo errores. 🚀
