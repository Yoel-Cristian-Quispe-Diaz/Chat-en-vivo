# 💬 Chat en vivo

Aplicación de chat en tiempo real desarrollada con **Node.js**, **Express** y **Socket.IO**. Los mensajes se envían y se reciben al instante entre todos los usuarios conectados, sin recargar la página.

> 🚧 Completa las secciones marcadas con `[...]` con los datos reales de tu proyecto.

## ✨ Características

- Mensajería en tiempo real mediante WebSockets.
- Varios usuarios conectados a la vez.
- Cliente web servido desde la carpeta `public/`.
- [Nombres de usuario, salas, notificación de conexión/desconexión, etc.]

## 🧰 Tecnologías

| Componente | Tecnología |
|---|---|
| Servidor | Node.js, Express `^4.21` |
| Tiempo real | Socket.IO `^4.8` |
| Desarrollo | Nodemon `^3.1` |
| Cliente | HTML, CSS y JavaScript |

## 📁 Estructura del proyecto

```
Chat-en-vivo/
├── public/              # Cliente web (HTML, CSS y JS del chat)
├── index.js             # Servidor Express + Socket.IO
├── package.json         # Dependencias y scripts
└── package-lock.json
```

## 🚀 Instalación

### Requisitos previos

- [Node.js](https://nodejs.org/) 16 o superior
- npm

### Pasos

1. **Clonar el repositorio**

   ```bash
   git clone https://github.com/Yoel-Cristian-Quispe-Diaz/Chat-en-vivo.git
   cd Chat-en-vivo
   ```

2. **Instalar las dependencias**

   ```bash
   npm install
   ```

3. **Iniciar el servidor**

   ```bash
   npm start
   ```

   Para desarrollo, con reinicio automático al guardar cambios:

   ```bash
   npm run dev
   ```

4. **Abrir el chat** en el navegador: `http://localhost:[PUERTO]`

   > Reemplaza `[PUERTO]` por el puerto que usa tu `index.js`.

## 💡 Cómo probarlo

1. Abre el chat en dos pestañas o ventanas del navegador.
2. Escribe un mensaje en una de ellas.
3. Verás que aparece al instante en la otra.

Para probarlo desde otro dispositivo de la misma red, usa la IP local de tu PC en lugar de `localhost`.

## 📜 Scripts disponibles

| Comando | Descripción |
|---|---|
| `npm start` | Inicia el servidor con Node |
| `npm run dev` | Inicia el servidor con Nodemon (reinicio automático) |

