# Vianda Market - Backend 🥩

Vianda Market es una plataforma de e-commerce dedicada a la venta de cortes de carne y productos de alta calidad. Este repositorio contiene el desarrollo del **Backend (API REST)** que da soporte a las operaciones de la tienda y el panel de administración del proyecto.

🔗 **[Visita el proyecto en vivo aquí](https://viandamarket-front-production.up.railway.app/)**

## ✨ Características Principales

El backend está diseñado para ofrecer un servicio seguro y eficiente:

- **🥩 Catálogo y Productos**: Endpoints para la gestión y listado de cortes de carne, gramajes, calidades y complementos.
- **🛒 Pedidos y Checkout**: Gestión persistente de pedidos y lógica backend para la pasarela de pagos.
- **🔐 Seguridad y Autenticación**: Sistema de usuarios, registro, inicio de sesión y protección de rutas mediante Tokens (JWT) y Spring Security.
- **⚙️ Diseño RESTful**: Arquitectura basada en API REST lista para integrarse sin problemas con el cliente web.

## 🛠️ Tecnologías Utilizadas

- Java (Lenguaje principal)
- Spring Boot (Framework web, Data JPA, Security)
- JSON Web Tokens (JWT) (Autenticación)
- MySQL (Base de datos relacional)
- Gradle (Gestor de dependencias y construcción)

## 🚀 Ejecución Local

> **⚠️ Importante:** Para ver la aplicación completa en funcionamiento (interfaz gráfica), también necesitarás el frontend. Puedes verlo desplegado en: **[Vianda Market Frontend](https://viandamarket-front-production.up.railway.app/)**.

1. Clona este repositorio en tu máquina local:
   ```bash
   git clone <URL_DEL_REPOSITORIO_BACKEND>
   cd GenMx-ViandaMarket-Back
   ```
2. Configura la base de datos:
   - Abre la carpeta `BaseDeDatos/` donde encontrarás los scripts SQL (`.sql` y modelo `.mwb`).
   - Ejecuta los scripts en tu servidor MySQL local para crear las tablas e insertar registros.
   - Revisa y ajusta las credenciales de conexión en `src/main/resources/application.properties` para que coincidan con tu base de datos local.
3. Ejecuta el proyecto usando Gradle:
   - En la raíz del proyecto, abre tu consola y ejecuta la siguiente instrucción:
     ```bash
     ./gradlew bootRun
     ```
     *(En Windows: `gradlew.bat bootRun`)*
4. El servidor se levantará de forma local en el puerto `8080` (ej: `http://localhost:8080`).
