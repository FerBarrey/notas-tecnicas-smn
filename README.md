# Notas Técnicas · Servicio Meteorológico Nacional (SMN)

Notas técnicas de mi autoría publicadas en el Repositorio Institucional del
Servicio Meteorológico Nacional de Argentina, elaboradas en el área de
**Meteorología y Sociedad** (Dirección Nacional de Pronósticos y Servicios para la Sociedad).

Temas: experiencia de usuario y ciudadana (CX), análisis de datos, procesamiento de
lenguaje natural y sistemas de alerta temprana para la gestión del riesgo de desastres.

---

## 📄 NT SMN 2026-217 · Análisis Estratégico de Experiencia Ciudadana (CX) mediante Procesamiento de Lenguaje Natural

**Título completo:** Análisis Estratégico de Experiencia Ciudadana (CX) mediante Procesamiento de
Lenguaje Natural (PNL): Una Arquitectura Orientada a Objetos para el Monitoreo Estratégico de la App móvil del SMN <br>
**Autor:** Fernando Diego Barreyro · **Fecha:** septiembre 2026

Ecosistema de ciencia de datos para monitorear la "Voz del Ciudadano" sobre la app oficial del SMN
(`ar.gob.smn`). Mediante web scraping y una arquitectura orientada a objetos (clase `ReviewManager`)
se extrajeron **4.107 reseñas** de Google Play, clasificadas con **RoBERTuito** (Transformers en español)
y analizadas con **LDA** para descubrir tópicos.

**Resultados principales**
- NPS percibido de **16,97**, con tendencia de recuperación desde la versión 0.0.9.
- Correlación de Pearson de **0,68** entre el sentimiento inferido por el modelo y la valoración del usuario.
- *Aha! moments* ligados a la precisión del dato; *pain points* en la estabilidad de widgets y la geolocalización.

`Python` `NLP` `Transformers` `RoBERTuito` `LDA` `Web scraping` `OOP` `CX`

📥 [PDF](NT-2026-217/Nota_Tecnica_SMN_2026-217.pdf) · 🔗 [Repositorio SMN](http://hdl.handle.net/20.500.12160/3316)

---

## 📄 NT SMN 2026-210 · Relevamiento de usos y valoraciones del Sistema de Alerta Temprana (2024–2025)

**Título completo:** Relevamiento de usos y valoraciones del Sistema de Alerta Temprana y productos del SMN
en usuarios del sector de emergencias y gestión del riesgo de desastres entre 2024 y 2025
**Autores:** Fernando Diego Barreyro y Julián Martín Goñi · **Fecha:** mayo 2026

Resultados de la encuesta nacional a usuarios del sector de emergencias y gestión del riesgo
(Defensas Civiles provinciales y de CABA, Ministerio de Seguridad de la Nación, Cruz Roja Argentina y
Administración de Parques Nacionales) sobre el Sistema de Alerta Temprana, el pronóstico extendido a 7 días,
el Pronóstico Semanal, el Pronóstico Climático Trimestral, el Informe ENOS, el monitoreo diario y mensual
y la app móvil del SMN.

Dimensiones evaluadas por producto: precisión, comprensión, utilidad, acceso, frecuencia de uso,
satisfacción y oportunidades de mejora.

`Encuestas` `Análisis de datos` `Sistemas de alerta temprana` `Gestión del riesgo` `UX`

📥 [PDF](NT-2026-210/Nota_Tecnica_SMN_2026-210.pdf) · 🔗 [Repositorio SMN](http://hdl.handle.net/20.500.12160/3248)

---

## Cómo citar

> Barreyro, F. D., 2026: Análisis Estratégico de Experiencia Ciudadana (CX) mediante Procesamiento de
> Lenguaje Natural (PNL): Una Arquitectura Orientada a Objetos para el Monitoreo Estratégico de la App
> móvil del SMN. *Nota Técnica SMN 2026-217*. http://hdl.handle.net/20.500.12160/3316

> Barreyro, F. D., Goñi, J. M., 2026: Relevamiento de usos y valoraciones del Sistema de Alerta Temprana
> y productos del SMN en usuarios del sector de emergencias y gestión del riesgo de desastres entre 2024
> y 2025.<br> *Nota Técnica SMN 2026-210*. http://hdl.handle.net/20.500.12160/3248

## Derechos

Documentos producidos en el Servicio Meteorológico Nacional. Según su nota de copyright, *"la información
aquí presentada puede ser reproducida a condición de que la fuente sea adecuadamente citada"*.
Los resultados y juicios expresados no presuponen un aval del SMN.
Fuente original: [Repositorio Institucional del SMN](https://repositorio.smn.gob.ar).
