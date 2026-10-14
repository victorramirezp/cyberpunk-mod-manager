# CYBERMOD 2077 // Night City Protocol

> Gestor web autocontenido de Mods y Load Order para **Cyberpunk 2077**, diseñado con estética Cyberpunk Night City (paleta oscura, amarillo neón `#fcee0a`, cian `#00f0ff` y rojo Arasaka `#ff003c`). Listo para **GitHub Pages**.

---

## ⚡ Características Principales

- **100% Autocontenido**: Un único archivo `index.html` sin build steps ni dependencias complejas.
- **Estética Cyberpunk 2077**: Bordes angulares chamfered (`clip-path`), scanlines de terminal, fuentes tipográficas tecnológicas (*Orbitron*, *Rajdhani*, *Share Tech Mono*) y efectos glitch y resplandor neón.
- **Modelo de Datos Completo**:
  - Nombre del mod.
  - Origen / Tipo de entrada: Enlace directo (NexusMods / URL) o Archivo/Ruta local (`.archive`, scripts CET, etc.).
  - Categorías y Prioridades:
    - ⚡ `Imprescindible / Core Engine` (CET, Redscript, ArchiveXL, TweakXL, Codeware, RED4ext).
    - 🌸 `Fem V` (Mods exclusivos de V femenino).
    - ⚡ `Mas V` (Mods exclusivos de V masculino).
    - 🎨 `Prescindible / Estético General` (Autos, reshades, radios, texturas).
    - ⚔️ `Gameplay / Skills` (Rebalanceos, perks, cyberware tweaks).
  - Notas y Dependencias (con botones de inserción rápida para `ArchiveXL`, `TweakXL`, `RED4ext`, etc.).
- **Persistencia en `localStorage`**: Todos los datos se guardan en el navegador y sobreviven a recargas de página.
- **Filtros Rápidos & Búsqueda en Vivo**:
  - Filtros por pestaña: *Todos*, *Core Engine*, *Fem V*, *Mas V*, *Estéticos*, *Gameplay*.
  - Búsqueda en tiempo real por nombre, archivo o dependencias.
- **Gestión Rápida de Tarjetas**:
  - Switch ON/OFF para activar/desactivar del orden de carga.
  - Botón de copiado con un clic ("Copiar ruta / enlace").
  - Enlaces directos a NexusMods / web.
  - Edición en modal dedicada.
  - Purga / Eliminación con confirmación de seguridad.
- **Sistema de Backup (JSON)**:
  - Exportar base de datos a `.json`.
  - Importar archivo de backup para restaurar o migrar entre ordenadores.
- **Sintetizador de Audio Cyberpunk (Web Audio API)**:
  - Bips y efectos sci-fi sin necesidad de archivos externos de audio, con opción de silenciar en el HUD.

---

## 🚀 Despliegue en GitHub Pages

1. Ve a los **Settings** de este repositorio en GitHub.
2. Navega a la sección **Pages** (menú izquierdo).
3. En **Build and deployment > Source**, selecciona `Deploy from a branch`.
4. Elige la rama `main` y la carpeta `/ (root)`.
5. Haz clic en **Save**. En cuestión de segundos tu app estará online.

---

*Desarrollado para la comunidad de modding de Cyberpunk 2077.*
