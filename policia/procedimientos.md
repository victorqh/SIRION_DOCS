---
description: Comandos obligatorios y procedimientos operativos
---

# PROCEDIMIENTOS

---

## Regla General

{% hint style="danger" %}
**Obligatorio:** Todo procedimiento DEBE tener rol escrito. Procedimientos sin `/me` `/do` pueden ser anulados.
{% endhint %}

---

## Plantillas de Comandos Obligatorias

### Identificación

**Opción 1:**
```
/me se acerca manteniendo distancia táctica
/me procede a identificarse como oficial y pediría al sujeto que se identifique
/do la oficial porta placa visible
```

**Opción 2:**
```
/me revisa cuidadosamente los bolsillos del sujeto
/do ¿tendría su DNI?
```

### Control de Situación

```
/me pediría enérgicamente "Mantenga las manos visibles"
/do ¿puedo ver claramente sus manos?
```

### Revisión de Pertenencias

```
/me procede a cachear al sujeto
/do el sujeto está siendo revisado
```

### Esposado

```
/me saca esposas y asegura las muñecas
/do el detenido queda esposado
```

---

## Lectura de Derechos (OBLIGATORIA)

### Comandos

```
/me refiere al intervenido respecto a "Tiene derecho a guardar silencio..."
/do ¿ha entendido sus derechos?
```

### Texto Completo de Derechos Miranda

{% hint style="info" %}
**El oficial debe decir textualmente:**
{% endhint %}

1. "Tiene derecho a guardar silencio. Cualquier cosa que diga puede y será usada en su contra ante un tribunal"

2. "Tiene derecho a consultar con un abogado y a que este esté presente durante cualquier interrogatorio"

3. "Si no puede costear un abogado, se le designará uno de oficio (gratuito) antes de que se le haga cualquier pregunta, si así lo desea"

4. "¿Entiende estos derechos tal como se los he leído? Teniendo estos derechos en cuenta, ¿desea hablar conmigo ahora?"

{% hint style="success" %}
**Nota:** No existe una única forma de realizar una intervención, pero se deberá respetar lo básico mencionado.
{% endhint %}

---

## Procedimiento de Detención Completo

### 1. Aseguramiento

```
/me reduce al sujeto colocándolo contra la pared
/me coloca las esposas en la espalda con palmas hacia afuera
/do el sujeto queda asegurado
```

### 2. Registro

```
/me procede a cachear cuidadosamente al detenido
/me revisa bolsillos, cinturón y áreas donde podría portar armas
/do ¿encontraría algo ilegal?
```

{% hint style="warning" %}
**Importante:** No quitar comida ni bebida del inventario.
{% endhint %}

### 3. Lectura de Derechos

**Debe realizarse ANTES de ingresar a comisaría**

```
/me lee los derechos Miranda al detenido
/do el sujeto ha sido informado de sus derechos
```

### 4. Traslado

```
/me escolta al detenido hacia la patrulla
/me asegura al sujeto en el asiento trasero
/do el detenido es trasladado a comisaría
```

### 5. Proceso en Comisaría

1. **Indicar motivo** - Explicar los cargos claramente
2. **Tomar foto** - Foto mugshot para registro
3. **Tomar datos** - Nombre completo, DNI, dirección
4. **Interrogatorio** - Si es necesario para la investigación
5. **Aplicar pena** - Multa/fianza o tiempo de cárcel

### 6. Aplicación de Pena

**Para delitos leves:**
* Multa económica
* Fianza para liberación

**Para delitos graves:**
* Tiempo de cárcel según Código Penal
* Multa adicional si corresponde

{% hint style="danger" %}
**Prohibido:** Asignar penas al azar. Siempre usar el Código Penal oficial.
{% endhint %}

### 7. Confiscación de Evidencia

Al arrestar, el agente debe:

* ✅ Confiscar todas las armas
* ✅ Confiscar drogas
* ✅ Confiscar artículos ilegales
* ✅ Documentarlos como evidencia
* ❌ NO quitar comida ni bebida

---

## Procedimientos de Persecución

### Maniobra PIT

