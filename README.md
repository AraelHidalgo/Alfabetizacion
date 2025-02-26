# Proyecto de Alfabetización en Zonas Rurales  
<img src="https://upload.wikimedia.org/wikipedia/commons/3/33/Escudo_unach.png" alt="Descripción de la imagen" width="135" height="90">

## Objetivo del Proyecto
El propósito principal de este proyecto es enseñar habilidades básicas de lectura y escritura a personas en comunidades rurales, utilizando un enfoque educativo innovador basado en tecnología accesible. Nuestro sistema se inspira en el libro del Dr. Óscar sobre alfabetización y busca adaptarse a las necesidades específicas de los usuarios.

## Características Principales
1. **Reconocimiento de voz**: Validación de palabras pronunciadas por los usuarios para reforzar el aprendizaje auditivo.
2. **Escritura por teclado**: Ejercicios interactivos que permiten practicar y corregir errores en tiempo real.
<!--3. **Modo offline**: Uso sin conexión a internet para garantizar la accesibilidad en áreas con recursos tecnológicos limitados.-->
3. **Evaluaciones personalizadas**: Retroalimentación basada en el progreso individual, ajustando la dificultad según el nivel del usuario.
4. **Interfaz intuitiva**: Diseñada para usuarios con bajo nivel de alfabetización, utilizando iconos claros y mínimo texto.
<!--
## 📂 Estructura del Repositorio
- **`/docs`**: Documentación del proyecto, incluyendo requisitos del sistema y diseño de la interfaz.
- **`/src`**: Código fuente del programa.
- **`/assets`**: Imágenes, íconos y recursos multimedia.
- **`/tests`**: Scripts y pruebas automatizadas para validar las funcionalidades.
-->
## 🏫 Institución Académica
Este proyecto se desarrolla en colaboración con la **Universidad Autónoma de Chiapas (UNACH)** y la **Facultad de Negocios**.

## Impacto Esperado
- Mejorar las tasas de alfabetización en comunidades rurales.
- Reducir la brecha educativa utilizando tecnología accesible.
- Fomentar el empoderamiento y el desarrollo personal a través de la educación.
<!--
## 🛠️ Tecnologías Utilizadas
- **Swift**: Para el desarrollo de la aplicación móvil.
- **Google Speech-to-Text API**: Reconocimiento de voz.
- **PostgreSQL**: Base de datos para almacenar el progreso de los usuarios.
-->
<!--## 👩‍💻 Colaboradores
- **[Tu Nombre]** - Coordinador del Proyecto  
- **Otros Colaboradores** - Listar nombres y roles (opcional).
-->
## Contacto
Si tienes alguna duda o deseas colaborar con el proyecto, no dudes en escribir a:  
**arael.hidalgo54@unach.mx**
## Estructura del Proyecto

El proyecto se organiza de la siguiente manera:

```
proyecto-alfabetizacion
└── proyecto-alfabetizacion
    ├── modulos
    │   ├── modulo-principal
    │   ├── modulo-pronunciacion
    │   └── modulo-caligrafia
    ├── infraestructura
    │   ├── autenticacion
    │   ├── notificaciones
    │   └── logging
    ├── database
    │   └── schema.sql
    ├── docker
    │   ├── docker-compose.yml
    │   ├── .dockerignore
    │   └── Dockerfile
    ├── README.md
    └── package.json
```

### Módulos

- **Modulo Principal**: Contiene la lógica principal de la aplicación, incluyendo el frontend y backend.
- **Modulo Pronunciación**: Se enfoca en la enseñanza de la pronunciación, con su propio frontend y backend.
- **Modulo Caligrafía**: Diseñado para ayudar en la enseñanza de la caligrafía, también con su propio frontend y backend.

### Infraestructura

- **Autenticación**: Maneja la lógica de autenticación de usuarios.
- **Notificaciones**: Se encarga de las notificaciones dentro de la aplicación.
- **Logging**: Gestiona los logs de la aplicación.

### Base de Datos

- **schema.sql**: Contiene el esquema de la base de datos utilizado por la aplicación.

### Docker

- **docker-compose.yml**: Configuración para Docker Compose, que define y ejecuta aplicaciones Docker.
- **.dockerignore**: Especifica qué archivos y directorios deben ser ignorados por Docker.
- **Dockerfile**: Instrucciones para construir la imagen Docker de la aplicación.

## Instalación

Para instalar las dependencias del proyecto, ejecute el siguiente comando en la raíz del proyecto:

```
npm install
```

## Uso

Para iniciar la aplicación, utilice el siguiente comando:

```
npm start
```

## Contribuciones

Las contribuciones son bienvenidas. Si desea contribuir, por favor abra un issue o un pull request.

## Licencia

Este proyecto está bajo la Licencia MIT. Consulte el archivo LICENSE para más detalles.