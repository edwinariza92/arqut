# 🧠 Ruta de Aprendizaje — Arquitectura de Computadores y Sistemas Operativos

> **Objetivo:** comprender los fundamentos de la arquitectura de computadores y de los sistemas operativos, conectándolos con ejemplos prácticos de programación en C.
>
> **Entorno:** Linux + GCC + Visual Studio Code.
>
> **Metodología:** Concepto → Ejemplo → Analogía → Preguntas → Mini examen → Corrección → Checkpoint.
>
> **Regla principal:** no avanzar solo por "terminar" temas. Un módulo se considera completado cuando existe comprensión práctica suficiente para explicarlo con palabras propias y resolver preguntas de aplicación.
>
> **Preparación:** Examen final en Coderbyte (formato por definir).

---

# 📊 Estado general

| Fase | Tema | Estado |
|---|---|---|
| 1 | Arquitectura de Computadores | ✅ Completado |
| 2 | Introducción a Sistemas Operativos | 🟢 En progreso |
| 3 | Conceptos Avanzados de Sistemas Operativos | 🟢 En progreso |
| 4 | Integración y Repaso General | ⬜ Pendiente |
| 5 | Preparación Examen Coderbyte | ⬜ Pendiente |

**Progreso orientativo:** Fase 2 — ~70% (Módulos 5, 6, 7 completados; Módulo 8 casi completado) · Fase 3 — 🟢 iniciada (Módulo 9 primera mitad)

---

# 📚 Cómo usamos este documento

Cada sesión sigue este ciclo:

1. 🧠 Concepto
2. 💻 Ejemplo
3. 🔍 Explicación
4. 🧪 Reto / Mini examen
5. 🐛 Revisión y corrección
6. 📝 Checkpoint
7. 🏆 Avance de módulo o proyecto

### Estados

- ⬜ Pendiente
- 🟢 En progreso
- ✅ Completado
- 🔁 Repasar
- 🧭 Adelanto

### Escala de Complejidad

Cada módulo tiene un nivel de complejidad del 1 al 5:

| Nivel | Significado |
|---|---|
| 1 | Conceptual básico, se entiende con una lectura |
| 2 | Requiere comprensión de relaciones entre conceptos |
| 3 | Requiere ejercicios prácticos para consolidar |
| 4 | Abstracción alta, varios conceptos encadenados |
| 5 | Complejidad máxima, requiere múltiples sesiones |

---

# 🧭 Reglas de estudio

1. Intentar responder antes de mirar las respuestas.
2. Explicar conceptos con palabras propias.
3. Usar ejemplos de C cuando ayuden a conectar teoría y práctica.
4. Registrar los errores importantes en cada checkpoint.
5. No avanzar si existe una confusión conceptual fundamental.
6. Hacer repasos periódicos de temas anteriores.
7. Al finalizar cada fase, realizar un examen de fase.
8. Al finalizar todo el recorrido, realizar un examen final.

---

# FASE 1 — ARQUITECTURA DE COMPUTADORES

## Objetivo de la fase

Entender cómo está organizado un computador y cómo la CPU ejecuta las instrucciones de un programa.

---

### 1. Arquitectura de Von Neumann

**Complejidad:** 2/5

- [x] Introducción
- [x] CPU
- [x] ALU
- [x] Unidad de Control
- [x] Memoria
- [x] Datos vs instrucciones
- [x] Programa almacenado
- [x] Entrada/Salida
- [x] Sistema de buses (datos, control, direcciones)
- [x] Cuello de botella de Von Neumann
- [x] Arquitectura Harvard (comparación)
- [x] Relación con programas en C
- [x] Mini examen
- [x] Corrección

**Estado:** ✅ Completado

---

### 2. Ciclo de Instrucción

**Complejidad:** 3/5

- [x] Introducción
- [x] Fetch (Búsqueda)
- [x] Decode (Decodificación)
- [x] Execute (Ejecución)
- [x] Program Counter (PC)
- [x] Instruction Register (IR)
- [x] Registros (propósito general, instrucción, estado, control)
- [x] Cálculo de dirección del operando
- [x] Captura del operando
- [x] Escritura de resultados
- [x] Relación entre CPU y memoria
- [x] Saltos y cambios del flujo de ejecución
- [x] Relación con `if`, `while` y `for`
- [x] Ciclo indirecto
- [x] Ciclo de interrupción
- [x] Mini examen
- [x] Corrección

**Estado:** ✅ Completado

---

### 3. CISC vs RISC

**Complejidad:** 2/5

