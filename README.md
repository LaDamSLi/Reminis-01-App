# Reminiscencia - App (Frontend)

Este es el repositorio para la aplicación nativa de "Reminiscencia", desarrollada usando React Native y Expo, partiendo de una plantilla de Expo NativeWind.

## Estructura del repositorio

El código principal de la aplicación se encuentra aquí, incluyendo la interfaz de usuario, navegación, y las peticiones a la API del backend.

## Flujo de Trabajo (Git Workflow)

Para mantener el código organizado y evitar conflictos en la rama `master` (o `main`), se debe seguir el siguiente flujo de trabajo estandarizado para todo el proyecto:

1. **Nunca trabajes directamente en `master`**.
2. **Crea una nueva rama** partiendo de `master` para cada nueva funcionalidad, arreglo o cambio:
   - Para nuevas características: `git checkout -b feat/nombre-de-la-caracteristica`
   - Para arreglos de errores: `git checkout -b fix/nombre-del-error`
   - Para tareas de mantenimiento o ajustes (UI, dependencias): `git checkout -b chore/nombre-de-la-tarea`
   - Para documentación: `git checkout -b docs/nombre-del-documento`
3. **Haz commits descriptivos** sobre los cambios realizados.
4. **Sube tu rama al repositorio remoto**: `git push origin nombre-de-la-rama`
5. **Abre un Pull Request (PR)** en GitHub hacia la rama `master`.
6. Después de revisar que los cambios funcionan correctamente (y no rompen nada), haz el "Merge" del PR hacia la rama principal.

---
_A continuación, la documentación original de la plantilla base utilizada:_

# 📱 Expo NativeWind Template

> 🚀 **Production-Ready Expo Starter Kit** - Mobile app template with 20+ pre-built UI components, TypeScript, NativeWind (Tailwind CSS), and platform-specific behaviors for iOS/Android.

## 🌟 Perfect For
- 📱 **Mobile App MVPs** - Launch faster with pre-built components
- 🏢 **Enterprise Apps** - Scalable architecture and TypeScript safety
- 🎨 **Design Systems** - Consistent UI across iOS and Android
- 🚀 **Startups** - Focus on your business logic, not UI implementation