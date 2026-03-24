**Contexto:**  
Desarrolla una aplicación móvil en **Flutter (Dart)** que simule la autenticación de usuarios para la plataforma **Crunchyroll**, utilizando un archivo `db.json` como base de datos local. La app debe estar dividida en **4 archivos** bien definidos, con estilos específicos y lógica de validación.

---

### **Estructura de Archivos**

1. **`main.dart`** – Pantalla principal con presentación de la app y navegación.
2. **`login.dart`** – Pantalla de inicio de sesión.
3. **`signup.dart`** – Pantalla de registro de usuarios.

---

### **Requisitos Funcionales**

#### **1. Pantalla Principal (`main.dart`)**
- **AppBar:**
  - Color de fondo: gris oscuro (`#1F1F1F` o similar).
  - Título: `"Crunchyroll"` en color naranja (`#FF7A2F`).
  - Logo izquierdo: imagen de `20x20` obtenida desde:
    ```
    https://github.com/MunizSalinasVictor/Imagenes-para-flutter-6toI-11-feb-2026/blob/main/Crunchyroll_Logo.png
    ```
- **Cuerpo:**
  - Imagen principal con degradado de opacidad hacia abajo (puede ser una imagen representativa de Crunchyroll).
  - Dos botones redondeados en color naranja:
    - **Iniciar Sesión** → navega a `login.dart`
    - **Registrarse** → navega a `signup.dart`

---

#### **2. Pantalla de Registro (`signup.dart`)**
- **Campos:**
  - Nombre de usuario
  - Correo electrónico
  - Contraseña
- **Estilos:**
  - Fondo: gris oscuro (mismo que AppBar).
  - Inputs: estilo **glassmorphism** (fondo gris ligeramente más claro con opacidad, borde sutil).
  - Texto de hint (ej. "correo@ejemplo.com"): gris claro.
  - Etiqueta de cada campo (ej. "Correo"): blanco.
- **Botón:** `"Registrarse"` en color naranja.
- **Texto inferior:** `"¿Ya tienes cuenta? Inicia Sesión"` → navega a `login.dart`.

---

#### **3. Pantalla de Login (`login.dart`)**
- **Campos:**
  - Correo electrónico
  - Contraseña
- **Estilos:** mismos que en registro.
- **Botón:** `"Iniciar Sesión"` en color naranja.
- **Texto inferior:** `"¿No tienes cuenta? Regístrate"` → navega a `signup.dart`.


---

### **Requisitos de Estilo (UI/UX)**
- **Colores:**
  - Fondo general y AppBar: gris oscuro (`#121212` o `#1E1E1E`).
  - Botones: naranja (`#FF7A2F`).
  - Texto de campos (etiquetas): blanco.
  - Texto de hint: gris claro (`#B0B0B0`).
- **Inputs:**
  - Estilo "glass" con fondo semi-transparente, bordes redondeados, sombra ligera.
- **Fuente:** legible, sin serif.

---

### **Entregables Esperados**
Código fuente completo en Flutter con los 3 archivos bien comentados, funcional y listo para ejecutarse en un entorno Flutter estándar.

---
