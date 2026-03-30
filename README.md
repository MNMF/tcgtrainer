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

## Despliegue en GitHub Pages (5 minutos)

1. Crear repo en github.com (ej: `pokertimer`)
2. Subir todos los archivos
3. Ir a Settings → Pages → Source: `main` / `root`
4. URL quedará en `tuusuario.github.io/pokertimer`

## Dominio propio (opcional)

1. Comprar dominio en NIC.cl (`pokertimer.cl`) o Namecheap (`pokertimer.gg`)
2. En GitHub Pages → Custom domain → ingresar el dominio
3. En el registrador de dominio, agregar CNAME apuntando a `tuusuario.github.io`
4. HTTPS se activa automático en ~24 horas

## Iconos

Generar íconos PNG en https://realfavicongenerator.net  
Subir una imagen cuadrada con el logo y descargar los tamaños 192x192 y 512x512.

## Seguridad

Al ser 100% frontend (sin servidor, sin base de datos, sin login):
- No hay superficie de ataque backend
- HTTPS automático con GitHub Pages
- Ningún dato del usuario sale del dispositivo
- Sin cookies, sin tracking

## Mantención

Costo mensual: $0  
Costo anual: ~$10-15 USD (solo dominio)

---

Hecho en Chile 🇨🇱 para la comunidad Pokemon TCG
