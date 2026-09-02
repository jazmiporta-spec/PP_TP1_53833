# PP_TP1_53833
Trabajo práctico 1 de Programación Orientada a Objetos en Java (POO) - Implementación de clases, herencia, polimorfismo y diagrama de memoria.

Este repositorio contiene la solución del Trabajo Práctico N° 1. El objetivo del sistema es gestionar *Eventos Universitarios*, administrando la asignación de salas, la creación de actividades (que pueden ser charlas y talleres) y la inscripción de estudiantes a estas.

Conceptos de POO Aplicados:
- Encapsulamiento: control de acceso a datos mediante calificadores (`private`, `public`, `final`).
- Herencia y clases abstractas: la clase base `Actividad` define comportamientos genéricos compartidos por las subclases `Charla` y `Taller`.
- Polimorfismo: tratamiento unificado de diferentes tipos de actividades al calcular costos y mostrar identificaciones dinámicamente.
- Relaciones entre objetos:
  - Asociación / Inscripción: entre `Actividad`, `Inscripcion` y `Estudiante`[cite: 1].
  - Agregación: la clase `Sala` existe de forma independiente a `EventoUniversitario`[cite: 1].
  - Composición: las actividades forman parte de la vida útil del `EventoUniversitario`[cite: 1].
 
IMAGENES
- Salida de consola:
<img width="487" height="477" alt="image" src="https://github.com/user-attachments/assets/e9080a31-f35e-46fe-aa39-7327c6eddf17" />

- Diagrama de memoria Heap & Stack:
<img width="1196" height="841" alt="Tp1 pto4 drawio" src="https://github.com/user-attachments/assets/a787dc6b-5e68-4ba9-a421-afcd1523c4fb" />
