# 🛒 Ecommerce

Este proyecto es una evaluación final del **Módulo 1: Data Analytics**, y consiste en crear una tienda online que permita gestionar productos, ventas y stock.

## 📦 Atributos

- `inventory`: Lista vacía de diccionarios donde se almacenan los productos.
- `total_sales`: Número decimal (`float`) que acumula el total de las ventas realizadas.

## ⚙️ Métodos

### ✅ `add_product()`
Permite agregar un nuevo producto o modificar uno existente.

### 👁️ `obtain_inventory()`
Muestra el inventario completo utilizando un bucle `for`.

**Ejemplo de salida:**

Nombre: Camisa | Precio: $20 | Cantidad: 50  
Nombre: Pantalón | Precio: $30 | Cantidad: 30  
Nombre: Zapatos | Precio: $50 | Cantidad: 40


### 🔍 `search_product()`
Permite buscar un producto específico recorriendo el inventario con un bucle `for`.

### 🔁 `update_stock()`
Actualiza la cantidad disponible de un producto en el inventario.

### 🗑️ `delete_stock()`
Elimina un producto del inventario.

### 💰 `sum_inventory_total()`
Calcula el valor total del inventario recorriendo todos los productos.

**Ejemplo:**

Si tenemos:
- 5 camisas que valen $5
- 10 calcetines que valen $1

Entonces:
```python
valor_camisas = 5 * 5      # = 25
valor_calcetines = 10 * 1  # = 10
valor_total = 25 + 10      # = 35

