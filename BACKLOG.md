## 📋 Product Backlog: Historias de Usuario (Perfil Cliente)

### HU-01: CREAR PERFIL DE USUARIO
* **Nombre:** CREAR PERFIL
* **Como:** Usuario Cliente
* **Puedo:** registrarme en la plataforma completando un formulario con mis datos personales (nombre, correo electrónico y contraseña).
* **Para:** tener una cuenta única y segura que me permita acceder a todos los servicios del ecosistema.
* **Dado que:** soy un usuario nuevo que acaba de descargar o ingresar a la plataforma por primera vez.
* **Cuando:** presiono el botón de "Registrarse" en la pantalla de inicio.
* **Entonces:** el sistema valida que mis datos sean correctos, crea mi cuenta y me da la bienvenida.

### HU-02: INICIAR SESIÓN
* **Nombre:** INICIAR SESIÓN
* **Como:** Usuario Cliente
* **Puedo:** ingresar a mi cuenta utilizando mi correo electrónico (o usuario) y mi contraseña.
* **Para:** acceder a mi panel personal para gestionar mis autos y ver mis turnos.
* **Dado que:** ya poseo una cuenta registrada y validada en el sistema.
* **Cuando:** introduzco mis credenciales en la pantalla de "Login".
* **Entonces:** el sistema me autentica y me redirige a la pantalla principal de búsqueda.

### HU-03: REGISTRAR VEHÍCULO
* **Nombre:** REGISTRAR VEHÍCULO
* **Como:** Usuario Cliente
* **Puedo:** cargar los datos técnicos de mi auto (patente, marca, modelo, año y kilometraje).
* **Para:** tener mi vehículo guardado en el sistema y no tener que cargar sus datos manualmente cada vez que pida un turno.
* **Dado que:** he iniciado sesión y me encuentro dentro de la sección "Mi Garaje" de mi perfil.
* **Cuando:** presiono "Agregar nuevo vehículo" y completo los campos solicitados.
* **Entonces:** los datos del auto quedan vinculados a mi cuenta listos para ser usados en una solicitud.

### HU-04: BUSCAR MECÁNICOS
* **Nombre:** BUSCAR MECÁNICOS
* **Como:** Usuario Cliente
* **Puedo:** utilizar una barra de búsqueda y aplicar filtros de especialidad (ej. frenos, motor, electricidad).
* **Para:** acotar la lista de talleres y encontrar a los profesionales que solucionen mi problema específico.
* **Dado que:** necesito asistencia mecánica y me encuentro en la pantalla de inicio del catálogo.
* **Cuando:** escribo una palabra clave en el buscador o selecciono una categoría.
* **Entonces:** la plataforma filtra la base de datos y me muestra solo las tarjetas de los mecánicos correspondientes.

### HU-05: VISUALIZAR PERFIL DEL MECÁNICO
* **Nombre:** VISUALIZAR PERFIL
* **Como:** Usuario Cliente
* **Puedo:** entrar al perfil detallado de un mecánico para ver sus trabajos destacados, su calificación promedio (estrellas) y las reseñas escritas por otros usuarios.
* **Para:** evaluar su reputación y tomar una decisión informada antes de dejarle mi auto.
* **Dado que:** vi una tarjeta de un taller en los resultados de búsqueda que me interesó.
* **Cuando:** hago clic sobre el nombre del mecánico en el catálogo.
* **Entonces:** el sistema me abre su página pública con todo su historial y referencias.

### HU-06: CREAR SOLICITUD DE SERVICIO
* **Nombre:** CREAR SOLICITUD
* **Como:** Usuario Cliente
* **Puedo:** redactar un mensaje de texto describiendo la falla de mi auto y seleccionar qué tipo de servicio requiero (diagnóstico o service general).
* **Para:** explicarle formalmente al mecánico qué le pasa a mi vehículo.
* **Dado que:** estoy convencido del mecánico que elegí y me encuentro en su perfil público.
* **Cuando:** presiono el botón "Contactar" y comienzo a llenar el campo de texto.
* **Entonces:** el sistema prepara el formulario para ser enviado.

### HU-07: ADJUNTAR EVIDENCIA MULTIMEDIA
* **Nombre:** ADJUNTAR EVIDENCIA
* **Como:** Usuario Cliente
* **Puedo:** subir fotografías, grabar un video corto o un audio directamente desde mi dispositivo.
* **Para:** complementar mi texto con pruebas visuales/sonoras (un ruido raro, una pieza rota) que ayuden al mecánico a evaluar si toma el trabajo.
* **Dado que:** estoy redactando la solicitud de servicio y quiero dar más detalles.
* **Cuando:** presiono el icono de "Subir Archivo" o "Micrófono" en el formulario de contacto.
* **Entonces:** el archivo se carga en la plataforma y queda adjunto al mensaje final.

