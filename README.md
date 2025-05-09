# Canonicals | Auditoría SEO Técnica – C&A México

Este repositorio contiene una auditoría técnica SEO enfocada en la revisión de etiquetas canónicas, estructura de encabezados HTML y aspectos fundamentales de SEO on-page para el sitio de C&A México.

## Categorías Analizadas

- [Página Principal (Home)](home.md)
- [Categoría Mujer](categoria-mujer.md)
- [Categoría Hombre](categoria-hombre.md)
- [Categoría Kids](categoria-kids.md)

## Objetivos

- Asegurar la presencia correcta de etiquetas `<link rel="canonical">`.
- Validar el uso adecuado de encabezados `<h1>`, `<h2>`, etc.
- Verificar metaetiquetas y estructura básica de SEO técnico.
- Emitir recomendaciones puntuales de mejora.

## Resultados Generales

| Sección       | Canonical Correcto | Encabezado `<h1>` | Observaciones Clave |
|---------------|--------------------|--------------------|----------------------|
| Home          | ✅ Sí               | ✅ Sí               | Requiere limpieza de código |
| Mujer         | ⚠️ No               | ❌ No               | Falta `<h1>` y canonical declarada |
| Hombre        | ⚠️ No               | ❌ No               | Mismo problema que Mujer |
| Kids          | ⚠️ No               | ❌ No               | Faltan canonical y estructura semántica clara |

## Recomendaciones Globales

- Incluir etiquetas `<link rel="canonical">` en todas las plantillas de categoría.
- Incorporar encabezado `<h1>` visible y descriptivo.
- Auditar uso excesivo de scripts externos que afectan Core Web Vitals.


----------

# Auditoría: Página Principal (Home)

## URL
[https://www.cyamoda.com](https://www.cyamoda.com)

## 🧩 Elementos Relevantes

| Elemento            | Estado    | Detalles |
|---------------------|-----------|----------|
| Canonical           | ✅ Sí     | `<link rel="canonical" href="https://www.cyamoda.com/" />` |
| `<h1>` Principal    | ✅ Sí     | Título visible y descriptivo |
| Meta Title          | ✅ Sí     | "Moda para Mujer, Hombre y Niños | C&A México" |
| Meta Description    | ✅ Sí     | Correctamente optimizada |

## 📌 Recomendaciones

- Limpiar scripts innecesarios en `<head>` para mejorar rendimiento.
- Incluir marcado estructurado (`Organization`, `WebSite`, `WebPage`).



--------

# Auditoría: Categoría Mujer

## URL
[https://www.cyamoda.com/mujer.html](https://www.cyamoda.com/mujer.html)

## 🧩 Elementos Relevantes

| Elemento            | Estado    | Detalles |
|---------------------|-----------|----------|
| Canonical           | ❌ No     | No existe `<link rel="canonical">` en el `<head>` |
| `<h1>` Principal    | ❌ No     | No se detectó ningún `<h1>` |
| Meta Title          | ✅ Sí     | "Ropa de Mujer | C&A México" |
| Meta Description    | ✅ Sí     | Presente y relevante |

## 📌 Recomendaciones

- Agregar: `<link rel="canonical" href="https://www.cyamoda.com/mujer.html" />`
- Incluir: `<h1>Moda para Mujer</h1>` como encabezado visible.


-------

# Auditoría: Categoría Hombre

## URL
[https://www.cyamoda.com/hombre.html](https://www.cyamoda.com/hombre.html)

## 🧩 Elementos Relevantes

| Elemento            | Estado    | Detalles |
|---------------------|-----------|----------|
| Canonical           | ❌ No     | No se encontró etiqueta canónica |
| `<h1>` Principal    | ❌ No     | Ausente en la estructura |
| Meta Title          | ✅ Sí     | "Ropa para Hombre | C&A México" |
| Meta Description    | ✅ Sí     | Alineada con intención de búsqueda |

## 📌 Recomendaciones

- Incluir etiqueta canónica explícita.
- Agregar encabezado `<h1>Ropa y Estilo para Hombre</h1>` en la parte superior.


------------

# Auditoría: Categoría Kids

## URL
[https://www.cyamoda.com/kids.html](https://www.cyamoda.com/kids.html)

## 🧩 Elementos Relevantes

| Elemento            | Estado    | Detalles |
|---------------------|-----------|----------|
| Canonical           | ❌ No     | No se encuentra en `<head>` |
| `<h1>` Principal    | ❌ No     | No se declara ningún encabezado principal |
| Meta Title          | ✅ Sí     | "Tendencias de Moda para Kids - C&A México" |
| Meta Description    | ✅ Sí     | Bien redactada, incluye productos |

## 📌 Recomendaciones

- Añadir: `<link rel="canonical" href="https://www.cyamoda.com/kids.html" />`
- Incluir encabezado visible: `<h1>Moda para Niños y Niñas</h1>`
- Optimizar jerarquía de encabezados para facilitar escaneo semántico por Google.


----------------

