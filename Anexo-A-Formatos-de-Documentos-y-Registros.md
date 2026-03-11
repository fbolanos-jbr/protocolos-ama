# ANEXO A - FORMATOS DE DOCUMENTOS Y REGISTROS

**Del Protocolo de Seguridad, Confidencialidad y Ciberseguridad**  
**Organización:** Asociación Manos Abiertas  
**Referencia:** Protocolo §20

Los siguientes son los formatos estándar para los documentos y registros enumerados en el §20. Use estas plantillas tal como están o adáptelas a las necesidades locales manteniendo los mismos campos y finalidad. Conserve los formularios completados de acuerdo con la política de retención de la organización.

---

## 1. FORMULARIO DE INFORME DE INCIDENTE

| Campo | Contenido |
|-------|--------|
| **ID del incidente** | [p. ej. INC-AAAA-NNN] |
| **Fecha del incidente** | |
| **Hora (aprox.)** | |
| **Ubicación / establecimiento** | |
| **Reportado por** | Nombre, rol, contacto |
| **Fecha del reporte** | |
| **Resumen (qué ocurrió)** | |
| **Sistemas / datos involucrados** | p. ej. EMR, expedientes en papel, dispositivo, correo electrónico |
| **Personas potencialmente afectadas** | Número estimado y categoría (p. ej. pacientes, personal); describir si se expusieron datos identificables |
| **Acciones inmediatas tomadas** | |
| **Gravedad** | Baja / Media / Alta / Crítica |
| **¿Se requiere notificación de brecha?** | Sí / No / Evaluación pendiente - si es sí, especificar a quién (p. ej. autoridad de datos, personas afectadas) y el plazo |
| **Seguimiento requerido** | |
| **Remitido a** | Gerente de Clínica / Persona Focal de Seguridad / Legal / Director/a Ejecutivo/a |
| **Aprobación final** | Nombre, rol, fecha |

*Notas / anexos (p. ej. capturas de pantalla, extractos de registros - almacenar de forma segura):*

---

## 2. REGISTRO DE ACCESO DE USUARIOS

| Nombre completo de la persona usuaria | Rol | Sistemas / aplicaciones autorizados | Fecha de concesión de acceso | Fecha de modificación (si aplica) | Fecha de revocación (si aplica) | Autorizado por |
|----------------|------|-----------------------------------|---------------------|-------------------------|------------------------------|------------|
| | | | | | | |
| | | | | | | |

*Actualizar cada vez que se conceda, cambie o revoque un acceso. Conservar el historial del personal que deja la organización.*

---

## 3. INVENTARIO DE DISPOSITIVOS

| ID del dispositivo | Tipo (portátil / teléfono / tableta / escritorio) | Persona usuaria asignada | Cifrado habilitado (S/N) | Inscrito en MDM (S/N) | SO / versión | Última actualización de seguridad | Estado (en uso / retirado / perdido) | Notas |
|-----------|----------------------------------------|---------------|---------------------------|---------------------|--------------|----------------------|----------------------------------|-------|
| | | | | | | | | |
| | | | | | | | | |

*Revisar al menos trimestralmente. Alinear con Protocolo §8.5, §8.11, §8.13.*

---

## 4. REGISTRO DE RIESGOS

| ID de Riesgo | Descripción | Probabilidad (B/M/A) | Impacto (B/M/A) | Mitigación / control | Responsable | Estado (abierto / mitigado / aceptado / cerrado) | Última revisión (fecha) |
|---------|-------------|--------------------|----------------|----------------------|-------|-----------------------------------------------|----------------------|
| R01 | Ejemplo: Robo de portátil con acceso al EMR | M | A | Cifrado, bloqueo de pantalla, procedimiento de revocación de acceso, borrado remoto por MDM | Persona Focal de Seguridad | Abierto | [Fecha] |
| | | | | | | | |
| | | | | | | | |

*Actualizar cuando se identifiquen nuevos riesgos o cambien los controles. Revisar al menos anualmente (Protocolo §6).*

