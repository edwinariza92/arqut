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
| 1 | Arquitectura de Computadores | 🟢 En progreso |
| 2 | Introducción a Sistemas Operativos | ⬜ Pendiente |
| 3 | Conceptos Avanzados de Sistemas Operativos | ⬜ Pendiente |
| 4 | Integración y Repaso General | ⬜ Pendiente |
| 5 | Preparación Examen Coderbyte | ⬜ Pendiente |

**Progreso orientativo:** Fase 1 — ~70%

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
- [ ] Mini examen
- [ ] Corrección

**Estado:** 🟢 En progreso (7 de 9 subtemas completados)

---

### 📝 Examen de Fase 1

- [ ] Examen teórico
- [ ] Preguntas de razonamiento
- [ ] Preguntas de aplicación
- [ ] Corrección
- [ ] Registro de errores
- [ ] Repaso de temas débiles

**Estado:** ⬜ Pendiente

---

# FASE 2 — INTRODUCCIÓN A SISTEMAS OPERATIVOS

## Objetivo de la fase

Comprender qué hace un sistema operativo y cómo administra los recursos del computador.

---

### 5. Estructuras de Sistemas Operativos

**Complejidad:** 2/5

- [ ] Qué es un sistema operativo
- [ ] Funciones principales (CPU, memoria, E/S)
- [ ] Roles del SO: administrador de recursos y máquina ampliada
- [ ] Monoprogramación vs multiprogramación
- [ ] Aprovechamiento de la CPU
- [ ] DMA (Acceso Directo a Memoria)
- [ ] Jerarquía de memoria (registros, caché, RAM, SSD, disco, nube)
- [ ] Caching
- [ ] Modo usuario vs modo supervisor
- [ ] Llamadas al sistema (system calls)
- [ ] Paso de parámetros (registros, tablas en memoria, stack)
- [ ] Protección de memoria (registro base y límite)
- [ ] Mini examen
- [ ] Corrección

**Estado:** ⬜ Pendiente

---

### 6. Procesos

**Complejidad:** 3/5

- [ ] Qué es un proceso
- [ ] Programa vs proceso
- [ ] Estado de un proceso (nuevo, listo, ejecución, bloqueado, terminado)
- [ ] PCB (Bloque de Control de Proceso)
- [ ] Creación de procesos (`fork()`)
- [ ] Relación padre-hijo
- [ ] Árbol de procesos
- [ ] Ejecución de nuevos programas (`exec`)
- [ ] Sincronización con `wait()`
- [ ] Terminación con `exit()`
- [ ] Terminación de procesos
- [ ] Procesos concurrentes
- [ ] Contexto de un proceso y cambio de contexto
- [ ] Procesos cooperantes
- [ ] Comunicación entre Procesos (IPC): señales, memoria compartida, semáforos, mensajes
- [ ] Relación con programas en C
- [ ] Mini examen
- [ ] Corrección

**Estado:** ⬜ Pendiente

---

### 7. Hilos (Threads)

**Complejidad:** 3/5

- [ ] Qué es un hilo
- [ ] Proceso vs hilo
- [ ] Recursos compartidos (código, datos, archivos)
- [ ] Stack propio de cada hilo
- [ ] Hilos dentro de un proceso
- [ ] Concurrencia vs paralelismo
- [ ] Hilos a nivel usuario vs nivel kernel
- [ ] Modelos multihilos (muchos a uno, uno a uno, muchos a muchos)
- [ ] Ventajas de los hilos
- [ ] Riesgos básicos
- [ ] Programación de hilos en C (POSIX: `pthread_create`, `pthread_join`, `pthread_exit`)
- [ ] Compilación con `-lpthread`
- [ ] Evolución: de monoproceso a multicore
- [ ] Mini examen
- [ ] Corrección

**Estado:** ⬜ Pendiente

---

### 8. Planificación de la CPU

**Complejidad:** 4/5

