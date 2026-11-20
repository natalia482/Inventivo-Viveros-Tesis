<div align="center">
  <img src="LOGO.png" alt="Logo Inventivo" width="160">

  <h1>🌿 Inventivo - Sistema de Gestión de Inventarios para Viveros 🌿</h1>
  <p><em>Digitalización y control eficiente de inventarios, insumos y remisiones para viveros de la región del Sumapaz</em></p>

  <a href="https://inventivo-viveros.onrender.com" target="_blank">
    <img src="https://img.shields.io/badge/🌐_Plataforma_Web-Visitar_en_Vivo-2E7D32?style=for-the-badge" alt="Plataforma Web en Vivo">
  </a>
  <a href="https://inventivo.onrender.com/plantas/listar.php?id_sede=10" target="_blank">
    <img src="https://img.shields.io/badge/⚙️_API_REST-Estado_Live-388E3C?style=for-the-badge" alt="API REST en Vivo">
  </a>
  <a href="https://repositorio.ucundinamarca.edu.co/items/36d9ba09-f551-4e5d-9a89-40fdbc981e68" target="_blank">
    <img src="https://img.shields.io/badge/🎓_Tesis_UdeC-Repositorio_Institucional-1B5E20?style=for-the-badge" alt="Repositorio Institucional UdeC">
  </a>
  <br><br>
</div>

---

## 📝 Descripción del Proyecto

**Inventivo** es una solución tecnológica diseñada para la digitalización y el control eficiente de inventarios en viveros. Desarrollada para la región del **Sumapaz**, con énfasis en la zona de **Chinauta, Cundinamarca**, la plataforma busca resolver la falta de herramientas accesibles para el manejo y monitoreo de la producción vegetal en comercios locales.

## 📌 Problema y Solución

Muchos viveristas de la región operan sin un sistema automatizado para registrar sus existencias, ventas y tipos de plantas, lo que puede generar pérdidas de información y descontrol operativo.

**Inventivo** centraliza y automatiza estos procesos mediante las siguientes funcionalidades:

- 🔐 **Autenticación y Roles:** Control de acceso seguro diferenciado para Propietarios, Administradores y Trabajadores por sede.
- 📦 **Gestión de Inventarios (CRUD):** Control completo de existencias de plantas, precios, insumos agrícolas y alertas de stock.
- 🧾 **Remisiones y Comprobantes PDF:** Generación automática de remisiones de venta descargables con cálculo de totales y actualización de inventario.
- 📋 **Auditoría y Trazabilidad:** Registro histórico de movimientos operativos realizados por cada usuario en el sistema.
- 🤖 **Asistente Virtual Integrado:** Módulo de chatbot de consulta y apoyo operativo dentro de la aplicación.
- 🌐 **Multiplataforma y Cloud:** Acceso desde navegador web y compatibilidad con dispositivos móviles, desplegado en la nube.

## 🛠️ Stack Tecnológico

- **Frontend:** Flutter (Dart).
- **Backend:** API REST propia desarrollada en PHP 8.2 (Arquitectura MVC + PDO) en contenedor Docker.
- **Base de Datos:** MySQL, administrada mediante phpMyAdmin (Clever Cloud en producción / XAMPP en local).
- **Diseño UI/UX:** Figma.
- **Despliegue Cloud:** Render (Static Site & Web Service) y Clever Cloud.

## 🔑 Acceso a la Demo en Vivo

Puedes probar la plataforma desplegada en **[inventivo-viveros.onrender.com](https://inventivo-viveros.onrender.com)** con las siguientes credenciales de demostración:

| Rol | Correo Electrónico | Contraseña |
|:---:|:---|:---|
| **Propietario / Admin** | `inventivoprueba@gmail.com` | `password` |

> *Nota: El backend está alojado en una instancia gratuita de Render; tras 15 minutos de inactividad, la primera petición puede tardar ~30 segundos mientras se activa el servidor.*

## 📸 Vista Previa

| Prototipo en Figma | Pantalla de Inicio | Pantalla de Login |
|:---:|:---:|:---:|
| <img src="./image.png" alt="Prototipo en Figma" width="100%"> | <img src="./image-2.png" alt="Pantalla de Inicio" width="100%"> | <img src="./image-1.png" alt="Pantalla de Login" width="100%"> |

## ⚙️ Requisitos Previos e Instalación Local

### Requisitos
Antes de ejecutar el proyecto localmente, asegúrate de contar con las siguientes herramientas:
- **Flutter SDK:** versión 3.0.0 o superior.
- **Dart SDK.**
- **Servidor web local:** XAMPP, WAMP o Laragon, con PHP y MySQL habilitados.
- **Android Studio:** opcional, para compilar y ejecutar la aplicación en Android.
- **Google Chrome:** para ejecutar la versión web.

### Pasos de configuración local

1. **Clonar el repositorio:**
   ```bash
   git clone [https://github.com/natalia482/Inventivo-Viveros-Tesis.git](https://github.com/natalia482/Inventivo-Viveros-Tesis.git)
   cd Inventivo-Viveros-Tesis
Configurar el backend y la base de datos:

Inicia los servicios de Apache y MySQL desde tu servidor local (XAMPP, WAMP o Laragon).

Abre phpMyAdmin en tu navegador: http://localhost/phpmyadmin.

Crea una nueva base de datos con el nombre bd_inventivo e importa el archivo SQL del proyecto.

Ubica los archivos del backend en la carpeta de tu servidor web local (por ejemplo: C:\xampp\htdocs\inventivo_backend).

Actualiza las credenciales de conexión en config/conexion.php si es necesario (host, usuario, contraseña y nombre de la base de datos).

Instalar las dependencias de Flutter:
Desde la raíz del proyecto, ejecuta:

Bash
flutter pub get
Ejecutar la aplicación:

En navegador web (Google Chrome):

Bash
flutter run -d chrome
En un emulador Android o dispositivo móvil:

Bash
flutter run
📜 Propiedad Intelectual y Publicación
Registro Nacional: El software cuenta con registro oficial ante la Dirección Nacional de Derecho de Autor (DNDA) de Colombia (Registro N.° 13-106-362).

Publicación académica: La tesis completa puede consultarse en el Repositorio Institucional de la Universidad de Cundinamarca.

👥 Autores y Créditos
Este proyecto fue desarrollado como trabajo de grado en la Universidad de Cundinamarca.

Natalia Villalobos

Ingeniera de Sistemas y Computación 💻

GitHub: @natalia482

LinkedIn: Briyit Natalia Villalobos Rodríguez

Jesús Aguirre

Ingeniero de Sistemas y Computación 💻

GitHub: @JesusDAguirre