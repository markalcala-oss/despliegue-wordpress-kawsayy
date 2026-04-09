# despliegue-wordpress-kawsayy
# Despliegue de WordPress en AWS - Proyecto Kawsay Villa Sur 🍈

Este repositorio contiene la documentación técnica y las evidencias del despliegue de una plataforma WordPress sobre una instancia de AWS (EC2), cumpliendo con los estándares de configuración de servidores Linux (LAMP Stack).

**Estudiante:** Mark Alcalá Peralta 
**Usuario del Sistema:** mark_alcala  
**IP del Servidor:** 98.81.151.201

---

## 🛠️ 1. Requerimiento Obligatorio de Usuario
Siguiendo las instrucciones del manual, se creó un usuario personalizado para gestionar todo el proceso de instalación, evitando trabajar directamente con el usuario por defecto (`ubuntu`).

* **Creación del usuario:** `sudo adduser mark_alcala`
* **Permisos Administrativos:** `sudo usermod -aG sudo mark_alcala`
* **Acceso:** El proceso se realizó logueado como `mark_alcala` mediante el comando `su - mark_alcala`.

---

## 🚀 2. Instalación del Stack LAMP
Para el funcionamiento de WordPress, se configuró el siguiente entorno:

1.  **L (Linux):** Ubuntu 24.04 LTS en AWS.
2.  **A (Apache):** Servidor web para servir el contenido de Kawsay Villa Sur.
3.  **M (MariaDB):** Motor de base de datos para almacenar productos y posts.
4.  **P (PHP):** Motor de procesamiento para WordPress.

---

## 🗄️ 3. Configuración de Base de Datos
Se ejecutaron los siguientes comandos en MariaDB para garantizar la persistencia de datos:

- **Base de Datos:** `kawsay_db`
- **Usuario de BD:** `mark_wp`
- **Privilegios:** Otorgados totalmente sobre `kawsay_db`.

---

## 🖼️ 4. Evidencias del Proyecto


---

## 🌐 5. Estructura de la Webb
El sitio final incluye las siguientes secciones personalizadas:
* **Inicio:** Bienvenida al mundo del maracuyá premium.
* **Nosotros:** Origen, Misión y Visión de la empresa.
* **origen:** Inicios de la empresa.

---
© 2026 - Proyecto Académico de Despliegue de Servidores.