- [x] Qué es un conjunto de instrucciones (ISA)
- [x] CISC (Complex Instruction Set Computer)
- [x] RISC (Reduced Instruction Set Computer)
- [x] Complejidad de instrucciones
- [x] Tamaño de instrucciones (variable vs fija)
- [x] Registros
- [x] Ejecución de instrucciones
- [x] Ventajas y desventajas
- [x] x86 (CISC)
- [x] ARM (RISC)
- [x] Comparación CISC vs RISC
- [x] Little Endian vs Big Endian
- [x] Sistemas embebidos (Arduino, Raspberry Pi, Nvidia Jetson)
- [x] Evolución y convergencia de ambas arquitecturas
- [x] Mini examen
- [x] Corrección

**Estado:** ✅ Completado

---

### 4. Segmentación (Pipelining)

**Complejidad:** 3/5

- [x] Concepto de pipeline
- [x] Ejecución por etapas
- [x] Paralelismo a nivel de instrucciones
- [x] Relación con Fetch/Decode/Execute
- [x] Ejemplo paso a paso
- [x] Throughput (mejora del rendimiento)
- [x] Ventajas y limitaciones
- [x] Mini examen
- [x] Corrección

**Estado:** ✅ Completado

---

### 📝 Examen de Fase 1

- [x] Examen teórico
- [x] Preguntas de razonamiento
- [x] Preguntas de aplicación
- [x] Corrección
- [x] Registro de errores
- [x] Repaso de temas débiles

**Estado:** ✅ Completado (73%)

---

# FASE 2 — INTRODUCCIÓN A SISTEMAS OPERATIVOS

## Objetivo de la fase

Comprender qué hace un sistema operativo y cómo administra los recursos del computador.

---

### 5. Estructuras de Sistemas Operativos

**Complejidad:** 2/5

- [x] Qué es un sistema operativo
- [x] Funciones principales (CPU, memoria, E/S)
- [x] Roles del SO: administrador de recursos y máquina ampliada
- [x] Monoprogramación vs multiprogramación
- [x] Aprovechamiento de la CPU
- [x] DMA (Acceso Directo a Memoria)
- [x] Jerarquía de memoria (registros, caché, RAM, SSD, disco, nube)
- [x] Caching
- [x] Modo usuario vs modo supervisor
- [x] Llamadas al sistema (system calls)
- [x] Paso de parámetros (registros, tablas en memoria, stack)
- [x] Protección de memoria (registro base y límite)
- [x] Mini examen
- [x] Corrección

**Estado:** ✅ Completado

---

### 6. Procesos

**Complejidad:** 3/5

- [x] Qué es un proceso
- [x] Programa vs proceso
- [x] Estado de un proceso (nuevo, listo, ejecución, bloqueado, terminado)
- [x] PCB (Bloque de Control de Proceso)
- [x] Creación de procesos (`fork()`)
- [x] Relación padre-hijo
- [x] Árbol de procesos
- [x] Ejecución de nuevos programas (`exec`)
- [x] Sincronización con `wait()`
- [x] Terminación con `exit()`
- [x] Terminación de procesos
- [x] Procesos concurrentes
- [x] Contexto de un proceso y cambio de contexto
- [x] Procesos cooperantes
- [x] Comunicación entre Procesos (IPC): señales, memoria compartida, semáforos, mensajes
- [x] Relación con programas en C
- [x] Mini examen
- [x] Corrección

**Estado:** ✅ Completado

---

### 7. Hilos (Threads)

**Complejidad:** 3/5

- [x] Qué es un hilo
- [x] Proceso vs hilo
- [x] Recursos compartidos (código, datos, archivos)
- [x] Stack propio de cada hilo
- [x] Hilos dentro de un proceso
- [x] Concurrencia vs paralelismo
- [x] Hilos a nivel usuario vs nivel kernel
- [x] Modelos multihilos (muchos a uno, uno a uno, muchos a muchos)
- [x] Ventajas de los hilos
- [x] Riesgos básicos
- [x] Programación de hilos en C (POSIX: `pthread_create`, `pthread_join`, `pthread_exit`)
- [x] Compilación con `-lpthread`
- [x] Evolución: de monoproceso a multicore
- [x] Mini examen
- [x] Corrección

**Estado:** ✅ Completado

---

### 8. Planificación de la CPU

**Complejidad:** 4/5

- [x] Qué es planificación
- [x] Scheduler (planificador)
- [x] Planificador largo plazo, corto plazo y mediano plazo
- [x] Objetivos de planificación (utilización, throughput, tiempo de retorno, tiempo de espera)
- [x] Ráfagas de CPU e I/O
- [x] Cambio de contexto y despachador (dispatcher)
- [x] Algoritmos no expropiativos:
  - [x] FCFS (First-Come, First-Served)
  - [x] HRRN (Highest Response Ratio Next)
- [x] Algoritmos expropiativos:
  - [x] Round Robin (quantum)
  - [x] SPN (Shortest Process Next)
  - [x] Colas de realimentación (Multilevel Feedback Queue)
