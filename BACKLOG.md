## 📋 Product Backlog: Historias de Usuario (Perfil Cliente)

### HU-01: CREAR PERFIL DE USUARIO
* **Nombre:** CREAR PERFIL
* **Como:** Usuario Cliente
* **Puedo:** registrarme en la plataforma completando un formulario con mis datos personales (nombre, correo electrónico y contraseña).
* **Para:** tener una cuenta única y segura que me permita acceder a todos los servicios del ecosistema.
* **Dado que:** soy un usuario nuevo que acaba de descargar o ingresar a la plataforma por primera vez.
* **Cuando:** presiono el botón de "Registrarse" en la pantalla de inicio.
* **Entonces:** el sistema valida que mis datos(nombre, mail, numero de telefono) sean correctos, crea mi cuenta y me da la bienvenida.

### HU-02: INICIAR SESIÓN
* **Nombre:** INICIAR SESIÓN
* **Como:** Usuario Cliente
* **Puedo:** ingresar a mi cuenta utilizando mi correo electrónico (o usuario) y mi contraseña.
* **Para:** acceder a mi panel personal para gestionar mis autos y ver mis turnos.
* **Dado que:** ya poseo una cuenta registrada y validada en el sistema.
* **Cuando:** introduzco mis credenciales en la pantalla de "Login".
* **Entonces:** el sistema me autentica dichos datos ingresados cuando se creo el perfil y me redirige a la pantalla principal de búsqueda.

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

### HU-04.1: BUSCAR MECÁNICOS EN MAPA
* **Nombre:** BUSCAR MECÁNICOS EN MAPA
* **Como:** Usuario Cliente
* **Puedo:** visualizar un mapa interactivo con mi ubicación actual y pines que marcan a los mecánicos cercanos dentro de un radio de kilómetros modificable.
* **Para:** encontrar rápidamente un taller que me quede cómodo geográficamente y evitar contactar por error a profesionales de otras ciudades o provincias.
* **Dado que:** necesito asistencia y me encuentro en la pantalla de búsqueda del catálogo.
* **Cuando:** presiono el botón "Ver en mapa" y concedo los permisos de ubicación de mi dispositivo.
* **Entonces:** el sistema cruza mis coordenadas con la base de datos y me muestra gráficamente solo a los mecánicos locales.



## 📋 Product Backlog: Historias de Usuario (Perfil Mecánico)

### HU-15: CREAR PERFIL DE TALLER
* **Nombre:** CREAR PERFIL DE TALLER
* **Como:** Usuario Mecánico
* **Puedo:** registrar mi cuenta completando mis datos personales, los de mi taller (nombre, dirección) y mis especialidades principales.
* **Para:** tener presencia en el catálogo público de la plataforma y empezar a recibir solicitudes de trabajo.
* **Dado que:** soy un profesional automotriz que desea digitalizar su gestión y conseguir nuevos clientes.
* **Cuando:** presiono el botón "Registrarse como Mecánico" en la pantalla inicial y completo el formulario.
* **Entonces:** el sistema crea mi perfil público y me da de alta en el motor de búsqueda de la aplicación.

### HU-15.1: CONFIGURAR UBICACIÓN EN MAPA
* **Nombre:** CONFIGURAR UBICACIÓN EN MAPA
* **Como:** Usuario Mecánico
* **Puedo:** fijar la dirección exacta de mi taller posicionando un marcador rojo (pin) sobre un mapa interactivo al momento de crear o editar mi perfil.
* **Para:** aparecer correctamente posicionado en las búsquedas geolocalizadas de los clientes de mi zona.
* **Dado que:** estoy configurando mi cuenta comercial para empezar a recibir solicitudes reales.
* **Cuando:** ingreso a la sección de "Ubicación" y arrastro el marcador hasta mi calle y altura exacta.
* **Entonces:** el sistema captura las coordenadas (latitud y longitud) del pin y las guarda permanentemente en la base de datos de mi perfil.


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


