# 📚 BookVault - Biblioteca Personal

<div align="center">

![BookVault Logo](https://img.shields.io/badge/BookVault-Tu%20Biblioteca%20Personal-6366F1?style=for-the-badge&logo=book&logoColor=white)

**Aplicación Android para gestión de biblioteca personal**

[![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://developer.android.com/)
[![Kotlin](https://img.shields.io/badge/Kotlin-0095D5?style=for-the-badge&logo=kotlin&logoColor=white)](https://kotlinlang.org/)
[![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)](https://firebase.google.com/)

---

### **Ilan Angeles Rodriguez**
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ilan-angeles-rodriguez)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ilanangelesrodriguez@gmail.com)

**Universidad Nacional del Santa** | **Aplicaciones Móviles**

</div>

## 📖 Descripción

**BookVault** es una aplicación Android desarrollada en Kotlin para el curso de Aplicaciones Móviles. Permite a los usuarios gestionar su biblioteca personal de libros de manera intuitiva y elegante, con funcionalidades completas de autenticación, almacenamiento en la nube y una interfaz de usuario.

### ✨ Características Principales

- 🔐 **Autenticación completa** con Firebase Auth
- 📚 **Gestión de biblioteca personal** con CRUD completo
- ⭐ **Sistema de calificaciones** con estrellas
- 🔍 **Búsqueda y filtros avanzados** por título, género y rating
- 🎨 **Diseño moderno** con Material Design 3
- ☁️ **Sincronización en la nube** con Firebase Realtime Database
- 👤 **Modo invitado** para usuarios sin cuenta

## 🛠️ Tecnologías Utilizadas

| Tecnología | Propósito |
|------------|-----------|
| **Kotlin** | Lenguaje de programación principal |
| **Android SDK** | Desarrollo de aplicación móvil |
| **Firebase Auth** | Autenticación de usuarios |
| **Firebase Realtime Database** | Base de datos en tiempo real |
| **Material Design 3** | Diseño de interfaz moderna |
| **ViewBinding** | Vinculación de vistas |
| **RecyclerView** | Listas dinámicas |

## 📱 Capturas de Pantalla

### 🔐 Pantalla de Autenticación
<img src="https://hebbkx1anhila5yf.public.blob.vercel-storage.com/1-hf2X9FNxzHlB5ggoXS4oJ8QWYNalQe.jpeg" width="300" alt="Login Screen">

**Funcionalidades:**
- Inicio de sesión con email y contraseña
- Registro de nuevos usuarios
- Recuperación de contraseña
- Modo invitado para acceso sin cuenta
- Validación de campos en tiempo real

---

### 📝 Registro de Usuario
<img src="https://hebbkx1anhila5yf.public.blob.vercel-storage.com/2-MzTKoshqzOrqcliUKR3loIs13z0T5X.jpeg" width="300" alt="Register Screen">

**Funcionalidades:**
- Creación de cuenta con validación
- Campos de email y contraseña seguros
- Alternancia entre login y registro
- Verificación de email automática

---

### 🏠 Dashboard Principal
<img src="https://hebbkx1anhila5yf.public.blob.vercel-storage.com/3-lLsTICMPKP4k901UBBNGTYtnxA9bU1.jpeg" width="300" alt="Main Dashboard">

**Funcionalidades:**
- Saludo personalizado al usuario
- Acceso rápido a estadísticas de lectura
- Navegación a logros literarios
- Gestión de perfil personal
- Configuración de la aplicación
- Botones de acción principales

---

### 📚 Mi Biblioteca
<img src="https://hebbkx1anhila5yf.public.blob.vercel-storage.com/4-VcyyIJwoEvh69bLdesUMgsV9TFvEPa.jpeg" width="300" alt="Library Screen">

**Funcionalidades:**
- Lista completa de libros del usuario
- Búsqueda por título o autor
- Filtros por género literario
- Filtros por rango de calificación (1-5 estrellas)
- Visualización de información detallada
- Opciones de edición y eliminación

---

### ➕ Agregar Nuevo Libro
<img src="https://hebbkx1anhila5yf.public.blob.vercel-storage.com/5-DcNSS2i37rKgjdQ4LhHyIO1F40xkLY.jpeg" width="300" alt="Add Book Screen">

**Funcionalidades:**
- Formulario intuitivo para nuevos libros
- Campo de título del libro
- Selección de género literario
- Sistema de calificación con estrellas
- Validación de campos obligatorios
- Guardado automático en la nube

## 🏗️ Arquitectura del Proyecto

```
app/
├── src/main/
│   ├── java/com/example/app_s10/
│   │   ├── MainActivity.kt           # Pantalla principal
│   │   ├── LoginActivity.kt          # Autenticación
│   │   ├── GamesListActivity.kt      # Lista de libros
│   │   ├── AddGameActivity.kt        # Agregar/editar libros
│   │   ├── GameAdapter.kt            # Adaptador RecyclerView
│   │   └── Game.kt                   # Modelo de datos
│   └── res/
│       ├── layout/                   # Layouts XML
│       ├── values/
│       │   ├── colors.xml           # Paleta de colores moderna
│       │   ├── strings.xml          # Textos de la aplicación
│       │   └── themes.xml           # Temas Material Design
│       └── drawable/                # Iconos y recursos gráficos
```

## 🔥 Funcionalidades Implementadas

### 🔐 Sistema de Autenticación
- [x] Login con email y contraseña
- [x] Registro de nuevos usuarios
- [x] Recuperación de contraseña
- [x] Autenticación anónima (modo invitado)
- [x] Verificación de email
- [x] Manejo de errores de autenticación

### 📚 Gestión de Biblioteca
- [x] Agregar libros con título, género y calificación
- [x] Editar información de libros existentes
- [x] Eliminar libros de la biblioteca
- [x] Visualizar lista completa de libros
- [x] Persistencia en Firebase Realtime Database

### 🔍 Búsqueda y Filtros
- [x] Búsqueda por título de libro
- [x] Filtros por género literario
- [x] Filtros por rango de calificación
- [x] Combinación de múltiples filtros
- [x] Resultados en tiempo real

### 🎨 Interfaz de Usuario
- [x] Diseño moderno con Material Design 3
- [x] Paleta de colores personalizada
- [x] Iconografía coherente
- [x] Animaciones suaves
- [x] Responsive design

## 🚀 Instalación y Configuración

### Prerrequisitos
- Android Studio Arctic Fox o superior
- SDK de Android 21+ (Android 5.0)
- Cuenta de Firebase
- Dispositivo Android o emulador

### Pasos de Instalación

1. **Clonar el repositorio**
```bash
git clone https://github.com/tu-usuario/bookvault-app.git
cd bookvault-app
```

2. **Configurar Firebase**
- Crear proyecto en [Firebase Console](https://console.firebase.google.com/)
- Habilitar Authentication y Realtime Database
- Descargar `google-services.json` y colocarlo en `app/`

3. **Abrir en Android Studio**
- Importar el proyecto
- Sincronizar dependencias de Gradle
- Ejecutar en dispositivo o emulador

## 📊 Estructura de Datos

### Modelo de Libro (Game.kt)
```kotlin
data class Game(
    val id: String = "",
    val title: String = "",           // Título del libro
    val genre: String = "",           // Género literario
    val platform: String = "",       // Plataforma (no usado)
    val rating: Float = 0f,          // Calificación (1-5 estrellas)
    val description: String = "",     // Descripción
    val releaseYear: Int = 0,        // Año de publicación
    val completed: Boolean = false,   // Leído/No leído
    val userId: String = "",         // ID del usuario propietario
    val createdAt: Long = System.currentTimeMillis()
)
```

## 🎯 Objetivos Académicos Cumplidos

- ✅ **Desarrollo en Kotlin**: Aplicación 100% en Kotlin
- ✅ **Arquitectura Android**: Uso correcto de Activities y Fragments
- ✅ **Material Design**: Implementación de componentes modernos
- ✅ **Base de datos**: Integración con Firebase
- ✅ **Autenticación**: Sistema completo de usuarios
- ✅ **CRUD Operations**: Crear, leer, actualizar, eliminar
- ✅ **UX/UI**: Interfaz intuitiva y atractiva

## 🔮 Futuras Mejoras

- [ ] Sincronización offline
- [ ] Recomendaciones de libros
- [ ] Compartir biblioteca con amigos
- [ ] Estadísticas avanzadas de lectura
- [ ] Integración con APIs de libros
- [ ] Notificaciones push
- [ ] Backup automático

## 👨‍💻 Autor

**Ilan Angeles Rodriguez**

💼 [LinkedIn](https://www.linkedin.com/in/ilan-angeles-rodriguez)

📧 [Email](mailto:ilanangelesrodriguez@gmail.com)

---

<div align="center">
