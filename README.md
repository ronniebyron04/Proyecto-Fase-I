# Proyecto-Fase-I
En este repositorio se encuentra el codigo fuente del programa y el readme.

Gestor de Stock para E-Commerce

En los e-commerce, las ofertas y descuentos son estrategias clave para atraer clientes, aumentar ventas y gestionar inventarios antiguos.

1.	Funcionamiento del Sistema:
El sistema utiliza estructura de datos como colas y pilas para optimizar la gestión del stock:
•	Colas (FIFO – First In, First Out): para manejar pedidos en orden de llegada.
•	Pilas (LIFO – Last In, First Out): Para estrategias de liquidación y gestionar productos con fechas de caducidad
•	Algoritmo de optimización de descuento: Para aplicar descuentos en función del nivel de stock y demanda

2.	Requisitos Técnicos
•	Lenguaje de programación: C#
•	Base de datos: SQL Server
•	Framework: .NET
•	Dependencias:
	Entity Framework
	NewTonsoft.Jason

3.	Instalación y Configuración
a.	Clonar el repositorio:
b.	Ejemplo: git clone https://github.com/usuario/gestion-stock.git
c.	Abrir el proyecto en Visual Studio.
d.	Restaurar paquetes de dependencias mediante NuGet.
e.	Configurar la cadena de conexión a SQL Server en appsettings.json o en el archivo de configuración correspondiente.
f.	Aplicar migraciones a la base de datos del Entity Framework:
g.	Ejemplo: dotnet ef database update
h.	Ejecutar el sistema desde Visual Studio

4.	Uso del Sistema
•	Registrar producto con cantidad y precio.
•	Procesar compras, actualizando el stock.
•	Gestión de descuentos y ofertar en función del inventario y demanda.
•	Generar reporte sobre stock, venta y efectividad de descuentos.
•	Generar recibos en formato JSON por cada compra realizada.


5.	Contribución y Desarrollo Futuro
•	Implementación de machine learning para predicción de demanda y optimización de descuentos.
•	Integración con plataformas de e-commerce populares.

