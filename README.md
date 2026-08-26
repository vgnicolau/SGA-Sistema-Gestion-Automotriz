# 🚗 S.G.A. – Sistema de Gestión Automotriz

> **Proyecto Académico:** Plataforma informática interactiva y centralizada para la optimización de servicios mecánicos.

---

## 📖 INTRODUCCIÓN

En el escenario económico y tecnológico actual, las pequeñas y medianas empresas dedicadas al mantenimiento y reparación automotriz se enfrentan al desafío de optimizar sus recursos para mantener su competitividad en el mercado. Tradicionalmente, la administración de los talleres mecánicos se ha caracterizado por una gestión manual, donde el registro de los diagnósticos, el control de inventarios y el seguimiento de las órdenes de trabajo se asientan en soportes físicos como cuadernos o fichas de papel. Esta falta de sistematización de la información no solo ralentiza los procesos operativos internos, sino que impacta de forma directa en el eslabón más crítico del negocio: la relación y la comunicación con el cliente.

La ausencia de un canal de comunicación centralizado y transparente genera una asimetría informativa entre el personal técnico y los propietarios de los vehículos. Habitualmente, los clientes experimentan altos niveles de incertidumbre al desconocer el estado real de la reparación, el desglose exacto de los costos por mano de obra y repuestos, o el cumplimiento de los plazos de entrega inicialmente acordados. Esta situación se ve agravada por la alta volatilidad en los precios de los componentes automotrices, lo que vuelve indispensable contar con presupuestos precisos y dinámicos para evitar pérdidas económicas en el taller y malentendidos con los usuarios.

El presente proyecto propone el desarrollo e implementación del S.G.A. como una solución de software orientada a digitalizar y ordenar de manera integral el ciclo de vida de los servicios mecánicos en la ciudad de San Fernando del Valle de Catamarca. El sistema será desarrollado utilizando **JavaScript** como lenguaje de programación principal para estructurar una interfaz dinámica e interactiva en tiempo real, integrada con un sistema de gestión de bases de datos relacionales administrado a través de **pgAdmin** con **PostgreSQL**. Mediante esta arquitectura tecnológica, el proyecto busca transformar la gestión informal y fragmentada en un flujo de trabajo previsible, eficiente y auditable, garantizando altos estándares de control de calidad y restituyendo la confianza de los usuarios en el sector.

---

## ⚠️ DEFINICIÓN DEL PROBLEMA

El problema principal es la **deficiencia en el seguimiento técnico, la comunicación y la entrega de presupuestos** durante la prestación del servicio en los talleres mecánicos.

### Causas
* Uso de un canal único o informal de comunicación con el cliente mediante mensajes de WhatsApp sueltos o llamadas que no quedan registradas.
* Gestión manual de la información interna como anotaciones en cuadernos, carpetas o fichas de papel.
* Errores humanos al registrar los datos del vehículo, kilometraje o las fallas detectadas.
* Ausencia de un seguimiento del estado del trámite de reparación; el cliente no sabe si su auto está desarmado, en espera de repuestos o listo.
* Acumulación de vehículos en el taller y priorización incorrecta de los trabajos del día.

### Consecuencias
* Pérdida de clientes debido a la desconfianza por demoras o cambios a último momento en los precios.
* Imagen negativa y pérdida de prestigio del taller entre los vecinos de la zona.
* Baja eficiencia operativa de los mecánicos por desorganización en el día a día.
* Cuello de botella en la recepción de la información ya que el dueño o encargado se satura al centralizar todas las consultas.
* Disminución de los ingresos económicos del negocio debido al retraso en las entregas de los vehículos.

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
La necesidad de implementar el S.G.A. se fundamenta en su alta viabilidad técnica y en el impacto positivo multidimensional sobre los talleres en San Fernando del Valle de Catamarca. La propuesta erradica las deficiencias causadas por flujos de comunicación fragmentados (como mensajes de texto sueltos o avisos verbales). Al centralizar la información, se eliminan las discrepancias relacionadas con los costos y el incumplimiento de fechas, estableciendo un marco de transparencia auditable.

**2. ¿Cuál es el impacto que tiene el problema y la importancia?**
En un contexto socioeconómico complejo con constante fluctuación en los costos de repuestos, la gestión manual es un factor de alto riesgo financiero. El software proporciona una herramienta de control preciso sobre presupuestos e insumos en tiempo real, evitando el desfasaje económico que perjudica la rentabilidad del taller y otorgando previsibilidad al cliente.

