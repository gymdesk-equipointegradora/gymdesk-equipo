# Documentos pendientes del libro

Herramientas del Método Escala que faltan en el Plan del Proyecto (partidas del WBS
1.1.1 a 1.1.5). Cada una tiene responsable, de qué documentos sale su información y
qué debe contener.

**Para todos:** usa la [plantilla](plantilla-documento.docx). Los documentos de
planeación van con **Fecha: 30 de marzo de 2026, Revisión 1**, igual que el WBS y
las matrices. Firman la Patrocinadora (Profa. Julieta Edith Hernández Guzmán) y el
Gerente del Proyecto (Oscar Espinoza Landeta). Nombre del archivo: el siguiente
número libre, por ejemplo `14-mapa-de-riesgos.docx`.

## Resumen

| Documento | Responsable | Apoyo | Partida WBS |
|---|---|---|---|
| [Mapa Mental de Expectativas](#mapa-mental-de-expectativas) | Abraham Cervantes | Fernando Vázquez | 1.1.1.1 |
| [Programa – Ruta Crítica](#programa--ruta-crítica) | José Alberto Herrera | Oscar Espinoza | 1.1.2.1.9 |
| [Estimados de Costos](#estimados-de-costos) | José Alberto Herrera | Fernando Vázquez | 1.1.2.1.10 |
| [Imprevistos y Contingencias](#imprevistos-y-contingencias) | José Alberto Herrera | — | 1.1.2.1.11 |
| [Presupuesto Base](#presupuesto-base) | Fernando Vázquez | José Alberto Herrera | 1.1.2.1.12 |
| [Programa de Erogaciones](#programa-de-erogaciones) | Fernando Vázquez | José Alberto Herrera | 1.1.2.1.13 |
| [Mapa de Riesgos](#mapa-de-riesgos) | Emmanuel Castro | Fátima Avelino | 1.1.2.1.16 |
| [Matriz de Administración de Riesgos](#matriz-de-administración-de-riesgos) | Emmanuel Castro | Fátima Avelino | 1.1.2.1.17 |
| [Control de Cambios](#control-de-cambios) | Fátima Avelino | Oscar Espinoza | 1.1.2.1.19 |
| [Lecciones Aprendidas](#lecciones-aprendidas) | Abraham Cervantes | Todos | 1.1.2.1.20 |
| [Listas de Aseguramiento de Calidad](#listas-de-aseguramiento-de-calidad) | Fátima Avelino | Emmanuel Castro | 1.1.3.1 |
| [Cotizaciones y Evaluación de Alternativas](#cotizaciones-y-evaluación-de-alternativas) | José Alberto Herrera | — | 1.1.3.2 y 1.1.3.3 |
| [Guía Rápida de Uso](#guía-rápida-de-uso) | Abraham Cervantes | Carlos Olaya | 1.5.4 |

Las fechas de entrega las pone la profesora; cuando pida uno, Oscar abre su issue
con fecha.

## Datos del proyecto que vas a necesitar

| Dato | Valor |
|---|---|
| Fechas | 23 de marzo al 22 de septiembre de 2026 (26 semanas) |
| Recursos humanos | Oscar 30 h/sem a $150; Carlos 30 h/sem a $120; los otros cinco 18 h/sem a $80 cada uno. Total $397,800 |
| Infraestructura | $18,600: 4 computadoras de $15,000 depreciadas 30% anual ($9,000); SDK de huella US$500 a $18 ($9,000); dominio $600; GitHub $0 |
| Administración | $11,900 |
| Equipo para el gimnasio | $2,800 |
| Costo directo | $431,100 |
| Imprevistos y contingencias | 5% y 5% del costo directo ($21,555 cada uno) |
| Estimado / Presupuesto | $452,655 / $474,210 |
| Hitos | Están en el Calendario de Eventos (documento 11) |

---

## Mapa Mental de Expectativas

**Qué es:** el primer paso del libro. Muestra a los involucrados clave del proyecto
y lo que espera cada uno de los entregables.

**De dónde sale:** Charter (involucrados) y Declaración del Alcance (entregables).

**Qué debe tener:**

- Al centro, el proyecto: "Implementación de GymDesk".
- Una rama por involucrado: Patrocinadora, Dirección del gimnasio, personal de
  recepción, socios del gimnasio, equipo de Grid.mx.
- En cada rama, 3 a 5 expectativas concretas ("cobrar en menos de 30 segundos",
  "que no entren socios vencidos", "aprender a usarlo en una sesión").
- Se dibuja en draw.io, Canva o XMind y se pega como imagen en la plantilla.

## Programa – Ruta Crítica

**Qué es:** las actividades del proyecto con su duración y orden; la ruta crítica
son las actividades que, si se retrasan, retrasan todo el proyecto.

**De dónde sale:** WBS (documento 03) y Calendario de Eventos (documento 11).

**Qué debe tener:**

1. Tabla con las actividades del último nivel del WBS: clave, nombre, duración en
   días y actividades predecesoras.
2. La red de actividades (diagrama de nodos con flechas).
3. Para cada actividad: inicio y fin más temprano, inicio y fin más tardío y holgura.
4. La ruta crítica marcada (actividades con holgura 0) y su duración total, que debe
   dar las 26 semanas del proyecto.
5. Un diagrama de Gantt. Se puede hacer en Excel, ProjectLibre o GanttProject.

## Estimados de Costos

**Qué es:** cuánto cuesta cada partida del WBS.

**De dónde sale:** la tabla de datos de arriba, el WBS y la Matriz de Roles.

**Qué debe tener:**

- Tabla por partida del WBS: recurso humano (horas × tarifa), materiales y equipo,
  servicios y total.
- Subtotales por fase (1.1 a 1.6) y el costo directo, que debe dar **$431,100**.
- Nota de cómo se calculó cada concepto (por ejemplo la depreciación de las computadoras).

## Imprevistos y Contingencias

**Qué es:** las reservas del proyecto. Según el libro, los **imprevistos** cubren
errores u omisiones propios del proyecto y los administra el Gerente; la
**contingencia** cubre factores externos y la autoriza la Patrocinadora.

**Qué debe tener:**

- Por qué se usa 5% y 5% (el alcance ya está definido).
- Cálculo: $431,100 × 5% = $21,555 de imprevistos y $21,555 de contingencia.
- Ejemplos de qué cubre cada uno (tipo de cambio del SDK, un equipo que falle, un
  proveedor que no entregue).
- Quién autoriza usar cada reserva.

## Presupuesto Base

**Qué es:** el presupuesto autorizado del proyecto, repartido en el tiempo.

**De dónde sale:** Estimados de Costos e Imprevistos y Contingencias.

**Qué debe tener:**

- Costo directo + imprevistos = estimado ($452,655); + contingencia = presupuesto ($474,210).
- Tabla por mes (marzo a septiembre) con el costo del mes y el acumulado.
- La gráfica del acumulado (curva S) hecha en Excel.

## Programa de Erogaciones

**Qué es:** cuándo sale el dinero: los pagos del proyecto mes por mes.

**Qué debe tener:**

- Tabla por mes con cada pago: sueldos, compra de computadoras, licencia del SDK,
  dominio, equipo del gimnasio.
- Total por mes y acumulado. Diferencia con el Presupuesto Base: aquí cuenta la
  fecha de pago (por ejemplo, la licencia se paga completa en un mes).

## Mapa de Riesgos

**Qué es:** los riesgos del proyecto acomodados por probabilidad e impacto.

**Qué debe tener:**

1. Lista de al menos 10 riesgos: técnicos (lector de huella, impresora), de
   personas (rotación de la recepción), externos (tipo de cambio, proveedor), de
   negocio (que ningún gimnasio quiera el sistema).
2. A cada riesgo, una probabilidad (1 a 5) y un impacto (1 a 5).
3. La matriz de 5 × 5 con cada riesgo en su casilla, en colores: verde (bajo),
   amarillo (medio) y rojo (alto).

## Matriz de Administración de Riesgos

**Qué es:** qué se hará con cada riesgo del mapa.

**Qué debe tener**, por riesgo: causa, efecto, señal de alerta (disparador),
estrategia (evitar, mitigar, transferir o aceptar), acción concreta y responsable.
Empieza por los riesgos en rojo.

## Control de Cambios

**Qué es:** cómo se pide, se evalúa y se autoriza un cambio al proyecto.

**Qué debe tener:**

- El procedimiento: quién puede pedir un cambio, a quién, y quién lo autoriza.
- El formato de solicitud: descripción, motivo, impacto en alcance, tiempo, costo y
  calidad, decisión y firma.
- Un registro de cambios con al menos un ejemplo (por ejemplo, agregar la
  autorización firmada del socio para registrar su huella).

## Lecciones Aprendidas

**Qué es:** lo que salió bien y lo que salió mal, para no repetir errores.

**Qué debe tener:** tabla con etapa del proyecto, qué pasó, causa, efecto y
recomendación. Pide a cada integrante al menos dos lecciones de su rol.

## Listas de Aseguramiento de Calidad

**Qué es:** la verificación de cada entregable contra sus criterios de aceptación.

**De dónde sale:** Declaración del Alcance (criterios) y Lista de Verificación (documento 08).

**Qué debe tener:** una lista por entregable principal (por ejemplo caja, acceso,
capacitación) con sus criterios, si se cumple, quién verificó y la fecha.

## Cotizaciones y Evaluación de Alternativas

**Qué es:** al menos tres cotizaciones por compra y una matriz para elegir la mejor.

**Qué debe tener:**

- Para cada compra de la Matriz de Abastecimientos (impresora térmica, lector de
  códigos, no-break, lector de huella): tres proveedores con precio, tiempo de
  entrega y garantía.
- Matriz de evaluación: criterios con peso (precio, entrega, garantía, soporte),
  calificación de cada proveedor y el elegido.

## Guía Rápida de Uso

**Qué es:** el material de capacitación para la recepción del gimnasio.

**Qué debe tener:** máximo 4 hojas con capturas: abrir turno, registrar entrada de
un socio, cobrar una membresía, vender un producto, hacer el corte de caja y qué
hacer si algo falla. Usa el instalador de *Releases* para tomar las capturas o
pídeselas a Carlos.
