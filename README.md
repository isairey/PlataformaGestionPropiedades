<div align="center">

<img width="220" src="https://cdn-icons-png.flaticon.com/512/3082/3082037.png" />

# 🏠 Laravel Rental Management System

### Plataforma web de gestión de rentas y propiedades 🚀

<p align="center">
  <b>Laravel Rental Management System</b> es una plataforma moderna desarrollada con Laravel para administrar propiedades, clientes, contratos de renta y operaciones inmobiliarias desde un entorno web seguro y dinámico.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Laravel-RentalSystem-FF2D20?style=for-the-badge&logo=laravel&logoColor=white">
  <img src="https://img.shields.io/badge/PHP-FullStack-777BB4?style=for-the-badge&logo=php&logoColor=white">
  <img src="https://img.shields.io/badge/MySQL-Database-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/OpenSource-PropertyManagement-success?style=for-the-badge">
</p>

<p align="center">
  <a href="#-acerca-del-proyecto">Acerca</a> •
  <a href="#-módulos-del-sistema">Módulos</a> •
  <a href="#-características">Características</a> •
  <a href="#-tecnologías-utilizadas">Tecnologías</a> •
  <a href="#-vista-previa">Vista previa</a>
</p>

</div>

---

# 🌌 Acerca del proyecto

**Laravel Rental Management System** es una plataforma inmobiliaria diseñada para automatizar la administración de propiedades y procesos de renta mediante una arquitectura moderna basada en Laravel.

El sistema permite gestionar:

- 🏠 Propiedades
- 👥 Inquilinos
- 📄 Contratos de renta
- 💳 Pagos y facturación
- 📅 Reservaciones
- 📊 Reportes administrativos
- 🔐 Usuarios y permisos
- 🌐 Operaciones inmobiliarias

---

# ✨ Características

## 🏘️ Gestión de propiedades

- 🏠 Registro de propiedades
- 📍 Gestión de ubicaciones
- 🖼️ Carga de imágenes
- 💰 Configuración de precios
- 📋 Información detallada

---

## 👥 Gestión de usuarios

- 👤 Registro de clientes
- 🔐 Inicio de sesión seguro
- 📄 Gestión de perfiles
- ⚡ Roles y permisos
- 📊 Administración centralizada

---

## 📄 Administración de rentas

- 📅 Gestión de contratos
- 💳 Control de pagos
- 📊 Historial de rentas
- 🏘️ Seguimiento de propiedades
- ⚡ Administración automatizada

---

## 📊 Panel administrativo

- 📈 Dashboard dinámico
- 👥 Gestión de usuarios
- 🏠 Supervisión inmobiliaria
- 💳 Control financiero
- 🔐 Gestión del sistema

---

# 👨‍💼 Módulos del sistema

## 🏠 Property Module

Módulo encargado de la gestión de propiedades inmobiliarias.

### Funcionalidades:

- ➕ Registro de propiedades
- 🖼️ Gestión de imágenes
- 📍 Configuración de ubicación
- 💰 Administración de precios
- 📋 Información inmobiliaria

---

## 👥 Tenant Module

Módulo utilizado por los inquilinos del sistema.

### Funcionalidades:

- 🔍 Buscar propiedades
- 📅 Solicitar rentas
- 💳 Gestionar pagos
- 📄 Consultar contratos
- 📋 Historial de actividades

---

## 🛠️ Admin Module

Módulo principal de administración.

### Funcionalidades:

- 👥 Gestión de usuarios
- 🏠 Supervisión de propiedades
- 📊 Dashboard administrativo
- 💳 Gestión financiera
- ⚙️ Configuración del sistema

---

# 🛠️ Tecnologías utilizadas

## 🎨 Frontend

<p>
  <img src="https://skillicons.dev/icons?i=html,css,js,bootstrap" />
</p>

- HTML5
- CSS3
- JavaScript
- Bootstrap
- Blade Templates

---

## ⚙️ Backend

<p>
  <img src="https://skillicons.dev/icons?i=php,laravel" />
</p>

- PHP
- Laravel
- Arquitectura MVC
- Eloquent ORM
- REST API

---

## 🗄️ Base de datos

