# 🚗 S.G.A. – Sistema de Gestión Automotriz (Plataforma de Intermediación)

> **Proyecto Académico:** Plataforma digital tipo Marketplace orientada a la intermediación, transparencia y seguimiento de servicios mecánicos automotrices.

---

## 📖 INTRODUCCIÓN

En el escenario tecnológico actual, la contratación de servicios de reparación y mantenimiento automotriz presenta un desafío crítico: la falta de confianza y la asimetría informativa entre el prestador del servicio y el cliente. Tradicionalmente, los usuarios se enfrentan a un mercado fragmentado donde la elección de un profesional se basa en recomendaciones verbales, careciendo de parámetros objetivos de calidad o reseñas medibles. 

Por otro lado, los mecánicos independientes y pequeños talleres carecen de herramientas digitales centralizadas para captar nuevos clientes, gestionar su demanda, enviar presupuestos vinculantes y documentar gráficamente su trabajo. Esta desconexión genera un ecosistema opaco, donde el cliente desconoce el estado real de su reparación y el mecánico sufre demoras en las aprobaciones o fricciones al momento del cobro.

El presente proyecto propone el desarrollo del S.G.A., una plataforma de intermediación (modelo Marketplace) orientada a conectar de manera directa a los propietarios de vehículos con una red de mecánicos en la ciudad de San Fernando del Valle de Catamarca. Mediante un sistema de catálogo con calificaciones, bitácora multimedia interactiva y flujos de aprobación de presupuestos, el software busca erradicar la informalidad, protegiendo tanto el poder de decisión del cliente como la integridad legal y financiera del profesional mecánico.

---

## ⚠️ DEFINICIÓN DEL PROBLEMA

El problema principal es la **asimetría de información y la falta de confianza** al momento de contratar servicios mecánicos, sumado a la informalidad en el seguimiento, presupuestación y métodos de pago.

### Causas
* Inexistencia de herramientas digitales para validar la reputación y especialidad de los mecánicos de forma objetiva (reseñas).
* Uso de canales informales (mensajes sueltos de WhatsApp) donde el cliente no tiene evidencia visual ni documentada del problema real del vehículo.
* Imposibilidad del usuario de rechazar o aceptar de forma auditable los arreglos adicionales que surgen durante el desarme.
* Desorganización en la agenda de los mecánicos, lo que provoca superposición de turnos o tiempos de espera prolongados.

### Consecuencias
* Desconfianza crónica de los usuarios por temor a sobreprecios, diagnósticos erróneos o reemplazos innecesarios.
* Pérdida de oportunidades comerciales para mecánicos capacitados que no tienen visibilidad digital.
* Conflictos legales o quejas cuando una pieza desgastada, que el cliente no quiso cambiar, termina fallando.
* Fricción al momento del cobro final debido a malentendidos en el presupuesto original.

---

## 📚 ANTECEDENTES

### Antecedentes Nacionales

#### 1. Sistema de gestión de talleres automovilísticos
* **Autor:** Francisco Sappia Badra y Juan Pablo Rojas
* **Objetivos:** Beneficiar tanto a los talleres mecánicos como a sus clientes, fortaleciendo el vínculo entre ambas partes y mejorando la experiencia global del servicio. Busca optimizar las operaciones internas del taller, gestionar eficientemente los turnos y los recursos, y mantener una comunicación transparente.
* **Metodología:** Investigación de campo aplicada al desarrollo de software (diagnóstico de la problemática, recopilación de información directa y diálogo con talleres). Diseño e implementación de la aplicación web interactiva TuneUp.
* **Resultados:** Desarrollo de un sistema funcional que permite a los clientes reservar turnos de manera fácil y rápida. Para los mecánicos, resultó ser una herramienta que evita demoras y agiliza la carga interna de diagnósticos técnicos.

