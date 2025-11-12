# BASE ISO 27001
Base para implementar ISO 27001

## Cláusulas 0 a 3 son la base o el prólogo de la norma.

No son requisitos auditables (es decir, un auditor no te va a poner una "no conformidad" por no cumplir la Cláusula 1), sino que establecen el contexto, el vocabulario y las reglas del juego para que puedas entender y aplicar el resto de la norma (del 4 al 10).



Cláusula 0: Introducción

Explica el propósito de la norma (ayudar a las organizaciones a gestionar la seguridad de su información).

Presenta el modelo en el que se basa: PDCA (Planificar-Hacer-Verificar-Actuar) o PHVA en español.

Aclara cómo se relaciona con otras normas de la familia 27000.

Cláusula 1: Objeto y campo de aplicación

Define formalmente qué hace esta norma: "especificar los requisitos para establecer, implementar, mantener y mejorar continuamente un Sistema de Gestión de Seguridad de la Información (SGSI)".

Establece que es genérica y aplicable a cualquier tipo de organización, sin importar su tamaño o sector.

Cláusula 2: Referencias normativas

Es la "bibliografía" de la norma.

Menciona otro documento que es indispensable para entender esta norma: la ISO/IEC 27001, que contiene el vocabulario y las definiciones fundamentales.

Cláusula 3: Términos y definiciones

Es el "glosario" o "diccionario" de la norma.

Define los términos clave para que todos entiendan lo mismo al leer el documento. Aunque la mayoría de las definiciones están en la ISO 27001 (mencionada en la Cláusula 2), aquí se reafirman o listan las más críticas.





En resumen: no te auditan contra las cláusulas 0-3, pero son de lectura obligatoria para poder entender y aplicar correctamente las cláusulas 4-10, que sí son los requisitos auditables.







## Cláusulas 4-10 (Requisitos del SGSI)
Estas son las cláusulas centrales que definen qué debe hacer la organización para construir y gestionar su sistema de seguridad. Las cláusulas 0 a 3 son introductorias (Objeto, Referencias y Términos). Los requisitos auditables comienzan en la 4.

Cláusula 4: Contexto de la organización

Implica comprender la propia organización, sus necesidades y expectativas, y las de las partes interesadas (clientes, reguladores, etc.).

Define el alcance del SGSI (qué partes de la empresa estarán cubiertas).

Cláusula 5: Liderazgo

Requiere el compromiso total de la alta dirección.

Establece la Política de Seguridad de la Información.

Define roles, responsabilidades y autoridades dentro del SGSI.

Cláusula 6: Planificación

Esta es una cláusula crucial. Incluye:

La evaluación y tratamiento de riesgos de seguridad de la información.

La definición de objetivos de seguridad y cómo se lograrán.

La planificación de cambios en el SGSI.

Cláusula 7: Soporte (Apoyo)

Se centra en los recursos necesarios para que el SGSI funcione.

Cubre la competencia del personal, la concienciación, la comunicación y la información documentada (gestión de documentos y registros).

Cláusula 8: Operación

Es la ejecución de lo planificado en la Cláusula 6.

Implica llevar a cabo la evaluación de riesgos y aplicar los tratamientos de riesgos (los controles).

Gestionar los cambios operativos de forma segura.

Cláusula 9: Evaluación del desempeño

Define cómo medir si el SGSI está funcionando bien.

Incluye el seguimiento y medición, las auditorías internas y la revisión por la dirección.

Cláusula 10: Mejora

Se basa en el ciclo "Planificar-Hacer-Verificar-Actuar" (PDCA).

Establece cómo gestionar las no conformidades (incidentes, fallos de auditoría), aplicar acciones correctivas y buscar la mejora continua del SGSI.



## Anexo A (Referencia de Controles de Seguridad)
A menudo, cuando la gente habla de ISO 27001, piensa en esta lista. El Anexo A no es una lista de requisitos obligatorios uno por uno; es un catálogo de posibles controles que seleccionas según tu evaluación de riesgos (Cláusula 6).

En la versión 2022, estos 93 controles se agrupan en 4 "temas" o dominios (en lugar de los 14 de la versión 2013):

A.5 Controles Organizacionales (37 controles)

Ejemplos: Políticas de seguridad, gestión de activos, seguridad en la nube, clasificación de la información.

