# eSports Arena Manager - React

Migración del frontend original de HTML/CSS/JavaScript a React + Vite.

## Requisitos
- Node.js 18+ recomendado
- Visual Studio Code

## Instalación
```bash
npm install
```

## Ejecutar
```bash
npm run dev
```

Luego abrir la dirección que muestra Vite, normalmente `http://localhost:5173`.

## Compilar para producción
```bash
npm run build
```

## Funcionalidades migradas
- Navegación con React Router.
- Inicio y selector de perfil.
- Persistencia del perfil mediante `localStorage`.
- Torneos con control según perfil.
- Equipos.
- Partidas.
- Ranking.
- Inscripción con validaciones.
- Registro con validaciones.
- Imágenes y estilos del proyecto original.
- Diseño responsive.

Los datos siguen siendo simulados, igual que en el frontend original. El proyecto queda preparado para reemplazarlos posteriormente por llamadas al backend/API.
