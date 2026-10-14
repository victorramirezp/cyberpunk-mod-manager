# CYBERMOD 2077 // Modular Catalog & Virtual Atelier Hub

> Aplicación web avanzada para la catalogación modular, gestión y orden de carga de mods de **Cyberpunk 2077**. Diseñada con estética Night City (paleta oscura `#08090d`, amarillo Kiroshi `#fcee0a`, cian `#00f0ff`, rojo Arasaka `#ff003c` y morado Neón `#b537f2`), 100% autocontenida en `index.html` y optimizada para **GitHub Pages**.

---

## ⚡ Novedades de la Arquitectura Modular v3.0

### 1. Hub Modular & Navegación por Secciones:
- **📊 Dashboard General**: Métricas en vivo (mods críticos, tiendas Atelier, estado del load order y accesos directos).
- **⚡ [CORE] Frameworks & Engine Essentials**: CET, Redscript, ArchiveXL, TweakXL, Codeware, RED4ext, Equipment-EX. Etiquetados como **"Crítico / No Desinstalar"** con bloqueo de seguridad ante desactivaciones accidentales.
- **🖥️ [GRÁFICOS & RENDIMIENTO]**:
  - Subcategorías: `LUTs / Color Grading`, `Texturas / Reshades`, `Optimizaciones / Rendimiento`.
  - Selector de **Impacto en Rendimiento** (Bajo / Medio / Alto) para planear actualizaciones de hardware o caídas de FPS.
- **🌸 [PERFIL: FEM V] y ⚡ [PERFIL: MAS V]**:
  - Filtrado por subcategorías: `Cuerpo & Mallas (Angel / Hyst / Solo)`, `Ropa & Outfits`, `Pelo & Cabello`, `Tatuajes / Piel / Cyberware visual`.
  - Integración nativa con **Virtual Atelier**: cada prenda se asocia a su tienda virtual con un solo clic.
- **🛍️ VIRTUAL ATELIER HUB (Módulo Exclusivo)**:
  - Agrupación por tienda holográfica (*Nola Dreamer Atelier*, *Viki Shop*, *Monsterkerg*, etc.).
  - Enlace directo a la tienda en NexusMods y catálogo de todas las prendas que dependen de ella.
  - Sección de prendas sin tienda para reasignación rápida.
- **💬 [HISTORIA, MISIONES & INMERSIÓN]**:
  - Subcategorías: `Misiones & Contenido Extra`, `Romance & Mensajes (Panam, Judy, etc.)`, `Comportamiento de NPCs / Ciudad`.
- **⚔️ [GAMEPLAY & COMBATE]**:
  - Subcategorías: `Skills / Stealth / Perks`, `Cyberware Tweaks (Sandevistan / Ciberpsicosis)`, `Armas & Vehículos`.

---

## 🛡️ Persistencia & Sistema de Backup Inteligente

- **`localStorage` Automático**: Todos los cambios se guardan al instante sin necesidad de backend.
- **Exportación en JSON**: Descarga un respaldo con metadata y timestamp (`cp2077_modular_backup_[fecha].json`).
- **Importación con Prevención de Sobreescrituras**:
  - **Modo Fusión (Recomendado)**: Integra los mods del archivo JSON agregando los faltantes sin borrar tus mods locales actuales.
  - **Modo Reemplazo Total**: Sobreescritura completa con confirmación explícita.

---

## 🚀 Despliegue en GitHub Pages

El proyecto está configurado y desplegado automáticamente en la rama `main`:
- **URL de Producción:** [https://victorramirezp.github.io/cyberpunk-mod-manager/](https://victorramirezp.github.io/cyberpunk-mod-manager/)

---

*Desarrollado para la comunidad de modding de Cyberpunk 2077.*
