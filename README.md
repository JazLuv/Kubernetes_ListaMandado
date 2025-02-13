# 🛒 Sistema de Gestión de Lista de Compras con Docker y Kubernetes

Sistema moderno para gestionar listas de compras (mandado) implementado con **Python**, **Flask** y desplegado en contenedores **Docker** orquestados por **Kubernetes** (minikube). Este proyecto demuestra buenas prácticas de desarrollo moderno y DevOps.

---

## 📋 Descripción del Proyecto

Este proyecto es un sistema de gestión de listas de compras diseñado para ayudar a los usuarios a organizar sus compras de manera eficiente. Permite crear, editar, eliminar y marcar productos como comprados. La aplicación está completamente containerizada usando **Docker** y desplegada en un cluster local de **Kubernetes** usando **minikube**.

---

## 🚀 Características Principales

- **Creación de listas de compras**: Los usuarios pueden crear múltiples listas de compras.
- **Gestión de productos**: Añadir, editar y eliminar productos de la lista.
- **Marcado de productos**: Marcar productos como comprados.
- **Interfaz amigable**: Diseño responsive y fácil de usar gracias a **Bootstrap**.
- **Containerización**: La aplicación está completamente containerizada con **Docker**.
- **Despliegue en Kubernetes**: Despliegue automatizado en un cluster de **Kubernetes** usando **minikube**.

---

## 🛠️ Tecnologías Utilizadas

### Backend
- **Python 3.x**: Lenguaje de programación principal.
- **Flask**: Framework web para construir la API y la lógica del servidor.
- **MySQL 8.0**: Base de datos para almacenar la información de las listas y productos.

### Frontend
- **HTML5**: Estructura de la interfaz de usuario.
- **CSS3**: Estilos para la interfaz.
- **JavaScript**: Interactividad en el lado del cliente.
- **Bootstrap 5**: Framework CSS para diseño responsive y componentes predefinidos.

### DevOps & Infraestructura
- **Docker**: Containerización de la aplicación.
- **Kubernetes (minikube)**: Orquestación de contenedores para despliegue local.
- **kubectl**: Herramienta para gestionar el clúster de Kubernetes.

---

## 🛠️ Configuración y Despliegue

### Prerrequisitos

Antes de comenzar, asegúrate de tener instalado lo siguiente:

```bash
# Instalar Docker
https://docs.docker.com/get-docker/

# Instalar minikube
https://minikube.sigs.k8s.io/docs/start/

# Instalar kubectl
https://kubernetes.io/docs/tasks/tools/

# Instalar Git
https://git-scm.com/downloads
```

---

## 💡 Beneficios de esta Arquitectura

### Desarrollo

- **Entorno de desarrollo consistente**: Todos los desarrolladores trabajan en el mismo entorno.
- **Fácil replicación del entorno**: Cualquier persona puede replicar el entorno con Docker.
- **Separación clara de componentes**: Backend, frontend y base de datos están separados.
- **Control de versiones efectivo**: Uso de Git para gestionar el código.

### Operaciones

- **Despliegue automatizado**: Kubernetes gestiona el despliegue de la aplicación.
- **Escalabilidad horizontal**: Fácilmente escalable añadiendo más réplicas.
- **Fácil mantenimiento**: Actualizaciones y rollbacks simplificados.
- **Monitoreo integrado**: Herramientas de monitoreo para supervisar el rendimiento.

### Seguridad

- **Aislamiento de componentes**: Cada servicio corre en su propio contenedor.
- **Gestión centralizada de secretos**: Kubernetes gestiona las credenciales de manera segura.
- **Actualizaciones simplificadas**: Actualizaciones sin tiempo de inactividad.
- **Backup y recuperación robustos**: Facilidad para hacer backup de la base de datos.

---

## ✍️ Autor

**Jaziel Benitez Alavez**, Estudiante de Desarrollo de Software.

- **GitHub**: [JazLuv](https://github.com/JazLuv)