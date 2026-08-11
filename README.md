# Arquitectura de Computadoras

Repositorio de apoyo para la materia **Arquitectura de Computadoras**, correspondiente al programa educativo de **Ingeniería en Sistemas Computacionales**.

La asignatura pertenece al **Departamento Académico de Sistemas Electrónicos** y al área académica de **Hardware**. De acuerdo con el programa de materia actualizado en julio de 2026, corresponde al **3.er semestre**, una carga de **3 horas teóricas / 2 horas prácticas por semana** y **8 créditos**. La asignatura es obligatoria y se imparte en modalidad presencial.

> **Nota:** Este repositorio complementa el trabajo realizado durante el curso. El material puede incluir notas, presentaciones, ejercicios, programas, simulaciones, prácticas y proyectos relacionados con arquitectura de computadoras, microcontroladores y programación MIPS.

## 🎯 Propósito de la materia

La asignatura es un curso **teórico-práctico** orientado al estudio de las arquitecturas de computadoras **CISC y RISC**, mediante el análisis de un procesador, sus componentes y la interacción con memoria y periféricos.

El curso contempla la programación de una microcomputadora basada en un **procesador RISC de 8 bits**, así como el estudio del conjunto de instrucciones y el modelo de programación del procesador **MIPS**.

Al finalizar el curso, el estudiante aplicará los principios de operación de una unidad central de procesamiento, sus componentes y su interconexión con memoria y sistemas periféricos para resolver problemas de cómputo, utilizando creatividad, análisis y criterios de calidad.

## 🎓 Objetivos del curso

1. Conocer los elementos básicos del procesador.
2. Identificar los componentes de un procesador.
3. Estudiar las arquitecturas de un procesador.
4. Programar y simular un microcontrolador de 8 bits.
5. Programar y simular al procesador MIPS.

## 📚 Contenido del curso

### Unidad I — Arquitectura de la CPU

**11 horas aproximadas**

- Introducción.
- Lenguajes y compiladores.
- Representación de instrucciones en la computadora.
- Concepto y elementos básicos de un procesador.
- Memorias, tipos y funcionamiento de sus buses.
- Concepto y tipos de bus.
- Sistema mínimo.
- Periféricos internos y externos.
- Arquitecturas Von Neumann y Harvard.
- Arquitecturas CISC y RISC.
- Concepto de microcontrolador.

**Objetivos:** explicar los conceptos de procesador, lenguaje, hardware, software, compilador y computadora; identificar arquitecturas; reconocer los elementos principales del microprocesador; distinguir microcontrolador y computadora; y comprender memorias, conexiones y arquitecturas computacionales.

### Unidad II — Arquitectura del microcontrolador

**12 horas aproximadas**

- Introducción.
- Características generales del microcontrolador.
- Puertos y pines de función especial.
- Circuito mínimo.
- Organización de la memoria.
- Registros de función especial y banderas.
- Entorno y herramientas de programación.
- Estructura de programa y vector de interrupciones.
- Conjunto de instrucciones.
- Modos de direccionamiento.
- Ejemplos.

La unidad desarrolla la introducción a la ejecución de programas en lenguaje de máquina, los modos de direccionamiento, los tipos de instrucciones y la realización de programas para el microcontrolador.

### Unidad III — Hardware del microcontrolador

**15 horas aproximadas**

- Descripción de hardware.
- Puertos de entrada-salida.
- Interrupciones externas.
- Temporizadores/Contadores.
- Interfaces serie.
- Reinicialización (*Reset*).
- Expansión de memorias y periféricos externos.
- Ejemplos.

El objetivo es comprender la conexión de periféricos y utilizar los distintos periféricos del microcontrolador para una aplicación real.

### Unidad IV — Conjunto de instrucciones y programación del procesador MIPS

**10 horas aproximadas**

- Introducción al procesador MIPS.
- Conjunto de instrucciones del procesador MIPS.
- Representación de instrucciones.
- Instrucciones aritméticas y lógicas.
- Toma de decisiones.
- Procedimientos.
- Datos inmediatos y direccionamiento.
- Arreglos y punteros.
- Simulación de programas.

La unidad busca comprender la arquitectura MIPS, conocer el conjunto de instrucciones del **MIPS R2000**, representar instrucciones, realizar programas y simular/verificar su funcionamiento.

## 🧪 Enfoque práctico

La materia combina exposición de conceptos, resolución de ejercicios, programación y simulación.

Entre las actividades contempladas se encuentran:

- Análisis de arquitecturas de procesadores.
- Estudio de componentes internos de una CPU.
- Trabajo con memorias y buses.
- Programación de microcontroladores RISC de 8 bits.
- Uso de puertos de entrada/salida.
- Manejo de interrupciones.
- Uso de temporizadores/contadores.
- Interfaces serie.
- Conexión y utilización de periféricos.
- Expansión de memoria y periféricos.
- Programación de MIPS.
- Representación y análisis de instrucciones.
- Simulación y verificación de programas.

## 🛠️ Herramientas y recursos

### Recursos tradicionales

- Pizarrón.
- Material de apoyo.
- Notas de la materia.
- Hojas técnicas de datos.
- Instrumentación electrónica.

### Recursos tecnológicos