### HU-08: RESPONDER A ESPERA DIFERIDA
* **Nombre:** RESPONDER ESPERA
* **Como:** Usuario Cliente
* **Puedo:** aceptar o rechazar formalmente la propuesta del mecánico de atenderme en una fecha diferida (ej. en 15 días).
* **Para:** decidir si prefiero esperar por ese profesional específico o cancelar el trámite para buscar a alguien con disponibilidad inmediata.
* **Dado que:** el mecánico no tiene agenda disponible hoy y me envió una contraoferta de tiempo.
* **Cuando:** visualizo la notificación emergente con los botones de "Aceptar espera" o "Cancelar".
* **Entonces:** mi respuesta actualiza el estado de la solicitud en el sistema y le avisa al mecánico mi decisión.

### HU-09: VISUALIZAR BITÁCORA DE ESTADOS
* **Nombre:** VISUALIZAR ESTADO DE REPARACIÓN
* **Como:** Usuario Cliente
* **Puedo:** ver una línea de tiempo interactiva que cambia según la etapa del arreglo (ingresado, desarmado, esperando repuestos, en arreglo).
* **Para:** saber exactamente en qué fase se encuentra mi auto sin tener que llamar por teléfono al taller.
* **Dado que:** el mecánico aceptó el auto y el vehículo ya se encuentra físicamente en el taller.
* **Cuando:** abro la sección "Mis Reparaciones Activas" en la app.
* **Entonces:** observo un panel gráfico con el progreso actualizado en tiempo real.

### HU-10: COMPROBAR EVIDENCIA DE REPUESTOS
* **Nombre:** COMPROBAR EVIDENCIA
* **Como:** Usuario Cliente
* **Puedo:** hacer clic en los hitos de la bitácora para abrir las fotografías subidas por el mecánico.
* **Para:** comprobar con mis propios ojos que la pieza vieja fue extraída y el repuesto nuevo fue efectivamente instalado.
* **Dado que:** el mecánico actualizó un estado de la reparación e incluyó fotos como respaldo.
* **Cuando:** selecciono una imagen en la línea de tiempo de mi bitácora.
* **Entonces:** se abre la foto en pantalla completa como prueba del trabajo realizado.

### HU-11: APROBAR ARREGLO EXTRA
* **Nombre:** APROBAR PRESUPUESTO EXTRA
* **Como:** Usuario Cliente
* **Puedo:** presionar un botón de "Aceptar" frente a una alerta de falla imprevista detectada por el mecánico.
* **Para:** autorizar formalmente el gasto adicional y permitir que el mecánico cambie esa pieza extra.
* **Dado que:** el mecánico desarmó el auto, encontró un problema nuevo, y me envió la notificación con el costo adicional.
* **Cuando:** leo la alerta y decido que quiero hacer esa reparación extra.
* **Entonces:** el costo se suma a mi factura final y el mecánico recibe luz verde para proceder.

### HU-12: RECHAZAR ARREGLO EXTRA (AVISO LEGAL)
* **Nombre:** RECHAZAR PRESUPUESTO EXTRA
* **Como:** Usuario Cliente
* **Puedo:** presionar "Rechazar" frente a un arreglo extra, lo cual me despliega una casilla donde acepto asumir el riesgo por no cambiar esa pieza.
* **Para:** mantener mi presupuesto original intacto, liberando al mecánico de la responsabilidad si esa pieza falla en el corto plazo.
* **Dado que:** el mecánico me sugirió cambiar una pieza extra pero no dispongo del dinero para hacerlo.
* **Cuando:** decido declinar la sugerencia y presiono "Rechazar arreglo".
* **Entonces:** mi firma digital de exención de responsabilidad se guarda en la base de datos y la reparación original continúa su curso normal.

### HU-13: ABONAR SERVICIO
* **Nombre:** ABONAR FACTURA
* **Como:** Usuario Cliente
* **Puedo:** visualizar el monto final desglosado y seleccionar mi método de pago (pasarela online o efectivo en sucursal).
* **Para:** saldar mi cuenta de manera segura y habilitar el sistema para poder retirar mi auto.
* **Dado que:** recibí la notificación de "Vehículo Listo" junto con el comprobante final.
* **Cuando:** presiono el botón de "Pagar" en el resumen final.
* **Entonces:** si pago online el sistema registra la transacción; si elijo efectivo el auto queda retenido en el sistema hasta que entregue el dinero físico en el taller.

