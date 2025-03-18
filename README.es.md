# Analizador de Ventas Mensuales

<onlyfor saas="false" withBanner="false">
  
### 🌱 Cómo iniciar este proyecto

Sigue las siguientes instrucciones:

1. Crear un nuevo repositorio haciendo fork en el [proyecto de Git](https://github.com/4GeeksAcademy/monthly-sales-analyzer-project) o [haciendo clic aquí](https://github.com/4GeeksAcademy/monthly-sales-analyzer-project/fork).
2. Abre el repositorio creado recientemente en Codespace usando la [extensión del botón de Codespace](https://docs.github.com/en/codespaces/developing-in-codespaces/creating-a-codespace-for-a-repository#creating-a-codespace-for-a-repository).
3. Una vez que el VSCode del Codespace haya terminado de abrirse, comienza tu proyecto siguiendo las instrucciones a continuación.

</onlyfor>


## 📝 Instrucciones

Se te ha proporcionado un archivo Python (`monthly_sales_analyzer.py`) que contiene datos de ventas de un mes para tres productos a lo largo de 20 días. Tu tarea es completar las funciones vacías para analizar estos datos utilizando habilidades básicas de Python: bucles, condicionales y estructuras de datos. Este proyecto evaluará tu capacidad para procesar y extraer información de un conjunto de datos, preparándote para conceptos de ciencia de datos.


- Los datos se almacenan en una variable llamada `sales_data`, una lista de 20 diccionarios. Cada diccionario representa un día y tiene:
    - `"day"`: Número del día (1 a 20).
    - `"product_a"`: Ventas del Producto A.
    - `"product_b"`: Ventas del Producto B.
    - `"product_c"`: Ventas del Producto C.

Ejemplo: 

```python
{"day": 1, "product_a": 150, "product_b": 80, "product_c": 200}
```

- Completa las cinco funciones de marcador de posición en el archivo. 

- Cada función analiza los `sales_data` de una manera específica. Usa solo Python básico, sin bibliotecas externas. El archivo incluye declaraciones `print` para probar tu trabajo.

#### Funciones a Completar:  
- **`total_sales_by_product(data, product_key)`:** Calcula las ventas totales de un producto dado (por ejemplo, `"product_a"`) a lo largo de 20 días.


- **`average_daily_sales(data, product_key)`:** Calcula el promedio de ventas diarias de un producto dado.


- **`best_selling_day(data)`:** Encuentra el día con las ventas totales más altas (suma de los tres productos).

- **`days_above_threshold(data, product_key, threshold)`:** Cuenta cuántos días las ventas de un producto superaron un umbral dado. (por ejemplo, 18).

- **`top_product(data)`:** Identifica qué producto (A, B o C) tuvo las ventas totales más altas.

- Para probar tu código escribe el siguiente comando en la linea de comando:

    ```bash
    python3 monthly_sales_analyzer.py
    ```

## ¿Te sientes confiado? 😎:  
- Agrega una función para encontrar el día con las peores ventas.
- Ordena los días por ventas totales y muestra los 3 mejores.
- Calcula el rango (máximo - mínimo) de las ventas de un producto.

  
Al final, habrás practicado el manejo de un conjunto de datos realista con Python básico, desarrollando habilidades para tu próximo curso de ciencia de datos. 

¡Diviértete analizando!🚀


## 🚛 Cómo entregar este proyecto

Una vez que completes los ejercicios, sigue estos pasos para enviarlos correctamente:  

1. **Guarda y confirma los cambios** en tu repositorio local:  

   ```sh
   git add .
   git commit -m "Completed exercises"
   ```
2. Sube los cambios a GitHub con:

    ```sh
    git push origin main
    ```
3. Dirígete a [4Geeks.com](https://4geeks.com) para enviar el enlace de tu repositorio.
