# Recetario Culinario

Recetario personal en formato Markdown, pensado para usar en Obsidian.md y conectar recetas, ingredientes, temporada y costes mediante enlaces internos.

## Objetivo del proyecto

- Centralizar recetas de cocina en notas Markdown.
- Reutilizar plantillas consistentes para recetas e ingredientes.
- Enlazar cada receta con sus ingredientes para navegación y consultas con Dataview.
- Preparar base para cálculo automático de `coste_racion` a partir de `precio_kg`.
- Facilitar planificación por temporada.

## Estructura

- `Recetas/`: recetas finales en Markdown.
- `Ingredientes/`: fichas de ingredientes enlazables.
- `Plantillas/`: plantillas base para nuevas recetas e ingredientes.
- `.obsidian/`: configuración de Obsidian y plugins del vault.

## Flujo recomendado

1. Clónate el repo y [abre la carpeta como bóveda](https://obsidian.md/help/manage-vaults#Create+vault+from+an+existing+folder).
2. Añadir la carpeta `Plantillas` en Opciones > Complementos. Crear receta nueva desde `Plantillas/Nueva receta.md`. 
3. Añadir ingredientes en `ingredientes` con enlaces wiki (`[[Ingrediente]]`).
4. Crear o completar fichas en `Ingredientes/` desde `Plantillas/Nuevo ingrediente.md`.
## Complementos recomendados
- [Dataview](obsidian://show-plugin?id=dataview)
## Convenciones

- Usar nombres claros y consistentes en notas (ejemplo: `Tomate.md`).
- Mantener `temporada` en recetas e ingredientes para filtrar por meses/estación.
- Guardar `precio_kg` actualizado en ingredientes para cálculo fiable de costes.
- Aprovechar `recetas_relacionadas` para backlinks útiles.

## Blog

Más cosas en: [Peluso Cocina](https://pelusococina.substack.com/)
