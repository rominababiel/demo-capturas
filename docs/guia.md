# Guía Rápida de Inicio

Bienvenido a la documentación de **demo-capturas**. Esta guía resume los pasos esenciales para comenzar a trabajar en el proyecto.

## 📋 Requisitos Previos

- **Git**: Tener Git instalado y configurado.
- **Node.js**: Versión LTS recomendada (>= 18.x).
- **Gestor de paquetes**: `npm` o `pnpm`.

## 🚀 Instalación y Puesta en Marcha

1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com/rominababiel/demo-capturas.git
   cd demo-capturas
   ```

2. **Instalar dependencias:**
   ```bash
   npm install
   ```

3. **Iniciar en modo desarrollo:**
   ```bash
   npm run dev
   ```

## 🌿 Flujo de Trabajo con Ramas

Para mantener un historial ordenado y trazable, seguimos un flujo basado en ramas:

- `main`: Rama principal estable.
- `feat/<nombre>`: Nuevas características o documentación (ej. `feat/docs`).
- `fix/<nombre>`: Corrección de errores.

### Pasos para contribuir:
1. Crear una rama a partir de `main`:
   ```bash
   git checkout -b feat/mi-funcionalidad
   ```
2. Realizar los cambios y realizar commits con formato descriptivo:
   ```bash
   git commit -m "feat: descripción del cambio"
   ```
3. Subir la rama y abrir un Pull Request hacia `main`.

## 📖 Buenas Prácticas

- Mantener commits atómicos y claros.
- Validar pruebas y estilo antes de solicitar revisión.
- Mantener la documentación sincronizada con el código.
