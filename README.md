# Evaluación Python: Análisis de satisfacción de clientes en una veterinaria

## 👉Envio: https://forms.gle/unSNRW654DDqXka66

## Contexto del caso

La veterinaria **Huellitas Felices** desea realizar un análisis preliminar sobre la percepción de sus servicios.  
Para ello, necesita simular información de **200 atenciones** realizadas a clientes durante un periodo de tiempo y procesar esos datos para identificar el nivel general de satisfacción.

Cada atención debe contener información básica del servicio prestado, el cliente atendido y una calificación de satisfacción.  
La gerencia desea conocer:

- El promedio general de satisfacción.
- La clasificación de cada atención según su calificación.
- Cuántas atenciones hubo por cada categoría.
- Qué servicios fueron mejor valorados.
- Un resumen final que apoye la toma de decisiones.

El objetivo de esta evaluación es que el estudiante aplique estructuras fundamentales de Python en un problema cercano a un escenario real de análisis de datos.

---

## Objetivo

Desarrollar un programa en Python que:

1. **Simule 200 registros de atención** usando estructuras como listas y diccionarios.
2. **Procese la información mediante funciones**.
3. **Calcule promedios y clasifique resultados** usando condicionales.
4. **Recorra y analice los datos** con ciclos `for`.
5. Presente resultados claros en consola.

---

## Requerimientos funcionales

El programa debe cumplir con lo siguiente:

### 1. Simulación de datos
Debe generar **200 registros** de atención de forma automática.

Cada registro debe almacenarse como un **diccionario** dentro de una **lista**.

Cada atención debe incluir como mínimo los siguientes campos:

- `id`
- `cliente`
- `mascota`
- `servicio`
- `costo`
- `calificacion`

### 2. Servicios posibles
Puede usar servicios como ejemplo:

- Baño
- Vacunación
- Consulta general
- Desparasitación
- Corte de uñas

### 3. Calificación
La calificación debe estar en una escala de **1 a 5**.

### 4. Procesamiento obligatorio
El programa debe permitir:

- Calcular el **promedio general** de las calificaciones.
- Clasificar cada registro según su calificación.
- Contar cuántos registros hay por clasificación.
- Mostrar cuántas veces aparece cada servicio.
- Identificar el servicio con mejor promedio de calificación.

### 5. Clasificación sugerida
Puede usarse la siguiente lógica:

- **Excelente**: calificación mayor o igual a 4.5
- **Buena**: calificación mayor o igual a 3.5 y menor que 4.5
- **Regular**: calificación mayor o igual a 2.5 y menor que 3.5
- **Crítica**: calificación menor que 2.5

---

## Restricciones técnicas

El desarrollo debe realizarse en **Python** y debe evidenciar obligatoriamente el uso de:

- **Listas**
- **Diccionarios**
- **Funciones**
- **Ciclos `for`**
- **Condicionales `if`, `elif`, `else`**

### Importante
- No se permite resolver todo en un solo bloque de código desordenado.
- El programa debe estar organizado en funciones.
- Debe ejecutarse correctamente desde consola.
- Se valorará el uso de nombres de variables claros y buena presentación de resultados.

---

## Funciones mínimas sugeridas

El programa debe tener al menos funciones como estas (pueden cambiar los nombres si se desea):

- Una función para **simular los 200 datos**
- Una función para **calcular el promedio**
- Una función para **clasificar una calificación**
- Una función para **contar clasificaciones**
- Una función para **contar servicios**
- Una función para **mostrar el resumen final**

---

## Salida esperada

El programa debe mostrar en consola, como mínimo:

- Total de registros generados
- Promedio general de satisfacción
- Cantidad de atenciones por clasificación
- Cantidad de atenciones por servicio
- Servicio mejor calificado
- Algunos registros de ejemplo

---

## Ejemplo de estructura de un registro

```python
{
    "id": 1,
    "cliente": "Laura Gómez",
    "mascota": "Max",
    "servicio": "Vacunación",
    "costo": 85000,
    "calificacion": 4.7
}
