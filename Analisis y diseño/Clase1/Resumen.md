# Resumen Ejecutivo: Análisis y Diseño de Software

## 1. ¿Por qué importan el Análisis y el Diseño?
**El problema de la industria:** El **66% de los proyectos de software fracasan** o se entregan con graves problemas (según el Standish Group). La causa principal *no es la mala programación*, sino los requerimientos mal definidos.
**Diferencia Fundamental:**
  **Análisis:** Define el 
  **QUÉ** se va a construir. Se enfoca en entender el problema, los usuarios, la información y las restricciones.
  
  **Diseño:** Define el **CÓMO** se va a construir. Se encarga de planear la solución, la arquitectura, los componentes y las tecnologías.
**La Regla del 1-10-100:** Corregir un error en la fase de análisis cuesta $1, en diseño cuesta $10, en programación $100 y en producción $1000+. *Pensar antes de actuar ahorra dinero y evita catástrofes.*

---

## 2. El Ciclo de Vida del Software
El desarrollo de software sigue un proceso cíclico compuesto por 6 fases principales:

1. **Análisis de Requerimientos:** Se entrevista a los usuarios para entender sus necesidades. Produce el documento de *Especificación de Requerimientos*.
2. **Diseño:** Se decide la arquitectura, bases de datos y la interfaz del sistema (creación de planos y prototipos).
3. **Implementación:** Los programadores escriben el código real basados en los planos del diseño.
4. **Pruebas:** Se verifica que el sistema funcione correctamente y no tenga vulnerabilidades o errores.
5. **Despliegue:** Se entrega el software al cliente y se pone en funcionamiento en un entorno real.
6. **Mantenimiento:** Fase constante donde se corrigen errores del día a día y se agregan nuevas mejoras.

---

## 3. Metodologías Estructuradas (Tradicionales)
**Filosofía:** Planificar absolutamente todo desde el principio y seguir el plan de manera rigurosa.
**Modelos Principales:**
**Modelo Cascada (Waterfall):** Lineal y rígido. Cada fase debe terminar por completo antes de que empiece la siguiente; no permite volver atrás fácilmente.
**Modelo en V:** Variante de la cascada donde cada fase de desarrollo tiene una fase de pruebas directamente emparejada.
**Modelo Espiral:** Enfoque cíclico enfocado en el análisis paso a paso y la reducción constante de riesgos.
**¿Cuándo usarlas?:** En sistemas críticos donde el fallo no es una opción (aviones, medicina, banca) o cuando los requerimientos son fijos e inmutables.

---

## 4. Metodologías Ágiles
**Filosofía:** Priorizar la adaptabilidad frente al cambio, el software funcional y la colaboración con el cliente por encima de los procesos y la documentación excesiva. El ciclo de vida se repite en bloques cortos llamados **iteraciones**.
**Marcos de Trabajo:**
  **Scrum:** Divide el trabajo en ciclos de 1 a 4 semanas (*Sprints*). Define roles clave como el *Product Owner* (define el qué), *Scrum Master* (elimina obstáculos) y el *Equipo de Desarrollo*.
**Kanban:** Gestión visual mediante un tablero de columnas (Por hacer -> Haciendo -> Probando -> Hecho) enfocado en limitar el trabajo en curso (*WIP*) para evitar atascos.
**XP (Extreme Programming):** Enfocado en la excelencia técnica. Promueve la programación en parejas, el desarrollo guiado por pruebas (*TDD*) y la refactorización continua.

---

## 5. Gestión de Requerimientos
Un requerimiento es la traducción de las necesidades del cliente al lenguaje técnico. Se dividen en:
**Requerimientos Funcionales:** Definen las acciones y servicios específicos que el sistema debe hacer (ej. *"El sistema debe permitir que el alumno consulte sus notas"*).
**Requerimientos No Funcionales:** Definen los atributos de calidad, rendimiento o restricciones bajo las cuales opera el sistema (ej. *"El sistema debe responder en menos de 2 segundos"* o *"Los datos deben estar encriptados"*).