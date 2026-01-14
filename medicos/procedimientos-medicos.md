---
description: Procedimientos médicos, instrumental y protocolos
---

# PROCEDIMIENTOS MÉDICOS

---

## Medical Bag 🏥

{% hint style="info" %}
**Medical Bag:** Herramienta principal del EMS con 7 instrumentos médicos especializados.
{% endhint %}

### Instrumentos del Medical Bag

| Instrumento | Uso Principal | Aplicación |
|------------|---------------|------------|
| 💉 **Desfibrilador** | Reanimación cardíaca | Personas inconscientes |
| 🩹 **Botiquín** | Traumas generales | Heridas, golpes, lesiones |
| 🔧 **Pinzas Médicas** | Extracción | Balas, fragmentos, objetos |
| 🧊 **Bolsa de Hielo** | Inflamación | Hinchazón, contusiones |
| 🔥 **Crema para Quemaduras** | Quemaduras | Fuego, electricidad, químicos |
| 🪡 **Kit de Sutura** | Heridas profundas | Cortes, laceraciones |
| 💊 **Sedante** | Pacientes violentos | Agitación, agresividad |

---

## Uso de Instrumentos

### Desfibrilador

**Indicaciones:**
* Paciente inconsciente
* Paro cardíaco
* Sin signos vitales

**Procedimiento:**
```
/me Coloca los electrodos del desfibrilador en el pecho del paciente
/do El desfibrilador analiza el ritmo cardíaco
/me Carga el desfibrilador a 200 joules
/me Grita "DESPEJADO" y aplica la descarga
/do ¿Se recupera el pulso? (El paciente decide)
```

---

### Botiquín de Primeros Auxilios

**Indicaciones:**
* Heridas superficiales
* Traumas leves
* Estabilización inicial

**Procedimiento:**
```
/me Abre el botiquín y evalúa las heridas del paciente
/me Limpia la zona afectada con antiséptico
/me Aplica vendaje estéril sobre la herida
/do El sangrado disminuye gradualmente
```

---

### Pinzas Médicas

**Indicaciones:**
* Heridas por arma de fuego
* Objetos incrustados
* Extracción de fragmentos

**Procedimiento:**
```
/me Revisa la entrada de la bala con una linterna
/me Aplica anestesia local en la zona
/do El paciente siente el efecto anestésico en 30 segundos
/me Introduce las pinzas cuidadosamente en la herida
/me Localiza el proyectil y lo extrae lentamente
/me Deposita la bala en un contenedor estéril
/me Limpia la herida y aplica sutura
```

{% hint style="warning" %}
**Importante:** Las balas extraídas deben entregarse a la policía como evidencia.
{% endhint %}

---

### Bolsa de Hielo

**Indicaciones:**
* Inflamación
* Contusiones
* Esguinces

**Procedimiento:**
```
/me Examina la zona hinchada palpando suavemente
/me Coloca la bolsa de hielo sobre el área afectada
/do El frío reduce la inflamación progresivamente
/me Mantiene la bolsa durante 15 minutos (2 minutos ROL)
```

---

### Crema para Quemaduras

**Indicaciones:**
* Quemaduras de primer grado
* Quemaduras de segundo grado
* Quemaduras químicas o eléctricas

**Procedimiento:**
```
/me Evalúa el grado de la quemadura
/me Enfría la zona con agua estéril
/me Aplica la crema especializada en toda el área afectada
/me Cubre con vendaje no adherente
/do La piel comienza a recuperarse
```

---

### Kit de Sutura

**Indicaciones:**
* Heridas profundas
* Laceraciones
* Cortes extensos

**Procedimiento:**
```
/me Limpia la herida con solución antiséptica
/me Prepara el hilo de sutura y la aguja
/me Aplica anestesia local
/do El paciente siente adormecimiento en la zona
/me Comienza a suturar la herida con puntos precisos
/me Realiza [número] puntos de sutura
/me Corta el exceso de hilo y desinfecta
/me Cubre con apósito estéril
```

---

### Sedante

**Indicaciones:**
* Paciente agresivo
* Crisis nerviosa
* Necesidad de inmovilización

**Procedimiento:**
```
/me Prepara la jeringa con sedante
/me Se acerca al paciente con precaución
/me Intenta calmar verbalmente al paciente
/intento Inyectar sedante en el brazo del paciente
/me Administra 5mg de [nombre del sedante]
/do El paciente comienza a calmarse en 1-2 minutos
```

{% hint style="danger" %}
**Autorización:** Debe haber justificación médica clara. Registrar en informe.
{% endhint %}

---

## Tablet EMS 📱

### Funciones de la Tablet

1. **Registro de Pacientes**
   * Historial médico
   * Alergias
   * Tratamientos previos

2. **Informes Médicos**
   * Estructura obligatoria
   * Registro de atención

3. **IPA (Información del Paciente Archivada)**
   * Acceso a historial confidencial
   * Solo personal autorizado

4. **Comunicación Interna**
   * Chat con otros EMS
   * Coordinación de casos

---

## Estructura de Informes

### Informe Médico Estándar