### HU-14: CALIFICAR ATENCIÓN
* **Nombre:** CALIFICAR ATENCIÓN
* **Como:** Usuario Cliente
* **Puedo:** otorgar una puntuación de estrellas y redactar un comentario sobre mi experiencia.
* **Para:** premiar al buen mecánico, generar confianza en la plataforma y advertir/ayudar a futuros clientes.
* **Dado que:** mi auto ya me fue entregado, aboné el servicio y se cerró la orden de trabajo.
* **Cuando:** el sistema me muestra la pantalla de cierre pidiéndome mi opinión.
* **Entonces:** mi reseña se guarda en la base de datos y aparece públicamente en el perfil de ese mecánico.


## 📋 Product Backlog: Historias de Usuario (Perfil Mecánico)

### HU-15: CREAR PERFIL DE TALLER
* **Nombre:** CREAR PERFIL DE TALLER
* **Como:** Usuario Mecánico
* **Puedo:** registrar mi cuenta completando mis datos personales, los de mi taller (nombre, dirección) y mis especialidades principales.
* **Para:** tener presencia en el catálogo público de la plataforma y empezar a recibir solicitudes de trabajo.
* **Dado que:** soy un profesional automotriz que desea digitalizar su gestión y conseguir nuevos clientes.
* **Cuando:** presiono el botón "Registrarse como Mecánico" en la pantalla inicial y completo el formulario.
* **Entonces:** el sistema crea mi perfil público y me da de alta en el motor de búsqueda de la aplicación.

### HU-16: INICIAR SESIÓN (MECÁNICO)
* **Nombre:** INICIAR SESIÓN
* **Como:** Usuario Mecánico
* **Puedo:** ingresar a mi cuenta utilizando mi correo electrónico y contraseña.
* **Para:** acceder a mi panel de control (Dashboard) donde gestiono mis mensajes, turnos y reparaciones activas.
* **Dado que:** ya poseo un taller registrado y validado en la plataforma.
* **Cuando:** introduzco mis credenciales en la pantalla de "Login para Profesionales".
* **Entonces:** el sistema me autentica y me redirige a mi bandeja de entrada.

### HU-17: VISUALIZAR BANDEJA DE ENTRADA
* **Nombre:** VISUALIZAR SOLICITUDES
* **Como:** Usuario Mecánico
* **Puedo:** ver una lista de mensajes nuevos enviados por clientes, incluyendo el texto descriptivo y las fotos/audios adjuntos.
* **Para:** evaluar el problema del vehículo antes de comprometerme a realizar el trabajo.
* **Dado que:** un cliente me encontró en el catálogo y me envió una solicitud de servicio.
* **Cuando:** ingreso a la sección "Bandeja de Entrada" en mi panel de control.
* **Entonces:** el sistema me despliega las tarjetas con la información detallada de cada petición pendiente.

### HU-18: ACEPTAR SOLICITUD Y AGENDAR TURNO
* **Nombre:** AGENDAR TURNO
* **Como:** Usuario Mecánico
* **Puedo:** presionar el botón de "Aceptar" en una solicitud y desplegar un calendario para elegir el día y horario en que recibiré el auto.
* **Para:** organizar mi agenda de trabajo y evitar superposición de vehículos en el taller.
* **Dado que:** leí la solicitud de un cliente y decidí que tengo la capacidad para realizar el diagnóstico o reparación.
* **Cuando:** selecciono una fecha y hora en el calendario emergente y confirmo la acción.
* **Entonces:** el sistema le envía la confirmación del turno al cliente y bloquea ese espacio en mi agenda.

### HU-19: DIFERIR SOLICITUD (ESPERA)
* **Nombre:** DIFERIR SOLICITUD
* **Como:** Usuario Mecánico
* **Puedo:** seleccionar la opción de "Diferir" y ofrecerle al cliente atenderlo en una cantidad determinada de días (tope máximo de 1 mes).
* **Para:** no perder el trabajo ni al cliente en momentos donde mi taller se encuentra con capacidad máxima.
* **Dado que:** leí la solicitud del cliente, me interesa el trabajo, pero actualmente no tengo turnos disponibles.
* **Cuando:** presiono "Atender en X días" e ingreso la cantidad de días de demora.
* **Entonces:** la solicitud queda en estado de "Espera" hasta que el cliente confirme si acepta o rechaza mi propuesta.

