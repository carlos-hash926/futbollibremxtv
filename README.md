# ⚽ Fútbol Libre — Addon de Stremio para fútbol y deportes

**Proyecto de integración con Stremio para explorar información sobre fútbol, consultar calendarios deportivos y organizar contenidos relacionados con competiciones nacionales e internacionales.**

🌐 **Sitio web del proyecto:** [Fútbol Libre](https://futbollibremxtv.com/)

> **Estado:** Proyecto en desarrollo. Este repositorio describe una integración propuesta; las funciones y los pasos de instalación estarán disponibles cuando se publique una versión funcional. No se ofrece actualmente una URL de instalación verificada.

## 📖 ¿Qué es Fútbol Libre para Stremio?

**Fútbol Libre para Stremio** es un proyecto orientado a aficionados que buscan una forma organizada de descubrir información de partidos, equipos, ligas y eventos deportivos desde una interfaz compatible con el ecosistema de addons de Stremio.

La propuesta consiste en crear un catálogo deportivo en español, con fichas informativas, horarios y referencias a fuentes oficiales o autorizadas. Para consultar información adicional del proyecto y sus publicaciones, visita [Fútbol Libre](https://futbollibremxtv.com/).

## ✨ Funcionalidades previstas

- **Calendario de partidos:** próximos encuentros con fecha, hora, equipos y competición.
- **Catálogo de fútbol:** navegación por torneos y categorías deportivas.
- **Cobertura internacional:** información sobre Liga MX, LaLiga, Premier League, Serie A, Bundesliga, Ligue 1 y torneos continentales, según la disponibilidad de datos.
- **Fichas detalladas:** información contextual de eventos y competiciones.
- **Búsqueda:** localización de partidos, equipos y eventos desde un catálogo compatible con Stremio.
- **Fuentes autorizadas:** enlaces a retransmisiones solamente cuando se disponga de los derechos o de una fuente permitida.
- **Interfaz en español:** nombres, categorías y descripciones adaptados al público hispanohablante.

Estas características son **objetivos de desarrollo**, no funcionalidades ya implementadas.

## 🏆 Competiciones de interés

| Competición | Región | Contenido previsto |
| --- | --- | --- |
| Liga MX | México | Calendario y fichas de partidos |
| LaLiga | España | Encuentros y equipos |
| Premier League | Inglaterra | Programación de jornadas |
| Serie A | Italia | Agenda de competición |
| Bundesliga | Alemania | Calendario y resultados informativos |
| Ligue 1 | Francia | Partidos y clubes |
| UEFA Champions League | Europa | Calendario y etapas del torneo |
| Copa Libertadores | Sudamérica | Partidos y seguimiento de la competición |
| Torneos de selecciones | Internacional | Fechas y eventos relevantes |

La disponibilidad dependerá de las fuentes de datos integradas y sus condiciones de uso.

## 🧩 ¿Cómo funciona un addon de Stremio?

Stremio utiliza un protocolo HTTP basado en respuestas JSON. Un addon puede publicar un manifiesto y ofrecer recursos como catálogos, metadatos y, cuando corresponda, streams autorizados.

| Recurso | Función |
| --- | --- |
| `manifest.json` | Identidad, versión y capacidades del addon |
| `catalog` | Listados de eventos o elementos disponibles |
| `meta` | Detalles de cada elemento del catálogo |
| `stream` | Fuentes reproducibles legalmente disponibles, si se implementan |

Documentación técnica: [Stremio Addon SDK](https://github.com/Stremio/stremio-addon-sdk) y [protocolo de addons](https://github.com/Stremio/stremio-addon-sdk/blob/master/docs/protocol.md).

## 🛠️ Tecnología propuesta

La implementación se plantea con **Node.js**, **JavaScript** y el paquete oficial `stremio-addon-sdk`. La aplicación podrá obtener programación deportiva desde una fuente de datos autorizada y devolver información estructurada mediante los recursos del protocolo de Stremio.

```text
Fútbol Libre — integración propuesta
├── manifest.json          # Identidad y capacidades
├── catalog                # Calendarios y categorías
├── meta                   # Información de eventos
└── fuentes autorizadas    # Datos y enlaces con permisos
```

La estructura anterior es conceptual y no implica que estos archivos o endpoints ya existan.

## 📥 Instalación

**Todavía no hay una versión pública instalable.** Cuando esté disponible, este apartado incluirá la URL HTTPS real del manifiesto y las instrucciones para agregar el complemento desde la interfaz de Stremio.

No se debe confundir la URL del sitio web con un endpoint de addon: `https://futbollibremxtv.com/` es la página del proyecto, **no** una dirección `/manifest.json` confirmada.

## 🌍 Fútbol Libre: información y recursos

Para novedades y contenido relacionado con el fútbol, consulta estos recursos del proyecto:

- **Página principal:** [Fútbol Libre — futbollibremxtv.com](https://futbollibremxtv.com/)
- **Información del proyecto:** este repositorio y su documentación.
- **Desarrollo de addons:** [SDK de Stremio en GitHub](https://github.com/Stremio/stremio-addon-sdk).

El objetivo es mantener una documentación clara en español sobre la integración y facilitar su evolución de forma abierta.

## 🤝 Colaboraciones

Se agradecen las contribuciones relacionadas con integración de calendarios deportivos, documentación, accesibilidad, traducciones, corrección de errores y pruebas. Antes de proponer fuentes audiovisuales, comprueba que su distribución y reproducción estén autorizadas.

## ⚖️ Aviso legal

Este proyecto no está afiliado, patrocinado ni respaldado por Stremio, ligas, clubes, cadenas de televisión ni titulares de derechos deportivos. Las marcas mencionadas pertenecen a sus respectivos titulares.

No se incluyen instrucciones para acceder a emisiones sin autorización. Cada integrador deberá respetar los derechos de autor, los términos de los proveedores y la normativa aplicable.

## ❓ Preguntas frecuentes

### ¿Qué es Fútbol Libre para Stremio?

Es una propuesta de addon deportivo que busca organizar información de fútbol y programación de partidos dentro de Stremio.

### ¿Puedo ver partidos de fútbol en vivo?

El proyecto se centra en la información deportiva. Cualquier reproducción que se añada en el futuro dependerá de fuentes legítimas y autorizadas.

### ¿Funciona en Android, Windows o macOS?

Stremio cuenta con clientes en distintas plataformas; la compatibilidad concreta del addon deberá comprobarse cuando se publique una versión funcional.

### ¿Dónde puedo encontrar más información de Fútbol Libre?

En el sitio web del proyecto: **[https://futbollibremxtv.com/](https://futbollibremxtv.com/)**.

---

**Fútbol Libre** · Proyecto de integración deportiva con Stremio · [Visitar sitio web](https://futbollibremxtv.com/)