- Proyector.
- Computadora.
- Plataforma Moodle.
- Compiladores de procesadores.
- Simuladores de procesadores AVR y MIPS.

## 📂 Organización del repositorio

```text
.
├── README.md
├── unidad-01-arquitectura-cpu/
│   ├── notas/
│   ├── presentaciones/
│   ├── ejercicios/
│   └── simulaciones/
├── unidad-02-arquitectura-microcontrolador/
│   ├── notas/
│   ├── presentaciones/
│   ├── ejercicios/
│   ├── codigo/
│   └── simulaciones/
├── unidad-03-hardware-microcontrolador/
│   ├── notas/
│   ├── presentaciones/
│   ├── ejercicios/
│   ├── codigo/
│   └── practicas/
├── unidad-04-mips/
│   ├── notas/
│   ├── presentaciones/
│   ├── ejercicios/
│   ├── codigo/
│   └── simulaciones/
├── practicas/
├── proyecto-final/
└── referencias/
```


## 📊 Evaluación

| Componente | Porcentaje |
|---|---:|
| 1.er parcial teórico-práctico | 15 % |
| 2.º parcial teórico-práctico | 20 % |
| 3.er parcial teórico-práctico | 20 % |
| Proyecto final práctico | 25 % |
| **Total** | **100 %** |

Los parciales consideran examen, tareas, exposiciones, investigaciones, prácticas, ejercicios y prácticas. El programa establece al menos **2 actividades por parcial** para tareas, exposiciones e investigaciones teóricas.

El proyecto final se califica tanto en equipo como de manera individual.

## 📝 Reportes de investigación

El formato es IEEE contemplando las secciones:

1. Abstract
2. Introducción.
3. Metodología
4. Código y Resultados.
5. Conclusiones.
6. Referencias.
7. Anexos:
  Prompts de referencia de uso de IA generativa.

## 🔧 Proyecto final

El curso contempla un **proyecto final práctico**, evaluado mediante:

- Proyecto.
- Reporte.

Las características específicas deberán seguir las indicaciones establecidas durante el curso.

## 📖 Bibliografía básica

1. Patterson, D., Hennesy J., *Computer Organization and Design*, Morgan Kaufman
2. T. R. McCalla, *Lógica digital y diseño de computadoras*, Noriega Megabyte.
3. M. Morris Mano, *Arquitectura de computadoras*, Prentice Hall Hispanoamericana, 1983.
4. Patterson & Hennessy, *Organización y arquitectura de computadores*, 4.ª edición, Morgan Kaufmann, EUA, 2012.
5. William Stallings, *Organización y Arquitectura de Computadoras*, 5.ª edición, Prentice Hall, 2000.
6. Muhammad Ali Mazidi, *The AVR Microcontroller and Embedded Systems*, Pearson, 2011.
7. C. Kühnell, *AVR RISC Microcontroller Handbook*, Newnes, 1998.

### Bibliografía complementaria

7. *MIPS Architecture for Programmers: The MIPS32 Instruction Set*, Document MD00086, MIPS Technologies, 2013.
8. Hojas de datos del microcontrolador **ATmega8515**.
9. Richard H. Barnett, *Embedded C Programming and the Atmel AVR*, Thompson, 2007.

## 🔗 Relación con otras materias

La asignatura tiene como antecedente **Circuitos Lógicos**.

Posteriormente sirve como antecedente o fundamento para:

- Lenguaje Ensamblador.
- Circuitos Eléctricos.
- Plataformas Embebidas.
- Instrumentación Electrónica.

## 📌 Uso del repositorio

Este repositorio está destinado al apoyo académico de la materia.

Se recomienda utilizar los materiales junto con las actividades desarrolladas durante las sesiones de clase y consultar el `README.md` de cada unidad o práctica antes de ejecutar programas o simulaciones.

Cuando una práctica incluya código, simulaciones o hardware específico, se recomienda documentar:

- Objetivo.
- Arquitectura utilizada.
- Componentes necesarios.
- Herramientas de software.
- Procedimiento.
- Código fuente.
- Resultados.
- Conclusiones.

## 📋 Datos de la asignatura

| Dato | Información |
|---|---|
| Materia | Arquitectura de Computadoras |
| Programa educativo | Ingeniería en Sistemas Computacionales |
| Semestre | 3.º |
| Plan de estudios | 2023 |
| Área académica | Hardware |
| Departamento | Sistemas Electrónicos |
| Horas semanales | 3 T / 2 P |
| Créditos | 8 |
| Modalidad | Presencial |
| Naturaleza | Obligatoria |
| Periodo | Agosto–Diciembre |
| Actualización del programa | Julio de 2026 |

## 📜 Referencia del programa

Los contenidos y la estructura general de este repositorio se basan en el:

**Programa de Materia — Arquitectura de Computadoras**  
**Semestre:** 3.º  
**Actualización:** julio de 2026

El programa corresponde al **Centro Académico de Ciencias Básicas**, **Departamento Académico de Sistemas Electrónicos**, **Programa Educativo de Ingeniería en Sistemas Computacionales**.

---

> **Aviso académico:** Este repositorio tiene fines educativos y sirve como material de apoyo para la asignatura. Para criterios administrativos, de evaluación, asistencia o acreditación, deberá consultarse el programa de materia vigente y las indicaciones establecidas durante el curso.
