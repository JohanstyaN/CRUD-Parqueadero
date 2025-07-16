# 🚗 CRUD Parqueadero

Sistema web para gestionar entradas y salidas en un parqueadero, con backend en PHP y MySQL, y frontend con AdminLTE.

---

## 🚀 Características

- Registro de ingreso de vehículos (placa, hora, tipo)  
- Registro de salida y cálculo de tarifa según tiempo  
- Listado y búsqueda de transacciones  
- Gestión de tarifas por tipo de vehículo  
- UI moderna con **AdminLTE**  

---

## 📦 Tecnologías

- **PHP 7+** · **MySQL**  
- **JavaScript** · **jQuery**  
- **AdminLTE** para el theme y componentes  
- **Travis CI** para integración y despliegue continuo  

---

## 🛠️ Requisitos

- PHP 7.4 o superior  
- MySQL 5.7+  
- Composer (para librerías PHP)  

---

## 📥 Instalación

~~~bash
# 1. Clona el repositorio
git clone https://github.com/JohanstyaN/CRUD-Parqueadero.git
cd CRUD-Parqueadero

# 2. Instala dependencias PHP
composer install

# 3. Configura la base de datos
#    Edita config/database.php con tus credenciales MySQL
mysql -u root -p < database/schema.sql

# 4. Levanta el servidor PHP
php -S localhost:8000 -t public
#    Abre http://localhost:8000 en tu navegador
~~~

---

## 📁 Estructura

~~~text
CRUD-Parqueadero/
├── app/
│   ├── controllers/   # Lógica de rutas y peticiones
│   ├── models/        # Clases de acceso a datos
│   └── views/         # Vistas con AdminLTE
├── config/
│   └── database.php   # Configuración MySQL
├── public/
│   ├── index.php      # Front controller
│   └── assets/        # CSS, JS, img
├── database/
│   └── schema.sql     # Script de creación de tablas
├── tests/             # (Opcional) pruebas unitarias
├── .travis.yml        # Configuración Travis CI
└── README.md
~~~

---

## 🤝 Contribuir

1. Crea un issue con la mejora o bug  
2. Haz fork → feature/mi-cambio → PR  
3. Espera revisión y merge  

---

## 📝 Licencia

MIT License

## 👤 Autor

Desarrollado por **Johan Sebastián Cañon**  
GitHub: [@JohanstyaN](https://github.com/JohanstyaN)  
LinkedIn: [linkedin.com/in/johan-sebastian-cañon-932b0b240](https://www.linkedin.com/in/johan-sebastian-cañon-932b0b240/)
