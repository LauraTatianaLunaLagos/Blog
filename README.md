# Blog Backend - Laravel

Este es el backend del blog, desarrollado con **Laravel** y basado en una API REST. Maneja la lógica del blog, incluyendo la gestión de autores y posts.

---

## Tecnologías utilizadas
- **Framework:** Laravel
- **Base de Datos:** MySQL
- **API:** Laravel API Resource
- **Autenticación:** No requerida

---

## Instalación y configuración

### **1. Clonar el repositorio**

### **2. Instalar dependencias**

### **3. Configurar la base de datos**
#### Importar la base de datos desde el script SQL

1. Abrir MySQL o phpMyAdmin.
2. Crear una base de datos llamada `blog_db`.
3. Importar el archivo del script

#### Configurar el archivo `.env`
Edita el archivo `.env` con los detalles de la base de datos:
```env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=blog_db
DB_USERNAME=TU_USUARIO
DB_PASSWORD=TU_CONTRASEÑA
```

### **4. Ejecutar migraciones (si no se importó la base de datos)**
```
php artisan migrate --seed
```

### **5. Iniciar el servidor de Laravel**
```
php artisan serve
```

## API Endpoints
Las rutas de la API están definidas en `routes/api.php`.
