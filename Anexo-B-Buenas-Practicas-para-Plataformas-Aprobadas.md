# ANEXO B - BUENAS PRACTICAS PARA PLATAFORMAS APROBADAS

**Del Protocolo de Seguridad, Confidencialidad y Ciberseguridad**  
**Organización:** Asociación Manos Abiertas  
**Referencia:** Protocolo §8.4, §8.6, §8.7, §8.9, §8.12, §17, §20

Este anexo brinda orientación práctica sobre el uso de plataformas aprobadas de comunicación, colaboración y conectividad, en línea con el Protocolo. No sustituye al Protocolo; aclara cómo usar estas herramientas de forma segura cuando estén autorizadas por la organización. La Persona Focal de Seguridad decide qué plataformas están aprobadas y puede restringir o añadir plataformas según el riesgo y el contexto legal.

---

## 1. PRINCIPIOS GENERALES

- **Aprobación:** Solo podrán utilizarse para trabajo con información Interna, Sensible o Altamente Sensible aquellas plataformas aprobadas explícitamente por la Persona Focal de Seguridad (y por el Gerente de Clínica cuando corresponda).
- **Adecuación al propósito:** Use la herramienta correcta para la finalidad correcta. Los datos Altamente Sensibles o identificables de pacientes no deben almacenarse ni intercambiarse en plataformas que no cumplan con los criterios del Protocolo (cifrado según §8.12, control de acceso, jurisdicción).
- **Minimizar el contenido:** Incluso en plataformas aprobadas, compartir solo lo mínimo necesario. Seguir los principios de comunicación con identidad mínima del §12.3 (p. ej. "Su cita es mañana a las 10:00 en [Clínica]" en lugar de información clínica).
- **Cuentas y dispositivos oficiales:** Cuando sea posible, utilizar cuentas y dispositivos administrados por la organización en lugar de personales para el trabajo de la clínica.
- **Autenticación:** Habilitar autenticación de dos factores en cada plataforma utilizada para el trabajo, conforme al §8.9. Se prefieren aplicaciones autenticadoras o tokens de hardware sobre SMS.
- **Actualizaciones y configuraciones:** Mantener aplicaciones y dispositivos actualizados; habilitar configuraciones de seguridad (bloqueo de pantalla, bloqueo de aplicación) como se describe a continuación.

---

## 2. GOOGLE WORKSPACE (GMAIL, GOOGLE DRIVE, GOOGLE SHEETS, ETC.)

**Cuándo puede aprobarse:** Para trabajo interno o de baja sensibilidad (políticas, materiales de capacitación, estadísticas no identificables, coordinación interna). Usar solo si la organización ha aprobado formalmente Google Workspace (o cuenta de Google) para trabajo y la Persona Focal de Seguridad ha evaluado la jurisdicción y los términos.

**Buenas prácticas:**

- **Cuentas:** Usar cuentas de Google administradas por la organización (`@sudominio`), no Gmail personal, para cualquier trabajo. No se permiten inicios de sesión compartidos; una persona por cuenta.
- **Autenticación de dos factores:** Habilitar 2FA en cada cuenta de Google usada para trabajo (véase §8.9).
- **Google Drive:**
  - **No** almacenar Datos Altamente Sensibles o datos identificables de pacientes (exportaciones de EMR, listas de pacientes, historias clínicas completas) en Google Drive, salvo que la organización lo haya aprobado explícitamente para esa finalidad, con permisos de carpetas apropiados, cifrado y revisión legal/jurisdiccional.
  - Para documentos Internos/Sensibles: usar unidades o carpetas compartidas con acceso estricto (solo personas nombradas que lo necesiten). Establecer el uso compartido como "Restringido" o "Solo la organización" cuando sea posible; evitar "Cualquier persona con el enlace".
  - No compartir enlaces a carpetas sensibles fuera de la organización sin autorización.
- **Google Sheets:**
  - **No** usar Google Sheets (u otros documentos de Google) como almacenamiento principal de datos identificables de pacientes o registros clínicos, salvo que la Persona Focal de Seguridad lo haya aprobado y el acceso esté limitado, registrado y cumpla con el Protocolo.
  - Si se usa para datos no identificables o agregados: restringir el acceso por correo electrónico; habilitar historial de versiones; evitar compartir públicamente o mediante enlaces abiertos.
