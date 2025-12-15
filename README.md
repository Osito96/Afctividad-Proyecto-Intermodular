# 🏋️‍♂️ GymPulse: Sistema de Gestión de Gimnasio Privado

## 📄 Descripción del Proyecto
Este proyecto consiste en el desarrollo de una aplicación multiplataforma para la gestión integral de un gimnasio privado. [cite_start]El objetivo es digitalizar el control de acceso, la gestión de clases y el seguimiento de los socios[cite: 1].

[cite_start]La aplicación será accesible desde distintos dispositivos (PC para administración, móvil/tablet para socios)[cite: 2], permitiendo una interacción fluida entre el gimnasio y sus usuarios.

## 🚀 Funcionalidades Principales

### 1. Gestión de Socios (Usuarios)
* [cite_start]**Registro y Perfil:** Alta de nuevos socios, edición de datos personales y consulta de historial de asistencia[cite: 4, 31].
* [cite_start]**Autenticación:** Sistema de login seguro diferenciado para socios y administradores[cite: 8, 34].
* **Membresía:** Visualización del estado de la cuota (activa/vencida).

### 2. Gestión de Actividades y Máquinas
* [cite_start]**Catálogo de Clases:** Búsqueda de clases (Yoga, Crossfit, Pilates) por horario o monitor[cite: 3].
* [cite_start]**Reservas:** Sistema para apuntarse a clases con control de aforo y fechas límite[cite: 5].
* [cite_start]**Inventario:** Control de máquinas y estado de mantenimiento (Alta/Baja/Reparación)[cite: 3, 6].

### 3. Panel de Administración
* [cite_start]**Dashboard:** Estadísticas de uso, socios activos y clases más populares[cite: 6, 40].
* [cite_start]**Gestión de Usuarios:** Posibilidad de modificar datos de socios o dar de baja perfiles[cite: 42].
* [cite_start]**Notificaciones:** Envío de avisos sobre cambios de horario o recordatorios de renovación[cite: 39].

## 🛠️ Stack Tecnológico
[cite_start]Siguiendo las recomendaciones para desarrollo moderno[cite: 10]:

* [cite_start]**Lenguaje:** Java / Kotlin (Android) o JavaScript (React Native)[cite: 12].
* [cite_start]**Base de Datos:** Firebase (tiempo real) o MySQL[cite: 14].
* [cite_start]**Interfaz Gráfica:** XML/Jetpack Compose o CSS/Bootstrap[cite: 16].
* [cite_start]**Control de Versiones:** Git + GitHub[cite: 18].
* [cite_start]**IDE:** Android Studio / IntelliJ IDEA / VS Code[cite: 20].

## 🎨 Diseño e Interfaz (UI/UX)
[cite_start]El diseño busca ser limpio y minimalista para facilitar la navegación[cite: 26].
* [cite_start]**Paleta de Colores:** Tonos enérgicos pero legibles (Negro, Blanco, Naranja/Azul)[cite: 27].
* [cite_start]**Tipografía:** Fuentes legibles como Roboto o Open Sans[cite: 28].
* [cite_start]**Responsive:** Adaptable a pantallas de móvil y escritorio[cite: 29].

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