#### 2. Aplicación de la realidad aumentada en la pedagogía de la educación primaria
* **Autor:** Universidad de San Andrés (Repositorio DSpace)
* **Objetivos:** Analizar el uso y el alcance de las nuevas tecnologías y herramientas digitales como un recurso que favorece y estimula los procesos de comprensión, aprendizaje e identificación en los usuarios.
* **Metodología:** Documental y bibliográfica. Análisis sistemático de diversas fuentes teóricas, datos históricos y utilidades prácticas.
* **Resultados:** Se evidenció la alta importancia y el impacto positivo que tiene la incorporación de interfaces interactivas y dinámicas para optimizar la asimilación de datos complejos, estimulando significativamente los resultados finales.

### Antecedentes Internacionales

#### 1. Diseño de un sistema de gestión para el control de procesos e inventarios ("Galarza Motores")
* **Autor:** Milton René Galarza Romero
* **Objetivos:** Diseñar un sistema integrado de gestión que permitiera controlar eficientemente los procesos internos de reparación y el manejo de inventario de repuestos. Eliminar la informalidad en las órdenes de trabajo para optimizar los tiempos de entrega.
* **Metodología:** Investigación descriptiva y de campo. Relevamiento de datos directo en el taller analizando tiempos muertos y fallas en el registro manual.
* **Resultados:** Diseño de un modelo de control que reduce significativamente los errores en presupuestos, evita desabastecimiento y ordena la agenda diaria, mejorando la productividad y la confianza.

#### 2. Rediseño del proceso de servicio de un taller mecánico automotriz
* **Autor:** Ignacio Andrés Alfaro Carrizo
* **Objetivos:** Rediseñar por completo el proceso de atención y reparación dentro de un taller mecánico automotriz para mejorar la calidad del servicio percibida por el usuario, disminuir los retrasos y generar un canal de comunicación transparente.
* **Metodología:** Enfoque de gestión por procesos. Se mapeó paso a paso el ciclo de vida del servicio identificando cuellos de botella informativos.
* **Resultados:** Se demostró cuantitativamente que al estandarizar el proceso y digitalizar la comunicación, los tiempos de espera disminuyeron, reflejando un aumento directo en la satisfacción de los clientes.

---

## 💡 JUSTIFICACIÓN

**1. ¿Cuál es el problema que se necesita resolver?**
Resulta imperativo resolver la brecha de confianza e ineficiencia operativa que existe entre conductores y profesionales del rubro. Al centralizar la oferta y la demanda en un solo sistema, se elimina la dependencia de canales informales. La plataforma instaura un marco de transparencia auditable, donde cada diagnóstico, evidencia multimedia y presupuesto queda registrado, evitando discrepancias en los costos y resguardando a ambas partes.

**2. ¿Cuál es el impacto que tiene el problema y la importancia?**
El impacto trasciende la incomodidad administrativa; afecta directamente la economía local. La postergación de mantenimientos por desconfianza deteriora el parque automotor. La importancia de esta solución radica en la modernización del rubro, introduciendo equidad competitiva para que los buenos profesionales destaquen por su mérito (calificaciones de usuarios) y brindando a los clientes previsibilidad financiera antes y durante la reparación.

**3. ¿Qué se va a realizar?**
Se desarrollará una plataforma integral que incluirá: un motor de búsqueda parametrizado por especialidad, un módulo para la carga asíncrona de solicitudes (diferenciando servicios genéricos de diagnósticos complejos), un sistema de "Bitácora Multimedia" para documentar el desarme, y flujos de aceptación o rechazo formal de arreglos extras con exención de responsabilidad legal para el mecánico.

**4. ¿Cuáles son los beneficios sociales?**
Fundamentado en marcos teóricos sobre la interacción digital, la interfaz visual clara cumple una función pedagógica. Socialmente, el sistema democratiza el acceso a servicios de calidad, disminuye drásticamente el estrés de la incertidumbre operativa y restituye la confianza mediante la evidencia fotográfica de cada pieza cambiada, fomentando el sentimiento de sentirse atendido y resguardado.

