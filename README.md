# Sidebar

Sidebar dinámico construido con React, Vite y Tailwind CSS v4.

![expanded sidebar](/public/assets/img/expanded-sidebar.png)

![collapsed sidebar](/public/assets/img/collapsed-sidebar.png)

## Stack

- **React 19**
- **Vite 8**
- **Tailwind CSS v4**
- **react-router-dom v7**
- **@tabler/icons-react**

## Scripts

```bash
pnpm dev       # desarrollo
pnpm build     # build producción
pnpm preview   # previsualizar build
pnpm lint      # lint
```

## Estructura

```
src/
├── components/     # Sidebar, SidebarItem, UserBar
├── data/           # sidebarData, userData
├── pages/          # páginas del dashboard
├── const/          # constantes
├── App.jsx         # rutas y layout
└── main.jsx        # entry point
```

## Sidebar

El sidebar tiene dos modos: `expanded` (texto + íconos) e `icon` (solo íconos). Los datos se configuran desde `src/data/sidebarData.jsx`. Incluye un UserBar al final con menú desplegable configurable desde `src/data/userData.jsx`.