-- 1. Políticas y Gobernanza (A.5.1 - A.5.8)
      Este grupo define las reglas y la dirección desde la alta gerencia.
      
      A.5.1 Políticas para la seguridad de la información: El documento principal (la "Constitución" de tu seguridad) aprobado por la dirección.
      
      A.5.2 Roles y responsabilidades: Define quién es responsable de qué (ej. CISO, dueños de activos, etc.).
      
      A.5.3 Segregación de funciones: Evita que una sola persona tenga demasiado control (ej. quien aprueba un pago no puede ser quien lo emite).
      
      A.5.5 Contacto con autoridades: Cómo y cuándo contactar a la policía, reguladores, etc.
      
      A.5.7 Inteligencia de amenazas (¡Nuevo en 2022!): Requiere que la organización recopile y analice activamente información sobre amenazas relevantes.
      
      A.5.8 Seguridad en la gestión de proyectos: Asegura que la seguridad se incluya en cualquier proyecto, desde el inicio.
      
-- 2. Gestión de Activos y Datos (A.5.9 - A.5.13)
      Se centra en saber qué tienes y cómo debes protegerlo.
      
      A.5.9 Inventario de información y otros activos: Tienes que saber qué información y qué hardware/software posees.
      
      A.5.10 Uso aceptable de los activos: Reglas para los empleados sobre cómo pueden (y no pueden) usar los equipos y la información de la empresa.
      
      A.5.12 Clasificación de la información: Definir niveles como "Público", "Interno", "Confidencial" o "Restringido".
      
      A.5.13 Etiquetado de la información: Marcar físicamente (o digitalmente) los documentos y datos según su clasificación.
      
-- 3. Gestión de Identidad y Acceso (A.5.14 - A.5.18)
      Controla quién puede ver y modificar qué.
      
      A.5.15 Control de acceso: La política general sobre cómo se otorga, revisa y revoca el acceso.
      
      A.5.16 Gestión de identidad: El proceso completo de crear, gestionar y eliminar usuarios (ciclo de vida del usuario).
      
      A.5.17 Información de autenticación: Reglas para contraseñas, tokens, MFA (múltiple factor de autenticación), etc.
      
      A.5.18 Gestión de derechos de acceso privilegiado: Controles especiales para las cuentas de "Administrador" o "root".
      
-- 4. Proveedores y Nube (A.5.19 - A.5.23)
      Gestiona el riesgo que proviene de terceros que manejan tus datos.
      
      A.5.19 Seguridad en las relaciones con proveedores: Establecer requisitos de seguridad en los contratos.
      
      A.5.21 Gestión de la seguridad en la cadena de suministro: Evaluar la seguridad de tus proveedores críticos.
      
      A.5.23 Seguridad en el uso de servicios en la nube (¡Nuevo en 2022!): Políticas específicas para proteger la información que está en plataformas como AWS, Azure, Google Cloud, SaaS, etc.
      
-- 5. Gestión de Incidentes de Seguridad (A.5.24 - A.5.28)
      Prepara a la organización para cuando algo malo ocurra.
      
      A.5.24 Planificación y preparación: Tener un plan de respuesta a incidentes antes de que ocurran.
      
      A.5.25 Evaluación de eventos de seguridad: Decidir si una alerta es realmente un incidente o un falso positivo.
      
      A.5.26 Respuesta a incidentes de seguridad: Las acciones a tomar durante un ciberataque (contener, erradicar, recuperar).
      
      A.5.28 Recolección de evidencia: Preservar la evidencia digital (forense) de manera adecuada.
      
--   6. Continuidad del Negocio (A.5.29 - A.5.30)
      Asegura que la organización pueda seguir operando durante un desastre.
      
      A.5.29 Planificación de la continuidad: El plan general de continuidad del negocio (BCP).
      
      A.5.30 Preparación de las TIC para la continuidad (¡Nuevo en 2022!): Se enfoca específicamente en la parte tecnológica (TI) de la continuidad, como los planes de recuperación ante desastres (DRP) y las copias de seguridad.
      
--   7. Cumplimiento y Auditoría (A.5.31 - A.5.37)
      Verifica que estás cumpliendo con las reglas internas y externas.
      
      A.5.31 Requisitos legales, regulatorios y contractuales: Identificar y mantener actualizada la lista de leyes que debes cumplir.
      
      A.5.34 Privacidad y protección de PII (Datos Personales): Controles específicos para cumplir con leyes de privacidad (como GDPR, LGPD, etc.).
      
      A.5.35 Revisión independiente: Auditorías internas o externas para verificar el cumplimiento.
      
      A.5.37 Procedimientos operativos documentados: Asegurarse de que las tareas críticas de TI y seguridad estén escritas y se sigan.
