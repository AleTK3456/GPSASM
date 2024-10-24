# GPSASM #
# Descripción
Este proyecto es una aplicación Android que implementa medidas de seguridad para proteger
contra vulnerabilidades comunes.

## Vulnerabilidades Identificadas
- Aplicación firmada con un certificado de depuración
- Instalación en versiones vulnerables de Android
- Depuración habilitada
- Datos de la aplicación pueden ser respaldados
- Receptor de Broadcast expuesto
- Acceso a ubicación fina y gruesa
- Acceso a estado de red e Internet

## Mejoras Implementadas
- Eliminar el uso del certificado de depuración
- Establecer un minSdkVersion más alto
- Configurar android:debuggable=false
- Deshabilitar el respaldo
- Limitar permisos peligrosos
- Definir permisos personalizados adecuadamente
- Revisar el Broadcast Receiver

## Cómo Ejecutar la Aplicación de Forma Segura
1. Clonar el repositorio
2. Importar el proyecto en Android Studio
3. Ejecutar la aplicación en un dispositivo o emulador
4. Asegurarse de que los permisos necesarios están configurados
## Reporte de Vulnerabilidades El reporte detallado de las pruebas de vulnerabilidad
realizadas se encuentra en el archivo `vulnerability_report.pdf`.