## 📋 Product Backlog: Historias de Usuario (Perfil Administrador)

### HU-26: CREAR PERFIL ADMINISTRATIVO
* **Nombre:** CREAR PERFIL ADMINISTRATIVO
* **Como:** Usuario Administrador Maestro
* **Puedo:** registrar una cuenta de superusuario con credenciales maestras y privilegios totales.
* **Para:** tener el control absoluto de la plataforma, gestionar las reglas de negocio y supervisar a todos los actores del ecosistema.
* **Dado que:** el sistema acaba de ser desplegado y no existe ninguna cuenta con permisos para moderar.
* **Cuando:** ejecuto el registro inicial mediante la consola del servidor.
* **Entonces:** el sistema genera una cuenta con permisos de nivel superior, diferenciándola estructuralmente de los clientes y mecánicos.

### HU-27: INICIAR SESIÓN ADMINISTRATIVA
* **Nombre:** INICIAR SESIÓN ADMINISTRATIVA
* **Como:** Usuario Administrador
* **Puedo:** ingresar al panel de control central (Backoffice) utilizando mi correo y contraseña.
* **Para:** acceder a las herramientas exclusivas de moderación, métricas y gestión de usuarios.
* **Dado que:** ya poseo una cuenta validada con rol de administrador en la base de datos.
* **Cuando:** introduzco mis credenciales en la ruta de acceso exclusiva (ej: /admin).
* **Entonces:** el sistema valida mis permisos y me redirige al tablero principal.

### HU-28: GESTIONAR SUB-ADMINISTRADORES
* **Nombre:** GESTIONAR SUB-ADMINISTRADORES
* **Como:** Usuario Administrador Maestro
* **Puedo:** crear nuevas cuentas administrativas secundarias y asignarles permisos limitados por módulos.
* **Para:** delegar tareas de soporte y moderación a un equipo de trabajo sin comprometer la seguridad financiera.
* **Dado que:** el volumen de usuarios creció y necesito ayuda operativa.
* **Cuando:** ingreso a la pestaña de "Gestión de Permisos" y doy de alta un nuevo rol.
* **Entonces:** el nuevo usuario recibe sus credenciales y solo accede a las pantallas habilitadas.

### HU-29: VERIFICAR IDENTIDAD DEL MECÁNICO
* **Nombre:** VERIFICAR IDENTIDAD
* **Como:** Usuario Administrador
* **Puedo:** revisar la documentación enviada por un nuevo mecánico (DNI, fotos del taller) y aprobar o rechazar su perfil.
* **Para:** garantizar que solo profesionales legítimos ofrezcan servicios, manteniendo la seguridad del Marketplace.
* **Dado que:** un usuario completó el formulario de registro como mecánico y está en estado "Pendiente".
* **Cuando:** presiono "Aprobar perfil" en el panel de control de usuarios.
* **Entonces:** el perfil se activa, se vuelve visible en el catálogo de búsqueda y se le notifica por correo.

### HU-30: VISUALIZAR MAPA DE CALOR (DEMANDA)
* **Nombre:** VISUALIZAR MAPA DE CALOR
* **Como:** Usuario Administrador
* **Puedo:** observar un mapa interactivo con zonas resaltadas según la concentración de solicitudes de servicio y talleres activos.
* **Para:** analizar geográficamente la demanda y saber en qué barrios de la ciudad faltan mecánicos.
* **Dado que:** necesito conocer las métricas de uso y distribución de la plataforma.
* **Cuando:** ingreso a la pestaña "Geolocalización" en el panel interno.
* **Entonces:** el sistema cruza las coordenadas y renderiza las zonas con mayor tráfico.

