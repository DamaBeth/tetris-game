# 🧩 Tetris

Una implementación moderna del clásico **Tetris**, desarrollada como una aplicación web con un enfoque en buenas prácticas de desarrollo Frontend, arquitectura escalable y una experiencia de usuario fluida.

El objetivo del proyecto no es únicamente recrear el videojuego, sino construir una aplicación mantenible utilizando herramientas modernas del ecosistema JavaScript.

---

## 📸 Preview

> Próximamente...

---

# ✨ Características

- 🎮 Mecánica clásica de Tetris
- ⌨️ Controles mediante teclado
- 📈 Sistema de puntuación
- 🚀 Incremento progresivo de dificultad
- 👀 Vista previa de la siguiente pieza
- 💾 Persistencia del mejor puntaje
- ⏸️ Pausa y reanudación de la partida
- 🎵 Soporte para efectos de sonido y música
- 📱 Diseño responsive
- 🌙 Tema claro y oscuro

---

# 🛠️ Stack Tecnológico

## Frontend

- React
- TypeScript
- Vite
- Tailwind CSS

## Manejo de estado

- Zustand

## Animaciones

- Framer Motion

## Testing

- Vitest
- React Testing Library

## Calidad de código

- ESLint
- Prettier

## CI/CD

- GitHub Actions

## Deployment

- Vercel

---

# 📁 Arquitectura

```
src
│
├── assets/
│
├── components/
│   ├── Board/
│   ├── Cell/
│   ├── HUD/
│   ├── Modal/
│   └── UI/
│
├── hooks/
│
├── store/
│
├── game/
│   ├── Board.ts
│   ├── Collision.ts
│   ├── Constants.ts
│   ├── Pieces.ts
│   ├── Rotation.ts
│   ├── Score.ts
│   └── GameEngine.ts
│
├── utils/
│
├── types/
│
├── styles/
│
├── App.tsx
└── main.tsx
```

---

# 🚀 Instalación

Clonar el repositorio

```bash
git clone https://github.com/DamaBeth/tetris-game.git
```

Entrar al proyecto

```bash
cd tetris
```

Instalar dependencias

```bash
npm install
```

Ejecutar el entorno de desarrollo

```bash
npm run dev
```

Construir para producción

```bash
npm run build
```

Ejecutar pruebas

```bash
npm run test
```

---

# 🎮 Controles

| Acción | Tecla |
|---------|-------|
| Mover izquierda | ← |
| Mover derecha | → |
| Rotar | ↑ |
| Descenso rápido | ↓ |
| Caída instantánea | Espacio |
| Pausa | P |

---

# 📋 Roadmap

## MVP

- [ ] Motor del juego
- [ ] Renderizado del tablero
- [ ] Sistema de colisiones
- [ ] Rotación de piezas
- [ ] Eliminación de líneas
- [ ] Sistema de puntuación
- [ ] Game Over

## Interfaz

- [ ] Menú principal
- [ ] Pantalla de pausa
- [ ] Pantalla de Game Over
- [ ] Animaciones
- [ ] Responsive

## Funcionalidades

- [ ] Sonidos
- [ ] Música
- [ ] Configuración
- [ ] Tema oscuro
- [ ] Persistencia del High Score

## Calidad

- [ ] Cobertura de pruebas
- [ ] GitHub Actions
- [ ] Optimización de rendimiento
- [ ] Accesibilidad

---

# 🧠 Objetivos del proyecto

Este proyecto busca fortalecer conocimientos relacionados con:

- Arquitectura de aplicaciones React.
- Desarrollo con TypeScript.
- Manejo de estado global mediante Zustand.
- Implementación de lógica de videojuegos.
- Desarrollo basado en componentes reutilizables.
- Testing de componentes y lógica de negocio.
- Integración continua mediante GitHub Actions.
- Optimización de rendimiento en aplicaciones web.

---

# 📚 Recursos

- Documentación oficial de React
- Documentación oficial de TypeScript
- Documentación oficial de Tailwind CSS
- Documentación oficial de Zustand
- Documentación oficial de Framer Motion
- Documentación oficial de Vitest

---

# 🤝 Contribuciones

Las contribuciones son bienvenidas. Si encuentras algún error o tienes una propuesta de mejora, puedes abrir un Issue o enviar un Pull Request.