--



A.6 Controles de Personas (8 controles)

Ejemplos: Verificación de antecedentes (screening), formación y concienciación, proceso disciplinario, teletrabajo.


¡Claro! El dominio A.6 Controles de Personas es breve pero fundamental. Se centra en el "factor humano" de la seguridad, reconociendo que las personas pueden ser tanto el activo más fuerte como el eslabón más débil.

Los 8 controles de este dominio cubren todo el ciclo de vida de un empleado o contratista en la organización:

-- 1. Antes de la Contratación
El objetivo es reducir el riesgo antes de que alguien tenga acceso a la información.

            A.6.1 Selección (Screening)

            Qué es: Es la verificación de antecedentes de los candidatos a un puesto, especialmente para roles sensibles (como administradores de sistemas, finanzas o directivos).

            Ejemplo: Comprobar referencias laborales, verificar títulos académicos o revisar antecedentes penales (siempre de acuerdo con la ley local y las normas de privacidad).

-- 2. Durante el Empleo
Aquí se busca asegurar que las personas entiendan sus responsabilidades y actúen de forma segura en el día a día.

            A.6.2 Términos y condiciones de empleo

            Qué es: Asegurarse de que las responsabilidades de seguridad estén claramente definidas en los contratos de trabajo o acuerdos de confidencialidad (NDA).

            Ejemplo: El contrato debe decir explícitamente que el empleado debe cumplir con las políticas de seguridad de la empresa y proteger la información confidencial.

            A.6.3 Concienciación, educación y formación en seguridad

            Qué es: El pilar central de la seguridad humana. Es el programa continuo para educar a todos sobre los riesgos.

            Ejemplo: Capacitaciones anuales obligatorias, simulacros de phishing, boletines informativos sobre nuevas amenazas, etc.

            A.6.4 Proceso disciplinario

            Qué es: Tener un proceso formal y comunicado para sancionar a quienes violen (intencionalmente o no) las políticas de seguridad.

            Ejemplo: Desde una advertencia verbal por dejar la pantalla desbloqueada hasta el despido por robar datos de clientes.

            A.6.5 Responsabilidades después del cese o cambio de empleo

            Qué es: Define las obligaciones de seguridad que continúan incluso después de que la persona deja la empresa.

            Ejemplo: La obligación de no divulgar secretos comerciales o devolver toda la propiedad de la empresa sigue vigente después del despido o renuncia.

-- 3. Cese y Gestión de Cambios
Estos controles gestionan la transición segura de las personas al salir de la empresa o cambiar de rol.

      A.6.6 Acuerdos de confidencialidad o no divulgación (NDA)

      Qué es: Documentos legales donde empleados o terceros (consultores, proveedores) se comprometen a no revelar información sensible de la empresa.

      A.6.7 Trabajo remoto (Teletrabajo)

      Qué es: Establece las reglas de seguridad específicas para las personas que trabajan desde fuera de la oficina.

      Ejemplo: Exigir el uso de VPN, asegurar la red Wi-Fi de la casa, política de pantalla limpia en el hogar (que la familia no vea datos de clientes), etc.

      A.6.8 Notificación de eventos de seguridad de la información

      Qué es: Un control que obliga a todo el personal a reportar cualquier cosa sospechosa que vea, de forma inmediata.

      Ejemplo: Instruir a los empleados para que llamen a la mesa de ayuda inmediatamente si reciben un correo de phishing o si creen que su máquina tiene un virus, en lugar de borrarlo o ignorarlo.

--