- **Gmail:**
  - Usar solo para trabajo desde cuentas de la organización. No enviar por correo datos identificables de pacientes ni registros completos salvo que estén cifrados (p. ej. correo seguro aprobado o método de adjunto cifrado). Preferir redacción neutral en asunto y cuerpo.
  - Tener cuidado con el phishing: no hacer clic en enlaces sospechosos ni abrir adjuntos inesperados; reportar a la Persona Focal de Seguridad.
- **Cerrar sesión:** Cerrar sesión en computadoras compartidas o públicas; no permanecer con sesión iniciada en dispositivos que usted no controle.

**Limitaciones:** Los términos y el tratamiento de datos de Google dependen de la jurisdicción y del producto. Para datos clínicos/de pacientes Altamente Sensibles, el Protocolo generalmente exige sistemas evaluados y cifrados, con ubicación clara de datos y salvaguardas contractuales (§8.2, §8.6, §17). Usar Google solo para finalidades y tipos de datos aprobados explícitamente por la organización.

---

## 3. PROTON / PROTON MAIL (PROTONMAIL, PROTON DRIVE, PROTON CALENDAR)

**Cuándo puede aprobarse:** Proton ofrece cifrado de extremo a extremo y servicios centrados en la privacidad. Puede aprobarse para comunicaciones o almacenamiento Sensibles o, con configuración y política adecuadas, de forma limitada para información Altamente Sensible, sujeto a revisión de la Persona Focal de Seguridad y revisión legal (jurisdicción, términos).

**Buenas prácticas:**

- **Proton Mail:**
  - Usar cuentas Proton administradas por la organización si esta utiliza Proton. Habilitar 2FA (véase §8.9).
  - Usar para correo relacionado con el trabajo solo desde cuentas aprobadas. Para contenidos dirigidos a pacientes o sensibles, mantener los mensajes mínimos (§12.3) y evitar poner información clínica detallada en el cuerpo del correo; documentar la información clínicamente relevante en el expediente oficial.
  - El correo de Proton a Proton está cifrado de extremo a extremo; hacia destinatarios que no usan Proton, el cifrado depende de la configuración (p. ej. mensaje protegido con contraseña). Seguir la política de la organización sobre cuándo usar opciones cifradas para destinatarios externos.
- **Proton Drive:**
  - Si se aprueba para almacenar archivos de trabajo: usar contraseña robusta y 2FA; compartir solo con personas específicas y autorizadas; no usar para bases de datos masivas de pacientes o exportaciones de EMR salvo aprobación explícita bajo los mismos criterios del §17 (almacenamiento en la nube de datos clínicos).
- **Dispositivos:** Usar solo en dispositivos con bloqueo de pantalla, cifrado (§8.12) y sistema operativo actualizado. No compartir credenciales de cuenta.

**Limitaciones:** Incluso con cifrado, evitar almacenar bases de datos clínicas completas o listas identificables de pacientes en unidades en la nube, salvo que la organización haya evaluado y aprobado ese uso conforme al §8.6 y §17.

---

## 4. SIGNAL

**Cuándo puede aprobarse:** Signal suele aprobarse para comunicación entre personal y, cuando la política lo permita, con pacientes, debido a su cifrado de extremo a extremo y metadatos mínimos. Usar solo si la organización ha aprobado explícitamente Signal para uso de la clínica.

**Buenas prácticas:**

- **Dispositivos / números oficiales:** Preferir teléfonos o SIM administrados por la clínica para Signal cuando sea posible (§7.6). Si se usan dispositivos personales, deben estar autorizados y asegurados (bloqueo de pantalla, cifrado, actualizaciones).
- **Contenido:** Mantener los mensajes mínimos (§12.3): citas, hora, lugar, instrucciones básicas. No escribir historiales clínicos completos, diagnósticos ni detalles identificables en Signal; registrar eso en el expediente clínico oficial.
- **Configuraciones:** Habilitar bloqueo de pantalla y, si está disponible, bloqueo de aplicación o mensajes temporales para chats sensibles. Activar el bloqueo de registro (PIN) para prevenir el secuestro del número.
- **Grupos:** Usar grupos solo para personal autorizado; no añadir pacientes a grupos amplios. No discutir casos identificables de pacientes en chats grupales salvo que sea necesario y esté autorizado.
- **Respaldo:** Las copias de seguridad de Signal (si están habilitadas) pueden contener el contenido de los mensajes; almacenar respaldos solo en dispositivos cifrados y alinearlos con la política de retención de datos. Es preferible no depender del historial de chats a largo plazo para datos clínicos; transferir la información esencial al expediente oficial y limpiar o limitar el historial según la política.

