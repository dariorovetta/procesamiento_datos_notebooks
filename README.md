# Análisis de Ventas de Notebooks

Este proyecto analiza datos de ventas de notebooks y datos de clientes, utilizando Python para explorar y relacionar atributos de productos con datos de clientes. Los datos se cargan desde un archivo Excel con varias hojas y se procesan para obtener insights relevantes para ventas y marketing.

## Descripción

Este proyecto está diseñado para combinar y analizar datos de productos y clientes, proporcionando insights sobre patrones de ventas, precios y características de los dispositivos. El objetivo es realizar análisis de ventas y evaluar qué modelos de notebooks son más populares en función de las características de los clientes.

### Columnas del Dataset de Notebooks

* **ID_NOTEBOOK** : Identificador único de la notebook.
* **MARCA** : Marca de la notebook.
* **PRODUCTO** : Nombre del modelo.
* **TIPO** : Tipo de dispositivo (Ultrabook, Notebook, etc.).
* **PULGADAS** : Tamaño de la pantalla en pulgadas.
* **RESOLUCION** : Resolución de la pantalla.
* **MARCA_PROCESADOR** : Marca del procesador.
* **PROCESADOR** : Modelo de procesador.
* **RAM_(GB)** : Cantidad de memoria RAM.
* **MEMORIA** : Tipo y capacidad de almacenamiento.
* **PLACA_VIDEO** : Tarjeta de video incluida.
* **SISTEMA_OPERATIVO** : Sistema operativo.
* **PESO_(KG)** : Peso del dispositivo.
* **PRECIO** : Precio de la notebook.
* **MONEDA** : Moneda del precio.

### Columnas del Dataset de Clientes

* **ID_CLIENTE** : Identificador único del cliente.
* **NOMBRE** : Nombre del cliente.
* **EDAD** : Edad del cliente.
* **PAIS** : País de residencia.
* **PROVINCIA** : Provincia o estado del cliente.

## Requerimientos

* **Python 3.x**
* Librerías:
  * `pandas`: Para manipulación de datos.
  * `numpy`: Para operaciones matemáticas y análisis.
  * `os`: Para acceder a rutas de archivos.

## Uso

1. Clona el repositorio.
2. Coloca el archivo de datos `Facturación Notebooks.xlsx` en la misma carpeta que el script.
3. Ejecuta el código en un entorno de Jupyter Notebook o como script de Python.

## Funcionalidades

* **Carga y Exploración de Datos** : Carga de datos desde un archivo Excel y análisis de su estructura.
* **Combinación de Datos** : Integración de datos de productos y clientes para análisis conjunto.
* **Análisis de Ventas** : Evaluación de ventas por producto y características del cliente.
