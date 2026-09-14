Proyecto de Modelamiento de Base de Datos - Retail Solari S.A.

## Descripción
Este repositorio contiene el desarrollo y normalización de un modelo de base de datos relacional para la empresa "Retail Solari S.A.". El proyecto soluciona un modelo conceptual incompleto, aplicando los estándares de normalización hasta la Tercera Forma Normal (3FN) para gestionar productos, proveedores, sucursales, clientes y ventas.

## Contenido del Repositorio
* **`Encargo_Semanal.docx`**: Documento principal con las evidencias solicitadas (Captura del Modelo Lógico en notación Barker, Captura del Modelo Relacional y Script DDL).
* **`Encargo_Semanal.zip`**: Archivo comprimido que contiene el proyecto original (`.dmd`) y su carpeta de recursos generada nativamente en Oracle Data Modeler.
* **`script_solari.sql`**: Script DDL con el código para la creación de tablas, restricciones, claves primarias (PK) y claves foráneas (FK) preparado para Oracle Database.

## Características Técnicas del Modelo
* **Normalización (1FN, 2FN, 3FN):** Independización de catálogos (Categorías, Marcas, Modelos, Regiones, Comunas).
* **Herencia y Subtipos:** Implementación de un supertipo `PROVEEDOR` con sus respectivos subtipos (`EMPRESA` y `PERSONA`) utilizando discriminadores.
* **Resolución de Relaciones N:M:** Desnormalización transaccional mediante la separación de cabecera (`BOLETA`) y detalle (`DETALLE_BOLETA`).
* **Notación Visual:** Uso riguroso de notación Barker (con cuadros concéntricos) para el MER-E y notación de Bachman para la vista relacional.

## Herramientas Utilizadas
* Oracle SQL Developer Data Modeler