A.7 Controles Físicos (14 controles)
--
1. Perímetros y Puntos de Entrada (A.7.1 - A.7.4)
El objetivo es detener a un intruso antes de que entre al edificio o a las áreas sensibles.

            A.7.1 Perímetros de seguridad física:

            Qué es: Define una "barrera" alrededor de las instalaciones de la empresa.

            Ejemplo: Muros, vallas, recepcionistas, puertas de entrada controladas, o incluso la propia pared de la oficina si está dentro de un edificio compartido.

            A.7.2 Controles de entrada física:

            Qué es: Cómo se controla quién pasa por ese perímetro.

            Ejemplo: Guardias de seguridad, puertas con tarjeta de acceso (magnética, RFID), torniquetes, o un sistema de intercomunicación con cámara.

            A.7.3 Seguridad de oficinas, despachos y recursos:

            Qué es: Reglas para asegurar áreas específicas dentro del perímetro.

            Ejemplo: Mantener las oficinas cerradas con llave fuera del horario laboral, no dejar a las visitas solas en áreas sensibles.

            A.7.4 Supervisión de la seguridad física:

            Qué es: Detectar y monitorear intentos de acceso no autorizados.

            Ejemplo: Cámaras de seguridad (CCTV), sensores de movimiento, alarmas de intrusión y el personal que vigila esos monitores.

2. Áreas Seguras (A.7.5 - A.7.6)
Estos controles se aplican a zonas de alta sensibilidad dentro del edificio, como los centros de datos (salas de servidores).

            A.7.5 Protección contra amenazas externas y ambientales:

            Qué es: Proteger los equipos críticos de desastres naturales o provocados por el hombre.

            Ejemplo: Extintores de incendios (específicos para equipos electrónicos), sistemas de control de temperatura (aire acondicionado) para el data center, protección contra inundaciones.

            A.7.6 Trabajo en áreas seguras:

            Qué es: Reglas especiales que aplican solo en esas zonas de alta seguridad.

            Ejemplo: Prohibir la entrada con teléfonos móviles o cámaras al centro de datos, mantener un registro de quién entra y sale, no permitir comida o bebida.

3. Equipos y Activos (A.7.7 - A.7.12)
Aquí el foco pasa del edificio a los dispositivos específicos.

            A.7.7 Escritorio limpio y pantalla limpia:

            Qué es: Una política clave para evitar que la información quede expuesta.

            Ejemplo: Escritorio limpio: Guardar documentos confidenciales bajo llave al final del día. Pantalla limpia: Bloquear la computadora (ej. Windows + L) cada vez que te levantas del puesto.

            A.7.8 Emplazamiento y protección de equipos:

            Qué es: Colocar los equipos de forma que se reduzca el riesgo.

            Ejemplo: Poner los servidores en un rack cerrado con llave, no ubicar una impresora con informes confidenciales al lado del baño, orientar los monitores de RRHH lejos de las visitas.

            A.7.10 Seguridad de los activos fuera de las instalaciones:

            Qué es: Reglas para proteger los equipos cuando salen de la oficina.

            Ejemplo: Políticas de seguridad para laptops (cifrado de disco obligatorio), no dejar la laptop a la vista en el auto, usar guayas de seguridad en conferencias.

            A.7.12 Eliminación segura o reutilización de equipos:

            Qué es: Asegurarse de que no queden datos en los equipos antes de botarlos, venderlos o reasignarlos.

            Ejemplo: Usar software de borrado seguro (Wiping) o destruir físicamente los discos duros viejos.

4. Infraestructura de Soporte (A.7.13 - A.7.14)
Se centra en los "cables y tuberías" que hacen funcionar la tecnología.

            A.7.13 Seguridad del cableado:

            Qué es: Proteger el cableado de red y de alimentación contra daños o pinchazos (intercepción de datos).

            Ejemplo: Usar canaletas para los cables, separar los cables de datos de los de electricidad, asegurar las cajas de conexión de red en las paredes.

            A.7.14 Mantenimiento de equipos:

            Qué es: Gestionar el mantenimiento (tanto interno como de terceros) de forma segura.

            Ejemplo: Revisar que el técnico que viene a reparar la fotocopiadora sea quien dice ser, y supervisarlo para que no acceda a información confidencial.

--


Ejemplos: Perímetros de seguridad, control de acceso físico, seguridad de escritorios limpios, protección contra amenazas ambientales.

A.8 Controles Tecnológicos (34 controles)

Ejemplos: Gestión de acceso lógico (usuarios y contraseñas), cifrado, copias de seguridad, protección contra malware, gestión de vulnerabilidades, seguridad de redes.

En resumen: Las Cláusulas 4-10 te dicen cómo construir y gestionar el sistema (el "motor" del SGSI), mientras que el Anexo A te da el catálogo de herramientas de seguridad (los controles) que puedes usar para proteger tu información.