### HU-20: RECHAZAR SOLICITUD
* **Nombre:** RECHAZAR SOLICITUD
* **Como:** Usuario Mecánico
* **Puedo:** declinar una petición de servicio escribiendo un breve motivo (ej. "No trabajo con esa marca" o "Falta de herramientas").
* **Para:** mantener mi bandeja de entrada limpia y liberar al cliente para que busque otro profesional.
* **Dado que:** recibí una solicitud para un tipo de trabajo que no realizo o no deseo tomar.
* **Cuando:** presiono el botón "Rechazar" y selecciono el motivo en el menú desplegable.
* **Entonces:** la solicitud se elimina de mi panel y el cliente es notificado de la cancelación.

### HU-21: ACTUALIZAR ESTADO DE REPARACIÓN
* **Nombre:** ACTUALIZAR ESTADO EN BITÁCORA
* **Como:** Usuario Mecánico
* **Puedo:** cambiar el estado de la orden de trabajo (Ej: Recepcionado, Desarmado, En Reparación, Listo) mediante botones interactivos.
* **Para:** mantener informado al cliente en tiempo real sobre el progreso de su auto y evitar que me llame por teléfono.
* **Dado que:** el vehículo ya ingresó a mi taller y comencé a trabajar físicamente en él.
* **Cuando:** completo una etapa del trabajo y presiono el botón de "Avanzar fase" en el panel de la orden.
* **Entonces:** la bitácora del cliente se actualiza automáticamente con el nuevo estado.

### HU-22: CARGAR EVIDENCIA FOTOGRÁFICA
* **Nombre:** CARGAR EVIDENCIA MULTIMEDIA
* **Como:** Usuario Mecánico
* **Puedo:** sacar fotos o grabar videos de las piezas rotas durante el desarme y de los repuestos nuevos instalados, y subirlas a la plataforma.
* **Para:** justificar mi trabajo, transparentar el proceso y darle total tranquilidad al dueño del auto.
* **Dado que:** me encuentro actualizando un estado en la bitácora de reparación del vehículo.
* **Cuando:** presiono el icono de "Adjuntar archivo" y selecciono la imagen desde mi celular/PC.
* **Entonces:** la foto se guarda en la base de datos y aparece disponible en la línea de tiempo del cliente.

### HU-23: NOTIFICAR ARREGLO EXTRA
* **Nombre:** NOTIFICAR ARREGLO EXTRA
* **Como:** Usuario Mecánico
* **Puedo:** pausar la reparación y enviarle al cliente una alerta detallando una falla imprevista junto con su costo adicional.
* **Para:** no tomar decisiones financieras por el cliente y obtener su autorización explícita antes de cambiar una pieza no presupuestada.
* **Dado que:** al desarmar el vehículo descubrí que un repuesto que parecía sano está a punto de romperse.
* **Cuando:** presiono el botón "Cargar Arreglo Extra", escribo el diagnóstico, el precio y envío la alerta.
* **Entonces:** el estado del vehículo cambia a "Esperando autorización" y no puedo avanzar hasta que el cliente acepte o firme el rechazo legal.

### HU-24: CERRAR ORDEN Y FACTURAR
* **Nombre:** CERRAR ORDEN DE TRABAJO
* **Como:** Usuario Mecánico
* **Puedo:** marcar el auto como "Listo", cargar el presupuesto final detallado (repuestos + mano de obra) y enviarlo.
* **Para:** dar por finalizada mi tarea técnica y habilitar la instancia de cobro.
* **Dado que:** terminé exitosamente todas las reparaciones, armé el vehículo y realicé las pruebas correspondientes.
* **Cuando:** presiono el botón "Finalizar Servicio y Generar Factura".
* **Entonces:** al cliente le llega la notificación para que proceda al pago mediante la plataforma.

### HU-25: CONFIRMAR PAGO PRESENCIAL
* **Nombre:** CONFIRMAR PAGO EN EFECTIVO
* **Como:** Usuario Mecánico
* **Puedo:** presionar un botón de "Pago Recibido" dentro del sistema para liberar definitivamente la orden de trabajo.
* **Para:** tener el control final de la entrega y asegurar que el vehículo no se retire sin haber cobrado.
* **Dado que:** el auto está listo pero el cliente seleccionó abonar en efectivo al momento de retirarlo.
* **Cuando:** el cliente se presenta en mi taller, me entrega el dinero en mano y presiono el botón de confirmación en la app.
* **Entonces:** la orden se cierra exitosamente, la transacción queda guardada en mi historial de ingresos y el cliente recibe la opción de calificarme.







vista de admin clientes, mapa de calor, estadisticas 