---

## 📍 UBICACIÓN Y POBLACIÓN OBJETIVO

* **Delimitación Espacial:** San Fernando del Valle de Catamarca.
* **Delimitación del Universo:** 
  1. **Usuarios Clientes (Demanda):** Propietarios de vehículos particulares que buscan transparencia, opciones seguras y validación de calidad a través de reseñas.
  2. **Usuarios Mecánicos (Oferta):** Profesionales independientes y dueños de talleres que buscan digitalizar su agenda, documentar su trabajo y captar nuevos clientes mediante su reputación online.

---

## 🎯 OBJETIVOS

### Objetivo General
Diseñar, desarrollar e implementar una plataforma digital transaccional (Marketplace) orientada a la intermediación de servicios mecánicos automotrices en San Fernando del Valle de Catamarca, con el propósito de conectar clientes con profesionales, centralizar la búsqueda mediante reseñas, y automatizar el seguimiento técnico mediante evidencia multimedia, garantizando un ecosistema de total transparencia.

### Objetivos Específicos
1. **Desarrollar un módulo de búsqueda y emparejamiento** que permita a los usuarios localizar mecánicos basándose en su especialidad, ubicación y un sistema de calificaciones por estrellas.
2. **Implementar un sistema de solicitudes y agenda** que permita a los clientes enviar evidencia preliminar, y a los mecánicos aceptar, diferir o rechazar el trabajo, asignando turnos de forma automatizada.
3. **Programar una bitácora multimedia bidireccional** donde el mecánico documente fotográficamente el avance, y el usuario pueda visualizar el estado de su vehículo en tiempo real.
4. **Desarrollar un flujo auditable de presupuestos variables**, que permita al mecánico sugerir arreglos extras durante la reparación, obligando al cliente a aceptarlos formalmente o rechazarlos asumiendo el riesgo (protección legal del profesional).
5. **Estructurar una base de datos relacional robusta** (PostgreSQL) que garantice la integridad de los historiales, reseñas, turnos y perfiles de los usuarios de la plataforma.

---

## 🏗️ MARCO TEÓRICO

### 1. Gestión de Procesos y Comunicación
* **1.1. Gestión por Procesos en Plataformas de Intermediación:** Identificación, modelado y automatización de los flujos de trabajo para maximizar la eficiencia entre distintas partes. La estandarización de hitos operativos mediante software erradica la improvisación en el ciclo de vida del servicio (desde la solicitud hasta la entrega), homogeneizando la experiencia sin importar qué mecánico preste el servicio.
* **1.2. Asimetría Informativa y Experiencia de Usuario:** La asimetría informativa ocurre cuando el prestador posee mayor conocimiento técnico que el cliente, generando desconfianza. La bitácora digital interactiva actúa como un puente pedagógico que neutraliza esta asimetría, transparentando el estado del vehículo y desglosando los costos de repuestos.

### 2. Arquitectura de Software y Tecnologías
* **2.1. Interfaces Dinámicas e Interactivas en Tiempo Real:** Se utiliza JavaScript debido a su naturaleza asíncrona y capacidad para gestionar eventos en el navegador, garantizando que las modificaciones de datos (como la carga de fotos o el cambio de estado en la reparación) se reflejen fluidamente en el panel del cliente.
* **2.2. Sistemas de Gestión de Bases de Datos Relacionales:** Se optó por PostgreSQL (administrado mediante pgAdmin) por ser un motor robusto y escalable, capaz de soportar transacciones complejas, garantizando la integridad referencial para vincular correctamente a los clientes, los mecánicos, los vehículos y las facturas.

### 3. Metodologías de Desarrollo
* **3.1. Marcos de Trabajo Ágiles (Scrum):** Marco de trabajo iterativo e incremental mediante ciclos cortos llamados Sprints, asegurando que los módulos complejos (como la pasarela de pagos o el sistema de reseñas) se construyan, testeen y validen de forma progresiva.
