# 📋 Product Backlog - Historias de Usuario

A continuación se detallan las Historias de Usuario (HU) que definen el comportamiento y los requerimientos funcionales de la plataforma de intermediación mecánica, estructuradas bajo el estándar Scrum.

---

### HU-01: Buscar mecánicos
* **Nombre:** BUSCAR MECÁNICOS
* **Como:** Usuario Cliente
* **Puedo:** filtrar y visualizar un catálogo de mecánicos por especialidad y calificación de reseñas.
* **Para:** elegir al profesional más adecuado, transparente y confiable para mi problema.
* **Dado que:** existe una necesidad de encontrar un taller con referencias objetivas y trabajos previos comprobables.
* **Cuando:** ingreso a la pantalla principal de la plataforma buscando asistencia técnica.
* **Entonces:** el sistema me muestra una lista de perfiles de mecánicos ordenados por relevancia, con sus estrellas y trabajos destacados.

---

### HU-02: Solicitar servicio
* **Nombre:** SOLICITAR SERVICIO
* **Como:** Usuario Cliente
* **Puedo:** redactar mi problema, adjuntar imágenes/audios y seleccionar si es un "Service Genérico" o una "Falla a Revisar".
* **Para:** brindarle al mecánico la información exacta que necesita para evaluar si toma el trabajo o no.
* **Dado que:** encontré un perfil de mecánico adecuado en el catálogo y decidí contactarlo.
* **Cuando:** oprimo el botón de "Contactar" dentro del perfil del profesional elegido.
* **Entonces:** se abre una nueva casilla donde cargo mi evidencia, se clasifica el tipo de solicitud y se envía a la sección de "Mensajes Nuevos" del mecánico.

---

### HU-03: Gestionar solicitud recibida
* **Nombre:** GESTIONAR SOLICITUD
* **Como:** Usuario Mecánico
* **Puedo:** aceptar la solicitud, aceptarla con diferimiento (tope de 1 mes) o rechazarla aclarando el motivo.
* **Para:** organizar la demanda de mi taller sin sobrecargarme de trabajo ni comprometerme a plazos irreales.
* **Dado que:** recibo una nueva notificación de un cliente potencial en mi bandeja de entrada.
* **Cuando:** analizo el audio/foto y decido si tengo la capacidad técnica y temporal para hacerlo.
* **Entonces:** selecciono una de las tres opciones; si elijo diferir, el sistema le pregunta al cliente si desea esperar esos días o si prefiere cancelar y buscar otro mecánico.

---

### HU-04: Asignar turno en calendario
* **Nombre:** ASIGNAR TURNO
* **Como:** Usuario Mecánico
* **Puedo:** desplegar mi calendario interno y seleccionar una fecha y hora específica para recibir el vehículo.
* **Para:** asegurar la organización de mi día y evitar que dos clientes vengan al mismo tiempo.
* **Dado que:** acepté formalmente la solicitud del cliente y necesitamos coordinar la entrega del auto.
* **Cuando:** presiono el botón de agendar tras la confirmación de la solicitud.
* **Entonces:** elijo el bloque horario en mi calendario, el cliente recibe la confirmación y el sistema programa recordatorios automáticos para ambos el día del turno.

---

### HU-05: Registrar bitácora multimedia
* **Nombre:** REGISTRAR AVANCES DE REPARACIÓN
* **Como:** Usuario Mecánico
* **Puedo:** subir fotos del estado inicial del auto, piezas retiradas y repuestos nuevos instalados.
* **Para:** brindar total transparencia sobre el procedimiento y justificar el cobro del servicio.
* **Dado que:** el vehículo ya ingresó al taller y estoy realizando el desarme o reemplazo físico de componentes.
* **Cuando:** completo una etapa crítica de la reparación.
* **Entonces:** cargo las imágenes desde mi interfaz y el sistema actualiza inmediatamente la vista del cliente para que vea los progresos.

---

### HU-06: Gestionar arreglos extra
* **Nombre:** GESTIONAR ARREGLO EXTRA
* **Como:** Usuario Cliente
* **Puedo:** aceptar o rechazar formalmente un presupuesto adicional por una falla imprevista detectada durante el desarme.
* **Para:** tener control absoluto sobre mi gasto final y decidir qué se repara.
* **Dado que:** el mecánico subió una evidencia de un problema no contemplado y envió el costo/tiempo adicional.
* **Cuando:** recibo la alerta de "Requiere acción: Autorizar arreglo extra".
* **Entonces:** si decido rechazarlo, el sistema me obliga a aceptar un aviso legal asumiendo el riesgo por el desgaste del repuesto original, el mecánico sigue con el arreglo inicial y queda eximido de futuras quejas sobre esa pieza específica.

---

### HU-07: Pagar reparación
* **Nombre:** PAGAR REPARACIÓN
* **Como:** Usuario Cliente
* **Puedo:** visualizar el monto total final, elegir mi método de pago (plataforma o efectivo) y coordinar el retiro.
* **Para:** saldar mi deuda de forma cómoda y recuperar mi vehículo.
* **Dado que:** el mecánico notificó que el auto está listo y adjuntó la factura final.
* **Cuando:** accedo a la pasarela de pagos integrada en la aplicación.
* **Entonces:** si pago online, se me habilita el horario de retiro; si elijo efectivo presencial, mi auto queda en estado "Pendiente de pago" y solo el mecánico, al recibir los billetes en el taller, podrá presionar el botón que libere la entrega en el sistema.

---

### HU-08: Calificar servicio
* **Nombre:** CALIFICAR SERVICIO
* **Como:** Usuario Cliente
* **Puedo:** otorgar una valoración de 1 a 5 estrellas y redactar un comentario sobre la atención recibida.
* **Para:** ayudar a otros usuarios a elegir de forma segura y premiar al buen profesional.
* **Dado que:** el vehículo ya fue retirado del taller y la orden de trabajo se cerró exitosamente.
* **Cuando:** ingreso a la plataforma después de haber finalizado mi experiencia con el mecánico.
* **Entonces:** mi reseña se publica automáticamente en el perfil público del profesional, afectando su posicionamiento en el catálogo del sistema.
