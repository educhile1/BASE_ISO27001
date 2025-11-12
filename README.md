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
      
      5. Gestión de Incidentes de Seguridad (A.5.24 - A.5.28)
      Prepara a la organización para cuando algo malo ocurra.
      
      A.5.24 Planificación y preparación: Tener un plan de respuesta a incidentes antes de que ocurran.
      
      A.5.25 Evaluación de eventos de seguridad: Decidir si una alerta es realmente un incidente o un falso positivo.
      
      A.5.26 Respuesta a incidentes de seguridad: Las acciones a tomar durante un ciberataque (contener, erradicar, recuperar).
      
      A.5.28 Recolección de evidencia: Preservar la evidencia digital (forense) de manera adecuada.
      
      6. Continuidad del Negocio (A.5.29 - A.5.30)
      Asegura que la organización pueda seguir operando durante un desastre.
      
      A.5.29 Planificación de la continuidad: El plan general de continuidad del negocio (BCP).
      
      A.5.30 Preparación de las TIC para la continuidad (¡Nuevo en 2022!): Se enfoca específicamente en la parte tecnológica (TI) de la continuidad, como los planes de recuperación ante desastres (DRP) y las copias de seguridad.
      
      7. Cumplimiento y Auditoría (A.5.31 - A.5.37)
      Verifica que estás cumpliendo con las reglas internas y externas.
      
      A.5.31 Requisitos legales, regulatorios y contractuales: Identificar y mantener actualizada la lista de leyes que debes cumplir.
      
      A.5.34 Privacidad y protección de PII (Datos Personales): Controles específicos para cumplir con leyes de privacidad (como GDPR, LGPD, etc.).
      
      A.5.35 Revisión independiente: Auditorías internas o externas para verificar el cumplimiento.
      
      A.5.37 Procedimientos operativos documentados: Asegurarse de que las tareas críticas de TI y seguridad estén escritas y se sigan.
--



A.6 Controles de Personas (8 controles)

Ejemplos: Verificación de antecedentes (screening), formación y concienciación, proceso disciplinario, teletrabajo.

A.7 Controles Físicos (14 controles)

Ejemplos: Perímetros de seguridad, control de acceso físico, seguridad de escritorios limpios, protección contra amenazas ambientales.

A.8 Controles Tecnológicos (34 controles)

Ejemplos: Gestión de acceso lógico (usuarios y contraseñas), cifrado, copias de seguridad, protección contra malware, gestión de vulnerabilidades, seguridad de redes.

En resumen: Las Cláusulas 4-10 te dicen cómo construir y gestionar el sistema (el "motor" del SGSI), mientras que el Anexo A te da el catálogo de herramientas de seguridad (los controles) que puedes usar para proteger tu información.