**Limitaciones:** Signal no reemplaza al EMR ni al registro oficial. Es un canal de comunicación, no un almacén de datos clínicos.

---

## 5. WHATSAPP

**Cuándo puede aprobarse:** WhatsApp es ampliamente utilizado y ofrece cifrado de extremo a extremo. Puede aprobarse para recordatorios de citas y comunicación mínima y neutral con pacientes o entre personal, cuando la organización haya aceptado los términos, la jurisdicción y las implicaciones sobre metadatos (p. ej. quién se comunica con quién y cuándo).

**Buenas prácticas:**

- **Número comercial / de clínica oficial:** Preferir WhatsApp Business o un número dedicado de la clínica administrado por la organización, en lugar de números personales, para que la rotación de personal no deje contactos de pacientes en cuentas personales.
- **Contenido:** Igual que Signal: mensajes mínimos y neutrales (§12.3). No incluir diagnósticos detallados, resultados de pruebas ni narrativa clínica identificable en el chat; documentarlo en el expediente oficial.
- **Configuraciones:** Habilitar la verificación en dos pasos (`Configuración > Cuenta > Verificación en dos pasos`). Usar bloqueo de pantalla y, cuando esté disponible, bloqueo de aplicación. Restringir quién puede ver la foto de perfil y el estado si eso pudiera revelar afiliación con la clínica.
- **Grupos:** No usar grupos grandes o abiertos para comunicación con pacientes. En grupos solo de personal: no compartir información identificable de pacientes salvo que sea necesario y esté autorizado.
- **Respaldo:** La copia de seguridad de WhatsApp en Google Drive o iCloud **no** está cifrada de extremo a extremo por defecto. Si el respaldo está habilitado, tener presente que su contenido podría ser accesible al proveedor de nube. Es preferible no respaldar chats de trabajo en nubes personales, o deshabilitar el respaldo para números de trabajo si la política así lo exige. Si la opción de copia de seguridad cifrada de extremo a extremo de WhatsApp está disponible, habilitarla.
- **Metadatos:** WhatsApp (Meta) puede ver que hubo comunicación y entre qué números; el contenido está cifrado de extremo a extremo. En contextos de alto riesgo, la organización puede preferir Signal u otra plataforma aprobada; seguir la guía de la Persona Focal de Seguridad.

**Limitaciones:** WhatsApp es una herramienta de comunicación, no un lugar para almacenar datos clínicos. No conservar listas o registros de pacientes en WhatsApp; no usarlo como único registro de decisiones clínicas.

---

## 6. TELEGRAM

**Cuándo puede aprobarse:** Solo si la Persona Focal de Seguridad lo aprueba explícitamente para finalidades específicas y limitadas. Los chats predeterminados de Telegram ("Cloud Chats") **no** están cifrados de extremo a extremo; el proveedor puede acceder al contenido. Solo los "Secret Chats" usan cifrado de extremo a extremo, y los Secret Chats no están disponibles para grupos.

**Buenas prácticas:**

- Si la organización aprueba Telegram para cualquier comunicación de trabajo, usar **Secret Chats** para todas las conversaciones uno a uno que involucren temas Sensibles o Altamente Sensibles.
- Habilitar 2FA (`Configuración > Privacidad y seguridad > Verificación en dos pasos`).
- Habilitar un código de acceso en la aplicación (`Configuración > Privacidad y seguridad > Código de acceso`).
- Usar temporizadores de autodestrucción en Secret Chats para conversaciones sensibles.
- **No** usar grupos o canales de Telegram para compartir datos identificables de pacientes, registros clínicos o información operativa Sensible (los chats grupales no pueden usar cifrado Secret Chat).
- **No** usar Telegram como plataforma para compartir archivos o almacenar documentos de trabajo.
- Tener presente que Telegram almacena los datos de Cloud Chats en sus servidores; cualquier dato en chats no secretos es accesible para el proveedor y potencialmente para solicitudes legales en la jurisdicción de Telegram.

**Limitaciones:** Debido a la falta de E2EE por defecto y a las limitaciones del cifrado en grupos, Telegram suele ser menos adecuado que Signal para comunicaciones sensibles. Si ambas opciones están disponibles, preferir Signal.

---

## 7. MICROSOFT 365 (OUTLOOK, ONEDRIVE, TEAMS, SHAREPOINT)

**Cuándo puede aprobarse:** Para organizaciones que hayan adoptado formalmente Microsoft 365 como su suite de productividad, sujeto a revisión de la Persona Focal de Seguridad sobre licencias, jurisdicción, residencia de datos y configuración.

