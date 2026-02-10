# Actividad 4 - Validador de Documentos (Strings e Inmutabilidad)

**Autor:** Larry David Botia Contreras  
**Tecnología:** Java (JDK) — Visual Studio Code  
**Tema:** Manipulación de `String`, Inmutabilidad y uso de `StringBuilder`

---

## Descripción del problema

En esta actividad se simula un sistema que recibe identificaciones con formato incorrecto.  
El objetivo es limpiar el texto, normalizarlo y generar una versión invertida, analizando cómo Java maneja la memoria cuando se trabaja con cadenas.

Se busca entender la diferencia entre:

- `String` (inmutable)
- `StringBuilder` (mutable y eficiente)

---

## Desarrollo realizado

### 1️⃣ Definición de entrada
Se creó una cadena inicial:

```java
String idSucio = " User_123 ";
