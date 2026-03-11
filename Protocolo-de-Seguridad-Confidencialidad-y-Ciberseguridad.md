# PROTOCOLO DE SEGURIDAD, CONFIDENCIALIDAD Y CIBERSEGURIDAD



|---|---|
| **Versión** | 1.0 |
| **Aprobado el** | 15 de marzo de 2026 |
| **Próxima revisión** | 10 de marzo de 2027 |
| **Aplica a** | Todo el personal, voluntariado, contratistas y socios de Asociación Manos Abiertas |

Este Protocolo establece reglas obligatorias para la protección de la información y la seguridad de los sistemas utilizados por Asociación Manos Abiertas en la operación de sus clínicas y servicios.

---

## Índice

1. [Finalidad](#1-finalidad)
2. [Alcance y aplicabilidad](#2-alcance-y-aplicabilidad)
3. [Definiciones y glosario](#3-definiciones-y-glosario)
4. [Principios rectores](#4-principios-rectores)
5. [Clasificación de la información](#5-clasificación-de-la-información)
6. [Evaluación y mitigación de riesgos](#6-evaluación-y-mitigación-de-riesgos)
7. [Gobernanza y roles](#7-gobernanza-y-roles)
8. [Protección de la información en las operaciones diarias](#8-protección-de-la-información-en-las-operaciones-diarias)
9. [Control de acceso](#9-control-de-acceso)
10. [Registro y auditoría](#10-registro-y-auditoría)
11. [Retención y destrucción de datos](#11-retención-y-destrucción-de-datos)
12. [Derechos de los datos de pacientes, consentimiento y prestación con identidad mínima](#12-derechos-de-los-datos-de-pacientes-consentimiento-y-prestación-con-identidad-mínima)
13. [Solicitudes de información por autoridades o terceros](#13-solicitudes-de-información-por-autoridades-o-terceros)
14. [Respuesta a incidentes](#14-respuesta-a-incidentes)
15. [Continuidad operativa y preparación para crisis](#15-continuidad-operativa-y-preparación-para-crisis)
16. [Terceros y cadena de suministro](#16-terceros-y-cadena-de-suministro)
17. [Aplicaciones web y almacenamiento en la nube de datos clínicos](#17-aplicaciones-web-y-almacenamiento-en-la-nube-de-datos-clínicos)
18. [Reglas de conducta del personal](#18-reglas-de-conducta-del-personal)
19. [Capacitación e implementación](#19-capacitación-e-implementación)
20. [Herramientas mínimas de gestión (plantillas y listas de verificación)](#20-herramientas-mínimas-de-gestión-plantillas-y-listas-de-verificación)
21. [Revisión y control documental](#21-revisión-y-control-documental)

---

## 1. FINALIDAD

**1.1**  
Este Protocolo establece reglas obligatorias para la protección de la información gestionada por Asociación Manos Abiertas en la operación de sus clínicas de salud sexual y reproductiva (SSR) y servicios relacionados en entornos restrictivos y potencialmente hostiles.

**1.2**  
Los objetivos de este Protocolo son:

- Garantizar el cumplimiento de todas las obligaciones aplicables de registro, reporte y protección de datos.
- Proteger a pacientes, personal, socios y a la organización frente a daños, acoso, criminalización o uso indebido de datos.
- Definir procedimientos claros y prácticos para el manejo de datos identificables de SSR, incluso en situaciones de presión legal o política, ataques digitales y riesgo físico.
- Establecer medidas de ciberseguridad y mitigación de riesgos alineadas con buenas prácticas reconocidas (Marco de Ciberseguridad NIST, principios ISO/IEC 27001), adaptadas al contexto y a los recursos de la organización.

**1.3**  
Este Protocolo es vinculante. El incumplimiento puede dar lugar a medidas disciplinarias, terminación del contrato y, cuando se requiera, notificación a las autoridades competentes o a los organismos profesionales pertinentes.

---

## 2. ALCANCE Y APLICABILIDAD

**2.1**  
Este Protocolo aplica a todos los servicios relacionados con SSR prestados o apoyados por Asociación Manos Abiertas, incluidos, entre otros:

- Consultas y procedimientos clínicos.
- Consejería y apoyo psicosocial.
- Servicios de farmacia y laboratorio.
- Líneas de atención, telemedicina y consultas remotas.
- Clínicas móviles y alcance comunitario.
- Agregación de datos, monitoreo, evaluación y reporte.

**2.2**  
Abarca todas las formas de información, independientemente del medio:

- Registros y libros en papel.
- Historias clínicas electrónicas (EMR) y bases de datos.
- Hojas de cálculo, documentos e informes.
- Aplicaciones de mensajería, correos electrónicos, registros de llamadas.
- Libros de citas, hojas de asistencia, formularios de referencia y formularios de consentimiento.

**2.3**  
También abarca las medidas técnicas y organizativas que protegen dicha información: redes, dispositivos, servicios en la nube, herramientas de terceros y los procesos para evaluar riesgos, responder a incidentes y asegurar la continuidad operativa.

**2.4**  
Este Protocolo aplica a:

- Todo el personal empleado (clínico, administrativo, directivo, de apoyo, TI, seguridad).
- Voluntariado y personal en prácticas.
- Consultores y contratistas con cualquier nivel de acceso a información o sistemas de la clínica.
- Organizaciones socias que reciban o procesen datos de Asociación Manos Abiertas en virtud de cualquier acuerdo.

El cumplimiento de este Protocolo es una condición para acceder a cualquier información o sistema de la clínica.

---

## 3. DEFINICIONES Y GLOSARIO

| Término | Definición |
|------|-----------|
| **2FA / MFA** | Autenticación de dos factores / autenticación multifactor. Método de seguridad que requiere dos o más credenciales independientes (p. ej. contraseña más un código de una aplicación autenticadora) para verificar la identidad de una persona usuaria. |
| **AES-256** | Estándar de cifrado avanzado con longitud de clave de 256 bits. Algoritmo de cifrado ampliamente adoptado y altamente seguro utilizado para proteger datos en reposo. |
| **E2EE** | Cifrado de extremo a extremo. Método de comunicación en el que solo la persona remitente y la destinataria pueden leer el contenido; el proveedor del servicio no puede acceder a él. |
| **EMR** | Historia clínica electrónica. Sistema digital para almacenar y gestionar información clínica de pacientes. |
| **Cifrado en reposo** | Protección de los datos mientras están almacenados (en un disco, base de datos o copia de seguridad) mediante cifrado para que no puedan leerse sin la clave de descifrado correcta. |
| **Cifrado en tránsito** | Protección de los datos mientras se transmiten por una red (p. ej. entre un navegador y un servidor) mediante protocolos como TLS. |
| **Datos Altamente Sensibles** | Información clasificada en el §5.4 de este Protocolo: cualquier registro que vincule la identidad de una persona con consultas, tratamientos o servicios relacionados con SSR. |
| **NIST** | Instituto Nacional de Estándares y Tecnología (EE. UU.). Publica marcos y estándares de ciberseguridad ampliamente utilizados. |
| **ISO/IEC 27001** | Norma internacional para sistemas de gestión de seguridad de la información (SGSI). |
| **OWASP** | Proyecto Abierto de Seguridad de Aplicaciones Web. Organización sin fines de lucro que produce guías y herramientas para la seguridad de aplicaciones web. |
| **Seudonimización** | Sustitución de información directamente identificable (p. ej. nombre) por un código o alias, de modo que los datos no puedan vincularse a una persona específica sin acceso a una clave separada. |
| **SaaS** | Software como Servicio. Software alojado en la nube y accesible por internet en lugar de estar instalado localmente. |
| **TLS** | Seguridad de la capa de transporte. Protocolo criptográfico que proporciona cifrado en tránsito; TLS 1.2 o superior es el estándar mínimo actual. |
| **VLAN** | Red de área local virtual. Método para segmentar una red física en redes lógicas aisladas con el fin de restringir el tráfico entre ellas. |
| **VPN** | Red privada virtual. Tecnología que crea un túnel cifrado entre un dispositivo y una red, protegiendo los datos en tránsito y ocultando la actividad de red de la persona usuaria frente a observadores locales. |

---

## 4. PRINCIPIOS RECTORES

**4.1 Cumplimiento legal con protección**  
La organización cumple plenamente con las leyes y regulaciones aplicables sobre historias clínicas, reportes y deberes profesionales, al tiempo que aplica todas las salvaguardas legalmente disponibles para proteger la confidencialidad de los pacientes y la seguridad del personal.

**4.2 Reconocimiento del riesgo**  
La organización reconoce la importancia de resguardar el historial clínico en general como parte fundamental del deber de confidencialidad y de la mitigación de riesgos para pacientes y personal, independientemente del tipo de atención. Todas las decisiones sobre el manejo de la información deben tener esto en cuenta.

**4.3 Documentación obligatoria**  
Cuando la ley exija la recopilación de identificadores específicos y detalles clínicos, esos requisitos se cumplirán. Las medidas de protección se centran en cómo se estructuran, almacenan, acceden, registran y divulgan los datos.

**4.4 Acceso por necesidad de saber**  
La información identificable de pacientes solo será accesible para personas que la requieran para desempeñar su función. La curiosidad, el interés personal o la presión política nunca son razones válidas.

**4.5 Minimización de datos**  
La organización recopila y conserva solo la información personal y clínica mínima necesaria para la atención, el cumplimiento legal y el reporte autorizado. Siempre que sea posible, los servicios se prestan con exposición reducida de identidad, como se describe en el §12.3.

---

## 5. CLASIFICACIÓN DE LA INFORMACIÓN

Para orientar las medidas de protección, Asociación Manos Abiertas clasifica la información de la siguiente manera:

**5.1 Pública**  
Comunicaciones públicas aprobadas, materiales IEC, estadísticas anonimizadas autorizadas para publicación.

**5.2 Interna**  
Políticas internas, materiales de capacitación, documentos operativos no sensibles.  
*Acceso:* disponible para el personal según necesidad; no se comparte externamente sin autorización.

**5.3 Sensible**  
Datos personales de contacto del personal; planes de seguridad y evaluaciones de riesgo; estadísticas no identificables pero políticamente sensibles (p. ej. servicios relacionados con temas bajo ataque público o político).  
*Acceso:* restringido a los equipos pertinentes; almacenado de forma segura.

**5.4 Altamente Sensible - Datos clínicos y vinculados a la identidad**  
Todo lo siguiente se clasifica como Altamente Sensible y recibe máxima protección:

- Cualquier registro que vincule la identidad de una persona (nombre, número de identificación, teléfono, dirección, usuario de redes sociales, etc.) con:
  - Consultas y tratamientos de SSR.
  - Uso de anticonceptivos, anticoncepción de emergencia.
  - Información relacionada con aborto (legal, postaborto, complicaciones).
  - Estado serológico VIH/ITS, pruebas y tratamiento.
  - Atención o identidad relacionada con LGBTQI+.
  - Servicios de SSR para adolescentes.
- Notas clínicas completas, resultados de laboratorio, recetas, cartas de referencia.
- Listas de citas u hojas de asistencia que identifiquen a personas como usuarias de la clínica cuando ese hecho en sí mismo implique riesgo.

*Acceso:* estrictamente basado en roles, registrado y controlado.

---

## 6. EVALUACIÓN Y MITIGACIÓN DE RIESGOS

**6.1 Evaluación de riesgos (mínimo una vez al año)**  
La organización realiza una evaluación estructurada de riesgos al menos una vez al año y después de cualquier incidente grave o cambio legal u operativo importante. El proceso incluye:

- **Identificar:** Enumerar activos (datos, sistemas, expedientes en papel, personal, instalaciones) y amenazas relevantes para el contexto (p. ej. presión legal o estatal, actores hostiles, criminalización de servicios; robo, pérdida o incautación de dispositivos y expedientes en papel; amenazas digitales como hackeo, phishing, malware, ransomware, vigilancia; riesgo interno).
- **Evaluar:** Para cada riesgo significativo, estimar probabilidad e impacto (p. ej. bajo / medio / alto). Priorizar los riesgos que puedan perjudicar a pacientes o personal o comprometer Datos Altamente Sensibles.
- **Tratar:** Para cada riesgo prioritario, definir uno o más controles: mitigar (reducir probabilidad o impacto); aceptar (aceptación documentada por la dirección cuando la mitigación no sea factible); transferir (p. ej. seguro, cláusulas contractuales); o evitar (discontinuar la actividad si el riesgo es inaceptable).
- **Monitorear:** Revisar y actualizar en consecuencia la evaluación de riesgos y el registro de riesgos.

**6.2 Registro de riesgos**  
Se mantiene un registro de riesgos (p. ej. una hoja de cálculo o tabla simple) con al menos: ID de Riesgo; Descripción; Probabilidad; Impacto; Mitigación / Control; Responsable; Estado; Última Revisión. Se actualiza cuando aparecen nuevos riesgos o cambian los controles. La Persona Focal de Seguridad apoya a la Directora Ejecutiva o al Director/a País en su mantenimiento y revisión.

---

## 7. GOBERNANZA Y ROLES

**7.1 Directora Ejecutiva / Director/a País**

- Aprueba este Protocolo y cualquier excepción.
- Designa a: Persona Focal Legal (puede ser asesoría externa); Persona Focal de Seguridad (puede ser TI u operaciones con mandato de seguridad).
- Autoriza las respuestas a solicitudes de información complejas o de alto riesgo por parte de autoridades.
- Asegura que la evaluación y el registro de riesgos se revisen y tengan apropiación a nivel de liderazgo.

**7.2 Gerente de Clínica**

- Asegura la implementación de este Protocolo en su establecimiento.
- Mantiene: almacenamiento seguro de expedientes en papel; lista de personas usuarias autorizadas para sistemas; inventario de dispositivos.
- Asegura inducción, refuerzos y supervisión rutinaria sobre cumplimiento.
- Sirve como primer punto de escalamiento para incidentes en sitio.

**7.3 Persona Focal de Seguridad / Responsable de TI**

- Diseña y supervisa cifrado, contraseñas, copias de seguridad, controles de acceso, seguridad de red, gestión de parches.
- Crea, modifica y revoca cuentas de usuario.
- Monitorea los registros cuando están disponibles.
- Lidera la respuesta técnica ante incidentes (sospecha de hackeo, malware, phishing, ransomware, etc.).
- Mantiene el inventario de dispositivos, apoya las pruebas de respaldo y recuperación y realiza revisiones periódicas de seguridad que cubren las áreas enumeradas en el §20.

**7.4 Personal clínico (médicos/as, enfermería, partería, consejería)**  
Recopila y documenta con precisión toda la información exigida legal y clínicamente; mantiene la confidencialidad en consultas y registros; utiliza solo herramientas y canales aprobados para la comunicación clínica; aplica los principios de identidad mínima (§12.3) siempre que sea posible; reporta de inmediato preocupaciones de seguridad o solicitudes irregulares.

**7.5 Personal de recepción y administrativo**  
Gestiona el registro, las citas y los expedientes de recepción de forma confidencial; evita la visibilidad de hojas de asistencia y pantallas para otras personas pacientes; sigue los procedimientos cuando autoridades o terceros solicitan información y no decide por su cuenta.

**7.6 Personal de compromiso comunitario y otros programas no clínicos**  
Aplica los estándares de confidencialidad e identidad mínima; utiliza teléfonos, SIM y canales aprobados según designación; transfiere cualquier dato registrado de manera oportuna a los sistemas oficiales y evita el almacenamiento prolongado en dispositivos personales.

**7.7 Voluntariado, personal en prácticas y contratistas**  
Accede solo a la información necesaria para las tareas definidas; no copia, exporta ni retiene datos de la clínica una vez finalizada la asignación.

**7.8 Socios con acceso a datos**  
Deben firmar acuerdos por escrito que exijan: confidencialidad; controles de seguridad al menos tan sólidos como los de este Protocolo; y notificación de incidentes a Asociación Manos Abiertas. Antes de introducir nuevos servicios en la nube, aplicaciones o dispositivos que procesen o almacenen Datos Altamente Sensibles, la Persona Focal de Seguridad (y la Persona Focal Legal, si es necesario) debe revisar las implicaciones legales y de seguridad.

---

## 8. PROTECCIÓN DE LA INFORMACIÓN EN LAS OPERACIONES DIARIAS

### 8.1 Historias clínicas y registros en papel

- **Almacenamiento:** Todos los archivos en papel que contengan Datos Altamente Sensibles se almacenan en gabinetes o salas cerradas con llave, bajo la responsabilidad del Gerente de Clínica.
- **Acceso:** Solo el personal clínico autorizado y el personal administrativo designado manipulan estos archivos.
- **Uso:** Los expedientes no se dejan desatendidos en consultorios, salas de espera o pasillos.
- **Fuera del establecimiento:** Los expedientes en papel solo se llevan fuera del establecimiento con autorización del Gerente de Clínica, en una bolsa cerrada, y se devuelven el mismo día cuando sea posible.

### 8.2 Historias clínicas electrónicas (EMR) y hojas de cálculo

- El EMR y cualquier registro digital con Datos Altamente Sensibles deben:
  - Utilizar cuentas de usuario individuales (sin inicios de sesión compartidos).
  - Exigir contraseñas robustas y autenticación de dos factores conforme al §8.9.
  - Estar alojados en infraestructura segura administrada por Asociación Manos Abiertas, o por un proveedor evaluado que cumpla con los estándares de cifrado del §8.12.
- **Almacenamiento local:** No se permiten copias sin cifrar de bases de datos EMR o de hojas de cálculo de pacientes en computadoras de escritorio, portátiles, USB o carpetas compartidas.
- **Uso sin conexión:** Si las copias locales temporales son esenciales (p. ej. por baja conectividad), deben estar en dispositivos cifrados con archivos protegidos por contraseña y eliminarse de forma segura una vez sincronizados.

### 8.3 Libros de citas, hojas de asistencia y formularios de consentimiento

- Se mantienen en recepción o en áreas clínicas de modo que otras personas pacientes no puedan leer entradas anteriores.
- Una vez completados, estos documentos se almacenan con las historias clínicas o en un lugar cerrado con llave designado.

### 8.4 Aplicaciones de mensajería, llamadas y consultas remotas

- Solo se usan canales aprobados (p. ej. aplicaciones con cifrado de extremo a extremo) para la comunicación con pacientes. Siempre que sea posible, usar números y dispositivos oficiales de la clínica.
- **Contenido:** Los mensajes deben ser neutrales y mínimos (hora, fecha, lugar, instrucciones básicas). Los detalles clínicos se documentan en el expediente oficial, no en historiales de chat extensos.
- El personal debe habilitar: bloqueo de pantalla en dispositivos; bloqueo de la aplicación cuando esté disponible.
- Los historiales de mensajes que contengan contenido sensible se eliminan periódicamente una vez que los datos esenciales están en el expediente oficial, en línea con la ley y el contexto de riesgo.
- **Correo electrónico:** Se utilizan dominios y cuentas de correo gestionados por la organización para el trabajo. No se envían por correo electrónico sin cifrar datos identificables de pacientes ni registros completos; deben usarse canales seguros aprobados o transferencia segura de archivos. Todo el personal recibe formación para no hacer clic en enlaces sospechosos ni abrir adjuntos inesperados, y para reportar de inmediato cualquier intento de phishing a la Persona Focal de Seguridad.

### 8.5 Dispositivos del personal

Cualquier dispositivo utilizado para acceder a Datos Altamente Sensibles (propiedad de la organización o dispositivo personal aprobado) debe contar con:

- Bloqueo de pantalla con PIN/contraseña robusta y bloqueo automático tras un corto período de inactividad (p. ej. máximo 5 minutos).
- Sistema operativo y parches de seguridad actualizados; actualizaciones automáticas habilitadas cuando sea posible.
- Antivirus/antimalware instalado y actualizado con protección en tiempo real habilitada.

Los dispositivos no deben compartirse con familiares, amistades u otras personas no autorizadas mientras la sesión esté iniciada. Se fomenta el uso de gestores de contraseñas aprobados por la organización para almacenar y generar contraseñas robustas; la contraseña maestra y las opciones de recuperación permanecen solo con la persona usuaria individual.

### 8.6 Medios externos y almacenamiento en la nube

- Solo pueden usarse memorias USB o discos externos cifrados, etiquetados y aprobados por la Persona Focal de Seguridad. Los datos transferidos a dichos medios son temporales; los archivos se eliminan de forma segura después de su uso.
- Los Datos Altamente Sensibles no se almacenan en cuentas personales en la nube ni en plataformas gratuitas no evaluadas. Solo se utilizan servicios en la nube y dominios de correo aprobados por la organización para datos clínicos.
- **Nube y SaaS:** Solo proveedores evaluados con cifrado conforme al §8.12, ubicación y jurisdicción de datos claras, y compromisos contractuales de seguridad y confidencialidad.

### 8.7 Seguridad de red

- **Redes de clínica y oficina:** El WiFi utiliza cifrado robusto (WPA3 o WPA2 con una frase de paso sólida). Si hay WiFi para visitantes, se usa una red de invitados separada; el acceso de invitados no debe extenderse a sistemas que contengan datos sensibles. Cuando sea factible, los sistemas que manejan Datos Altamente Sensibles deben estar en una VLAN o segmento de red separado. Se cambian las contraseñas de administración predeterminadas de routers/firewalls y el firmware se mantiene actualizado.
- **Acceso remoto:** El acceso al EMR o a sistemas sensibles desde fuera de la clínica solo se realiza a través de una VPN o una solución aprobada de acceso remoto. Se prohíbe el acceso al EMR o a sistemas sensibles desde WiFi abierto o público sin VPN.
- **VPN:** La organización proporciona o designa una VPN aprobada para el personal que necesite acceder a sistemas de la clínica de forma remota o que opere en entornos donde el tráfico de red pueda ser monitoreado. El personal debe activar la VPN antes de acceder a cualquier sistema que contenga datos Sensibles o Altamente Sensibles desde fuera de las redes de la clínica u oficina. La VPN debe utilizar cifrado robusto (p. ej. WireGuard, OpenVPN o IPsec con AES-256). No se permiten servicios VPN gratuitos o no evaluados; solo podrán utilizarse proveedores VPN aprobados por la organización o la propia infraestructura VPN de la organización. La Persona Focal de Seguridad es responsable de seleccionar, configurar y distribuir el acceso VPN.

### 8.8 Respaldo y recuperación

- EMR y bases de datos críticas: copias de seguridad regulares y automatizadas (al menos diarias si los datos cambian a diario). Las copias se almacenan en una ubicación separada (fuera del sitio o en un sistema separado) y cifradas conforme al §8.12. Las copias deben estar aisladas de la red principal (p. ej. fuera de línea o inmutables) para que el ransomware no pueda cifrarlas.
- La restauración de copias de seguridad se prueba al menos una vez al año para asegurar que los datos puedan recuperarse.
- La retención de copias de seguridad se alinea con la política de retención de datos (§11). Si se sospecha ransomware, se sigue la respuesta a incidentes del §14.3; no se realiza pago de rescate sin decisión legal/ejecutiva y consideración de sanciones y ética aplicables.

### 8.9 Autenticación

- **Autenticación de dos factores (2FA/MFA):** Habilitada para todos los sistemas que almacenan o permiten acceso a Datos Altamente Sensibles cuando sea técnicamente posible. Se prefieren aplicaciones autenticadoras (p. ej. Google Authenticator, Authy) o tokens de hardware sobre la verificación por SMS, que es vulnerable a intercambio fraudulento de SIM e interceptación. Este requisito aplica a: EMR y sistemas clínicos; cuentas de correo usadas para trabajo; almacenamiento en la nube y plataformas SaaS; interfaces administrativas de aplicaciones web; acceso VPN.
- **Contraseñas:** Cuando los sistemas requieren contraseñas, las personas usuarias deben elegir contraseñas robustas y únicas y no reutilizarlas entre sistemas. Se fomenta el uso de un gestor de contraseñas aprobado por la organización. Las contraseñas no deben compartirse, escribirse en notas visibles ni almacenarse en texto plano.
- Todas las demás secciones de este Protocolo que hagan referencia a autenticación o 2FA remiten a esta sección como requisito normativo único.

### 8.10 Seguridad física (TI e instalaciones)

- Los servidores y equipos de red se ubican en áreas cerradas y controladas por acceso; solo el personal autorizado de TI/seguridad tiene acceso. Cuando sea factible, los puertos de red no utilizados se deshabilitan y el equipo crítico no se expone en áreas de acceso público.
- Escritorio limpio: los documentos y dispositivos sensibles se guardan bajo llave cuando no están en uso; las pantallas se bloquean al abandonar la estación de trabajo.

### 8.11 Gestión de dispositivos móviles

- Se informa al personal que los dispositivos propiedad de la organización no deben ser utilizados en ninguna instancia con fines o para actividades personales.
- Ningún tercero sin autorización debe tener en su posesión dispositivos que pertenecen a la organización ni poseer las credenciales de acceso a dichos dispositivos.
- La Persona Focal de Seguridad mantiene un registro de todos los dispositivos inscritos, alineado con el inventario de dispositivos (§20).

### 8.12 Estándares de cifrado

Para asegurar una protección consistente en todos los sistemas y datos, se aplican los siguientes estándares mínimos de cifrado:

- **Datos en reposo:** AES-256 (o resistencia equivalente, p. ej. ChaCha20-Poly1305) para bases de datos, copias de seguridad, cifrado completo de disco y contenedores de archivos cifrados. Cuando un sistema o dispositivo no sea compatible con AES-256, se utiliza el estándar más sólido disponible y la limitación se documenta en el registro de riesgos.
- **Datos en tránsito:** TLS 1.2 o superior para todos los sistemas web, API y transmisión de correo electrónico. Los protocolos antiguos (SSL, TLS 1.0, TLS 1.1) se deshabilitan.
- **Túneles VPN:** AES-256 o equivalente, utilizando protocolos como WireGuard, OpenVPN (con AES-256-GCM) o IPsec (con AES-256).
- **Mensajería con cifrado de extremo a extremo:** Las plataformas de mensajería aprobadas deben usar protocolos E2EE reconocidos (p. ej. Protocolo Signal).
- **Gestión de claves:** Las claves de cifrado se almacenan de forma segura, separadas de los datos cifrados cuando sea factible. Las claves no se codifican de forma fija en el código fuente ni en archivos de configuración. El acceso a las claves se restringe al personal autorizado. La rotación de claves sigue la guía del proveedor o de la industria.


### 8.13 Viajes con dispositivos (cruces fronterizos y viajes de alto riesgo)

El personal que viaje (incluidos cruces de frontera) con dispositivos que puedan contener o acceder a datos Sensibles o Altamente Sensibles debe seguir estas buenas prácticas:

- **Dispositivos solo para viaje:** Cuando sea factible, usar un dispositivo dedicado para viaje (teléfono, portátil o tableta) sin Datos Altamente Sensibles almacenados localmente. Acceder a los sistemas de la clínica de forma remota solo cuando sea necesario, mediante VPN, y desconectarse después.
- **Datos mínimos:** Si un dispositivo debe llevar datos para el viaje, almacenar solo el mínimo necesario para el propósito específico. Eliminar o borrar de forma segura todos los datos innecesarios antes de la salida. No transportar registros completos de pacientes, exportaciones de EMR o bases de datos clínicas en dispositivos de viaje.
- **Borrado seguro antes de fronteras:** Al cruzar fronteras donde la inspección o incautación de dispositivos sea un riesgo conocido, considerar el borrado seguro del dispositivo antes del cruce (conforme al §8.13). Asegurar que los datos esenciales estén respaldados en la nube aprobada o en sistemas de la clínica y puedan restaurarse al llegar. La Persona Focal de Seguridad o el Gerente de Clínica puede asesorar sobre cuándo es apropiado.
- **Planificación:** El personal que viaje regularmente a destinos de alto riesgo debe comentar sus planes de viaje y estrategia de dispositivos con la Persona Focal de Seguridad o el Gerente de Clínica antes de la salida.

---

## 9. CONTROL DE ACCESO

**9.1**  
Los derechos de acceso se conceden según el rol y la necesidad documentada. Son aprobados por el Gerente de Clínica e implementados por la Persona Focal de Seguridad/TI.

**9.2**  
Cada persona usuaria tiene una cuenta individual; es responsable de todas las acciones realizadas bajo esa cuenta; y no debe compartir contraseñas.

**9.3**  
Cuando el personal cambia de rol o se retira, su acceso se revisa y ajusta de inmediato, y las cuentas se deshabilitan inmediatamente al salir. Se borran o reprovisionan de forma remota.

---

## 10. REGISTRO Y AUDITORÍA

**10.1**  
Cuando los sistemas lo permitan, se registra lo siguiente: inicios y cierres de sesión; acceso o modificación de registros Altamente Sensibles.

**10.2**  
La Persona Focal de Seguridad/TI revisa los registros periódicamente y cuando se sospecha un incidente.

---

## 11. RETENCIÓN Y DESTRUCCIÓN DE DATOS

**11.1 Retención**  
Los registros clínicos se conservan durante el período de 10 años. La organización establece un calendario claro de retención equilibrando continuidad de la atención, defensa legal y riesgo.

**11.2 Destrucción**  
Cuando sea legal y esté autorizado: los registros en papel se destruyen mediante trituración segura o incineración controlada; los registros electrónicos se eliminan usando métodos de borrado seguro coherentes.

---

## 12. DERECHOS DE LOS DATOS DE PACIENTES, CONSENTIMIENTO Y PRESTACIÓN CON IDENTIDAD MÍNIMA

### 12.1 Gestión del consentimiento

- Antes de recopilar información personal o clínica, se informa a las personas pacientes, en lenguaje claro y accesible, sobre: qué datos se recopilan y por qué; cómo se almacenarán y protegerán; quién dentro de la organización puede acceder a ellos; sus derechos según el §12.2; y cualquier obligación legal que la organización tenga respecto de sus datos.
- El consentimiento se obtiene antes o en el momento de la recopilación de datos.
- Cuando se utilice consentimiento por escrito, los formularios de consentimiento se almacenan con las mismas protecciones que los datos clínicos Altamente Sensibles (§8.1, §8.2).
- Las personas pacientes pueden retirar en cualquier momento el consentimiento para tratamientos de datos no obligatorios. Las implicaciones del retiro se explican claramente.


### 12.2 Derechos de las personas pacientes respecto de sus datos

Las personas pacientes tienen los siguientes derechos, ejercidos de manera que no genere riesgo adicional para ellas ni para otras personas:

- **Derecho a ser informadas:** Pueden solicitar qué datos personales y clínicos posee la organización sobre ellas y los fines para los cuales se utilizan.
- **Derecho de acceso:** Pueden solicitar revisar sus historias clínicas. Las solicitudes son gestionadas por el/la clínico/a tratante o el Gerente de Clínica y se atienden dentro de un plazo razonable, sujetas al juicio clínico y a consideraciones de seguridad.
- **Derecho de corrección:** Pueden solicitar la corrección de inexactitudes fácticas en sus registros. Las opiniones clínicas y evaluaciones profesionales no están sujetas a corrección a solicitud de la persona paciente, pero los desacuerdos pueden dejarse asentados en el expediente.
- **Derecho a solicitar restricción o eliminación:** Pueden solicitar que los datos no obligatorios se restrinjan en su uso o se eliminen. La organización documenta tales solicitudes y su respuesta.
- **Gestión de solicitudes:** Las solicitudes relativas a derechos de datos se dirigen al/a la clínico/a tratante o al Gerente de Clínica, quien consulta a la Persona Focal Legal cuando sea necesario. Las solicitudes y resultados se documentan. La organización no exige a las personas pacientes justificar su solicitud más allá de confirmar su identidad.

### 12.3 Prestación del servicio con identidad mínima y seudónima

La organización adopta un enfoque de identidad mínima como principio operativo por defecto: solo se recopila, registra y comunica la información estrictamente necesaria para la atención clínica y el cumplimiento legal.

**12.3.1 Recolección de datos**

- Cuando la ley exija información de identidad, ese requisito se cumplirá. Cuando no lo exija, la organización utilizará identificadores seudónimos (p. ej. códigos alfanuméricos de paciente) en lugar de nombres completos en sistemas internos, registros y comunicaciones.
- Los formularios de registro y procesos de admisión se revisan periódicamente para eliminar campos recopilados por costumbre en lugar de por necesidad.

**12.3.2 Separación de identificadores y datos clínicos**

- Cuando sea factible, la información directamente identificable (nombre, identificación, número de teléfono) se almacena por separado de los detalles clínicos (diagnósticos, tratamientos, resultados de pruebas). El vínculo entre ambos se mantiene mediante un código único de paciente accesible solo para personal clínico autorizado.
- Esta separación reduce el riesgo de que una sola brecha, incautación o acceso no autorizado exponga simultáneamente identidad e información clínica.

---

## 13. SOLICITUDES DE INFORMACIÓN POR AUTORIDADES O TERCEROS

**13.1 Regla general**  
Ningún miembro del personal en recepción o a nivel de clínica puede divulgar información Altamente Sensible ni conceder acceso a sistemas por simple solicitud.

**13.2 Pasos requeridos**  
Reconocer cortésmente la solicitud. Solicitar documentación escrita (orden, mandamiento, carta) que especifique la base legal y los datos exactos requeridos. Informar inmediatamente al Gerente de Clínica y a la Directora Ejecutiva o a la Persona Focal Legal.

**13.3 Decisión**  
La Directora Ejecutiva o la Persona Focal Legal evalúan la validez y alcance de la solicitud, las obligaciones legales y las protecciones disponibles. El personal cumple solo con instrucciones de esta autoridad designada.

**13.4 Minimización dentro de la ley**  
Si la divulgación es legalmente obligatoria: solo se comparten los registros específicos nombrados; no se entregan exportaciones masivas ni bases de datos completas salvo que se exija de forma expresa y legal. Siempre que sea legalmente permisible, se proporcionan datos seudonimizados o codificados en lugar de datos directamente identificables.

---

## 14. RESPUESTA A INCIDENTES

**14.1 Dispositivo perdido o robado**  
La persona miembro del personal informa de inmediato al Gerente de Clínica y a la Persona Focal de Seguridad. La Persona Focal de Seguridad/TI: intenta bloqueo/borrado remoto si está disponible; revoca el acceso (correo, EMR, aplicaciones de mensajería) desde ese dispositivo; evalúa la exposición de datos según el cifrado y las configuraciones. Se completa un Informe de Incidente; se consideran las notificaciones requeridas.

**14.2 Visita en sitio de autoridades exigiendo acceso**  
El personal de primera línea: mantiene la calma y el respeto; indica que la política exige que el/la Director/a o la Persona Focal Legal revise cualquier solicitud de historias clínicas; no inicia sesión en sistemas para ellas, no entrega contraseñas ni produce archivos en el momento. El Gerente de Clínica contacta inmediatamente a la Directora Ejecutiva o a la Persona Focal Legal. Todos los detalles (nombres, agencia, documentos, hora, exigencias exactas) se documentan. Las acciones se toman únicamente por instrucción del liderazgo designado.

**14.3 Incautación de dispositivos o expedientes en papel por autoridades**  
Cuando las autoridades incauten dispositivos (portátiles, teléfonos, tabletas), expedientes en papel u otros medios durante una visita en sitio, allanamiento o inspección:

- **Personal en sitio:** Mantener la calma; no resistirse físicamente ni obstruir una incautación legal si la resistencia aumentaría el riesgo. Anotar y registrar: qué artículos fueron incautados (ID de dispositivos, descripciones, contenido aproximado); nombres, agencia y funciones de quienes realizan la incautación; cualquier documento presentado (mandamiento, orden, recibo); fecha y hora. Completar un Informe de Incidente (Anexo A, §1). Informar de inmediato al Gerente de Clínica y a la Directora Ejecutiva o a la Persona Focal Legal.
- **Persona Focal de Seguridad (al ser notificada):** Actualizar el Inventario de Dispositivos; marcar los dispositivos como "Incautado - [fecha], [agencia]". Evaluar qué datos podían estar en los dispositivos y documentarlo para la evaluación de brecha.
- **Directora Ejecutiva o Persona Focal Legal:** Evaluar la base legal de la incautación; activar apoyo legal; determinar si se requiere notificación de brecha a pacientes, autoridades o reguladores; coordinar cualquier respuesta formal o seguimiento con la agencia que realizó la incautación.
- **Recuperación:** El personal afectado por la incautación de dispositivos recibe dispositivos de reemplazo y acceso restablecido tan pronto como sea practicable. Las credenciales de acceso de los dispositivos incautados no se reutilizan. El registro de riesgos se actualiza.

**14.4 Sospecha de intrusión digital, malware, phishing o ransomware**  
Personal: dejar de usar el dispositivo para trabajo sensible; no reenviar mensajes sospechosos; informar inmediatamente a la Persona Focal de Seguridad. Persona Focal de Seguridad/TI: aislar dispositivos afectados si es necesario; revocar credenciales comprometidas; cambiar contraseñas; escanear en busca de malware y revisar registros; preservar registros y evidencias para revisión. El incidente se documenta y revisa para prevenir recurrencia. Ransomware: no pagar sin decisión legal/ejecutiva; seguir procedimientos de contención y recuperación, incluido el uso de copias de seguridad aisladas cuando estén disponibles.

**14.5 Coerción de personal**  
Tan pronto como la organización sea informada: se suspenden todas las cuentas y accesos del personal afectado; se revisan actividades recientes en busca de accesos o descargas inusuales; se moviliza apoyo legal cuando sea posible; los detalles operativos sensibles no se discuten por canales inseguros.

**14.6 Clasificación y seguimiento de incidentes**  
Los incidentes se clasifican por gravedad (bajo / medio / alto / crítico) según la exposición de datos, el impacto en pacientes o personal y el impacto operativo. Después del incidente: se documentan la causa raíz, las lecciones aprendidas y las acciones correctivas; se actualizan el registro de riesgos y los procedimientos según sea necesario; las lecciones (anonimizadas) pueden compartirse en capacitaciones de refuerzo.

---

## 15. CONTINUIDAD OPERATIVA Y PREPARACIÓN PARA CRISIS

**15.1 Continuidad operativa**  
La organización define qué servicios y sistemas son esenciales y considera escenarios de interrupción como cortes de energía, pérdida de conectividad, fallas de dispositivos, ransomware, evacuación o cierre. Procedimientos simples y escritos describen cómo continuar servicios críticos con TI limitada, quién decide activar estas medidas y cómo se informa al personal. Los pasos clave se prueban o se recorren al menos una vez al año.

**15.2 Comunicación en crisis**  
Existe un canal designado y una lista de contactos para alertas urgentes de seguridad o protección. El personal sabe que no debe discutir detalles operativos sensibles en canales inseguros. La organización define quién puede hablar con medios o autoridades sobre incidentes; todo el resto del personal remite a la persona vocera designada (por lo general la Directora Ejecutiva o la Persona Focal Legal). Si una brecha o incidente puede afectar a pacientes, la organización define, con insumos legales/éticos, si se debe notificar y cómo hacerlo, de conformidad con la ley y este Protocolo.

---

## 16. TERCEROS Y CADENA DE SUMINISTRO

- Los socios y proveedores con acceso a datos deben contar con contratos que incluyan confidencialidad, requisitos de seguridad alineados con este Protocolo y notificación de incidentes a Asociación Manos Abiertas.
- El software utilizado en dispositivos que manejan datos sensibles debe provenir de fuentes conocidas, mantenidas y canales oficiales de distribución; no se utiliza software no evaluado o pirateado en esos dispositivos.
- Antes de introducir nuevos servicios en la nube, aplicaciones o dispositivos que vayan a procesar o almacenar Datos Altamente Sensibles, la Persona Focal de Seguridad (y la Persona Focal Legal, si es necesario) revisa las implicaciones legales y de seguridad.

---

## 17. APLICACIONES WEB Y ALMACENAMIENTO EN LA NUBE DE DATOS CLÍNICOS

Cuando Asociación Manos Abiertas utilice o desarrolle aplicaciones web (incluidas interfaces móviles o de escritorio con backend) que almacenen o procesen datos clínicos o información identificable de pacientes, se aplicarán los siguientes criterios y prácticas. Esto incluye cualquier sistema nuevo o existente que contenga Datos Altamente Sensibles en la nube o en servidores de la organización o de terceros.

**17.1 Criterios de seguridad y diseño para aplicaciones web y backends**

- **Autenticación y control de acceso:** Todo acceso a la aplicación y a cualquier backend o interfaz administrativa debe requerir cuentas individuales de usuario (sin inicios de sesión compartidos). Las contraseñas robustas y la autenticación de dos factores son obligatorias conforme al §8.9. El acceso basado en roles asegura que las personas usuarias solo vean y hagan lo que su rol requiere (necesidad de saber). Se implementan tiempos de expiración de sesión y cierre de sesión seguro.
- **Cifrado:** Todos los Datos Altamente Sensibles se cifran en tránsito y en reposo de acuerdo con los estándares definidos en el §8.12. Las claves de cifrado se gestionan de forma segura; no se codifican de forma fija en el código fuente ni en archivos de configuración.
- **Seguridad del backend y las API:** Las API del backend y las interfaces administrativas no se exponen a internet público sin autenticación y autorización robustas. Las contraseñas predeterminadas y las cuentas de prueba se eliminan en producción. Las entradas se validan y sanean para prevenir inyecciones (SQL, XSS). Las operaciones sensibles (exportación masiva, eliminación) se registran y se restringen a roles autorizados.
- **Registro y auditoría:** El acceso a la aplicación (inicios y cierres de sesión), el acceso o modificación de registros Altamente Sensibles y las acciones administrativas (creación de usuarios, cambios de permisos, exportación de datos) se registran con identidad del usuario, marca temporal y acción. Los registros se almacenan de forma segura, se conservan según la política y se revisan periódicamente y en caso de incidente.
- **Minimización y retención de datos:** Solo se recopilan y almacenan los datos necesarios para la finalidad definida (atención clínica, cumplimiento legal, reporte autorizado), en línea con el §12.3. La retención y eliminación segura siguen el §11.
- **Desarrollo e implementación seguros:** El código y las dependencias se mantienen actualizados; las vulnerabilidades conocidas se corrigen. Si la organización desarrolla la aplicación, se siguen prácticas de desarrollo seguro (p. ej. lineamientos OWASP); si la desarrolla un tercero, los requisitos de seguridad y manejo de datos se especifican contractualmente y se verifican antes de la implementación. Los datos sensibles (contraseñas, claves API, cadenas de conexión) no se almacenan en el código fuente ni en repositorios públicos.

**17.2 Almacenamiento en la nube de datos clínicos y de pacientes**

- **Selección de proveedor:** Los proveedores de nube y alojamiento utilizados para la aplicación web o para almacenar datos clínicos/de pacientes deben ser evaluados por la Persona Focal de Seguridad (y la Persona Focal Legal cuando corresponda). Los criterios incluyen: cifrado conforme al §8.12; ubicación y jurisdicción claras de los datos (considerando riesgos de acceso legal y residencia de datos); compromisos contractuales de seguridad, confidencialidad y notificación de brechas; cumplimiento de la legislación aplicable.
- **Configuración:** El almacenamiento (bases de datos, almacenamiento de objetos) se configura con cifrado habilitado; el acceso se restringe por identidad y rol; el acceso público se deshabilita. Las copias de seguridad se cifran y almacenan en una ubicación separada o con inmutabilidad cuando sea posible para proteger frente a ransomware. La segmentación de red y las reglas de firewall limitan quién puede alcanzar el backend y los almacenes de datos.
- **No almacenar Datos Altamente Sensibles en nubes no evaluadas o personales:** Los datos clínicos e identificables de pacientes solo se almacenan en entornos de nube o alojamiento aprobados y evaluados por la organización. No se almacenan en cuentas personales en la nube, SaaS gratuitos o no evaluados, ni servicios de terceros no aprobados.
- **Integración con este Protocolo:** Todo acceso a la aplicación web y a sus datos está sujeto a este Protocolo (control de acceso §9, registro §10, retención §11, respuesta a incidentes §14, capacitación §19). La Persona Focal de Seguridad asegura que la aplicación y sus componentes en la nube se incluyan en el inventario de dispositivos/infraestructura, en las pruebas de respaldo y recuperación y en las revisiones periódicas de seguridad.

**17.3 Introducción o cambio de aplicaciones web**

Antes de implementar una nueva aplicación web o backend que vaya a contener datos clínicos o de pacientes, o antes de realizar un cambio importante a una existente: la Persona Focal de Seguridad (y la Persona Focal Legal, si es necesario) la revisa conforme a esta sección y al §16 (terceros y cadena de suministro). Cualquier brecha se corrige o se acepta formalmente como excepción por la Directora Ejecutiva. Las buenas prácticas para plataformas aprobadas que puedan usarse junto al sistema clínico se establecen en el Anexo B.

---

## 18. REGLAS DE CONDUCTA DEL PERSONAL

Estas reglas son obligatorias y deben ser comprendidas por todo el personal.

**18.1 Uso de dispositivos personales**  
Permitido solo si el Gerente de Clínica lo autoriza expresamente y el dispositivo cuenta con bloqueo de pantalla, cifrado (si está disponible) y software actualizado. No está permitido: almacenamiento permanente de listas o registros de pacientes en dispositivos personales; permitir que otras personas usen el dispositivo mientras la sesión esté iniciada en cuentas de la clínica.

**18.2 Espacios de trabajo y conversaciones**  
Las consultas y discusiones de casos deben realizarse fuera del alcance auditivo de otras personas pacientes y visitantes. El personal no discute información identificable de pacientes en espacios públicos, redes sociales ni chats grupales personales.

**18.3 Prohibiciones no negociables (resumen)**  
Las siguientes prácticas están estrictamente prohibidas y constituyen falta grave. Esta lista resume prohibiciones clave del Protocolo para consulta rápida y capacitación; no limita las obligaciones establecidas en otras partes de este documento.

- Usar cuentas de usuario compartidas o genéricas para cualquier sistema que contenga Datos Altamente Sensibles.
- Guardar bases de datos o hojas de cálculo de pacientes sin cifrar en portátiles personales, teléfonos personales o memorias USB no aprobadas.
- Enviar por correo o mensajería listas completas de pacientes, registros de clínica o datos identificables de SSR a cuentas personales o plataformas abiertas.
- Compartir fotos, historias, capturas de pantalla o detalles de casos de pacientes que puedan identificar a personas, en línea o con terceros, sin consentimiento formal e informado y revisión/autorización explícita de riesgos.
- Proporcionar contraseñas, acceso directo a bases de datos o acceso irrestricto a pantallas a autoridades, donantes, periodistas o visitantes.
- Dejar expedientes en papel, dispositivos o pantallas expuestos en recepción, pasillos, salas de reuniones, vehículos o espacios públicos.
- Usar cibercafés o computadoras públicas/compartidas para acceder a sistemas de la clínica o a Datos Altamente Sensibles sin utilizar una VPN.
- Instalar software, VPN o aplicaciones no aprobadas en dispositivos de la clínica que manejen datos sensibles.
- Desactivar controles de seguridad (antivirus, actualizaciones, bloqueos de pantalla, cifrado) sin autorización escrita de la Persona Focal de Seguridad/TI.
- Ignorar dispositivos perdidos, correos sospechosos o comportamientos inusuales del sistema en vez de reportarlos de inmediato.
- Utilizar servicios VPN gratuitos o no evaluados en lugar de la VPN aprobada por la organización.

---

## 19. CAPACITACIÓN E IMPLEMENTACIÓN

**19.1 Inducción**  
Antes de acceder a cualquier dato de la clínica, todo el personal, voluntariado y contratistas debe recibir una orientación que cubra: este Protocolo y por qué existe en el contexto actual; cómo responder si las autoridades solicitan información; cómo reportar un incidente; cómo reconocer phishing y enlaces/adjuntos sospechosos; uso seguro del correo electrónico, mensajería y VPN; seguridad de dispositivos (bloqueo de pantalla, cifrado, actualizaciones) y reporte de dispositivos perdidos e incidentes; viajes con dispositivos y buenas prácticas en cruces fronterizos para personal que pueda viajar con dispositivos de trabajo.

**19.2 Refuerzos**  
Al menos una vez al año, y después de cualquier incidente importante o cambio legal: se realizan breves sesiones de refuerzo en cada clínica; se utilizan escenarios realistas (teléfono perdido, autoridades incautando dispositivos, correo de phishing, solicitud no autorizada).

**19.3 Capacitación específica por rol**  
La Persona Focal de Seguridad/TI y los Gerentes de Clínica reciben orientación adicional sobre control de acceso, registro, respaldo, respuesta a incidentes, uso del registro de riesgos y de las herramientas de gestión del Anexo A. También conocen el Anexo B (buenas prácticas de plataformas) para apoyar al personal.

**19.4 Documentación**  
Se registra la asistencia a las capacitaciones. El acceso a los sistemas solo se proporciona después de completar la inducción.

---

## 20. HERRAMIENTAS MÍNIMAS DE GESTIÓN (PLANTILLAS Y LISTAS DE VERIFICACIÓN)

La organización mantiene y utiliza los siguientes documentos y registros. **Los formatos y plantillas de cada uno se establecen en el Anexo A - Formatos de Documentos y Registros.** Las buenas prácticas para el uso de plataformas aprobadas de comunicación y colaboración (Google Workspace, ProtonMail, Signal, WhatsApp) se establecen en el **Anexo B - Buenas Prácticas para Plataformas Aprobadas.**

Resumen de herramientas (véase el Anexo A para formatos y plantillas completos):

- **Formulario de Informe de Incidente** (§14): Quién, qué, cuándo, dónde, sistemas involucrados, acciones inmediatas, gravedad, personas potencialmente afectadas, notificación requerida, seguimiento, aprobación final.
- **Registro de Acceso de Usuarios** (§9): Nombre, rol, sistemas autorizados, fecha de concesión, fecha de modificación, fecha de revocación.
- **Inventario de Dispositivos** (§8.5, §7.3, §8.11): ID del dispositivo, tipo, persona usuaria asignada, cifrado habilitado (S/N), última actualización, estado.
- **Registro de Riesgos** (§6.2): ID de Riesgo; Descripción; Probabilidad; Impacto; Mitigación / Control; Responsable; Estado; Última Revisión.
- **Chequeo Mensual de Seguridad de la Clínica (Gerente de Clínica):** Lista de verificación: almacenamiento seguro de expedientes en papel; no hay listas visibles de pacientes; cuentas de usuario actualizadas; no hay dispositivos o USB no aprobados; incidentes registrados y escalados.
- **Acuerdo de Confidencialidad y Seguridad de Datos** (§7.8): Borrador para socios y contratistas con acceso a datos (confidencialidad, medidas de seguridad, notificación de incidentes).
- **Compromiso de Confidencialidad (Personal/Voluntariado)** (§2.4, §18): Compromiso breve firmado por personal empleado, voluntariado y personal en prácticas antes del acceso a información o sistemas.
- **Registro de Asistencia a Capacitación** (§19.4): Registro de asistencia a la inducción y a los refuerzos de seguridad y confidencialidad.
---

## 21. REVISIÓN Y CONTROL DOCUMENTAL

**21.1**  
Este Protocolo se revisa al menos una vez cada 12 meses y después de cualquier incidente grave, cambio legal o cambio importante en el riesgo. Cualquier revisión es aprobada por la Directora Ejecutiva, recibe un nuevo número de versión y se comunica a todo el personal.

**21.2**  
Las prácticas de este Protocolo son coherentes con principios de marcos reconocidos como el Marco de Ciberseguridad NIST (Identificar, Proteger, Detectar, Responder, Recuperar) e ISO/IEC 27001 (gestión de seguridad de la información basada en riesgos). Cuando se utilicen aplicaciones web o móviles, deben considerarse los lineamientos OWASP para diseño e implementación seguros. La adopción puede ser gradual; la prioridad es implementar el Protocolo en su totalidad de acuerdo con la capacidad y el riesgo.

**21.3**  
Este documento es la fuente única y autoritativa para seguridad, confidencialidad y ciberseguridad de Asociación Manos Abiertas en el alcance descrito anteriormente. El Anexo A (Formatos de Documentos y Registros) y el Anexo B (Buenas Prácticas para Plataformas Aprobadas) forman parte del Protocolo y se actualizan en línea con él.

---

*Fin del Protocolo de Seguridad, Confidencialidad y Ciberseguridad*