### HU-31: SUSPENDER CUENTAS
* **Nombre:** SUSPENDER CUENTAS
* **Como:** Usuario Administrador
* **Puedo:** bloquear temporal o permanentemente el acceso de un cliente o mecánico.
* **Para:** penalizar comportamientos fraudulentos, exceso de reportes o incumplimiento de normas.
* **Dado que:** detecté actividad sospechosa o recibí múltiples quejas sobre un usuario.
* **Cuando:** selecciono el estado "Suspendido" dentro del perfil del usuario y redacto el motivo.
* **Entonces:** el usuario pierde el acceso inmediatamente.

### HU-32: MEDIAR DISPUTAS DE SERVICIO
* **Nombre:** MEDIAR DISPUTAS
* **Como:** Usuario Administrador
* **Puedo:** acceder al historial de chat, bitácora de estados, fotos y presupuestos de una orden de trabajo específica.
* **Para:** actuar como árbitro imparcial si un cliente denuncia un mal arreglo o un mecánico reporta falta de pago.
* **Dado que:** un usuario generó un ticket de "Reportar problema".
* **Cuando:** abro el ticket de soporte en el sistema de administración.
* **Entonces:** obtengo acceso de lectura a toda la evidencia de esa reparación para emitir un fallo.

### HU-33: MODERAR RESEÑAS Y COMENTARIOS
* **Nombre:** MODERAR RESEÑAS
* **Como:** Usuario Administrador
* **Puedo:** ocultar o eliminar reseñas y comentarios públicos que contengan insultos, spam o información falsa.
* **Para:** mantener un entorno respetuoso y asegurar que el catálogo de calificaciones sea objetivo.
* **Dado que:** un sistema automático o un usuario reportó un comentario ofensivo.
* **Cuando:** presiono el botón "Eliminar reseña" desde el panel de moderación.
* **Entonces:** el comentario desaparece del perfil público del mecánico y se recalcula su puntaje.

### HU-34: CONFIGURAR COMISIONES DE PLATAFORMA
* **Nombre:** CONFIGURAR COMISIONES
* **Como:** Usuario Administrador
* **Puedo:** establecer o modificar el porcentaje de comisión que la plataforma retiene por cada pago procesado online.
* **Para:** ajustar el modelo de negocio y garantizar la rentabilidad del software.
* **Dado que:** necesito actualizar los márgenes de ganancia del sistema.
* **Cuando:** ingreso el nuevo valor porcentual en la sección "Configuración Financiera" y guardo los cambios.
* **Entonces:** todas las futuras órdenes de trabajo calcularán la retención en base a este nuevo porcentaje.

### HU-35: LIQUIDAR PAGOS A MECÁNICOS
* **Nombre:** LIQUIDAR PAGOS
* **Como:** Usuario Administrador
* **Puedo:** aprobar la transferencia del dinero acumulado en la plataforma hacia la cuenta bancaria (CBU/CVU) del mecánico.
* **Para:** completar el ciclo financiero y asegurar que los profesionales reciban su dinero descontando la comisión.
* **Dado que:** los clientes han pagado servicios mediante la pasarela online y los fondos están retenidos en el sistema.
* **Cuando:** presiono "Aprobar Liquidación" en el panel de finanzas del mecánico.
* **Entonces:** el sistema registra la salida de dinero y cambia el estado del saldo a "Transferido".

### HU-36: GESTIONAR CATEGORÍAS Y ESPECIALIDADES
* **Nombre:** GESTIONAR CATEGORÍAS
* **Como:** Usuario Administrador
* **Puedo:** crear, editar o eliminar las etiquetas de especialidades mecánicas (ej: "Inyección Electrónica", "GNC").
* **Para:** mantener el catálogo organizado y adaptado a las nuevas necesidades del mercado automotor.
* **Dado que:** necesito agregar un nuevo tipo de servicio que los mecánicos puedan seleccionar en sus perfiles.
* **Cuando:** ingreso a "Gestión de Categorías", agrego el nuevo nombre y guardo.
* **Entonces:** la nueva etiqueta queda disponible inmediatamente en los filtros de búsqueda y en el registro de mecánicos.

