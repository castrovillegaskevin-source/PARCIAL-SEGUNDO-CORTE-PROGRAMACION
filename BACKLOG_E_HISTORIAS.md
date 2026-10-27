# 📋 Backlog e Historias de Usuario - VitalHogar Salud

Este documento describe el paso a paso metodológico para transformar los requerimientos levantados del sistema médico domiciliario en **Historias de Usuario** y su posterior organización en un **Backlog** priorizado para el desarrollo del software en Java.

---

## 🧭 Paso a Paso: De los Requerimientos al Backlog

1. **Identificación de la Necesidad (Requerimientos):** Se recolectaron las reglas funcionales, técnicas y de dominio necesarias para el funcionamiento del servicio médico en casa (menú, registro, planes, descuentos, archivo TXT y restricciones de negocio).
2. **Definición de Historias de Usuario:** Cada requerimiento funcional se tradujo a una historia de usuario usando la estructura ágil oficial: `Como [rol], Quiero [funcionalidad], Para [beneficio/objetivo]`.
3. **Construcción del Backlog:** Se organizaron las historias de usuario en una lista estructurada o inventario de trabajo pendiente (*Backlog*), asignándoles un nivel de prioridad (Alta, Media, Baja) para planificar las fases de programación en consola.

---

## 👤 Historias de Usuario (HU)

* **[HU-01] Menú Interactivo Continuo**
  * **Como** operador o médico del servicio domiciliario,
  * **Quiero** visualizar un menú con 8 opciones y mantener la ejecución continua del programa,
  * **Para** navegar y seleccionar las acciones de gestión médica de forma ordenada.
  * **Requerimiento asociado:** RF-01, RF-09, RF-10

* **[HU-02] Registro de Datos del Cliente**
  * **Como** vendedor del servicio médico,
  * **Quiero** ingresar por teclado el nombre, la cédula, los síntomas y la dirección de residencia del usuario,
  * **Para** registrar formalmente la atención y ubicar correctamente al paciente.
  * **Requerimiento asociado:** RF-02

* **[HU-03] Selección de Plan y Cobertura**
  * **Como** operador del sistema,
  * **Quiero** seleccionar el plan médico preventivo (`PB` o `PP`) e ingresar la cantidad de personas cubiertas,
  * **Para** definir las bases del cálculo financiero del servicio.
  * **Requerimiento asociado:** RF-03, RF-04

* **[HU-04] Cálculo de Costos y Descuento por Síntomas**
  * **Como** administrador del sistema,
  * **Quiero** calcular automáticamente el valor mensual y aplicar un 12.5% de descuento si el síntoma reportado es "gripa" o "alergia",
  * **Para** garantizar el cobro exacto y los beneficios corporativos del cliente.
  * **Requerimiento asociado:** RF-05, RF-06

* **[HU-05] Respaldo de Transacciones y Visualización**
  * **Como** usuario del sistema,
  * **Quiero** visualizar la información en pantalla y generar un respaldo físico en un archivo `.txt`,
  * **Para** asegurar la persistencia y consulta de los datos de la factura.
  * **Requerimiento asociado:** RF-07, RF-08

---

## 📊 Backlog del Proyecto (Product Backlog)

| Identificador | Historia de Usuario | Prioridad |
| :--- | :--- | :--- |
| **HU-01** | Menú interactivo continuo y control de salida | **Alta** |
| **HU-02** | Registrar datos personales y clínicos del cliente | **Alta** |
| **HU-03** | Seleccionar tipo de plan (`PB`/`PP`) y otros usuarios | **Alta** |
| **HU-04** | Calcular valor mensual y aplicar descuento clínico | **Media** |
| **HU-05** | Visualizar información en consola y respaldo TXT | **Baja** |
