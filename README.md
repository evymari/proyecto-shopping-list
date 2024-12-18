# 🛒 **Aplicación de Lista de la Compra: CRUD con JavaScript y Backend**

Este proyecto consiste en una lista de la compra funcional que permite gestionar productos a través de una aplicación frontend conectada a un backend desarrollado con Spring Boot.

## 🚀 **Características**

- **Frontend:** Interfaz para visualizar, añadir, actualizar y eliminar productos.
- **Backend:** API REST para operaciones CRUD con validaciones.
- **Persistencia:** Gestión de datos utilizando un repositorio de productos.

## 📝 **Tecnologías Utilizadas**

### Frontend:
- **HTML5** y **CSS3** para el diseño.
- **JavaScript** para la lógica y manejo del DOM.
- **Fetch API** para la comunicación con el backend.

### Backend:
- **Java** con **Spring Boot** para construir la API REST.
- **Spring Data JPA** para la gestión de la base de datos.
- **H2 Database** (configurable) como base de datos en memoria.

---

## 📂 **Estructura del Proyecto**

    ```plaintext
            ├── frontend/
            │   ├── index.html       # Interfaz principal
            │   ├── styles.css       # Estilos de la aplicación
            │   └── app.js           # Lógica de la lista de la compra
            ├── backend/
            │   ├── src/
            │   │   ├── main/
            │   │   │   ├── java/com/grupo4/shopping_list_backend/
            │   │   │   │   ├── ControllerProduct.java  # Controlador de la API
            │   │   │   │   ├── Product.java            # Modelo de producto
            │   │   │   │   └── ProductRepository.java  # Repositorio de productos
            │   │   └── resources/
            │   │       ├── application.properties     # Configuración del backend
            │   └── test/                              # Pruebas
            ├── README.md          # Documentación
📖 Uso




📖 Uso
1. Clonar el repositorio:
   bash

          git clone https://github.com/<tu-repositorio>.git
2. Configurar el Backend:
   Dirígete al directorio backend/.
   Configura el archivo application.properties según tus necesidades.

   Ejecuta la aplicación Spring Boot:

           mvn spring-boot:run

## 🤝 Contribuidores

Equipo de Desarrollo:

- Juan Ignacio -https://github.com/juanignacioFG
- Yuliia  -https://github.com/YuliiaBi1a
- Evelyn - https://github.com/evymari
- Carito - https://github.com/carovasq
- Paula - https://github.com/PCalvoGarcia


¡Gracias por visitar nuestro proyecto! 🎉

