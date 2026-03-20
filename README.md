# Team
This project was developed by:

María Noriega

Carlos Castro

# Customer Order Management System

## Project Overview

This project is a terminal-based **Customer Order Management System** developed in Python. The system allows users to:

- Register clients
- Register products
- Create orders
- Consult registered orders
- Calculate daily income
- Generate a final sales report

The solution was built using dictionaries and tuples as the main data structures, following the challenge requirements. Functions were used to organize the program logic, making the code modular, clear, and reusable.

---

## System Architecture

The program follows a modular structure based on functions. Each function has a specific responsibility within the system. The main components of the system are:

1. **System Data Container**: Stores clients, products, orders, and the order counter.
2. **Validation Functions**: Verifies that text fields are not empty and that numeric values are valid and positive.
3. **Registration Functions**: Registers clients and products in the system.
4. **Order Management Functions**: Creates orders and calculates order totals.
5. **Reporting Functions**: 
   - Consults orders
   - Calculates daily income
   - Groups orders by client
   - Summarizes sold products
   - Generates the final report
6. **Menu Functions**: 
   - Displays the menu
   - Processes user options
   - Runs the system loop

---

## Instructions to Run the Program

1. Make sure **Python 3** is installed on your computer.
2. Save the file as `sistema_pedido.py` or any preferred name.
3. Open a terminal in the folder where the file is located.
4. Run the program with the following command:
    ```bash
    python sistema_pedido.py
    ```
5. Use the menu options displayed in the terminal:
    - Register client
    - Register product
    - Create order
    - Consult orders
    - Calculate daily income
    - Generate final report
    - Exit

---

## Data Structures Used

1. **Dictionaries**  
   Dictionaries are used to store:
   - Clients
   - Products
   - Orders
   - Grouped report data  
   They allow fast access to data through unique keys such as client ID, product ID, or order ID.

2. **Tuples**  
   Tuples are used to store product information:
   - Product ID
   - Product name
   - Unit price  
   A tuple is appropriate here because product data is grouped in a fixed structure.

3. **Strings**  
   Strings are used for:
   - Names
   - Emails
   - IDs
   - Messages
   - Reports

4. **Integers and Floats**  
   - **Integers** are used for counters and quantities.
   - **Floats** are used for prices, totals, and income calculations.

---

## Description of the Implemented Modules

### 1. Data Creation Module
- `crear_datos_sistema()`

This part creates the main structure of the system.

### 2. Validation Module
- `validar_texto_no_vacio()`
- `validar_flotante_positivo()`
- `validar_entero_positivo()`

This module validates user input to ensure data integrity.

### 3. Client Module
- `registrar_cliente()`

This module registers clients in the system.

### 4. Product Module
- `registrar_producto()`

This module registers products in the system.

### 5. Order Module
- `calcular_total_pedido()`
- `crear_pedido()`

This module creates and manages orders.

### 6. Query and Reporting Module
- `formatear_catalogo_clientes()`
- `formatear_catalogo_productos()`
- `consultar_pedidos()`
- `calcular_ingresos_diarios()`
- `agrupar_pedidos_por_cliente()`
- `resumir_productos_vendidos()`
- `generar_reporte_final()`

This module generates information and reports.

### 7. Menu Module
- `construir_texto_menu()`
- `procesar_opcion_menu()`
- `ejecutar_sistema()`

This module controls the interaction with the user through the terminal.

---

## Conclusion

This project demonstrates how to build a functional order management system using Python fundamentals. It applies modular programming, validation, structured data storage, and report generation in a console-based application.

---