{% hint style="warning" %}
**Requisitos para ejecutar PIT:**
* Solo a velocidades inferiores a 90-100 km/h
* El sospechoso debe ser un riesgo real
* Requiere autorización de un superior (Sargento o mayor)
{% endhint %}

```
Oficial: "Solicitando autorización para PIT, velocidad controlada"
Superior: "Autorizado, ejecute con precaución"
```

### Persecución Aérea

* Los helicópteros mantienen altura de seguridad
* Solo disparan con permiso del Jefe de Policía
* Únicamente en situaciones de rehenes o peligro extremo

### Bloqueos Vehiculares

* Deben ser visibles para el sospechoso
* Debe haber vía de escape clara
* **Excepción:** Objetivos de "Alta Prioridad" (Robo al Yate o Banco Central)

### Acoso Vehicular (Swarming)

{% hint style="danger" %}
**Prohibido:** Las unidades de apoyo deben mantener distancia de seguridad para evitar colisiones múltiples.
{% endhint %}

---

## Procedimientos Generales

La policía debe siempre:

1. ✅ **Identificarse** - Mostrar placa y nombre
2. ✅ **Mostrar causa** - Explicar motivo de la intervención
3. ✅ **Lectura de derechos** - Si hay detención
4. ✅ **Respetar comandos** - Usar `/me` y `/do` obligatoriamente
5. ✅ **Negociar** - Siempre procurar negociación razonable

---

## Registro de Vehículos

{% hint style="info" %}
**Requisitos para registrar un vehículo:**
{% endhint %}

* Causa probable (comportamiento sospechoso, delito visible)
* Sospecha razonable (información de inteligencia)
* Consentimiento del conductor

```
/me se acerca al vehículo con precaución
/me solicita permiso para revisar el vehículo
/do ¿el conductor acepta?

[Si acepta]
/me procede a revisar cuidadosamente el interior del vehículo
/do ¿encontraría algo ilegal?
```

{% hint style="warning" %}
**Sin causa probable, sospecha razonable o consentimiento, el registro es ilegal.**
{% endhint %}

---

## Control de Tráfico

### Detención de Tráfico

```
/me activa las luces y sirena de la patrulla
/me indica al conductor que se detenga a un lado
/do el conductor se detendría?

[Al detenerse]
/me se aproxima con precaución al vehículo
/me solicita licencia de conducir y documentos del vehículo
```

### Infracciones Comunes

| Infracción | Multa | Procedimiento |
|-----------|-------|---------------|
| Exceso de velocidad | $100 - $500 | Advertencia o multa |
| Conducción temeraria | $200 - $1,000 | Multa + posible detención |
| Sin licencia | $500 + detención | Confiscar vehículo |
| Conducir bajo influencia | $1,000 - $5,000 | Detención + multa |

---

## Negociaciones

### Principios de Negociación

{% hint style="success" %}
**Siempre procurar negociar cuando se pidan cosas razonables.**
{% endhint %}

### ✅ Peticiones RAZONABLES

* Salida segura
* Tiempo para escapar
* Hasta 7 chalecos
* Dinero proporcional IC

### ❌ Peticiones NO RAZONABLES

* Poner autos en inventario
* Más de 7 chalecos
* Millones IC sin justificación
* Salir de radio
* Rendirse sin luchar

**Ejemplo de negociación:**

```
Criminal: "Queremos 5 chalecos y salida limpia por 5 minutos"
Policía: "Podemos dar 5 chalecos. Salida limpia de 3 minutos, luego podemos perseguir"
```

---

## Uso Progresivo de la Fuerza

### Escalera de Fuerza

1. **Presencia** - Mostrar autoridad
2. **Diálogo** - Comunicación verbal
3. **Orden verbal** - Instrucciones claras y firmes
4. **Control físico** - Reducción sin armas
5. **Táser** - Si hay resistencia activa
6. **Fuerza letal** - Solo ante amenaza de muerte

{% hint style="danger" %}
**Importante:** No saltar pasos sin justificación. La fuerza debe ser proporcional a la amenaza.
{% endhint %}
