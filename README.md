# PokeTimer 🎴

Herramienta de entrenamiento para jugadores de Pokemon TCG.  
Mide el tiempo entre cada acción de tu turno para entrenar velocidad de juego.

## Funcionalidades

- Timer por acción con categorías: normal, buscar deck, barajar mano, calcular daño
- Modo un jugador o dos jugadores (un solo dispositivo)
- Estadísticas de sesión con gráfico de tendencia
- Compartir resultado como texto o imagen
- PWA instalable en celular (sin App Store)
- Dark mode automático
- Funciona offline

## Estructura

```
pokertimer/
├── index.html      # App completa
├── manifest.json   # Config PWA
├── sw.js           # Service Worker (offline)
├── icons/
│   ├── icon-192.png
│   └── icon-512.png
└── README.md
```


Al ser 100% frontend (sin servidor, sin base de datos, sin login):
- No hay superficie de ataque backend
- HTTPS automático con GitHub Pages
- Ningún dato del usuario sale del dispositivo
- Sin cookies, sin tracking


Hecho en Chile 🇨🇱 para la comunidad Pokemon TCG