```
🏥 INFORME MÉDICO EMS

📋 DATOS DEL CASO
━━━━━━━━━━━━━━━━━━━━━
Agente a cargo: [Nombre EMS]
Rango: [Rango]
Fecha: [DD/MM/AAAA]
Hora: [HH:MM]
Lugar: [Ubicación exacta]

👤 PACIENTE
━━━━━━━━━━━━━━━━━━━━━
Nombre: [Nombre completo]
Edad aproximada: [Años]
Estado: [Consciente/Inconsciente]

📍 SITUACIÓN
━━━━━━━━━━━━━━━━━━━━━
Descripción: [Descripción detallada de la emergencia]
Personas involucradas: [Nombres y roles]
Tags: [#] [Etiquetas relevantes]

🩺 EVALUACIÓN MÉDICA
━━━━━━━━━━━━━━━━━━━━━
Signos vitales:
- Pulso: [bpm]
- Respiración: [rpm]
- Presión: [mmHg]

Lesiones encontradas:
[Lista detallada]

🔧 TRATAMIENTO APLICADO
━━━━━━━━━━━━━━━━━━━━━
Procedimientos:
1. [Procedimiento 1]
2. [Procedimiento 2]
3. [Procedimiento 3]

Instrumental utilizado:
- [Instrumento 1]
- [Instrumento 2]

Medicamentos administrados:
- [Medicamento] [Dosis] [Vía]

✅ RESULTADO
━━━━━━━━━━━━━━━━━━━━━
Estado final: [Estable/Crítico/Derivado]
Recomendaciones: [Indicaciones al paciente]
Seguimiento: [Sí/No] [Detalles]

👮 AUTORIDADES
━━━━━━━━━━━━━━━━━━━━━
Policía notificada: [Sí/No]
Agentes presentes: [Nombres]
Evidencia entregada: [Descripción]

📝 OBSERVACIONES
━━━━━━━━━━━━━━━━━━━━━
[Notas adicionales relevantes]

━━━━━━━━━━━━━━━━━━━━━
Firma: [Nombre] - [Rango]
```

---

## IPA - Información del Paciente Archivada

{% hint style="danger" %}
**CONFIDENCIAL:** La IPA es información ultra confidencial protegida por ley.
{% endhint %}

### Acceso a la IPA

**Quién puede acceder:**
* Director
* Jefe de EMS
* Médico tratante del caso
* Con orden judicial

**Prohibiciones:**
* No compartir con terceros
* No usar para beneficio personal
* No divulgar sin autorización
* No acceder sin motivo médico

### Contenido de la IPA

La IPA contiene:
* 📋 Historial médico completo
* 💊 Medicamentos recetados
* 🩺 Tratamientos realizados
* 🔬 Resultados de análisis
* 🧬 Alergias y condiciones
* 📝 Informes anteriores

---

## Protocolos de Radio

### Comunicación con Dispatch

```
EMS → Dispatch: "Control, aquí Ambulancia 2-1, código 3 al Hospital"
Dispatch: "Recibido Ambulancia 2-1, código 3 autorizado"
```

### Solicitud de Recursos

```
EMS: "Control, solicito apoyo policial en [ubicación], código azul"
Control: "Recibido, despachando unidades policiales a tu posición"
```

### Anuncio de Llegada

```
EMS: "Control, Ambulancia 2-1 en escena, evaluando situación"
Control: "Recibido 2-1, mantente en frecuencia"
```

---

## Medicamentos Opioides

{% hint style="warning" %}
**Restricción:** Los opioides requieren autorización especial y registro exhaustivo.
{% endhint %}

### Requisitos para Prescribir

1. **Dolor severo justificado**
2. **Autorización de Especialista o superior**
3. **Registro en IPA**
4. **Baja médica de 3 días mínimo**

### Procedimiento

```
/me Evalúa el nivel de dolor del paciente (escala 1-10)
/do El paciente indica dolor nivel [número]
/me Consulta con el especialista sobre prescripción de opioides
/me Autoriza la receta de [medicamento opioide]
/me Explica efectos secundarios y precauciones
/me Registra en la Tablet: "Prescripción opioide autorizada"
/me Entrega baja médica de 3 días
```

### Control y Seguimiento

* **Seguimiento obligatorio** a los 3 días
* **Revisar dependencia** o efectos adversos
* **Registrar evolución** en IPA
* **Posible renovación** solo con evaluación presencial

---

## Eutanasia / Desconexión

{% hint style="danger" %}
**PROHIBIDO:** La eutanasia está completamente prohibida en el servidor.
{% endhint %}

* No se puede desconectar a un paciente
* No se puede "dejar morir" intencionalmente
* Siempre se debe intentar salvar vidas
* Viola los principios del EMS

**Excepción:** CK autorizado por administración (PKT/CK oficial)

---

## Resumen de Procedimientos

### Orden de Prioridad en Atención

1. **Evaluación inicial** (signos vitales)
2. **Estabilización** (detener sangrado, desfibrilar)
3. **Tratamiento específico** (suturas, extracción balas)
4. **Medicación** (analgésicos, antibióticos)
5. **Traslado** (si requiere hospital)
6. **Registro** (informe completo en Tablet)

### Comandos Obligatorios

{% hint style="info" %}
**Recordatorio:** Usar `/me` y `/do` en todos los procedimientos médicos.
{% endhint %}

* `/me` → Acciones del EMS
* `/do` → Reacciones del entorno/paciente
* `/intento` → Acciones que pueden fallar

---

## Situaciones Especiales

### Muerte Roleada

Si el paciente decide morir:
* Respetar su decisión
* Certificar la muerte
* Notificar a policía si es sospechosa
* Llamar a funeraria
* No se puede forzar reanimación

### Embarazo

* Derivar a especialista en Ginecobstetricia
* Extremar precauciones
* Evitar medicamentos contraindicados
* Priorizar salud de madre y bebé

### Pediatría

* Derivar a especialista en Pediatría
* Dosis de medicamentos ajustadas
* Presencia de tutor/padre obligatoria
* Comunicación adaptada a la edad

---

{% hint style="success" %}
**Recuerda:** La calidad del rol médico depende de la atención a los detalles. Usa los comandos, describe las acciones, y crea experiencias inmersivas para todos.
{% endhint %}
