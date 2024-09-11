# Repositorio Aplicación Ejemplo - UD01: Introducción a Android
Este repositorio contiene un proyecto de ejemplo para el Módulo de **Programación Multimedia y Dispositivos Móviles** del Ciclo Formativo de Grado Superior en **Desarrollo de Aplicaciones Multiplataforma** del IES Profesor Juan Antonio Carrillo Salcedo.

La aplicación tiene como objetivo servir de introducción al desarrollo de aplicaciones móviles en **Android**, explicando la arquitectura del sistema, la estructura de un proyecto Android y la comunicación entre actividades. Además, el proyecto incluye partes no finalizadas, que deberán ser completadas por los estudiantes para poner en práctica los conocimientos adquiridos.

# Contenidos

El proyecto cubre los siguientes temas:

- **Arquitectura de Android**: Explicación de los componentes clave como Actividades y Vistas.
- **Estructura de un proyecto Android**: Análisis de los archivos y directorios principales que componen un proyecto Android, como `AndroidManifest.xml`, `res`, `src`, `build.gradle.kts` entre otros.
- **Comunicación entre actividades**: Explicación sobre cómo las actividades se comunican entre sí utilizando `Intents` y cómo pasar datos entre actividades.
- **Prácticas guiadas**: Partes de la aplicación estarán sin completar para que los estudiantes puedan aplicar lo aprendido en clase.

# Requisitos

Para ejecutar y desarrollar en este proyecto, necesitarás:

- **Android Studio** (versión recomendada: Android Studio Koala o superior) [Descargar](https://developer.android.com/codelabs/basic-android-kotlin-compose-install-android-studio?hl=es-419#0) 
- **JDK 22 o superior** [Descargar](https://www.oracle.com/es/java/technologies/downloads/)
- Un dispositivo Android o un emulador configurado.

# Descarga del proyecto

**1a.** Clona este repositorio en tu máquina local y abre el proyecto en Android Studio:

   ```bash
   git clone https://github.com/usuario/proyecto-android-ejemplo.git
   ```  

**1b.** Abre Android Studio y clona el repositorio desde la opción Git > Clone...

![image](https://github.com/user-attachments/assets/7008b328-f011-41a9-bc0e-30bfdb56a053)

**2.** Sincroniza las dependencias de Gradle y espera a que finalice la configuración.

**3.** Conecta un dispositivo Android o configura un emulador.

**4.** Ejecuta la aplicación desde Android Studio.


# Estructura del proyecto

* **`/app`**: Carpeta principal que contiene el código de la aplicación.
     * **`/src`**: Contiene el código fuente de la aplicación.
          * **`/main`**: Carpeta principal del código fuente.
               * **`/java`**: Contiene los archivos .java con las clases y actividades.
               * **`/res`**: Carpeta de recursos, que contiene los layouts, imágenes y otros recursos necesarios.
                 - **`drawable/`**: Recursos gráficos.
                 - **`layout/`**: Archivos XML de diseño.
                 - **`mipmap/`**: Iconos de la aplicación.
                 - **`values/`**: Archivos XML que contienen valores como strings y estilos.
               * **`AndroidManifest.xml`**: Archivo de manifiesto que define las actividades, permisos y otros componentes clave de la aplicación. 
          * **`test/`**: Código fuente para pruebas unitarias.
          * **`androidTest/`**: Código fuente para pruebas instrumentadas.
     * **`build.gradle.kts`**: Archivo de configuración del módulo `app` en formato Kotlin DSL para Gradle. Define dependencias y configuraciones específicas del módulo.