**3. ¿Qué se va a realizar?**
A nivel interno, el S.G.A. promueve una comunicación coherente que permite coordinar de forma efectiva recursos humanos y materiales. Al asignar tareas con base en la urgencia y complejidad, se disminuye la sobrecarga laboral y el apuro de último momento, traduciéndose en una ejecución técnica meticulosa.

**4. ¿Cuáles son los beneficios sociales?**
Fundamentado en marcos teóricos sobre la interacción digital y la experiencia de usuario, la interfaz visual clara cumple una función pedagógica. Al permitir al usuario visualizar de forma gráfica, secuencial e interactiva el estado real de la reparación mediante la bitácora del sistema, se facilita la asimilación del servicio. Esto disminuye drásticamente el estrés de la incertidumbre operativa y fomenta el sentimiento de sentirse atendido y escuchado.

---

## 📍 UBICACIÓN Y POBLACIÓN OBJETIVO

* **Delimitación Espacial:** Talleres de reparación mecánica y electricidad del automotor situados en la ciudad de San Fernando del Valle de Catamarca.
* **Delimitación del Universo:** 
  1. **Administradores:** Dueños de los talleres.
  2. **Usuarios Técnicos:** Mecánicos encargados de las reparaciones.
  3. **Clientes Finales:** Propietarios de autos particulares.

---

## 🎯 OBJETIVOS

### Objetivo General
Diseñar, desarrollar e implementar un Sistema de Gestión Automotriz mediante una plataforma informática interactiva y centralizada, con el propósito fundamental de agilizar, optimizar y transparentar el seguimiento técnico, la presupuestación y la prestación del servicio mecánico en San Fernando del Valle de Catamarca. El proyecto busca guiar de manera ordenada el ciclo de vida completo de cada reparación vehicular, coordinando eficientemente los recursos humanos y materiales para garantizar el cumplimiento de los plazos de entrega, asegurar estándares de control de calidad y elevar los niveles de confianza.

### Objetivos Específicos
1. **Diseñar e implementar una base de datos relacional robusta** mediante el motor PostgreSQL (utilizando pgAdmin) para estructurar y resguardar de forma organizada el registro confidencial de clientes, datos técnicos de vehículos y el historial cronológico de reparaciones.
2. **Desarrollar los módulos lógicos e interactivos** mediante el lenguaje JavaScript, garantizando que el procesamiento de datos de las tareas diarias, el control de estados en tiempo real y la visualización funcionen de manera fluida y segura.
3. **Desarrollar un sistema lógico de registro de estados en tiempo real** que permita actualizar y visualizar de manera sencilla las distintas etapas del ciclo de vida de la reparación.
4. **Programar un panel centralizado de presupuestos digitales**, donde se detallen de forma transparente y desglosada los costos asociados a la mano de obra y materiales utilizados, minimizando discrepancias al momento del cobro.

---

## 🏗️ MARCO TEÓRICO

### 1. Gestión de Procesos y Comunicación
* **1.1. Gestión por Procesos:** Identificación, modelado, automatización y optimización continua de los flujos de trabajo de una organización para maximizar la eficiencia. La estandarización de hitos operativos mediante software erradica la improvisación y los cuellos de botella administrativos.
* **1.2. Asimetría Informativa y Experiencia de Usuario:** La asimetría informativa ocurre cuando el personal técnico posee mayor conocimiento que el cliente, generando desconfianza. La bitácora digital interactiva actúa como un puente pedagógico que neutraliza esta asimetría y restituye la confianza.

### 2. Arquitectura de Software y Tecnologías
* **2.1. Interfaces Dinámicas e Interactivas en Tiempo Real:** Se utiliza JavaScript debido a su naturaleza asíncrona y capacidad para gestionar eventos en el navegador, garantizando que las modificaciones de datos en el servidor se reflejen inmediatamente sin recargar la página.
* **2.2. Sistemas de Gestión de Bases de Datos Relacionales:** Se optó por PostgreSQL (administrado mediante pgAdmin) por ser un motor robusto, escalable y con excelente soporte para transacciones complejas, garantizando la integridad referencial y seguridad de los datos.

### 3. Metodologías de Desarrollo
* **3.1. Marcos de Trabajo Ágiles (Scrum):** Marco de trabajo iterativo e incremental mediante ciclos cortos llamados Sprints, asegurando que los módulos se construyan, testeen y validen de forma progresiva para minimizar riesgos de desviación.
