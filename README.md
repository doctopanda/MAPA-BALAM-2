# MAPA-BALAM-2 🐆

Visor cartográfico público del Distrito de Salud 05 (Navojoa), Sonora.

**Estado:** repositorio preparado para publicación con GitHub Pages. El atlas cartográfico estará disponible cuando se suba el paquete público y se active Pages.

## Qué se publica
Cartografía censal previamente preparada: límites municipales, localidades, AGEB y manzanas de los cinco municipios disponibles. La selección de polígonos es informativa y no representa por sí misma cobertura ni incidencia epidemiológica.

## Qué NO se publica
Bases nominales SIESA, pacientes, CURP, domicilios identificables, auditorías internas, ni datos operativos privados. El proyecto BALAM completo permanece local.

## Desplegar el atlas
1. Subir **`MAPA_BALAM_GITHUB_PAGES_SOLO_PUBLICO.zip`** a la raíz de la rama `main` mediante **Add file → Upload files**. No usar el ZIP del BALAM local.
2. En **Settings → Pages → Build and deployment**, seleccionar **GitHub Actions**.
3. En la pestaña **Actions**, esperar el despliegue **Publicar MAPA BALAM**.
4. Abrir **https://doctopanda.github.io/MAPA-BALAM-2/**.

La automatización extrae el ZIP, conserva la estructura `index.html`, `atlas/`, `assets/` y `data/atlas/`, y publica una web estática.

**Fuente de origen:** BALAM Jaguar v5.1, cartografía DS05 procesada. **Mapa Polo REV:** https://aocejogarcia.github.io/polo_rev/ (proyecto externo independiente).

## Seguridad
No incluir datos clínicos ni de campo en GitHub Pages: los repositorios y los archivos servidos por Pages son públicos. No se debe inferir que un polígono sin datos representa cero intervenciones.

---
BALAM, Observatorio Distrital. Primera edición pública, octubre 2026.
