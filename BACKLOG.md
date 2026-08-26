# 📋 Historias de Usuario - Perfil: Usuario Cliente

### HU-01: Buscar mecánicos
* **Nombre:** BUSCAR MECÁNICOS
* **Como:** Usuario Cliente
* **Puedo:** filtrar y explorar un catálogo de mecánicos según su especialidad, ubicación y calificación por estrellas.
* **Para:** elegir al profesional más adecuado y confiable para mi problema.
* **Dado que:** mi vehículo presenta una falla y necesito encontrar un taller con referencias comprobables.
* **Cuando:** ingreso a la pantalla principal de búsqueda de la aplicación.
* **Entonces:** el sistema me despliega una lista de perfiles ordenados por relevancia o cercanía.

---

### HU-02: Solicitar servicio
* **Nombre:** SOLICITAR SERVICIO
* **Como:** Usuario Cliente
* **Puedo:** redactar mi problema, seleccionar el tipo de servicio y adjuntar archivos multimedia (fotos o audios).
* **Para:** brindarle al profesional la información exacta que necesita para evaluar el trabajo.
* **Dado que:** seleccioné un perfil de mecánico que me interesó dentro del catálogo.
* **Cuando:** oprimo el botón de "Contactar" y se abre el formulario de solicitud.
* **Entonces:** la solicitud se envía y queda registrada en mi perfil bajo el estado "Pendiente de respuesta".

---

### HU-03: Confirmar espera diferida
* **Nombre:** CONFIRMAR ESPERA DE TURNO
* **Como:** Usuario Cliente
* **Puedo:** aceptar o rechazar la propuesta de atención en una fecha posterior (espera).
* **Para:** decidir si prefiero esperar a ese mecánico en particular o cancelar para buscar otro.
* **Dado que:** el mecánico respondió a mi solicitud indicando que tiene demora y me ofreció diferir la atención.
* **Cuando:** recibo la notificación emergente de "Atención diferida".
* **Entonces:** al presionar "Aceptar", conservo mi lugar en su agenda; al presionar "Rechazar", se cancela la solicitud para que pueda contactar a alguien más.

---

### HU-04: Consultar avance de reparación
* **Nombre:** CONSULTAR AVANCE DE REPARACIÓN
* **Como:** Usuario Cliente
* **Puedo:** visualizar una línea de tiempo interactiva con los estados del auto y las fotos que sube el mecánico.
* **Para:** tener un seguimiento transparente de los trabajos y las piezas que se están cambiando.
* **Dado que:** ya entregué el vehículo en el taller y la reparación se encuentra en curso.
* **Cuando:** abro la sección "Bitácora" de mi vehículo en la plataforma.
* **Entonces:** veo detallado cada paso completado (ej. desarme, reparación) con su respectiva evidencia visual.

---

### HU-05: Gestionar arreglo extra
* **Nombre:** GESTIONAR ARREGLO EXTRA
* **Como:** Usuario Cliente
* **Puedo:** aprobar un presupuesto adicional o rechazarlo aceptando las condiciones legales de desgaste.
* **Para:** tener control absoluto sobre el gasto final y decidir qué se repara en mi vehículo.
* **Dado que:** el mecánico detectó una falla imprevista durante el desarme y me envió la alerta con el costo extra.
* **Cuando:** presiono la notificación de "Requiere acción: Autorizar arreglo extra".
* **Entonces:** si lo apruebo, se suma al presupuesto final; si lo rechazo, el sistema registra mi firma digital de exención de responsabilidad y la reparación original continúa.

---

### HU-06: Pagar servicio
* **Nombre:** PAGAR SERVICIO
* **Como:** Usuario Cliente
* **Puedo:** visualizar el monto final y seleccionar si abono mediante tarjeta/transferencia en la app o en efectivo presencial.
* **Para:** saldar mi cuenta de forma cómoda y habilitar el retiro de mi auto.
* **Dado que:** el mecánico notificó que el trabajo está listo y generó la factura digital.
* **Cuando:** accedo a la pasarela de pagos desde el resumen de mi orden finalizada.
* **Entonces:** al confirmar el pago online, se me habilita coordinar el retiro; si elijo efectivo, mi auto queda "Pendiente de pago" hasta que el mecánico reciba el dinero en mano.

---

### HU-07: Calificar atención
* **Nombre:** CALIFICAR ATENCIÓN
* **Como:** Usuario Cliente
* **Puedo:** otorgar una puntuación de 1 a 5 estrellas y redactar una breve reseña de mi experiencia.
* **Para:** ayudar a otros usuarios a elegir de forma segura y retroalimentar el catálogo de la plataforma.
* **Dado que:** el servicio ya fue abonado y retiré mi vehículo exitosamente.
* **Cuando:** el sistema me muestra la pantalla final de cierre de la orden de trabajo.
* **Entonces:** mi reseña se publica inmediatamente en el perfil público del profesional.
