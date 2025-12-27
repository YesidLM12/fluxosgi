# Sistema de Gestión de Inventario (SGI)

## 📝 Descripción
Este proyecto consiste en una plataforma integral para el control de activos, gestión de flujos comerciales y administración de relaciones con terceros (clientes y proveedores). El sistema está diseñado para optimizar la cadena de suministro y proporcionar visibilidad en tiempo real mediante un tablero de control analítico.

## 🛠️ Requerimientos Funcionales (RF)

### 1. Gestión de Usuarios y Seguridad (RBAC)
- **Autenticación:** Inicio de sesión seguro con hashing de contraseñas.
- **Roles y Permisos:** - `Admin`: Control total del sistema.
  - `Almacenista`: Gestión de stock y movimientos.
  - `Vendedor`: Consulta de precios y creación de órdenes.
- **Auditoría:** Registro de actividades críticas (logs) por usuario.

### 2. Módulo de Inventario
- **Maestro de Productos:** CRUD completo con campos para SKU, código de barras, categorías y stock mínimo.
- **Control de Existencias:** Actualización automática ante entradas y salidas.
- **Alertas:** Notificaciones de stock bajo basadas en umbrales configurables.

### 3. Terceros y Entidades
- **Gestión de Proveedores:** Registro de contactos y catálogos de suministro.
- **Gestión de Clientes:** Base de datos de clientes con historial de compras.

### 4. Gestión de Órdenes
- **Flujo de Trabajo:** Creación y seguimiento de órdenes (Compra/Venta).
- **Estados de Orden:** `Pendiente`, `En Proceso`, `Completado`, `Cancelado`.
- **Lógica de Negocio:** Validación de disponibilidad antes de confirmar salidas.

### 5. Reportes y Analítica
- **Dashboard:** Gráficos interactivos de movimientos mensuales y productos estrella.
- **Exportación:** Generación de reportes en formato **CSV** para análisis externo.

## 🚀 Funcionalidades Extra (Roadmap)
- [ ] Soporte para múltiples almacenes (Multi-warehouse).
- [ ] Integración con lectores de códigos de barras (API de cámara o escáner).
- [ ] Sistema de valoración de inventario (PEPS/FIFO).

## 🗂️ Estructura de Datos Sugerida


## 💻 Stack Tecnológico
- **Backend:** Java / Spring Boot / Spring Security / Spring Data / Hibernate.
- **Frontend:** React.
- **Base de Datos:** MySQL.
- **Autenticación:** JSON Web Tokens (JWT).

## 📄 Licencia
Este proyecto está bajo la Licencia MIT.