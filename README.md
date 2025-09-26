# 🎬 Videoc v0

[![Laravel](https://img.shields.io/badge/Laravel-9.x-red?logo=laravel)](https://laravel.com/)
[![PHP](https://img.shields.io/badge/PHP-8.x-blue?logo=php)](https://www.php.net/)
[![GitHub](https://img.shields.io/badge/GitHub-videoc--v0-181717?logo=github)](https://github.com/g-masdeu/videoc-v0)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

Videoc es una aplicación web desarrollada con **Laravel** que permite a los usuarios explorar un catálogo de películas. Los usuarios pueden ver el listado de películas, consultar detalles y, si son administradores, gestionar el contenido (crear, editar y eliminar películas).

---

## 🌟 Funcionalidades

### Para usuarios:
- 📄 Listado completo de películas.
- 🎥 Ver detalles de cada película (sinopsis, año, género, etc.).

### Para administradores:
- ➕ Crear nuevas películas.
- ✏️ Editar películas existentes.
- 🗑️ Eliminar películas del catálogo.

---

## 🛠 Tecnologías utilizadas

- **Framework:** Laravel 9.x  
- **Lenguaje:** PHP 8.x  
- **Base de datos:** MySQL / SQLite  
- **Frontend:** Blade Templates  
- **Autenticación:** Sistema de usuarios y roles (usuario/admin)  

---

## 🚀 Instalación

1. Clona el repositorio:
   ```bash
   git clone https://github.com/g-masdeu/videoc-v0.git
   cd videoc-v0
   ```
2. Instala las dependencias:
  ```bash
  composer install
   ```
3. Copia y configura el archivo .env:
  ```bash
  cp .env.example .env
```
  Edita los datos de conexión a tu base de datos:
```
  DB_CONNECTION=mysql
  DB_HOST=127.0.0.1
  DB_PORT=3306
  DB_DATABASE=nombre_de_tu_base
  DB_USERNAME=usuario
  DB_PASSWORD=contraseña
  ```
4. Genera la clave de la aplicación:
  ```bash
  php artisan key:generate
```

5. Ejecuta migraciones y seeders:
  ```bash
  php artisan migrate --seed
```

6. Levanta el servidor local:
  ```bash
  php artisan serve
```

El correo y la constraseña para el admin son: admin@admin.es y contraseña: admin1234

📌 Uso
Accede a la página principal para ver el listado de películas.
Haz clic en cualquier película para ver sus detalles.
Inicia sesión como administrador para poder agregar, editar o eliminar películas.

🤝 Contribuciones

¡Las contribuciones son bienvenidas!
Abre un issue o un pull request para sugerir mejoras o reportar errores.
