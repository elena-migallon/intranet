# Intranet Web – Proyecto DAW

Proyecto de intranet web desarrollado como parte de la formación en Desarrollo de Aplicaciones Web (DAW).  
La aplicación está orientada a la gestión interna de una empresa, incluyendo módulos de ventas, recursos humanos y facturación.

---

## Descripción

Aplicación web diseñada para la gestión de procesos internos, permitiendo:

- Gestión de empleados, centros y productos (RRHH)
- Gestión de clientes y ventas
- Registro y consulta de facturación
- Control de acceso mediante autenticación de usuarios

El objetivo del proyecto fue desarrollar una solución funcional que automatizara tareas administrativas y centralizara la información en una única plataforma.

---

## Arquitectura

El proyecto sigue una estructura modular basada en la separación de responsabilidades, inspirada en el patrón MVC:

- `app/` → Configuración, lógica de negocio y acceso a datos.
- `plantillas/` → Vistas y componentes reutilizables (cabecera, navegación, pie).
- `public/` → Punto de entrada y recursos públicos (index, imágenes, login).
- `vendor/` → Dependencias gestionadas con Composer.
- `composer.json` → Gestión de dependencias y autoload.

---

## Gestión de sesiones, acceso y roles

El acceso a la intranet está protegido mediante control de sesiones en PHP. 
Garantizando que únicamente usuarios registrados puedan acceder a la aplicación y en función de su rol.

---

## Base de datos

Base de datos relacional diseñada en MySQL.

Incluye:

- Tablas independientes disponibles en la carpeta `Dump20241208`.
- Archivo completo `Dump20241208.sql` con la base de datos íntegra.

Se aplicaron CRUD y consultas SQL

---

## Tecnologías utilizadas

- PHP
- MySQL
- HTML5
- CSS3
- JavaScript
- Bootstrap
- Composer (gestión de dependencias)

---

## Estado del proyecto

Proyecto académico desarrollado con fines formativos.  
Funcional y estructurado, con posibilidad de ampliación y mejora.