**Buenas prácticas:**

- **Cuentas:** Usar solo cuentas de Microsoft 365 administradas por la organización. No usar Outlook.com o Hotmail personales para el trabajo. No se permiten inicios de sesión compartidos.
- **Autenticación de dos factores:** Habilitar 2FA en todas las cuentas (véase §8.9). Si la organización utiliza Azure AD / Entra ID, aplicar MFA mediante políticas de acceso condicional cuando sea posible.
- **Outlook (correo):**
  - No enviar datos identificables de pacientes ni registros completos por correo salvo que estén cifrados (p. ej. cifrado de mensajes de Microsoft o adjunto cifrado aprobado). Usar lenguaje neutral en asuntos y cuerpo.
  - Reportar correos sospechosos mediante la función integrada de reporte de phishing o a la Persona Focal de Seguridad.
- **OneDrive y SharePoint:**
  - **No** almacenar Datos Altamente Sensibles o identificables de pacientes en OneDrive o SharePoint salvo que la Persona Focal de Seguridad lo haya aprobado conforme a los mismos criterios del §8.6 y §17 (cifrado, control de acceso, jurisdicción, salvaguardas contractuales).
  - Para documentos Internos/Sensibles: utilizar uso compartido restringido (solo personas específicas), no "Cualquier persona con el enlace". Habilitar versionado. Usar etiquetas de sensibilidad cuando estén disponibles.
- **Teams:**
  - Usar para coordinación interna, reuniones y comunicación no clínica. No compartir datos identificables de pacientes en chats o canales de Teams salvo que la organización haya aprobado Teams para esa finalidad con controles de acceso adecuados.
  - Para videocon­sultas (telemedicina): usar solo si está aprobado; habilitar contraseñas de reunión y salas de espera; no grabar sin consentimiento y sin política; si se graba, almacenar y eliminar conforme al Protocolo (§11).
  - Restringir el acceso de invitados a canales de Teams solo a colaboradores externos autorizados.
- **Cerrar sesión:** Cerrar sesión en computadoras compartidas o públicas; no permanecer con sesión iniciada en dispositivos que usted no controle.

**Limitaciones:** El tratamiento de datos y la jurisdicción en Microsoft 365 dependen del acuerdo de licenciamiento y de la configuración del tenant. La organización debe revisar el Anexo de Tratamiento de Datos y configurar la residencia de datos. Para datos clínicos/de pacientes Altamente Sensibles, el Protocolo exige sistemas evaluados y cifrados con salvaguardas claras (§17).

---

## 8. ZOOM Y VIDEOCONFERENCIA

**Cuándo puede aprobarse:** Para telemedicina, consultas remotas, reuniones de equipo y capacitación, sujeto a revisión de la Persona Focal de Seguridad.

**Buenas prácticas:**

- Usar cuentas de Zoom administradas por la organización (u otra plataforma equivalente aprobada), no cuentas personales gratuitas, para cualquier trabajo que involucre contacto con pacientes o información Sensible.
- Habilitar 2FA en la cuenta (véase §8.9).
- **Seguridad de la reunión:** Habilitar salas de espera para que las personas participantes sean admitidas solo por el anfitrión. Exigir contraseñas de reunión. Deshabilitar "Unirse antes que el anfitrión" para reuniones sensibles. Utilizar la sala de espera para verificar participantes.
- **Compartir pantalla:** Tener cuidado con lo visible en pantalla; cerrar aplicaciones y documentos no relacionados antes de compartir. No compartir pantallas con datos de pacientes salvo que sea clínicamente necesario y todas las personas participantes estén autorizadas.
- **Grabación:** No grabar consultas ni reuniones sin el consentimiento explícito de todas las personas participantes y conforme a la política de la organización. Si se graba: almacenar las grabaciones solo en almacenamiento aprobado y cifrado (no en dispositivos personales ni en nubes personales); eliminar las grabaciones cuando ya no sean necesarias, de acuerdo con el §11.
- **Chat:** No compartir información identificable de pacientes en el chat de la reunión. Los registros del chat pueden persistir después de la reunión; limpiar o eliminar si se compartió contenido sensible.
- **Cifrado de extremo a extremo:** Zoom ofrece E2EE para algunos tipos de reuniones; habilitarlo cuando esté disponible para consultas sensibles. Tener presente que el E2EE puede desactivar algunas funciones (p. ej. grabación en la nube, salas para grupos).