- [ ] Qué es planificación
- [ ] Scheduler (planificador)
- [ ] Planificador largo plazo, corto plazo y mediano plazo
- [ ] Objetivos de planificación (utilización, throughput, tiempo de retorno, tiempo de espera)
- [ ] Ráfagas de CPU e I/O
- [ ] Cambio de contexto y despachador (dispatcher)
- [ ] Algoritmos no expropiativos:
  - [ ] FCFS (First-Come, First-Served)
  - [ ] HRRN (Highest Response Ratio Next)
- [ ] Algoritmos expropiativos:
  - [ ] Round Robin (quantum)
  - [ ] SPN (Shortest Process Next)
  - [ ] Colas de realimentación (Multilevel Feedback Queue)
- [ ] Tiempo de espera, tiempo de respuesta, turnaround time
- [ ] Ejercicios de cálculo de tiempos
- [ ] Comparación de algoritmos
- [ ] Planificación en tiempo real
- [ ] Planificación SMP (Symmetric Multiprocessing)
- [ ] Afinidad de procesador
- [ ] Mini examen
- [ ] Corrección

**Estado:** ⬜ Pendiente

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

- [ ] Por qué el SO administra memoria
- [ ] Memoria física y direcciones de memoria
- [ ] Traducción de direcciones lógicas a físicas
- [ ] MMU (Unidad de Manejo de Memoria)
- [ ] Registro de relocalización
- [ ] Momentos de asociación de direcciones (compilación, carga, ejecución)
- [ ] Carga dinámica y encadenamiento dinámico
- [ ] Asignación contigua
- [ ] Registros base y límite
- [ ] Fragmentación interna y externa
- [ ] Algoritmos de ubicación (primer ajuste, mejor ajuste, siguiente ajuste, peor ajuste)
- [ ] Compactación
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

**Estado:** ⬜ Pendiente

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

---

# 🧠 Conceptos que debo poder explicar

Antes del examen final debería poder explicar con mis propias palabras:

### Fase 1
- [ ] Qué es Von Neumann
- [ ] Qué hace la CPU, ALU y Unidad de Control
- [ ] Qué almacena la memoria
- [ ] Qué es un sistema de buses
- [ ] Qué es el cuello de botella de Von Neumann
- [ ] Qué diferencia hay entre Von Neumann y Harvard
- [ ] Qué es Fetch, Decode y Execute
- [ ] Qué es el PC y el IR
- [ ] Qué es un registro
- [ ] Qué son los ciclos indirecto e de interrupción
- [ ] Qué diferencia hay entre CISC y RISC
- [ ] Qué es Little Endian vs Big Endian
- [x] Qué es Pipelining y cómo mejora el throughput

### Fase 2
- [ ] Qué es un sistema operativo y sus funciones
- [ ] Qué diferencia hay entre monoprogramación y multiprogramación
- [ ] Qué es el DMA
- [ ] Qué es la jerarquía de memoria
- [ ] Qué son las llamadas al sistema
- [ ] Qué es un proceso
- [ ] Qué es un PCB
- [ ] Qué es `fork()` y cómo crea procesos
- [ ] Qué es un cambio de contexto
- [ ] Qué es IPC
- [ ] Qué es un hilo
- [ ] Qué diferencia hay entre proceso e hilo
- [ ] Qué son hilos a nivel usuario vs kernel
- [ ] Qué hace el scheduler
- [ ] Qué son FCFS, Round Robin, SPN

### Fase 3
- [ ] Qué es la gestión de memoria
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

Estado: 🟡 En progreso (pendiente completar mini examen)

## Checkpoint Fase 1 — Examen de Fase

Estado: ⬜ Pendiente

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

**Fase:** 1 — Arquitectura de Computadores
**Módulo:** 4 — Segmentación (Pipelining)
**Próximo tema:** Completar mini examen de Pipelining (pendiente preguntas 3 y 6)
**Próximo reto:** Corrección del mini examen

**Último concepto dominado:** Ventajas y limitaciones del pipeline (hazards, dependencias de datos, branch prediction).

**Último avance:** Pipelining: concepto, etapas, solapamiento, ejemplo, throughput vs latencia, ventajas y limitaciones (7 de 9 subtemas).

