# Poiosofía Pub 📚

Arquitectura institucional de publicaciones poiosóficas.

---

## 🎯 Propósito del Proyecto

Este repositorio es el núcleo de auto-institución intelectual del proyecto poiosófico. Aquí se alojan informes, análisis, observaciones insurgentes y textos creativos que forman parte de un proceso continuo de pensamiento crítico y creación conceptual.

**Poiosofía** busca establecer un flujo de trabajo que conecte la ideación asistida, el versionado colaborativo y la publicación web, creando un ecosistema integral para la producción y difusión de conocimiento insurgente.

---

## 📂 Estructura de Carpetas

```
poiosofia-pub-
│
├── publicar/          # Archivos Markdown listos para publicar
│   └── README.md      # Descripción de contenidos publicables
│
├── borradores/        # Trabajo en curso
│   └── README.md      # Espacio para iterar y experimentar
│
├── plantillas/        # Plantillas Markdown para tipos de texto
│   ├── README.md
│   ├── plantilla-informe.md
│   ├── plantilla-analisis.md
│   ├── plantilla-observaciones.md
│   ├── plantilla-texto-creativo.md
│   └── plantilla-nota-breve.md
│
└── README.md          # Este archivo
```

### `/publicar`
Contiene los archivos Markdown que han completado el proceso de revisión y están listos para su distribución e integración en los canales de publicación.

### `/borradores`
Espacio para documentos en desarrollo: análisis incompletos, reflexiones en proceso, observaciones que están siendo elaboradas. Aquí se itera, experimenta y maduran las ideas antes de trasladarlas a `/publicar`.

### `/plantillas`
Plantillas Markdown estructuradas para mantener consistencia en formato y estilo. Incluye 5 tipos de plantillas:
- **Informe**: Para reportes y análisis estructurados
- **Análisis**: Para investigaciones profundas
- **Observaciones**: Para reflexiones insurgentes y cuestionamientos
- **Texto Creativo**: Para ensayos y escritura poética-filosófica
- **Nota Breve**: Para apuntes y notas rápidas

---

## 🔄 Flujo de Trabajo

```
Copilot → GitHub → Web
```

1. **Copilot** (Ideación): Usa GitHub Copilot para asistir en la redacción, estructuración y desarrollo de textos.

2. **GitHub** (Versionado): Almacena, versiona y organiza los textos en el repositorio, manteniendo un historial completo de cambios.

3. **Web** (Publicación): Los archivos de `/publicar` se integran en plataformas web para difusión pública.

### Ciclo de vida de un texto

```
[Idea] → /borradores → [Iteración] → /publicar → [Web]
```

---

## 🚀 Guía Rápida de Uso de las Plantillas

### 1. Selecciona la plantilla adecuada
Navega a `/plantillas` y elige la que mejor se adapte a tu tipo de texto:
- ¿Necesitas estructurar un reporte formal? → `plantilla-informe.md`
- ¿Vas a hacer un análisis profundo? → `plantilla-analisis.md`
- ¿Quieres cuestionar el status quo? → `plantilla-observaciones.md`
- ¿Escribirás un ensayo creativo? → `plantilla-texto-creativo.md`
- ¿Apunte rápido? → `plantilla-nota-breve.md`

### 2. Copia la plantilla
Copia el contenido de la plantilla elegida a un nuevo archivo en `/borradores`.

### 3. Completa las secciones
Llena cada sección con tu contenido. Las plantillas incluyen:
- Campos marcadores `[...]` que debes reemplazar
- Estructura predefinida para guiar tu escritura
- Formato consistente con el proyecto

### 4. Itera y mejora
Trabaja en el borrador, revisa, ajusta y perfecciona el contenido.

### 5. Publica
Cuando el texto esté listo, muévelo a `/publicar` para que esté disponible para integración web.

---

## 📝 Ejemplo de Uso

```bash
# 1. Copiar plantilla a borradores
cp plantillas/plantilla-analisis.md borradores/mi-primer-analisis.md

# 2. Editar y desarrollar el contenido
# (trabaja en borradores/mi-primer-analisis.md)

# 3. Cuando esté listo, mover a publicar
mv borradores/mi-primer-analisis.md publicar/mi-primer-analisis.md
```

---

## 🌐 Integración Web

Los archivos en `/publicar` están listos para ser integrados en plataformas de publicación web (GitHub Pages, sitios estáticos, CMS, etc.).

---

## 📌 Convenciones

- **Formato**: Markdown (.md)
- **Encoding**: UTF-8
- **Nombres de archivo**: kebab-case (ej: `mi-texto-filosofico.md`)
- **Tags**: Usar etiquetas al final de cada documento para clasificación

---

## 🧠 Filosofía del Proyecto

Este repositorio no es solo un archivo de textos, sino una **praxis de auto-institución intelectual**. Cada documento es parte de un proceso de construcción de conocimiento insurgente, crítico y creativo.

La arquitectura está diseñada para:
- **Transparencia**: Todo el historial de cambios es público
- **Iteración**: Los borradores son parte del proceso
- **Consistencia**: Las plantillas aseguran calidad y estructura
- **Flujo continuo**: De la idea a la publicación sin fricciones

---

**Inicio del proyecto**: 2026-02-08 18:19:30  
**Primer texto**: [primer-texto.md](publicar/primer-texto.md)  

---

_Este repositorio forma parte del proyecto poiosófico de auto-institución intelectual._