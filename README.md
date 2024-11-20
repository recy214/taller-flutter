# Curso de Desarrollo Web con Flutter

## Requisitos Previos

### Conocimientos Básicos

1. Uso básico de computadora y navegador web.
2. Conocimientos básicos sobre qué es una aplicación web (opcional).
3. Familiaridad básica con comandos en la terminal (opcional).

### Herramientas Necesarias

1. **Computadora con conexión a internet:**
   - Sistema operativo: Windows, macOS, o Linux.
   - Procesador básico o intermedio.
   - Espacio en disco: Al menos 2 GB libres.

2. **Navegador recomendado:**
   - Google Chrome (para probar las aplicaciones web).

3. **Editor de texto o IDE:**
   - **Recomendado:**
     - [Visual Studio Code](https://code.visualstudio.com/)
   - Extensiones necesarias para VS Code:
     - [Flutter](https://marketplace.visualstudio.com/items?itemName=Dart-Code.flutter)
     - [Dart](https://marketplace.visualstudio.com/items?itemName=Dart-Code.dart-code)

4. **Entorno de desarrollo local:**
   - [Flutter SDK](https://docs.flutter.dev/get-started/install) instalado y configurado.
   - Tener [Git](https://git-scm.com/) instalado para gestionar proyectos y repositorios.

5. **Servicios en la nube:**
   - **Supabase**: [Crear cuenta gratuita](https://supabase.com/) para la gestión de bases de datos y autenticación en tiempo real.

6. **Cuenta en servicios opcionales:**
   - [GitHub](https://github.com/) para gestionar repositorios de código.

---

## Recursos a Descargarse Previamente

1. **Flutter SDK:**
   - Descárgalo desde la página oficial:  
     [Descargar Flutter SDK](https://docs.flutter.dev/get-started/install)
   - Asegúrate de seguir las instrucciones específicas para tu sistema operativo.

2. **Archivos base del curso:**
   - Clona o descarga el repositorio del curso en GitHub:
     [Descargar aquí](https://github.com/usuario/repositorio-curso-flutter-web)

3. **Configuración inicial de Supabase:**
   - Crea un proyecto en Supabase.
   - Anota las credenciales y URLs generadas para conectarte desde Flutter.

---

## Herramientas y Recursos Complementarios

1. **Prueba inicial:**
   - Crea un proyecto en Flutter y pruébalo en el navegador con el siguiente comando:
     ```bash
     flutter create mi_proyecto_web
     cd mi_proyecto_web
     flutter run -d chrome
     ```

2. **Configuración inicial con Supabase:**
   - Agrega la dependencia de Supabase a tu proyecto Flutter:
     ```bash
     flutter pub add supabase_flutter
     ```
   - Inicializa Supabase en tu proyecto:
     ```dart
     Supabase.initialize(
       url: 'https://<tu-supabase-url>',
       anonKey: '<tu-supabase-anon-key>',
     );
     ```

3. **Documentación recomendada:**
   - [Flutter Web Docs](https://docs.flutter.dev/web) - Guía oficial para Flutter Web.
   - [Dart Documentation](https://dart.dev/guides) - Documentación oficial de Dart.
   - [Supabase Docs](https://supabase.com/docs) - Documentación oficial de Supabase.

4. **Comunidades y recursos:**
   - [Flutter Community](https://flutter.dev/community) - Encuentra soporte y tutoriales.
   - [Stack Overflow](https://stackoverflow.com/questions/tagged/flutter) - Foro para resolver dudas técnicas.

---

## Contacto

Si tienes dudas antes o durante el curso, puedes contactarme en:
- **Correo:** nugetdepatto.stay@gmail.com

¡Nos vemos en el curso! 🚀
