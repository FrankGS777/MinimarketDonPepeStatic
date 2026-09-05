# Prototipo estático para Figma Make

Esta carpeta es una réplica navegable del Minimarket Don Pepe con datos simulados. No se conecta a Express, MySQL ni Docker: su propósito es presentar, probar flujos y convertir la interfaz en un prototipo de Figma.

## Abrir localmente

Abre `index.html` con un navegador o con Live Server en Visual Studio Code.

## Llevarlo a Figma Make

1. Crea un archivo nuevo en **Figma Make**.
2. Abre **Code** y sube o arrastra los archivos de esta carpeta.
3. Indica en el chat de Make: `Usa index.html, styles.css y app.js como fuente. Conserva sin cambios la identidad visual, las tres experiencias por rol y todas las interacciones simuladas.`
4. Si Make trabaja con React, pide que convierta el contenido a componentes sin modificar la estructura, estilos ni estados descritos en los archivos.

## Perfiles de demostración

- Administrador: dashboard, catálogos, usuarios, compras, WMS, inventario, ventas y reportes.
- Almacenero: recepción, tareas WMS, zonas/LOC, lotes, kardex, conteos y salud de stock.
- Vendedor: punto de venta, ventas propias y consulta básica de productos.

Las funciones se simulan en memoria durante la sesión: crear productos, proveedores, usuarios, órdenes, LOC, tareas y conteos; recibir órdenes; ejecutar tareas; aprobar auditorías; y cobrar ventas.
