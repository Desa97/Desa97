-gantt
    title Proyecto Instavi - Módulo de Administración
    dateFormat  YYYY-MM-DD
    section Registro y Autenticación
    Registro de Administradores :a1, 2024-10-01, 1w
    Inicio de Sesión de Administradores :a2, after a1, 1w
    Contraseña Segura :a3, after a2, 1w
    Cierre de Sesión Seguro :a4, after a3, 1w
    
    section Gestión de Usuarios y Roles
    Crear/Actualizar/Eliminar Cuentas de Usuario :b1, after a4, 2w
    Asignación de Roles y Permisos :b2, after b1, 2w
    Auditoría de Actividades :b3, after b2, 2w
    Notificaciones a Administradores :b4, after b3, 1w
    
    section Gestión de Inventario
    Agregar/Actualizar/Eliminar Productos de Inventario :c1, after b4, 3w
    
    section Configuración General y Seguridad
    Configuración del Sistema :d1, after c1, 2w
    Generación y Exportación de Reportes :d2, after d1, 2w
    Respaldo y Restauración de Base de Datos :d3, after d2, 1w>