---

## 5. CHEQUEO MENSUAL DE SEGURIDAD DE LA CLÍNICA (GERENTE DE CLÍNICA)

**Clínica / establecimiento:** _______________________  
**Mes:** _______________________  
**Completado por:** _______________________  
**Fecha:** _______________________

| Verificación | Sí / No | Comentarios |
|-------|----------|----------|
| Expedientes en papel almacenados en gabinetes/salas cerrados con llave | | |
| No hay listas visibles de pacientes ni datos sensibles en áreas públicas | | |
| La lista de acceso de usuarios está actualizada; se revocó el acceso del personal que se fue | | |
| No hay dispositivos o USB no aprobados en uso para datos sensibles | | |
| Los dispositivos propiedad de la organización están inscritos en MDM y cumplen | | |
| Los incidentes (si los hubo) están registrados y escalados | | |
| Las hojas de asistencia / materiales de citas no son visibles para otras personas pacientes | | |
| Los dispositivos tienen bloqueo de pantalla y están bloqueados cuando quedan desatendidos | | |
| Se observan prácticas de identidad mínima (señalización neutral, no se recopilan identificadores innecesarios) | | |

*Aprobación final:* _______________________ (Gerente de Clínica)

---

## 6. ACUERDO DE CONFIDENCIALIDAD Y SEGURIDAD DE DATOS (SOCIOS / CONTRATISTAS)

*Usar para organizaciones socias o contratistas que reciban o procesen datos de Asociación Manos Abiertas. Referencia: Protocolo §7.8.*

**Entre:**  
Asociación Manos Abiertas, [dirección], ("Organización")  
**y**  
[Nombre del socio/contratista], [dirección], ("Receptor")

**Fecha de entrada en vigor:** _______________________

**1. Finalidad**  
El Receptor recibirá o tendrá acceso a información de la Organización en relación con [describir finalidad, p. ej. proyecto conjunto, evaluación, soporte técnico]. Este acuerdo establece las obligaciones del Receptor para proteger dicha información.

**2. Confidencialidad**  
El Receptor acepta mantener confidencial toda la información recibida de la Organización o a la que acceda en los sistemas de la Organización que no sea de acceso público, incluyendo, entre otros: datos identificables de pacientes, información clínica, datos del personal, planes operativos y de seguridad, y cualquier información marcada o razonablemente entendida como confidencial ("Información Confidencial"). El Receptor no divulgará Información Confidencial a terceros salvo con el consentimiento previo y por escrito de la Organización o cuando la ley lo exija, y en ese caso solo después de notificar a la Organización.

**3. Medidas de seguridad**  
El Receptor aplicará medidas de seguridad al menos tan robustas como las del Protocolo de Seguridad, Confidencialidad y Ciberseguridad de la Organización (según lo proporcionado o resumido por la Organización). Estas incluyen: acceso solo por necesidad de saber; cuentas de usuario individuales cuando se utilicen sistemas; cifrado de datos sensibles en tránsito y en reposo conforme a los estándares del Protocolo (§8.12); almacenamiento y eliminación seguros; no almacenamiento de Datos Altamente Sensibles en dispositivos personales o servicios en la nube no aprobados.

**4. Uso y retención**  
El Receptor utilizará la Información Confidencial solo para la finalidad acordada con la Organización. El Receptor no copiará, retendrá ni almacenará Información Confidencial más allá de lo necesario para dicha finalidad. Al finalizar la relación o a solicitud, el Receptor eliminará o devolverá de forma segura toda la Información Confidencial y confirmará por escrito que así lo ha hecho.

**5. Notificación de incidentes**  
El Receptor notificará a la Organización sin demora (y en todo caso dentro de [24/48] horas) cualquier brecha real o sospechada de confidencialidad, pérdida de datos, acceso no autorizado o incidente de seguridad que involucre la información de la Organización. El Receptor cooperará en cualquier investigación y mitigación.

