# 🛍️ Tienda de Ropa - SM2 EXAMEN PRÁCTICO

## 📱 Alumno: Justin Zinedine Zevallos Purca
Aplicación móvil desarrollada en **Flutter** para la gestión de una tienda de ropa. Esta app permite a los usuarios **registrarse**, **iniciar sesión**, **recuperar su contraseña**, y también realizar operaciones como **agregar productos** (para el vendedor) y **visualizar el catálogo de productos** (para el cliente).

---

## 📱 Funcionalidades implementadas

### ✅ Historias seleccionadas del Product Backlog

1. **PBI-009 - Recuperación de contraseña**  
   *Como usuario, quiero recuperar mi contraseña para poder acceder a mi cuenta en caso de olvido.*

2. **PBI-011 (derivado) - Agregar productos a la tienda**  
   *Como vendedor, quiero agregar nuevos productos con imagen, descripción y precio para que estén disponibles en la tienda.*

> ✅ **Nota:** El Login está implementado por defecto, pero no forma parte de las historias evaluadas.

---

## 🚀 Características generales

- Registro de usuarios con Firebase Authentication  
- Recuperación de contraseña  
- Interfaz moderna y responsiva  
- Almacenamiento de imágenes en Cloudinary  
- Gestión de productos (Agregar y visualizar)

---
## 🖥️ Cómo ejecutar el proyecto (Windows)
Para poder ejecutar este proyecto en Windows, sigue estos pasos:
bre una terminal (PowerShell o terminal integrada en Visual Studio Code).
2. Ejecuta el siguiente comando para instalar todas las dependencias necesarias:
flutter pub get
y lo ejecutas en el main(si lo hacen en otro lugar no funcionara)

<img src="https://github.com/user-attachments/assets/212c6f94-114f-4700-9394-1edb75ee647e" width="700"/>


## 📸 Capturas de pantalla

### 🏠 Pantalla de inicio
<img src="https://github.com/user-attachments/assets/728dbdd4-b234-409f-90d0-14bac408a600" width="300"/>

---

### 🔐 Registro de cuenta
<img src="https://github.com/user-attachments/assets/d8fac0bc-aca1-432a-96c1-226374ee0d1a" width="300"/>

---

### 🔓 Inicio de sesión
<img src="https://github.com/user-attachments/assets/71efc635-60d7-4044-8721-85f0338890b8" width="300"/>

---

### ❓ Recuperación de contraseña (PBI-009)
<img src="https://github.com/user-attachments/assets/91ee5a4e-a2ca-4cf5-a5be-0ac8e0d92044" width="300"/>

#### ✉️ Resultado del envío (correo recibido)
<img src="https://github.com/user-attachments/assets/5e584131-c888-4800-84ad-e57ed196bb18" width="300"/>

---

## 🛒 Agregar productos a la tienda (PBI-011)

### 🧑‍💼 Panel del vendedor (después de iniciar sesión)
<img src="https://github.com/user-attachments/assets/23944c84-f601-4039-a0ed-5183710d86fb" width="300"/>

---

### 📍 Navegación hacia sección de productos (Navbar)
<img src="https://github.com/user-attachments/assets/8cX6vSkLQPhtwHAgNyw1n6" width="300"/>

---

### ➕ Botón para agregar producto (ícono +)
<img src="https://github.com/user-attachments/assets/0ecb3f1d-68cc-4f5e-8f33-d176dea2443b" width="300"/>


---

### 📝 Formulario para agregar producto
<img src="https://github.com/user-attachments/assets/dc483fea-0c3b-404a-a17e-eb3d7ad66fa0" width="300"/>

## 🔒 Gestión de sesión y perfil (opcional)
Además de las funcionalidades solicitadas, se implementó un menú de navegación para el vendedor, donde puede acceder a su perfil o cerrar sesión de forma segura.
### 📋 Menú del Vendedor

<img src="https://github.com/user-attachments/assets/b3709eec-1b47-4761-adbe-1bf610193f15" width="300"/>


### 👤 Vista del Perfil del usuario logueado

<img src="https://github.com/user-attachments/assets/d61cdac3-f6b2-4f35-8ea6-2c5a8ecdd680" width="300"/>


---

## 📦 Gestión de almacenamiento y base de datos

### ☁️ Cloudinary – Almacenamiento de imágenes

Se utilizó **Cloudinary** para subir y almacenar imágenes de productos. La app carga la imagen a Cloudinary y guarda la URL pública en la base de datos.

<img src="https://github.com/user-attachments/assets/42b6ccf2-1173-4f49-8891-3dd23d8a36aa" width="500"/>

---

### 🔥 Firebase – Base de datos Firestore

La base de datos utilizada es **Cloud Firestore**. Aquí se almacenan todos los datos de los productos, incluyendo nombre, categoría, precios, variantes y la URL de la imagen.

<img src="https://github.com/user-attachments/assets/de24d266-9388-41a6-b0ca-e1f843235878" width="700"/>

---

## 🔗 Enlaces y Referencias

- [Flutter](https://flutter.dev/)  
- [Firebase Authentication](https://firebase.google.com/docs/auth)  
- [Cloud Firestore](https://firebase.google.com/docs/firestore)  
- [Cloudinary (almacenamiento de imágenes)](https://cloudinary.com/)  
- [Repositorio GitHub del proyecto](https://github.com/JustinZP/SM2_EXAMEN_PRACTICO)
- "https://github.com/JustinZP/SM2_EXAMEN_PRACTICO.git"

---

## 📝 Evaluación

Este repositorio ha sido creado como parte del **examen práctico de la unidad II** del curso de Desarrollo de Aplicaciones Móviles. Contiene dos historias de usuario seleccionadas del Product Backlog