- [x] Tiempo de espera, tiempo de respuesta, turnaround time
- [ ] Ejercicios de cálculo de tiempos
- [ ] Comparación de algoritmos
- [x] Planificación en tiempo real
- [x] Planificación SMP (Symmetric Multiprocessing)
- [x] Afinidad de procesador
- [x] Mini examen
- [x] Corrección

**Estado:** 🟢 En progreso

---

### 📝 Examen de Fase 2

- [ ] Examen teórico
- [ ] Preguntas de razonamiento
- [ ] Ejercicios de planificación
- [ ] Corrección
- [ ] Registro de errores
- [ ] Repaso de temas débiles

**Estado:** ⬜ Pendiente

---

# FASE 3 — CONCEPTOS AVANZADOS DE SISTEMAS OPERATIVOS

## Objetivo de la fase

Comprender cómo el sistema operativo administra memoria y almacenamiento.

---

### 9. Gestión de Memoria

**Complejidad:** 4/5

- [x] Por qué el SO administra memoria
- [x] Memoria física y direcciones de memoria
- [x] Traducción de direcciones lógicas a físicas
- [x] MMU (Unidad de Manejo de Memoria)
- [x] Registro de relocalización
- [x] Momentos de asociación de direcciones (compilación, carga, ejecución)
- [x] Carga dinámica y encadenamiento dinámico
- [x] Asignación contigua
- [x] Registros base y límite
- [x] Fragmentación interna y externa
- [x] Algoritmos de ubicación (primer ajuste, mejor ajuste, siguiente ajuste, peor ajuste)
- [x] Compactación
- [ ] Paginación (páginas, marcos, tabla de páginas)
- [ ] Traducción de direcciones con paginación
- [ ] Paginación multinivel
- [ ] Tabla de páginas invertida
- [ ] Páginas compartidas
- [ ] Segmentación (segmentos de código, datos, stack)
- [ ] Tabla de segmentos
- [ ] Protección y compartición de segmentos
- [ ] Combinación segmentación + paginación (Multics, Intel)
- [ ] Intercambio (swapping)
- [ ] Mini examen
- [ ] Corrección

**Estado:** 🟢 En progreso (primera mitad completada: direcciones, MMU, binding, fragmentación, algoritmos)

---

### 10. Memoria Virtual

**Complejidad:** 5/5

- [ ] Concepto de memoria virtual
- [ ] Memoria física vs virtual
- [ ] Separación lógica-física
- [ ] Paginación por demanda
- [ ] Bit de presente y bit de modificado
- [ ] Page fault (fallo de página)
- [ ] Proceso de manejo de fallo de página
- [ ] Reemplazo de páginas
- [ ] Política óptima (teórica, no implementable)
- [ ] LRU (Least Recently Used)
- [ ] FIFO (First-In, First-Out)
- [ ] Anomalía de Belady
- [ ] Algoritmo de Reloj (Clock)
- [ ] Asignación de marcos (fija, proporcional, por prioridad)
- [ ] Reemplazo local vs global
- [ ] Hiperpaginación (thrashing)
- [ ] Modelo del conjunto residente
- [ ] Tamaño de página y localidad
- [ ] TLB (Translation Look-aside Buffer)
- [ ] Tiempo de acceso efectivo
- [ ] Mini examen
- [ ] Corrección

**Estado:** ⬜ Pendiente

---

### 11. Sistemas de Archivos

**Complejidad:** 3/5

- [ ] Qué es un sistema de archivos
- [ ] Archivos, directorios, metadatos
- [ ] Permisos de archivos
- [ ] Rutas (absolutas y relativas)
- [ ] Operaciones básicas (crear, abrir, leer, escribir, cerrar, eliminar)
- [ ] Descriptor de archivo
- [ ] Funciones de directorio (`opendir`, `readdir`, `closedir`)
- [ ] Formateo de bajo nivel y alto nivel
- [ ] Estructura de particiones
- [ ] MBR (Master Boot Record)
- [ ] Sectores lógicos y direccionamiento CHS
- [ ] Mapas de bits (nodos-i y datos)
- [ ] Bloques y su tamaño
- [ ] Nodos-i (atributos, punteros directos, indirectos)
- [ ] Sistemas de archivos comunes:
  - [ ] FAT16 / FAT32
  - [ ] exFAT
  - [ ] NTFS
  - [ ] ext3 / ext4
  - [ ] ISO 9660 / UDF
- [ ] Arquitectura jerárquica del sistema de archivos
- [ ] Relación con C
- [ ] Mini examen
- [ ] Corrección

**Estado:** ⬜ Pendiente

---

### 📝 Examen de Fase 3

