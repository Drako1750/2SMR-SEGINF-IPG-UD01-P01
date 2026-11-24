# Entrega Práctica UD01 · Auditoría y fortificación Clínica Dental Sonrisas

- **Nombre y apellidos del alumno/a:**
- **Grupo:** 2º SMR
- **Fecha de realización:**

---

### Actividad 1 · Mecanismos y objetivos de la seguridad informática

| ID | Mecanismo | Objetivo principal (C, I, D, NR) | Física / Lógica | Activa / Pasiva | Justificación |
|:---|:---|:---:|:---:|:---:|:---|
| 1.1 | SAI servidor |D|Física|Pasiva|Minimiza el daño causado|
| 1.2 | Cifrado BitLocker |C|Lógica|Activa||
| 1.3 | Cortafuegos perimetral | | | | |
| 1.4 | Copias de seguridad NAS |D|Lógica|Activa| |
| 1.5 | Antivirus corporativo |I|Lógica|Activa|Evita que exista un peligro|

---

### Actividad 2 · Cadena del incidente de seguridad

1. **Activos afectados:**
   - Activo 1:Datos de los clientes
   - Activo 2:Reputación
2. **Amenaza:**
   -El atacante
3. **Vulnerabilidad y clasificación:**
   -Conocida sobre el software instalado, ya que era una vulnerabilidad conocida
4. **Riesgo previo:**
   -Que un atacante se aprovechara de la vulnerabilidad comprometiendo la confidencialidad e integridad de los datos de los clientes.
5. **Ataque:**
   -Un exploit el cual le permitio descargar las bases de datos con los datos de los clientes y sus citas.
6. **Impacto:**
   - Impacto cuantitativo:La perdida de dinero al cancelar las citas de los clientes y las perdidas debidas a la mala reputación obtenida.
   - Impacto cualitativo:El derecho a la confidencialidad de los datos de los clientes.

---

### Actividad 3 · Plan de contingencia

1. **Clasificación de medidas:**
   - Medida A: Mantener contratado un servicio de soporte técnico con reposición de piezas hardware en
un plazo máximo de 24 horas
   - Medida B:Realizar una copia de seguridad completa de la base de datos médica cada noche y
almacenarla en una ubicación externa segura.
   - Medida C:Conmutar la conexión de red a un módem 4G/5G de respaldo en el momento exacto en que
se interrumpe la fibra óptica principal.
   - Medida D:Aislar inmediatamente de la red local cualquier equipo en el que salte una alerta de
infección activa para evitar el contagio.
   - Medida E: Alquilar un equipo informático temporal y volcar la configuración para reanudar la
facturación tras un desastre en la recepción.
   - Medida F:Reinstalar el sistema operativo y restaurar la copia de seguridad en un servidor de
sustitución tras una avería irreparable del disco duro.
2. **Diferencia entre plan de respaldo y plan de recuperación:**
   -El plan de respaldo se lleva a cabo antes de un ataque/desastre y el de recuperación después con el objetivo de minimizar los daños y volver a la normalidad.
---

### Actividad 4 · Software malicioso y test de intrusión

#### 4.1. Diagnóstico de malware
- **Caso 1:**
  - Tipo de malware:Troyano
  - Justificación (archivo anfitrión e intervención usuario):El trabajador abre un archivo con codigo malicioso, engañado por ingenieria social creyendo que estaba haciendo otra cosa como abrir el pdf.
- **Caso 2:**
  - Tipo de malware:Gusano
  - Justificación (archivo anfitrión e intervención usuario):Se propaga solo por la red local.
- **Medida preventiva para Caso 2:**

#### 4.2. Secuenciación de test de intrusión
- Secuencia ordenada cronológicamente (letras):
- Fases correspondientes:
  - Acción ...: Fase ...
  - Acción ...: Fase ...
  - Acción ...: Fase ...
  - Acción ...: Fase ...

---

### Actividad 5 · Contraseñas e identificación digital

#### 5.1. Contraseñas
1. **Comparativa de seguridad frente a fuerza bruta:**
2. **Política de contraseñas (3 reglas):**
   - Regla 1:
   - Regla 2:
   - Regla 3:

#### 5.2. Identificación digital
3. **Mecanismos aplicados:**
   - Trámite A:
   - Trámite B:
4. **Objetivo de seguridad garantizado y diferencia con usuario/contraseña:**