### HU-37: GENERAR REPORTES ESTADÍSTICOS
* **Nombre:** GENERAR REPORTES
* **Como:** Usuario Administrador
* **Puedo:** exportar documentos en formato PDF o Excel con el resumen de usuarios activos, turnos concretados e ingresos mensuales.
* **Para:** presentar informes de rendimiento en defensas académicas o reuniones de negocio.
* **Dado que:** requiero extraer la información consolidada de la base de datos.
* **Cuando:** selecciono un rango de fechas y presiono "Exportar Reporte" en el panel de métricas.
* **Entonces:** el sistema procesa los datos y descarga el archivo estructurado en mi dispositivo.

## 📋 Product Backlog: Historias de Usuario (Soporte y Configuración Específica)

### HU-38: RECUPERAR CONTRASEÑA (CLIENTE)
* **Nombre:** RECUPERAR CONTRASEÑA
* **Como:** Usuario Cliente
* **Puedo:** solicitar un enlace seguro de recuperación ingresando mi correo electrónico registrado.
* **Para:** restablecer mi clave de acceso y no perder el historial de reparaciones de mis vehículos.
* **Dado que:** olvidé mi contraseña y el sistema me impide iniciar sesión en la plataforma.
* **Cuando:** presiono el enlace "Olvidé mi contraseña" en la pantalla de Login y envío el formulario.
* **Entonces:** el sistema genera un token de un solo uso y me envía un correo electrónico para crear una nueva clave.

### HU-39: RECUPERAR CONTRASEÑA (MECÁNICO)
* **Nombre:** RECUPERAR CONTRASEÑA
* **Como:** Usuario Mecánico
* **Puedo:** solicitar un enlace seguro de recuperación ingresando el correo de mi taller.
* **Para:** restablecer mi clave de acceso y no perder la comunicación con los clientes que tienen turnos agendados.
* **Dado que:** olvidé mi contraseña y no puedo acceder a mi panel de trabajo.
* **Cuando:** presiono el enlace "Olvidé mi contraseña" en el Login para Profesionales y envío el formulario.
* **Entonces:** el sistema verifica mi identidad y me envía las instrucciones de recuperación al correo registrado.

### HU-40: RECUPERAR CONTRASEÑA (ADMINISTRADOR)
* **Nombre:** RECUPERAR CONTRASEÑA
* **Como:** Usuario Administrador
* **Puedo:** solicitar el blanqueo de mi clave maestra a través de un protocolo de seguridad de doble factor.
* **Para:** recuperar el control central del sistema sin comprometer la seguridad de la base de datos.
* **Dado que:** olvidé mi credencial de acceso al panel de Backoffice.
* **Cuando:** ejecuto el proceso de recuperación en la ruta de administración.
* **Entonces:** el sistema envía una alerta de seguridad y el enlace de recuperación a la casilla de correo corporativa.

### HU-41: EDITAR PERFIL DE USUARIO (CLIENTE)
* **Nombre:** EDITAR PERFIL
* **Como:** Usuario Cliente
* **Puedo:** modificar mis datos personales, como mi número de teléfono o correo electrónico.
* **Para:** asegurar que los mecánicos puedan contactarme correctamente ante cualquier emergencia con mi vehículo.
* **Dado que:** cambié mi número de celular y mi información de contacto anterior quedó obsoleta.
* **Cuando:** ingreso a la sección "Configuración de Perfil", edito el campo telefónico y presiono "Guardar cambios".
* **Entonces:** el sistema actualiza mis datos de contacto permanentemente en la base de datos.

### HU-42: EDITAR PERFIL DE TALLER (MECÁNICO)
* **Nombre:** EDITAR PERFIL DE TALLER
* **Como:** Usuario Mecánico
* **Puedo:** modificar la descripción de mi negocio, actualizar mi dirección o agregar nuevas especialidades a mi catálogo.
* **Para:** mantener mi oferta de servicios actualizada y no perder clientes si mi taller cambia de ubicación.
* **Dado que:** me mudé a un local nuevo o adquirí herramientas para ofrecer un servicio distinto.
* **Cuando:** ingreso a "Editar Perfil Comercial", modifico la dirección o selecciono nuevas etiquetas y guardo los cambios.
* **Entonces:** el catálogo público se actualiza inmediatamente mostrando mi nueva información a los clientes.