- [ ] Examen teórico
- [ ] Preguntas de razonamiento
- [ ] Ejercicios prácticos
- [ ] Corrección
- [ ] Registro de errores
- [ ] Repaso de temas débiles

**Estado:** ⬜ Pendiente

---

# FASE 4 — INTEGRACIÓN Y REPASO GENERAL

## Objetivo de la fase

Consolidar todos los conceptos y establecer relaciones entre ellos.

---

### 12. Relaciones entre temas

**Complejidad:** 3/5

- [ ] Cómo Von Neumann se relaciona con los SO modernos
- [ ] Cómo el ciclo de instrucción conecta con la planificación de CPU
- [ ] Cómo CISC/RISC influye en el diseño de SO
- [ ] Cómo la segmentación de CPU se relaciona con la gestión de memoria
- [ ] Cómo los procesos usan la memoria (paginación, segmentación)
- [ ] Cómo los hilos comparten recursos en memoria
- [ ] Cómo la memoria virtual permite multiprogramación eficiente
- [ ] Cómo los sistemas de archivos almacenan el estado de procesos

### 13. Mapa conceptual integrado

**Complejidad:** 3/5

- [ ] Crear mapa mental de Arquitectura de Computadores
- [ ] Crear mapa mental de Sistemas Operativos
- [ ] Conectar ambos mapas
- [ ] Identificar 10 relaciones clave entre temas

### 📝 Examen Integrador de Fase 4

- [ ] Preguntas que cruzan temas de todas las fases
- [ ] Casos prácticos
- [ ] Corrección
- [ ] Registro de errores

**Estado:** ⬜ Pendiente

---

# FASE 5 — PREPARACIÓN EXAMEN CODERBYTE

## Objetivo de la fase

Simular el examen final y reforzar áreas débiles.

---

### 14. Banco de preguntas por tema

**Complejidad:** 3/5

- [ ] Von Neumann (10 preguntas)
- [ ] Ciclo de Instrucción (10 preguntas)
- [ ] CISC vs RISC (10 preguntas)
- [ ] Pipelining (10 preguntas)
- [ ] Estructuras de SO (10 preguntas)
- [ ] Procesos (10 preguntas)
- [ ] Hilos (10 preguntas)
- [ ] Planificación de CPU (10 preguntas)
- [ ] Gestión de Memoria (10 preguntas)
- [ ] Memoria Virtual (10 preguntas)
- [ ] Sistemas de Archivos (10 preguntas)

### 15. Simulacros

**Complejidad:** 4/5

- [ ] Simulacro 1 — 30 preguntas mixtas (selección múltiple, V/F, conceptuales)
- [ ] Simulacro 2 — 30 preguntas con ejercicios de cálculo
- [ ] Simulacro 3 — 30 preguntas integrales (casos que cruzan temas)
- [ ] Simulacro 4 — Prueba final tipo Coderbyte

### 16. Repaso dirigido

**Complejidad:** 2/5

- [ ] Identificar temas con más errores
- [ ] Sesión de repaso por tema débil
- [ ] Repetir preguntas falladas
- [ ] Verificar dominio antes del examen

**Estado:** ⬜ Pendiente

---

# 📌 REGISTRO DE ERRORES

Usaremos esta sección para registrar conceptos que hayan causado dificultades.

