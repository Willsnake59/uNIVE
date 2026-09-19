# Gestor de Gastos - Progressive Web App (PWA)

Aplicación web progresiva completa, moderna, responsiva y local-first para la gestión de finanzas personales, presupuestos, control de deudas y metas de ahorro.

## 🚀 Características Principales

- **Arquitectura Local-First:** Persistencia completa en el dispositivo con **IndexedDB** (funciona 100% offline).
- **PWA Instalable:** Service Worker con Workbox, Web App Manifest, caché offline y soporte de instalación en Chrome, Edge, Safari, iOS y Android.
- **Panel Financiero (Dashboard):** Métricas en tiempo real de saldo neto, ingresos, gastos, deudas y distribución gráfica por categorías.
- **Accesos Directos y Atajos de Teclado:** Navegación por teclado (`G` para Gasto, `I` para Ingreso, `N` para Nuevo Movimiento, `?` para el mapa de atajos) y tarjetas interactivas de acceso directo.
- **Control de Movimientos:** Historial con filtros por fecha, categoría y tipo, ordenamiento y paginación.
- **Control de Deudas:** Registro de préstamos y deudas con abonos parciales y liquidación.
- **Metas de Ahorro:** Progreso visual, registro de aportes y celebración al completar metas.
- **Presupuestos y Análisis:** Fijación de límites mensuales por categoría con alertas automáticas al 80% y 100%.
- **Configuración y Privacidad:** Modo claro / oscuro, multimoneda (COP, USD, EUR, etc.), exportación e importación de respaldos en formato JSON y datos de prueba restablecibles.

## 🛠️ Tecnologías

- **Framework:** React 19 + TypeScript
- **Bundler & Tooling:** Vite 8 + `vite-plugin-pwa` (Workbox 7)
- **Enrutamiento:** React Router 7
- **Iconografía:** Lucide React
- **Estilos:** CSS Modular y Tokens de Diseño Personalizados (sin dependencias externas de CSS)
- **Pruebas:** Vitest + React Testing Library + JSDOM
- **Calidad:** ESLint 10 + TypeScript ESLint

## 📦 Scripts Disponibles

Desde la raíz del proyecto:

```bash
# Iniciar servidor de desarrollo
pnpm dev

# Compilar para producción (TypeScript + Vite PWA)
pnpm build

# Ejecutar suite de pruebas unitarias y de componentes
pnpm test

# Ejecutar análisis de linter
pnpm lint

# Previsualizar el bundle de producción localmente
pnpm preview
```
