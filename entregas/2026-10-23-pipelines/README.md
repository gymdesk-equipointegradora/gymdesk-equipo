# Pipelines

- **Entrega:** 23 de octubre de 2026, 23:59
- **Se entrega:** documento con el diagrama del pipeline de Integración Continua de GymDesk
- **Responsable de la entrega:** Fernando Vázquez

## Quién hace qué

| Quién | Qué sube a esta carpeta | Para cuándo | Estado |
|---|---|---|---|
| Emmanuel Castro | `etapa-test.md`: qué se prueba y con qué herramientas | 22 oct | Pendiente |
| Fátima Avelino | `etapa-resultado.md`: qué pasa en verde y en rojo | 22 oct | Pendiente |
| José Alberto Herrera | `infraestructura.md`: GitHub Actions, Runners y costo | 22 oct | Pendiente |
| Abraham Cervantes | `diagrama.png`: diagrama en draw.io o Canva | 23 oct, 14:00 | Pendiente |
| Carlos y Oscar | Revisión técnica | 23 oct, 18:00 | Pendiente |
| Fernando Vázquez | `pipeline-gymdesk.docx`: documento final | 23 oct, 20:00 | Pendiente |

## Datos técnicos de GymDesk

| Etapa | Qué pasa | Comandos / herramientas |
|---|---|---|
| Commit | Se sube una rama y se abre un Pull Request hacia `main` | `git push`, Pull Request en GitHub |
| Build | Un Runner de Windows instala dependencias y compila | `npm ci`, `npm run build` (TypeScript + React), `cargo build` (Rust / Tauri) |
| Test | Corren las pruebas automáticas | `cargo test` (105 pruebas del backend), `tsc` (tipos de TypeScript) |
| Resultado | Palomita verde o tache rojo en el Pull Request; en rojo no se puede fusionar | Checks de GitHub, protección de `main`, instalador como artifact |

## Ejemplo en vivo

Este mismo repositorio tiene un pipeline real en `.github/workflows/revision.yml`:
cada Pull Request pasa por sus etapas y, si falla, no se puede fusionar a `main`.
Sirve como evidencia y como base para la próxima sesión, donde se escribirá el
archivo YAML.