| Fecha | Tema | Error | Corrección | Estado |
|---|---|---|---|---|
| 2026-08-13 | Von Neumann | Confusión entre Unidad de Control y ejecución directa | La Unidad de Control coordina; la ALU realiza operaciones | ✅ |
| 2026-08-13 | Ciclo de Instrucción | Confundir FETCH de instrucciones con obtención de datos | FETCH obtiene la instrucción; los operandos pueden requerir pasos adicionales | ✅ |
| 2026-08-13 | Ciclo de Instrucción | PC como "registro de instrucciones" | PC mantiene la dirección de la próxima instrucción | ✅ |
| 2026-08-13 | Flujo de ejecución | Pensar que `if`, `while` y `for` crean hilos | Estas estructuras controlan el flujo; no crean threads | ✅ |
| 2026-08-14 | CISC vs RISC | Confundir registros R1/R2/R3 con procesos | R1, R2 y R3 son registros de la CPU; un proceso es otro concepto | ✅ |
| 2026-08-14 | CISC vs RISC | Confundir ISA con una simple lista de instrucciones | La ISA define instrucciones, registros y reglas/interfaz de la arquitectura | ✅ |
| 2026-08-16 | Pipelining | Confundir resource hazard con data hazard | Resource hazard = misma etapa; Data hazard = resultado no listo | ✅ |
| 2026-08-18 | Pipelining | Confundir branch prediction con predicción de tiempo | Branch prediction predice si un salto será tomado o no para mantener el pipeline lleno | ✅ |
| 2026-08-18 | Ciclo de Instrucción | Confundir IR con PC | PC almacena dirección de próxima instrucción; IR almacena instrucción actual | ✅ |
| 2026-08-18 | Von Neumann | No reconocer que "programa almacenado" significa datos e instrucciones en la misma memoria | En Von Neumann, datos e instrucciones comparten la misma memoria principal | ✅ |
| 2026-08-18 | Estructuras SO | Confundir modo supervisor con el SO completo (Linux/Windows) | Modo supervisor es el modo donde ejecuta el kernel del SO, no el SO completo | ✅ |
| 2026-08-20 | Hilos | Confundir `-lthread` con `-lpthread` | El flag correcto es `-lpthread` (con "p" de POSIX threads) | ✅ |
| 2026-08-20 | Hilos | Pensar que race condition es el único riesgo de memoria compartida | Race condition es el más directo; deadlock y starvation son riesgos más generales | ✅ |
| 2026-08-20 | Hilos | Confundir void* con void (pensar que es porque no retorna nada) | void* es un puntero genérico que acepta cualquier tipo de dato, no solo "no retorna nada" | ✅ |
| 2026-08-21 | Transiciones de estados | Pensar que el scheduler decide el paso a Bloqueado | Lo decide el propio proceso al hacer la llamada al sistema | ✅ |
| 2026-08-21 | Overhead del scheduler | Juzgar el costo por valor absoluto (ms) | Importa la proporción decisión/ráfaga, no los ms absolutos | ✅ |
| 2026-08-21 | Cálculo de tiempos | Calcular sin construir primero la línea de tiempo | Dibujar siempre quién corre y cuándo antes de aplicar fórmulas | ✅ |
| 2026-08-25 | FCFS | Calcular waiting time incorrectamente (12.75 en vez de 5.75) | Construir la línea de tiempo y restar llegada de inicio de ejecución | ✅ |
| 2026-08-25 | SPN | No considerar que procesos llegan en distintos momentos | Verificar disponibilidad antes de ordenar por ráfaga | ✅ |
| 2026-08-25 | Round Robin | Calcular turnaround sin trazar línea de tiempo paso a paso | Siempre dibujar la cola y los tiempos antes de calcular | ✅ |
| 2026-08-25 | V/F | Pensar que FCFS minimiza waiting time | SPN minimiza waiting; FCFS produce efecto convoy | ✅ |
| 2026-08-25 | V/F | Pensar que Round Robin nunca produce starvation | Puede ocurrir si quantum es muy pequeño y siempre llegan procesos nuevos | ✅ |
| 2026-08-28 | Gestión de Memoria | Aritmética con ceros: 500+25000=2500 (era 25500); 40−12=38 (era 28); 30000+1500=32000 (era 31500) | Verificar siempre sumas/restas como paso final; 3 errores del mismo tipo en una sesión | 🔁 |
| 2026-08-28 | Gestión de Memoria | Confundir mejor ajuste con primer ajuste | Mejor ajuste = hueco más pequeño que quepa (menor sobrante), no el primero | ✅ |
| 2026-08-28 | Gestión de Memoria | Siguiente ajuste: llegar a D saltando el hueco C | La búsqueda continúa en orden circular desde la última posición | ✅ |

---

# 🧠 Conceptos que debo poder explicar

Antes del examen final debería poder explicar con mis propias palabras:

### Fase 1
- [x] Qué es Von Neumann
- [x] Qué hace la CPU, ALU y Unidad de Control
- [x] Qué almacena la memoria
- [x] Qué es un sistema de buses
- [x] Qué es el cuello de botella de Von Neumann
- [x] Qué diferencia hay entre Von Neumann y Harvard
- [x] Qué es Fetch, Decode y Execute
- [x] Qué es el PC y el IR
- [x] Qué es un registro
- [x] Qué son los ciclos indirecto e de interrupción
- [x] Qué diferencia hay entre CISC y RISC
- [x] Qué es Little Endian vs Big Endian
- [x] Qué es Pipelining y cómo mejora el throughput
- [x] Qué es branch prediction

### Fase 2
- [x] Qué es un sistema operativo y sus funciones
- [x] Qué diferencia hay entre monoprogramación y multiprogramación
- [x] Qué es el DMA
- [x] Qué es la jerarquía de memoria
- [x] Qué son las llamadas al sistema
- [x] Qué es un proceso
- [x] Qué es un PCB
- [x] Qué es `fork()` y cómo crea procesos
- [x] Qué es un cambio de contexto
- [x] Qué es IPC
- [x] Qué es un hilo
- [x] Qué diferencia hay entre proceso e hilo
- [x] Qué son hilos a nivel usuario vs kernel
- [x] Qué hace el scheduler
- [x] Qué son FCFS, Round Robin, SPN

