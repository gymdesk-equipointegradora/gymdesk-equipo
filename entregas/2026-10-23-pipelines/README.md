# Pipelines

- **Entrega:** 23 de octubre de 2026, 23:59
- **Se entrega:** documento con el diagrama del pipeline de Integración Continua de GymDesk
- **Responsable de la entrega:** Fernando Vázquez
- **Lo que pide la profesora:** el diagrama lógico del pipeline (Commit → Build →
  Test → Resultado) y responder: qué comandos forman el Build, qué framework de
  pruebas se usa en Test y cómo se visualiza y reporta el Resultado. Regla clave:
  si las pruebas fallan, el código no se fusiona a `main`.

## Quién hace qué

| Quién | Qué sube a esta carpeta | Para cuándo | Estado |
|---|---|---|---|
| Emmanuel Castro | `etapa-test.md` | 22 oct | Pendiente |
| Fátima Avelino | `etapa-resultado.md` | 22 oct | Pendiente |
| José Alberto Herrera | `infraestructura.md` | 22 oct | Pendiente |
| Abraham Cervantes | `diagrama.png` | 23 oct, 14:00 | Pendiente |
| Carlos y Oscar | Revisión técnica | 23 oct, 18:00 | Pendiente |
| Fernando Vázquez | `pipeline-gymdesk.docx` | 23 oct, 20:00 | Pendiente |

## Cómo hacer cada parte

- **Etapa Test (Emmanuel):** explica con tus palabras qué pruebas corren (`cargo
  test` con 105 pruebas del backend y la revisión de tipos `tsc`), qué revisan y qué
  pasa si una falla.
- **Etapa Resultado (Fátima):** explica qué significa verde y rojo, dónde se ve (los
  *Checks* del Pull Request) y por qué la protección de `main` impide fusionar en rojo.
- **Infraestructura (José Alberto):** qué es GitHub Actions, qué es un Runner (una
  máquina limpia de Windows o Linux que presta GitHub), y el costo (gratis dentro de
  los minutos incluidos).
- **Diagrama (Abraham):** 4 bloques de colores conectados (Commit, Build, Test,
  Resultado) con sus comandos debajo, y una salida verde (fusionar a `main`) y una
  roja (bloqueado, corregir).
- **Documento final (Fernando):** portada, el diagrama, las tres preguntas
  respondidas con las partes de arriba y la conclusión.

## Datos técnicos de GymDesk

| Etapa | Qué pasa | Comandos / herramientas |
|---|---|---|
| Commit | Se sube una rama y se abre un Pull Request hacia `main` | `git push`, Pull Request en GitHub |
| Build | Un Runner de Windows instala dependencias y compila | `npm ci`, `npm run build` (TypeScript + React), `cargo build` (Rust / Tauri) |
| Test | Corren las pruebas automáticas | `cargo test` (105 pruebas del backend), `tsc` (tipos de TypeScript) |
| Resultado | Palomita verde o tache rojo en el Pull Request; en rojo no se puede fusionar | Checks de GitHub, protección de `main`, instalador como artifact |

## Ejemplo en vivo

Este repositorio tiene un pipeline real en `.github/workflows/revision.yml`. Abre
cualquier Pull Request y ve la pestaña *Checks*: es exactamente lo que describe la
tarea. Sirve como evidencia y como base para la próxima sesión.