**6. Personal**  
El Receptor garantizará que cualquier miembro de su personal, subcontratista o agente que tenga acceso a la información de la Organización esté sujeto a obligaciones equivalentes de confidencialidad y seguridad y sea informado de la naturaleza sensible de la información (incluidos contextos en los que los datos de SSR o de pacientes puedan exponer a las personas a daños).

**7. Plazo y supervivencia**  
Este acuerdo aplica durante toda la duración de la relación y subsiste tras su finalización. Las obligaciones de confidencialidad y seguridad continúan aplicándose a cualquier información ya recibida hasta que sea eliminada o devuelta de forma segura.

**8. Ley aplicable**  
[Opcional: p. ej. Este acuerdo se rige por las leyes de [jurisdicción].]

**Firmas**

| Por Asociación Manos Abiertas | Por [nombre del socio/contratista] |
|--------------------------|-------------------------------|
| Nombre: _______________________ | Nombre: _______________________ |
| Cargo: _______________________ | Cargo: _______________________ |
| Firma: _______________________ | Firma: _______________________ |
| Fecha: _______________________ | Fecha: _______________________ |

---

## 7. COMPROMISO DE CONFIDENCIALIDAD (PERSONAL / VOLUNTARIADO)

*Usar para personal empleado, voluntariado y personal en prácticas. Referencia: Protocolo §2.4, §4, §18.*

**Organización:** Asociación Manos Abiertas

Yo, _______________________ (nombre completo), en mi calidad de _______________________ (rol), reconozco que:

1. He recibido y comprendido el Protocolo de Seguridad, Confidencialidad y Ciberseguridad de la Organización (o el resumen pertinente) y acepto cumplirlo como condición para mi acceso a cualquier información o sistema de la clínica.

2. Mantendré confidencial toda información identificable de pacientes, datos clínicos y demás información sensible o interna a la que acceda en el curso de mi trabajo. No divulgaré dicha información a nadie sin autorización, incluyendo a familiares, amistades, redes sociales o comunicaciones personales.

3. Accederé solo a la información que necesite para desempeñar mi función (necesidad de saber). No utilizaré cuentas compartidas ni compartiré mis contraseñas. Reportaré inmediatamente cualquier dispositivo perdido, preocupación de seguridad o solicitud de información por parte de autoridades a mi supervisión y a la Persona Focal de Seguridad.

4. Seguiré los principios de identidad mínima y minimización de datos de la organización, recopilando y compartiendo solo la información necesaria para la atención clínica y el cumplimiento legal.

5. Entiendo que el incumplimiento de estas obligaciones puede dar lugar a medidas disciplinarias, incluida la terminación del contrato o de la relación de colaboración, y puede tener consecuencias legales o profesionales.

**Firma:** _______________________  
**Fecha:** _______________________

*Conservar con el expediente de personal. Completar antes de conceder acceso a sistemas o información sensible.*

---

## 8. REGISTRO DE ASISTENCIA A CAPACITACIÓN

*Usar para registrar la asistencia a la inducción y a los refuerzos en seguridad y confidencialidad. Referencia: Protocolo §19.4.*

**Tipo de capacitación:** _______________________ (p. ej. Inducción en Seguridad y Confidencialidad / Refuerzo Anual)  
**Fecha:** _______________________  
**Persona formadora/facilitadora:** _______________________  
**Ubicación:** _______________________  
**Temas cubiertos:** _______________________ (p. ej. visión general del Protocolo, comunicación con identidad mínima, respuesta a incidentes, conciencia sobre phishing, VPN y seguridad de dispositivos)

| Nombre completo | Rol | Firma | Notas (p. ej. primera vez / refuerzo) |
|-----------|------|-----------|-------------------------------------|
| | | | |
| | | | |
| | | | |

*Conservar para demostrar cumplimiento. Acceso a sistemas solo después de completar la inducción.*

---

*Fin del Anexo A - Formatos de Documentos y Registros*
