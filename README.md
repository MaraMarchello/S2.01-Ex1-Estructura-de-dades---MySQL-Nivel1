# S2.01-Ex1-Estructura-de-dades---MySQL-Nivel1
# Sistema de Gestión de Base de Datos para Óptica

## 📄 Descripción - Ejercicio
Este proyecto implementa un sistema de base de datos para una óptica. Gestiona información sobre proveedores, marcas, gafas, clientes, empleados y ventas. La estructura de la base de datos permite el seguimiento del inventario de gafas, información de clientes (incluidas recomendaciones) y registros de ventas.

## 💻 Tecnologías utilizadas
- Java
- SQL (Base de datos H2)
- JDBC
- Eclipse IDE

## 📋 REQUISITOS
- Java JDK 11 o superior
- Eclipse IDE
- Motor de base de datos H2

## 🛠️ Instalación
1. Clonar el repositorio:
   ```
   git clone https://github.com/MaraMarchello/S2.01-Ex1-Estructura-de-dades---MySQL-Nivel1.git
   ```
2. Abrir el proyecto en Eclipse:
   - Archivo > Importar > Proyectos existentes en el espacio de trabajo
   - Seleccionar el directorio del repositorio clonado
   - Hacer clic en Finalizar

3. Configurar la conexión a la base de datos si es necesario en las propiedades de la aplicación.

## ▶️ Implementación
1. El esquema de la base de datos se crea automáticamente utilizando el archivo `schema.sql`
2. Los datos de muestra se cargan desde el archivo `data.sql`
3. Ejecutar la aplicación para comenzar a gestionar la base de datos de la óptica

## 🌐 DESPLIEGUE
Para desplegar este proyecto en un entorno de producción:

1. Configurar un servidor de base de datos de producción (MySQL, PostgreSQL, etc.)
2. Actualizar las propiedades de conexión a la base de datos para apuntar a tu base de datos de producción
3. Ejecutar el script schema.sql en tu base de datos de producción
4. Configurar tu servidor de aplicaciones (Tomcat, Jetty, etc.) para desplegar la aplicación

## 🤝 Contribución
Si deseas contribuir a este proyecto:

1. Haz un fork del repositorio
2. Crea una rama de características (`git checkout -b feature/TuFuncion`)
3. Confirma tus cambios (`git commit -m 'Añadir TuFuncion'`)
4. Sube a la rama (`git push origin feature/TuFuncion`)
5. Abre una solicitud de extracción
