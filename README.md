# 🏋️‍♂️ GymPulse: Sistema de Gestión de Gimnasio Privado

## 📄 Descripción del Proyecto
Este proyecto consiste en el desarrollo de una aplicación multiplataforma para la gestión integral de un gimnasio privado. El objetivo es digitalizar el control de acceso, la gestión de clases y el seguimiento de los socios.

La aplicación será accesible desde distintos dispositivos (PC para administración, móvil/tablet para socios), permitiendo una interacción fluida entre el gimnasio y sus usuarios.

## 🚀 Funcionalidades Principales

### 1. Gestión de Socios (Usuarios)
* **Registro y Perfil:** Alta de nuevos socios, edición de datos personales y consulta de historial de asistencia.
* **Autenticación:** Sistema de login seguro diferenciado para socios y administradores.
* **Membresía:** Visualización del estado de la cuota (activa/vencida).

### 2. Gestión de Actividades y Máquinas
* **Catálogo de Clases:** Búsqueda de clases (Yoga, Crossfit, Pilates) por horario o monitor.
* **Reservas:** Sistema para apuntarse a clases con control de aforo y fechas límite.
* **Inventario:** Control de máquinas y estado de mantenimiento (Alta/Baja/Reparación).

### 3. Panel de Administración
* **Dashboard:** Estadísticas de uso, socios activos y clases más populares.
* **Gestión de Usuarios:** Posibilidad de modificar datos de socios o dar de baja perfiles.
* **Notificaciones:** Envío de avisos sobre cambios de horario o recordatorios de renovación.

## 🛠️ Stack Tecnológico
Siguiendo las recomendaciones para desarrollo moderno:

* **Lenguaje:** Java / Kotlin (Android) o JavaScript (React Native).
* **Base de Datos:** Firebase (tiempo real) o MySQL.
* **Interfaz Gráfica:** XML/Jetpack Compose o CSS/Bootstrap.
* **Control de Versiones:** Git + GitHub.
* **IDE:** Android Studio / IntelliJ IDEA / VS Code.

## 🎨 Diseño e Interfaz (UI/UX)
El diseño busca ser limpio y minimalista para facilitar la navegación.
* **Paleta de Colores:** Tonos enérgicos pero legibles (Negro, Blanco, Naranja/Azul).
* **Tipografía:** Fuentes legibles como Roboto o Open Sans.
* **Responsive:** Adaptable a pantallas de móvil y escritorio.

## 📱 Prototipos (Wireframes)

### Pantalla de Login
```text
+--------------------------------------+
|             [cite_start][ LOGO GYM ]             | [cite: 30]
|   "Bienvenido a tu zona de entreno"  |
|--------------------------------------|
| [cite_start][ Email / Usuario ]                  | [cite: 31]
| [ Contraseña ]                       |
| [cite_start][ INICIAR SESIÓN ]                   | [cite: 32]
| ¿Olvidaste tu contraseña?            [cite_start]| [cite: 33]
+--------------------------------------+

+--------------------------------------------------+
| Estadísticas del día:                            | [cite: 91]
| - Socios en el centro: 45                        | [cite: 93]
| - Clases completas: 2                            |
|--------------------------------------------------|
| Gestión:                                         |
| [Añadir Clase] [Gestionar Socios] [Inventario]   | [cite: 96, 99]
+--------------------------------------------------+

