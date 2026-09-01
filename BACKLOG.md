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