### Fase 3
- [x] Qué es la gestión de memoria
- [ ] Qué es la paginación
- [ ] Qué es una tabla de páginas
- [ ] Qué es la segmentación
- [ ] Qué es la memoria virtual
- [ ] Qué es un page fault
- [ ] Qué es el reemplazo de páginas (LRU, FIFO, Clock)
- [ ] Qué es el thrashing
- [ ] Qué es el TLB
- [ ] Qué es un sistema de archivos
- [ ] Qué es un nodo-i
- [ ] Qué son los mapas de bits

---

# 🔄 Control de versiones

Se recomienda utilizar Git para este archivo.

El archivo funciona como una **bitácora de aprendizaje**, por lo que Git permite conservar el historial de cambios y recuperar estados anteriores.

## Flujo recomendado

Después de cada sesión:

```bash
git status
git add RUTA_ARQ_SO.md
git commit -m "checkpoint: completa tema X"
```

Ejemplos:

```bash
git commit -m "checkpoint: completa Von Neumann"
git commit -m "checkpoint: completa ciclo de instruccion"
git commit -m "checkpoint: completa CISC vs RISC"
```

---

# 📝 CHECKPOINTS REALIZADOS

## Checkpoint Fase 1 — Módulo 1 (Von Neumann)

Estado: ✅ Realizado

## Checkpoint Fase 1 — Módulo 2 (Ciclo de Instrucción)

Estado: ✅ Realizado

## Checkpoint Fase 1 — Módulo 3 (CISC vs RISC)

Estado: ✅ Realizado

## Checkpoint Fase 1 — Módulo 4 (Pipelining)

Estado: ✅ Realizado

## Checkpoint Fase 1 — Examen de Fase

Estado: ✅ Realizado (73%)

## Checkpoint Fase 2 — Módulo 5 (Estructuras de SO)

Estado: ✅ Realizado (94%)

## Checkpoint Fase 2 — Módulo 6 (Procesos)

Estado: ✅ Realizado (100%)

## Checkpoint Fase 2 — Módulo 7 (Hilos)

Estado: ✅ Realizado (100%)

---

# 📈 REGISTRO DE SESIONES

## Sesión 1 — Arquitectura de Computadores (Inicio)

- Arquitectura de Von Neumann: CPU, ALU, Unidad de Control, memoria, buses.
- Ciclo de Instrucción: Fetch, Decode, Execute, PC, IR, registros.
- CISC vs RISC: ISA, x86 vs ARM, convergencia.
- Pipelining: concepto básico, etapas, solapamiento.
- Errores registrados: 6 (ver tabla de errores).

Estado: 🟢 Fase 1 / Módulo 4 en progreso.

## Sesión 2

- Pipelining: Throughput vs latencia, ventajas y limitaciones.
- Conceptos cubiertos: throughput, latencia, resource hazards, data hazards, control hazards, branch prediction.
- Mini examen: 4/6 correctas (pendiente: data hazard y explicación de throughput/latencia).
- Error registrado: confundir resource hazard con data hazard.
- Próxima sesión: completar mini examen y corrección.

Estado: 🟢 Fase 1 / Módulo 4 casi completado (7/9 subtemas).

## Sesión 3

- Repaso rápido de Pipelining: etapas, throughput, hazards.
- Mini examen completado: 5/6 correctas (83%).
- Error registrado: confundir branch prediction con predicción de tiempo.
- Módulo 4 completado.
- Próximo paso: Examen de Fase 1.

Estado: 🟢 Fase 1 / Módulo 4 completado — pendiente Examen de Fase.

## Sesión 4

- Examen de Fase 1 completado: 73% (9.5/13)
- Errores registrados: confundir IR con PC, concepto de programa almacenado
- Fase 1 oficialmente completada
- Inicio de Fase 2: Introducción a Sistemas Operativos

Estado: ✅ Fase 1 completada — Iniciando Fase 2.

## Sesión 5

- Fase 2 iniciada: Introducción a Sistemas Operativos
- Módulo 5 completado: Estructuras de SO (94% en mini examen)
- Conceptos cubiertos: SO, roles, funciones, multiprogramación, DMA, jerarquía de memoria, caching, modos, system calls, parámetros, protección de memoria
- Error registrado: confundir modo supervisor con SO completo
- Próximo paso: Módulo 6 — Procesos

Estado: 🟢 Fase 2 / Módulo 5 completado.

## Sesión 6

- Módulo 6 completado: Procesos (100% en mini examen)
- Conceptos cubiertos: proceso, programa vs proceso, estados, PCB, fork(), padre-hijo, árbol de procesos, exec(), wait(), exit(), código de retorno, zombies/huérfanos, cambio de contexto, procesos cooperantes, IPC (señales, pipes, memoria compartida, semáforos, mensajes), relación con C
- Mini examen: 7/7 (100%)
- Errores registrados: ninguno nuevo
- Próximo paso: Módulo 7 — Hilos (Threads)