### HU-43: GESTIONAR GARAJE (ELIMINAR VEHÍCULO)
* **Nombre:** GESTIONAR GARAJE (ELIMINAR VEHÍCULO)
* **Como:** Usuario Cliente
* **Puedo:** dar de baja u ocultar un vehículo que había registrado previamente en mi cuenta.
* **Para:** mantener mi lista limpia si vendí el auto y ya no requiero servicios para él.
* **Dado que:** acabo de vender mi vehículo y ya no me corresponde gestionar sus reparaciones.
* **Cuando:** presiono el icono de "Eliminar" junto al auto en la sección "Mi Garaje".
* **Entonces:** el vehículo deja de aparecer como opción al solicitar un turno.

### HU-44: CANCELAR TURNO PROGRAMADO (CLIENTE)
* **Nombre:** CANCELAR TURNO PROGRAMADO
* **Como:** Usuario Cliente
* **Puedo:** anular un turno previamente agendado antes de la fecha de ingreso al taller.
* **Para:** avisar con anticipación que no asistiré y evitar una calificación negativa por ausencia.
* **Dado que:** tuve un imprevisto personal o mi auto no arranca para llevarlo en el día pactado.
* **Cuando:** ingreso a mis turnos pendientes y presiono "Cancelar Turno" detallando el motivo.
* **Entonces:** el turno se anula y el mecánico recibe una notificación inmediata liberando su agenda.

### HU-45: CANCELAR TURNO PROGRAMADO (MECÁNICO)
* **Nombre:** CANCELAR TURNO PROGRAMADO
* **Como:** Usuario Mecánico
* **Puedo:** anular un turno previamente confirmado antes de recibir físicamente el vehículo.
* **Para:** no dejar al cliente esperando frente a un imprevisto de fuerza mayor en mi taller (ej: corte de luz, enfermedad).
* **Dado que:** tuve una emergencia en el local y no podré operar en el día pactado.
* **Cuando:** ubico el turno en mi calendario y presiono "Cancelar Turno" indicando la razón.
* **Entonces:** el espacio se libera, el sistema notifica al cliente y le sugiere reprogramar o buscar otro profesional.

### HU-46: VISUALIZAR NOTIFICACIONES (CLIENTE)
* **Nombre:** VISUALIZAR NOTIFICACIONES
* **Como:** Usuario Cliente
* **Puedo:** acceder a un historial (icono de campana) con alertas sobre cambios de estado en mi auto o presupuestos extra.
* **Para:** enterarme de forma rápida de las novedades de mi reparación sin revisar manualmente la bitácora.
* **Dado que:** el mecánico actualizó el diagnóstico mientras yo no tenía la aplicación abierta.
* **Cuando:** presiono el icono de la campana en la barra superior de la pantalla.
* **Entonces:** se despliega una lista cronológica con las alertas y los enlaces directos a mi orden de trabajo.

### HU-47: VISUALIZAR NOTIFICACIONES (MECÁNICO)
* **Nombre:** VISUALIZAR NOTIFICACIONES
* **Como:** Usuario Mecánico
* **Puedo:** acceder a un panel de alertas centralizado (icono de campana) para ver nuevas solicitudes de turnos o respuestas de clientes a los presupuestos.
* **Para:** gestionar eficientemente mi demanda sin tener que revisar cada chat individualmente.
* **Dado que:** un cliente nuevo me contactó o aprobó un arreglo extra mientras yo estaba trabajando.
* **Cuando:** toco la campana de notificaciones en mi panel de control.
* **Entonces:** el sistema me muestra las últimas interacciones pendientes de lectura.




vista de admin clientes, mapa de calor, estadisticas 

