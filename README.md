# Actividad 2 - Utilería JS

## Portada

**Nombre:** Uriel Espinoza de la Rosa
**Proyecto:** Utilería JS
**Carrera:** Ingeniería en Sistemas Computacionales, ITO

## ¿Qué problema resuelve?

Esta librería JavaScript permite validar datos comunes dentro de formularios web sin depender de frameworks pesados. Su objetivo es reutilizar funciones nativas para validar correos electrónicos, nombres, números de teléfono, fechas de nacimiento y obligar al uso de contraseñas seguras. 

El proyecto incluye:
* Un formulario principal de registro.
* Una ventana modal dinámica que muestra la edad calculada.
* Una página de login que valida el formato del correo y la seguridad de la contraseña.
* Funciones adicionales para el cálculo de salud física (IMC) y porcetanje de descuento.

## Instalación

Para usar la librería se debe enlazar el archivo `utileria.js` dentro del HTM.

## Funciones obligatorias

**1. Validación de Texto (Solo letras)**
Verifica que la cadena contenga exclusivamente letras, permitiendo el uso de acentos y espacios, ideal para nombres completos.
```javascript
console.log(soloLetras("Uriel")); 
// Resultado: true
console.log(soloLetras("Uriel123")); 
// Resultado: false

**2. Validación de Longitud Máxima**
Asegura que un valor numérico o cadena de texto no exceda el límite de caracteres permitido (ej. números telefónicos a 10 dígitos).
```javascript
console.log(validarLongitud("9511234567", 10)); 
// Resultado: true
console.log(validarLongitud("123456789012", 10)); 
// Resultado: false
