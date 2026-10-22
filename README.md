# GymDesk · Equipo del proyecto

Espacio de trabajo del equipo de **Grid.mx** para el proyecto GymDesk: documentos
del libro, pruebas, entregas de clase y seguimiento de tareas.

> **¿Necesitas algo técnico?** Capturas, una versión del instalador, datos de cómo
> funciona algo, comandos o diagramas del sistema: abre un issue de tipo **Tarea**
> y asígnalo a Oscar (o avísale por WhatsApp). Se te pasa por escrito.

## ¿Qué es GymDesk?

Sistema de escritorio para administrar gimnasios: control de acceso por huella,
código o QR; caja y punto de venta; socios y membresías; inventario; reportes.
Funciona completo sin internet y los datos se quedan en la computadora del gimnasio.

- **Precio:** $849 al mes o $8,499 al año, IVA incluido. 30 días de prueba gratis.
- **Instalador:** descárgalo desde la sección *Releases* de este repositorio.

## Empieza aquí

1. Busca tu nombre en [`roles/`](roles/) y lee tu guía: qué te toca, qué documentos
   del libro son tuyos y cómo hacerlos.
2. Revisa [`docs/pendientes.md`](docs/pendientes.md): los documentos del libro que
   faltan, con responsable e instrucciones.
3. Revisa [`entregas/`](entregas/): las tareas de Classroom abiertas y tu parte en cada una.
4. Para subir tu trabajo, sigue [CONTRIBUIR.md](CONTRIBUIR.md).

## Equipo y roles

| Integrante | Rol | Guía |
|---|---|---|
| Oscar Espinoza Landeta | Gerente del Proyecto y Arquitecto de Software | [gerencia.md](roles/gerencia.md) |
| Carlos Olaya Gutiérrez | Frontend, Diseño UX/UI y SEO | [diseno-ux.md](roles/diseno-ux.md) |
| Fernando Vázquez Valeriano | Analista de Mercado | [mercado.md](roles/mercado.md) |
| Fátima Avelino Celis | Analista de Calidad | [calidad.md](roles/calidad.md) |
| Emmanuel Castro Salvador | Ingeniero de Pruebas (QA) | [pruebas-qa.md](roles/pruebas-qa.md) |
| José Alberto Herrera Flores | Coordinador de Abastecimientos | [abastecimientos.md](roles/abastecimientos.md) |
| Abraham Cervantes Romero | Capacitación y Comunicación | [capacitacion.md](roles/capacitacion.md) |

## Carpetas

| Carpeta | Qué contiene |
|---|---|
| [`roles/`](roles/) | Guía de trabajo de cada rol |
| [`docs/`](docs/) | Documentos del proyecto (libro APP), pendientes y plantilla |
| [`pruebas/`](pruebas/) | Casos de prueba de GymDesk |
| [`entregas/`](entregas/) | Una carpeta por cada tarea de Classroom |

## Cómo trabajamos

1. **Cada tarea es un issue** con responsable y fecha. Se ve en el tablero del proyecto.
2. **Nunca se sube directo a `main`.** Crea una rama, sube tu parte y abre un Pull Request.
3. **El pipeline revisa tu Pull Request** (pestaña *Checks*). Si sale en rojo, corrige
   antes de pedir revisión. Si sale en verde, Oscar lo revisa y lo fusiona.
4. **Errores de GymDesk:** se reportan como issue con la plantilla *Reporte de error*.
5. **Revisiones de calidad:** se registran con la plantilla *Verificación de calidad*.

## Propiedad

GymDesk fue desarrollado por Oscar Espinoza Landeta y Carlos Olaya Gutiérrez.
Los documentos de este repositorio son trabajo del equipo para la materia de
Administración Profesional de Proyectos y el Proyecto Integrador.
