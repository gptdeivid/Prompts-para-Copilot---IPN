# Prompts-para-Copilot---IPN

Prompt engineering es el arte de diseñar instrucciones precisas y estratégicas para obtener respuestas útiles y de calidad de modelos de inteligencia artificial (IA) como Claude y Copilot. En el contexto de desarrollo web, un prompt es el texto que le envías a la IA (por ejemplo, “genera la estructura HTML para una landing page institucional”) para que te ayude a crear código, contenido, o diseño de manera progresiva y automatizada.

¿Por qué es relevante para código web?

Los modelos de IA pueden generar desde estructuras HTML y CSS, hasta contenido persuasivo, scripts de validación o configuraciones técnicas, siempre que el prompt sea claro y detallado.

Dividir una tarea compleja en una secuencia de prompts progresivos permite construir soluciones “de abajo hacia arriba”, validando y refinando resultados en cada paso.

Permite optimizar el trabajo, ahorrar tiempo, y reducir errores al automatizar partes repetitivas y creativas del desarrollo.


Fase 1: Estructura Base (Prompts 1-3)
Prompt 1: Análisis de necesidades del IPN

text
Actúa como especialista digital. Analiza necesidades del IPN para una landing page orientada a estudiantes, padres, profesionales y empleadores. Presenta objetivos de conversión en formato tabla (Público | Objetivo | CTA principal).
Prompt 2: Estructura HTML5 semántica

text
Desarrolla la estructura HTML5 básica de landing page para el IPN. Debe incluir header fijo, navegación simple, hero section, 4 secciones principales y footer institucional. Usa colores púrpura #682444 y blanco.
Prompt 3: Sistema de colores y tipografía IPN

text
Define paleta de máximo 5 colores (incluyendo púrpura institucional), 2-3 familias tipográficas, tamaños para títulos y textos, y ratios de contraste WCAG AA. Presenta ejemplos en markdown.
Fase 2: Contenido y Copywriting (Prompts 4-6)
Prompt 4: Propuestas de valor en variantes

text
Redacta tres variantes de propuesta de valor para el IPN: excelencia académica, oportunidades profesionales, transformación social. Cada variante debe incluir headline, subtítulo persuasivo y CTA claro.
Prompt 5: Contenido persuasivo por secciones

text
Genera copy para: Sobre IPN (breve descripción + 3 diferenciadores), Programas académicos (media superior, licenciatura, posgrado - una línea cada uno), Testimonios (3 estudiantes/egresados), CTAs diferenciados según público.
Prompt 6: Microcopy y optimización

text
Optimiza microcopy: placeholders de formularios, etiquetas de botones, mensajes de error y confirmaciones, links de información. Muestra versión antes/después, orientado a conversión y accesibilidad.
Fase 3: Formularios y Conversión (Prompts 7-8)
Prompt 7: Formulario optimizado

text
Diseña formulario con 5 campos clave (nombre, email, teléfono, carrera, nivel académico), validación HTML5, mensajes personalizados de error. Da estructura HTML con comentarios.
Prompt 8: Segmentar landing para públicos

text
Crea tres variantes de landing: estudiantes de bachillerato, padres de familia y profesionales en capacitación. Define headline, puntos clave, CTA y multimedia sugerida para cada segmento en tabla comparativa.
Fase 4: Diseño y Experiencia (Prompts 9-11)
Prompt 9: CSS componentes principales

text
Genera CSS usando Flexbox/Grid y variables, para header, hero, cards, testimonios, formulario, footer. Incluye media queries y animaciones suaves.
Prompt 10: Diseño mobile-first

text
Ajusta tipografía, botones, formulario, imágenes y menú para mobile. Da ejemplos críticos de media queries y reglas de accesibilidad táctil.
Prompt 11: Accesibilidad WCAG 2.1 AA

text
Audita HTML/CSS usando checklist accesibilidad: contraste, orden de headings, atributos alt, navegación teclado, ARIA labels, etiquetas en formularios. Presenta tabla con cambios y beneficios.
Fase 5: Contenido Multimedia (Prompts 12-13)
Prompt 12: Especificaciones de imágenes/video

text
Define dimensiones, formato, peso y descripción ideal para imágenes hero (1920x600px), programas (400x300px), testimonios (200x200px), y video opcional (15-30s). Da ejemplos de HTML <picture> y optimizaciones.
Prompt 13: Iconografía SVG personalizada

text
Especifica 8 iconos temáticos en SVG (programas, becas, experiencia, investigación, comunidad, innovación, admisiones, contacto): dimensiones, estilo, paleta, casos de uso. Incluye código base y guidelines CSS.
Fase 6: Funcionalidad e Integración (Prompts 14-16)
Prompt 14: JavaScript Vanilla

text
Implementa interacciones: validación formulario en tiempo real, scroll suave, carrusel de testimonios, banner cookies. Da código modular y comentado.
Prompt 15: API REST backend

text
Define endpoints clave (POST leads, GET programs, POST newsletter), estructura JSON, validaciones, manejo de errores y ejemplos de fetch() con seguridad básica.
Prompt 16: Analytics con GA4 y eventos

text
Mapea eventos tracking: page view, cta click, form submit, scroll tracking, interacción testimonios, descargas, contactos. Proporciona código GTM/GA4 y estructura recomendada.
Fase 7: Optimización y Testing (Prompts 17-19)
Prompt 17: SEO on-page y técnico

text
Establece meta tags, estructura headings, JSON-LD schema markup, palabras claves, y optimiza Core Web Vitals (<2.5s). Checklist de SEO y comandos de testeo incluidos.
Prompt 18: Tests A/B estadísticos

text
Diseña 3 tests A/B: headline funcional vs emocional, color de botón CTA, longitud del formulario. Define métricas, tamaño de muestra y duración recomendadas.
Prompt 19: Checklist preexlanzamiento

text
Listado exhaustivo (funcionalidad, diseño, accesibilidad, seguridad, performance, contenido, analytics, monitoreo, navegadores, legal) en formato interactivo y escala de severidad.
