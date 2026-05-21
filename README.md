# 💪 Rutinas de Ejercicio · Mario Redondo Exercise Physiology Cancer Center

Aplicación web estática para consultar y seguir las rutinas de entrenamiento personalizadas. Sin servidor, sin dependencias externas, funciona directamente desde el navegador.

## ✨ Funcionalidades

- **Vista semanal** — esquema de días Fza/Ae/Descanso de un vistazo
- **Rutinas detalladas** — 7 rutinas de fuerza (A–G) con todos los ejercicios, series, repeticiones e instrucciones completas
- **Marcar ejercicios** — marca cada ejercicio como completado; el progreso se guarda en el navegador (localStorage)
- **Temporizador integrado** — para ejercicios isométricos como planchas, con cuenta atrás visual circular
- **Trabajo cardiovascular** — instrucciones y temporizador para sesiones de cardio
- **Modo oscuro** — diseño oscuro de alta legibilidad

## 🚀 Cómo usar

### Opción 1 — Abrir directamente
Descarga o clona el repositorio y abre `index.html` en cualquier navegador moderno. No necesita servidor.

### Opción 2 — GitHub Pages
1. Sube el repositorio a GitHub
2. Ve a **Settings → Pages**
3. Selecciona la rama `main` y carpeta `/ (root)`
4. La app estará disponible en `https://tuusuario.github.io/nombre-repo`

## 📁 Estructura

```
/
└── index.html   ← toda la app en un solo archivo
└── README.md
```

## 📋 Rutinas incluidas

| Rutina | Esquema semanal |
|--------|----------------|
| A | Lun · Fza |
| B | Mié · Fza (Ae·Fza·Ae·Fza·Ae) |
| C | Vie · Fza |
| D | Fza·Ae·Ae·Fza·Ae |
| E | Ae·Fza·Ae·Fza·Ae |
| F | Fza·Ae·Ae·Fza·Ae |
| G | Ae·Fza·Ae·Ae·Fza |

## 🏋️ Ejercicios cubiertos

Sentadillas, fondos, planchas, remos, press militar, peso muerto, hip thrust, tracción TRX, bird dog, bicho muerto, escalador, zancadas, curl de bíceps, y más — con instrucciones completas de ejecución para cada uno.

## 🛠️ Tecnología

- HTML5 / CSS3 / JavaScript vanilla
- Google Fonts (DM Sans + DM Mono)
- `localStorage` para guardar el progreso entre sesiones
- Sin frameworks, sin build tools, sin instalación

---
*Diseñado para uso personal. Basado en las rutinas prescritas por Mario Redondo — Exercise Physiology Cancer Center.*