**Limitaciones:** La videoconferencia es una herramienta de comunicación; las decisiones clínicas y notas deben documentarse en el EMR oficial, no en chats ni grabaciones.

---

## 9. VPN (RED PRIVADA VIRTUAL)

**Cuándo es obligatoria:** El personal que acceda a sistemas de la clínica, EMR, correo electrónico o cualquier sistema que contenga datos Sensibles o Altamente Sensibles desde fuera de la red de la clínica u oficina debe usar la VPN aprobada por la organización (véase Protocolo §8.7).

**Buenas prácticas:**

- **Solo VPN aprobada:** Utilizar solo la VPN proporcionada o designada por la organización (p. ej. servidor VPN alojado por la organización, o proveedor comercial evaluado seleccionado por la Persona Focal de Seguridad). Los servicios VPN gratuitos o no evaluados están estrictamente prohibidos: muchos registran tráfico, insertan publicidad o son operados por entidades desconocidas.
- **Cuándo activarla:** Antes de acceder a cualquier sistema de trabajo (EMR, correo, almacenamiento en la nube, aplicaciones web) desde una red doméstica, hotel, datos móviles o cualquier red fuera de la clínica/oficina. La VPN debe conectarse antes de abrir la aplicación de trabajo y permanecer conectada durante toda la sesión.
- **Configuración:** La Persona Focal de Seguridad configura y distribuye las credenciales o perfiles de acceso VPN. El personal no modifica configuraciones VPN ni instala software VPN alternativo en dispositivos de trabajo.
- **Cifrado:** La VPN debe usar cifrado robusto (p. ej. WireGuard, OpenVPN con AES-256-GCM o IPsec con AES-256) conforme al §8.12.
- **Túnel dividido:** Si la VPN está configurada por la organización, seguir el perfil configurado. En caso de duda, usar modo de túnel completo (todo el tráfico a través de la VPN) cuando se manejen datos Sensibles o Altamente Sensibles.
- **Seguridad del dispositivo:** La VPN no sustituye otras medidas de seguridad del dispositivo (bloqueo de pantalla, cifrado, actualizaciones, antivirus). Ambas son obligatorias.
- **Resolución de problemas:** Si la conexión VPN falla, no acceder a sistemas Sensibles o Altamente Sensibles sin ella. Contactar a la Persona Focal de Seguridad para soporte. En una emergencia en la que la VPN no esté disponible y el acceso sea clínicamente crítico, el Gerente de Clínica o la Persona Focal de Seguridad debe autorizar y documentar la excepción.

**Limitaciones:** Una VPN protege los datos en tránsito entre el dispositivo y la red de la organización, pero no protege contra amenazas en el propio dispositivo (malware, keyloggers) ni contra una persona atacante con acceso físico al dispositivo. La VPN debe combinarse con las medidas de seguridad del dispositivo del §8.5.

---

## 10. REFERENCIA RÁPIDA: QUE VA DONDE

| Tipo de información | Preferido / aprobado | Evitar |
|---------------------|---------------------|--------|
| Datos identificables de pacientes, notas clínicas, registros | EMR oficial / sistema clínico aprobado; papel en almacenamiento cerrado con llave | Correo personal, Drive personal, WhatsApp/Signal como único registro, nube no aprobada, Telegram Cloud Chats |
| Recordatorios de citas (texto mínimo) | Mensajería aprobada (Signal, WhatsApp, etc.) con lenguaje neutral según §12.3 | Mensajes clínicos largos; SMS si no está cifrado y es sensible |
| Políticas internas, capacitación (Interna) | Almacenamiento organizacional aprobado (p. ej. Drive restringido, SharePoint, OneDrive) | Enlaces públicos; cuentas personales |
| Información operativa sensible (p. ej. planes de seguridad) | Acceso restringido, por necesidad de saber; cifrado cuando sea posible | Correo a cuentas personales; enlaces abiertos en la nube; Telegram Cloud Chats |
| Acceso remoto a sistemas de la clínica | VPN aprobada por la organización + dispositivo aprobado | WiFi abierto/público sin VPN; cibercafés; servicios VPN gratuitos |

---

## 11. CONTROL DOCUMENTAL

Este anexo forma parte del Protocolo. Se revisa al menos cada 12 meses y cuando se aprueban nuevas plataformas o cambian los riesgos. Las actualizaciones son aprobadas por el/la Director/a Ejecutivo/a y comunicadas por la Persona Focal de Seguridad y los Gerentes de Clínica.

*Fin del Anexo B - Buenas Practicas para Plataformas Aprobadas*