Estado: 🟢 Fase 2 / Módulo 6 completado.

## Sesión 7

- Módulo 7 completado: Hilos (100% en mini examen final)
- Conceptos cubiertos: qué es un hilo, proceso vs hilo, recursos compartidos/propios, stack exclusivo, concurrencia vs paralelismo, hilos a nivel usuario vs kernel, modelos multihilos (one-to-one en pthreads), ventajas, riesgos (race condition, deadlock, starvation), evolución de monoproceso a multicore
- Programación en C: pthread_create, pthread_join, pthread_exit, flag -lpthread
- Mini examen conceptual: 5.5/7 (79%) → Mini examen final: 8/8 (100%)
- Errores registrados: flag -lpthread (corregido), race condition (corregido)
- Próximo paso: Módulo 8 — Planificación de la CPU

Estado: 🟢 Fase 2 / Módulo 7 completado.

## Sesión 8

- Inicio del Módulo 8: Planificación de la CPU (primera mitad)
- Conceptos cubiertos: qué es planificar, transición Listo→Ejecución (dispatch), quién decide cada transición de estado, schedulers de largo/mediano/corto plazo, overhead y su proporción, ráfagas de CPU e I/O, CPU-bound vs I/O-bound, métricas turnaround y waiting time
- Ejercicios FCFS básicos de cálculo de tiempos resueltos (waiting, turnaround, instantes de inicio/fin)
- Mini examen parcial: conceptual 4/4 ✅; cálculos 3/3 tras corrección (error inicial: no construir línea de tiempo antes de calcular)
- Errores registrados: 3 nuevos (transición a Bloqueado, overhead proporcional, línea de tiempo)
- Próximo paso: Despachador (dispatcher) y cambio de contexto, luego algoritmo FCFS formal

Estado: 🟢 Fase 2 / Módulo 8 en progreso (primera mitad).

## Sesión 9

- Módulo 8 continuado: segunda mitad
- Conceptos cubiertos: despachador (dispatcher) y cambio de contexto, 5 métricas de planificación (utilización, throughput, turnaround, waiting, response), algoritmos no expropiativos (FCFS, HRRN), algoritmos expropiativos (Round Robin, SPN), MLFQ (colas de realimentación), planificación en tiempo real (hard/soft/firm), SMP y afinidad de procesador
- Mini examen completo del Módulo 8: 13/19 (68%)
- Errores registrados: cálculo FCFS incorrecto, SPN sin considerar llegadas escalonadas, Round Robin sin línea de tiempo, V/F sobre FCFS y starvation
- Próximo paso: Completar ejercicios de cálculo de tiempos y comparación de algoritmos, luego Examen de Fase 2

Estado: 🟢 Fase 2 / Módulo 8 casi completado (faltan ejercicios de cálculo y comparación).

## Sesión 10

- Inicio de la Fase 3: Módulo 9 — Gestión de Memoria (primera mitad)
- Conceptos cubiertos: por qué el SO administra memoria (protección y asignación), direcciones lógicas vs físicas, MMU, registro de relocalización (base/límite), momentos de asociación (compilación, carga, ejecución), carga dinámica, encadenamiento dinámico (estático vs dinámico), asignación contigua, fragmentación interna y externa, compactación, algoritmos de ubicación (primer, siguiente, mejor, peor ajuste)
- Ejercicios: traducción de direcciones lógica→física con base/límite, algoritmo de colocación con huecos
- Mini-checkpoint: 5/6 (83%) — error en suma 30000+1500
- Errores registrados: 3 (aritmética con ceros repetida ×3, mejor ajuste vs primer ajuste, siguiente ajuste saltando huecos)
- Próximo paso: Paginación (páginas, marcos, tabla de páginas, traducción)

Estado: 🟢 Fase 3 / Módulo 9 en progreso (primera mitad).

---

# 🔁 REPASOS

Registrar aquí conceptos que necesiten reforzarse.

- [ ] 
- [ ] 
- [ ] 

---

# 🐛 ERRORES IMPORTANTES APRENDIDOS

Registrar errores que hayan servido para entender conceptos.

### Von Neumann — Unidad de Control vs ALU

Error: Confundir la función de la Unidad de Control con la ejecución directa de operaciones.

Aprendizaje: La Unidad de Control **coordina** y **dirige**; la ALU **ejecuta** las operaciones aritméticas y lógicas.

### Ciclo de Instrucción — FETCH

Error: Pensar que FETCH obtiene tanto la instrucción como los datos.

Aprendizaje: FETCH solo obtiene la **instrucción** de la memoria. Los operandos pueden requerir pasos adicionales (cálculo de dirección y captura del operando).

