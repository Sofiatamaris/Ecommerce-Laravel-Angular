# Proyecto Ecommerce FullStack con Laravel 10 y Angular 17

Este repositorio alberga el código fuente de un sistema de comercio electrónico integral. El proyecto consta de un robusto backend desarrollado con Laravel 
y dos interfaces de usuario frontend independientes creadas con Angular: una para la tienda online (ecommerce) y otra para la administración.

## Características Principales del Ecommerce:

* **Arquitectura FullStack:**
    * **Backend:** API RESTful desarrollada con Laravel.
    * **Frontend:** Dos aplicaciones Angular separadas:
      
        * **Ecommerce:** Interfaz para los clientes.
          ![](https://github.com/Sofiatamaris/Ecommerce-Laravel-Angular/blob/main/imagenes/tienda.png?raw=true)
  
           
        * **Administrador:** Panel para la gestión del sistema.
          ![](https://github.com/Sofiatamaris/Ecommerce-Laravel-Angular/blob/main/imagenes/admin.png?raw=true)
          
* **Tecnologías Frontend:**
    * Angular 17: Arquitectura standalone y Server-Side Rendering (SSR).
    * Carrito de compra: Implementado de forma asíncrona utilizando BehaviorSubject.
* **Backend y Base de Datos:**
    * Laravel: Framework PHP para el desarrollo del backend y la API.
    * MySQL: Base de datos relacional para el almacenamiento de la información.
* **Seguridad:**
    * JWT (JSON Web Tokens): Implementación para la autenticación y autorización segura de la API.
* **Notificaciones:**
    * Envío automático de correos electrónicos con los detalles de las compras realizadas.
* **Control de Acceso:**
    * Uso de Guards en Angular para la protección y control de acceso a las diferentes rutas de las aplicaciones frontend.
* **Gestión de Productos:**
    * Módulo completo para la administración de productos, incluyendo variaciones y especificaciones.
* **Marketing y Ventas:**
    * Módulo para la creación y gestión de promociones y cupones de descuento.
* **Moneda:**
    * Funcionalidad para el cambio dinámico de monedas entre Bolivares (VEN) y Dólares estadounidenses (USD).
* **Reportes y Análisis:**
    * Generación de reportes gráficos detallados sobre las ventas (mensuales, anuales, por categorías y marcas).
    * Opción para descargar los reportes de ventas en formatos Excel (XLSX) y PDF.
* **Pasarelas de Pago:**
    * Integración de las pasarelas de pago de Paypal y Mercado Pago para aceptar pagos con tarjetas de crédito y débito.
