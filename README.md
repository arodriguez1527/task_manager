## Requisitos del Sistema

- PHP >= 7.3
- Composer
- Servidor de base de datos MySQL

## Instalacion

Siga estos pasos para configurar y ejecutar el proyecto localmente:

1. **Clonar el Repositorio:**

2. **Instalar Dependencias de Composer:**

3. **Copiar el Archivo de Configuracion:**
Copie el archivo `.env.example` a `.env` y actualice las variables de entorno segun sea necesario:

4. **Generar Clave de Aplicacion:**
php artisan key:generate

5. **Configurar la Base de Datos:**
Configure las variables de entorno en el archivo `.env` para conectar su base de datos:

```env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=nombre_base_de_datos
DB_USERNAME=usuario_base_de_datos
DB_PASSWORD=contraseña_base_de_datos
``` 
php artisan migrate 

php artisan serve