<p>
  <img src="https://skillicons.dev/icons?i=mysql" />
</p>

- MySQL
- Relaciones SQL
- Migraciones Laravel
- Persistencia de datos

---

## 🧰 Herramientas

<p>
  <img src="https://skillicons.dev/icons?i=git,github,vscode" />
</p>

- Git
- GitHub
- Composer
- Visual Studio Code
- Laravel Artisan

---

# 📂 Estructura del proyecto

```bash
PlataformaGestionPropiedades
/
│
├── app/                      # Lógica del sistema
├── bootstrap/                # Bootstrap Laravel
├── config/                   # Configuración
├── database/                 # Migraciones y seeders
├── public/                   # Archivos públicos
├── resources/                # Vistas y assets
├── routes/                   # Rutas web y API
├── storage/                  # Archivos temporales
├── tests/                    # Pruebas
├── vendor/                   # Dependencias
├── artisan                   # CLI Laravel
├── .env
├── composer.json
├── README.md
└── LICENSE
```

---

# ⚡ Instalación

## 📋 Requisitos

- PHP 8+
- Composer
- MySQL
- Node.js
- Apache / Nginx

---

# 🚀 Configuración del proyecto

## 1️⃣ Clonar repositorio

```bash
git clone https://github.com/isairey/PlataformaGestionPropiedades
.git
```

---

## 2️⃣ Instalar dependencias

```bash
composer install
```

---

## 3️⃣ Instalar dependencias frontend

```bash
npm install
```

---

## 4️⃣ Configurar entorno

```bash
cp .env.example .env
```

---

## 5️⃣ Generar clave Laravel

```bash
php artisan key:generate
```

---

## 6️⃣ Configurar base de datos

Editar archivo `.env`

```env
DB_DATABASE=rental_management
DB_USERNAME=root
DB_PASSWORD=
```

---

## 7️⃣ Ejecutar migraciones

```bash
php artisan migrate
```

---

## 8️⃣ Iniciar servidor

```bash
php artisan serve
```

---

## 9️⃣ Abrir sistema

```bash
http://127.0.0.1:8000
```

---

# 📊 Funcionalidades principales

## 🏠 Gestión inmobiliaria

- Administración de propiedades
- Gestión de contratos
- Historial de rentas
- Gestión de imágenes

---

## 👥 Administración de usuarios

- Registro y autenticación
- Roles administrativos
- Gestión de perfiles
- Seguridad integrada

---

## 💳 Control financiero

- Pagos de rentas
- Facturación
- Reportes financieros
- Historial de transacciones

---



# 🧠 Objetivos del proyecto

## 🎯 Aprendizaje y administración

- Desarrollo full stack
- Arquitectura MVC
- Gestión inmobiliaria
- Seguridad web
- Bases de datos relacionales
- APIs modernas
- Automatización administrativa

---

# 🚧 Roadmap

## 🔮 Próximas mejoras

- 📱 Aplicación móvil
- ☁️ Deploy cloud
- 💳 Pagos electrónicos
- 🤖 Recomendaciones inteligentes
- 📊 Dashboard avanzado
- 🌐 API REST completa
- 🔔 Notificaciones en tiempo real

---

# 🤝 Contribuciones

Las contribuciones son bienvenidas ❤️

## Cómo contribuir

1. Fork del proyecto

```bash
git checkout -b feature/nueva-funcionalidad
```

2. Commit

```bash
git commit -m "✨ Nueva funcionalidad"
```

3. Push

```bash
git push origin feature/nueva-funcionalidad
```

4. Pull Request 🚀

---

# 👨‍💻 Desarrollador

<div align="center">

## Isai Reyes — Laravel Full Stack Developer

Desarrollador apasionado por plataformas inmobiliarias, sistemas administrativos y aplicaciones modernas 🚀

</div>

---

# 🌟 Apoya el proyecto

⭐ Dale una estrella  
🍴 Haz fork  
📢 Comparte el proyecto

---

# 📜 Licencia

Proyecto open source bajo licencia MIT orientado al aprendizaje y administración de sistemas de renta inmobiliaria.

---

<div align="center">

### 🏠 Laravel Rental Management System — administración inteligente de propiedades y rentas 🚀

</div>
