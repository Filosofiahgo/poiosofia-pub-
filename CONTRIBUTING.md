# Guía de Contribución — Flujo de Trabajo Editorial

Esta guía describe el proceso completo para crear, desarrollar y publicar textos en el proyecto poiosófico.

---

## 1. Iniciar un Nuevo Texto

1. Elige la plantilla adecuada de la carpeta `plantillas/`:
   - `plantilla-analisis.md` — Para análisis críticos
   - `plantilla-informe.md` — Para informes estructurados
   - `plantilla-nota-breve.md` — Para ideas rápidas
   - `plantilla-observaciones.md` — Para observaciones insurgentes
   - `plantilla-texto-creativo.md` — Para ensayos y escritura creativa

2. Copia la plantilla a `borradores/` con un nombre descriptivo:

   ```bash
   cp plantillas/plantilla-analisis.md borradores/mi-nuevo-analisis.md
   ```

3. Completa los metadatos (autor, fecha, categoría) y empieza a escribir.

---

## 2. Desarrollar en Borradores

- Trabaja en `borradores/` hasta que el texto esté maduro.
- Puedes crear múltiples versiones o iterar libremente.
- Los documentos en `borradores/` no se consideran publicados.

---

## 3. Clasificar por Área Temática

Cuando el texto tenga forma definida, muévelo a la carpeta temática correspondiente:

| Carpeta | Contenido |
|---------|-----------|
| `Arts-Performing/` | Guiones, notas de performance, medios, expresiones artísticas |
| `Critical-Thinking/` | Ensayos, críticas, bitácoras, análisis |
| `Theory-Practice/` | Textos filosóficos, investigación, teoría |

---

## 4. Publicar

1. Revisa que el texto esté completo y finalizado.
2. Copia o mueve el archivo a `publicar/`.
3. Los archivos en `publicar/` están listos para distribución.

---

## Convenciones de Nombres

- Usa nombres descriptivos en minúsculas con guiones: `mi-analisis-sobre-tema.md`
- Incluye la fecha si es relevante: `2026-02-09-nota-breve.md`
- Mantén la extensión `.md` para todos los textos.

---

## Uso de Git

- Trabaja en una rama (`branch`) cuando desarrolles textos extensos.
- Usa mensajes de commit descriptivos en español.
- Abre un Pull Request cuando el texto esté listo para revisión.

---

## Linting

El proyecto usa `markdownlint` para mantener la consistencia de formato. Ejecuta la validación antes de publicar:

```bash
# Desde VS Code: ejecuta la tarea "markdownlint"
# O desde la terminal si tienes markdownlint-cli instalado:
markdownlint '**/*.md'
```