### CISC vs RISC — Registros

Error: Confundir los registros de la CPU (R1, R2, R3) con procesos del sistema.

Aprendizaje: Los registros son ubicaciones de almacenamiento **dentro de la CPU**. Un proceso es una entidad que se ejecuta en el sistema operativo.

### CISC vs RISC — ISA

Error: Pensar que la ISA es simplemente una lista de instrucciones.

Aprendizaje: La ISA (Instruction Set Architecture) define **instrucciones, registros, modos de direccionamiento, manejo de memoria e interfaz** que la arquitectura ofrece al software.

### Pipelining — Data Hazard vs Resource Hazard

Error: Confundir "resource hazard" con "data hazard".

Aprendizaje:
- **Resource hazard:** Dos instrucciones necesitan la **misma etapa** del pipeline al mismo tiempo.
- **Data hazard:** Una instrucción necesita el **resultado de otra** que aún no está listo.

### Pipelining — Branch Prediction

Error: Confundir branch prediction con predicción de tiempo de ejecución.

Aprendizaje: **Branch prediction** es una técnica que intenta predecir si un salto condicional (`if`, `for`, `while`) será tomado o no, para mantener el pipeline lleno y evitar ciclos vacíos.

### Ciclo de Instrucción — PC vs IR

Error: Confundir el PC (Program Counter) con el IR (Instruction Register).

Aprendizaje:
- **PC**: almacena la **dirección** de la próxima instrucción a ejecutar.
- **IR**: almacena la **instrucción** actual que se está decodificando/ejecutando.

### Von Neumann — Programa Almacenado

Error: No reconocer que "programa almacenado" significa datos e instrucciones en la misma memoria.

Aprendizaje: En la arquitectura Von Neumann, **tanto los datos como las instrucciones se almacenan en la misma memoria principal** y comparten el mismo bus. Esta es una de sus características fundamentales.

### Estructuras de SO — Modo Supervisor

Error: Confundir el modo supervisor con el SO completo (Linux/Windows).

Aprendizaje: El **modo supervisor** es el nivel de ejecución donde corre el **kernel** del SO. Linux/Windows son sistemas operativos completos que incluyen el kernel, utilidades y interfaz. El modo supervisor es solo una forma de ejecución del procesador.

---

# 🎯 REGLAS DEL CURSO

1. Intentar resolver los retos antes de pedir la solución.
2. Los errores son parte del aprendizaje.
3. No avanzar automáticamente si un concepto fundamental no está claro.
4. Los checkpoints sirven para medir comprensión, no memoria.
5. Podemos hacer adelantos sin cambiar el orden oficial.
6. Cada fase debe terminar con al menos un examen de fase.
7. Explicar primero el "por qué" y después los detalles técnicos.
8. Comparar conceptos entre sí cuando ayude a entender.
9. Priorizar comprensión de los mecanismos internos del hardware y del SO.
10. Conectar cada tema con ejemplos reales de programación en C cuando sea posible.

---

# 🏁 META FINAL

Al terminar esta ruta, el objetivo es que puedas:

- Explicar la arquitectura Von Neumann y sus componentes.
- Describir el ciclo de instrucción completo.
- Comparar CISC y RISC con ejemplos reales.
- Explicar cómo funciona el Pipelining y sus limitaciones.
- Definir qué es un SO y sus funciones principales.
- Explicar qué son los procesos y cómo se crean (`fork`, `exec`, `wait`).
- Diferenciar procesos de hilos y programar hilos en C con POSIX.
- Comparar algoritmos de planificación de CPU con ejemplos prácticos.
- Explicar paginación, segmentación y memoria virtual.
- Describir cómo funcionan los sistemas de archivos a nivel bajo.
- Resolver preguntas de selección múltiple, verdadero/falso y ejercicios de cálculo.
- Estar preparado para el examen en Coderbyte.

---

# 📌 ESTADO ACTUAL

**Fase:** 3 — Conceptos Avanzados de Sistemas Operativos
**Módulo:** 9 — Gestión de Memoria (🟢 En progreso — primera mitad completada)
**Próximo tema:** Paginación (páginas, marcos, tabla de páginas)
**Próximo reto:** Segunda mitad del Módulo 9 (paginación + segmentación + swapping) y mini examen del módulo

**Último concepto dominado:** Direcciones lógicas/físicas, MMU, registro base/límite, binding (compilación/carga/ejecución), carga y encadenamiento dinámico, fragmentación interna/externa, compactación, 4 algoritmos de ubicación.

**Último avance:** Fase 3 iniciada — primera mitad del Módulo 9 completada (mini-checkpoint 5/6). Pendiente de retomar: ejercicios de cálculo del Módulo 8 y Examen de Fase 2.

