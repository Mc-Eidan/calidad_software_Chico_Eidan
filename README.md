# Calidad de Software
# Autor: Eidan Chico

Este repositorio tiene como objetivo presentar conceptos básicos sobre la calidad de software, con especial enfoque en la validación de aplicaciones mediante pruebas unitarias y pruebas end-to-end (E2E).

## 1. ¿Qué es la calidad de software?

La calidad de software se refiere al grado en que un producto cumple con los requisitos esperados, satisface las necesidades del usuario y está libre de defectos relevantes. Un software de calidad no solo funciona, sino que también es mantenible, seguro, confiable y fácil de usar.

### Características principales

- Funcionalidad: el sistema hace lo que debe hacer.
- Confiabilidad: el software funciona de manera estable y consistente.
- Usabilidad: es fácil de entender y usar.
- Eficiencia: usa recursos de forma adecuada.
- Mantenibilidad: puede ser modificado y mejorado sin grandes dificultades.
- Seguridad: protege datos e integra mecanismos de control.
- Portabilidad: funciona correctamente en diferentes entornos.

## 2. Conceptos básicos importantes

### Requisitos
Los requisitos describen lo que debe hacer el sistema. Pueden ser:

- Requisitos funcionales: acciones y comportamientos esperados.
- Requisitos no funcionales: rendimiento, seguridad, escalabilidad, usabilidad, etc.

### Defectos y errores
Un defecto es una falla en el software que puede causar un comportamiento incorrecto. Un error puede aparecer por una mala implementación, una mala especificación o una mala interpretación del requerimiento.

### Verificación y validación
- Verificación: se comprueba si el producto fue construido correctamente.
- Validación: se comprueba si el producto satisface las necesidades reales del usuario.

## 3. Pruebas de software

Las pruebas son una parte clave de la calidad del software porque permiten detectar fallos antes de que el sistema llegue al usuario final.

### Objetivos de las pruebas

- Detectar errores tempranamente.
- Asegurar que el software cumple requisitos.
- Mejorar la confianza en los cambios realizados.
- Reducir riesgos en producción.

### Tipos de pruebas

- Pruebas unitarias
- Pruebas de integración
- Pruebas de sistema
- Pruebas de regresión
- Pruebas E2E
- Pruebas de rendimiento
- Pruebas de seguridad

## 4. Pruebas unitarias

Las pruebas unitarias validan unidades pequeñas de código, generalmente funciones o métodos, de manera aislada.

### ¿Qué buscan?

- Confirmar que una función devuelve el resultado esperado.
- Detectar errores lógicos en bloques pequeños.
- Facilitar la corrección rápida y segura.

### Beneficios

- Son rápidas de ejecutar.
- Ayudan a detectar fallos en etapas tempranas.
- Mejoran la calidad del código. 
- Facilitan refactorizaciones.

### Ejemplo conceptual

Si tenemos una función que suma dos números, la prueba unitaria validaría:

- 2 + 2 = 4
- 0 + 5 = 5
- -1 + 1 = 0

### Buenas prácticas

- Probar casos positivos y negativos.
- Mantener pruebas simples y legibles.
- No depender de estructuras complejas.
- Ejecutarlas con frecuencia.

## 5. Pruebas E2E (End-to-End)

Las pruebas E2E validan el comportamiento completo de una aplicación desde la perspectiva del usuario. Se simula un flujo real de uso para verificar que todos los componentes integrados funcionan correctamente.

### ¿Qué buscan?

- Comprobar que la aplicación funciona como un sistema completo.
- Validar flujos reales de negocio.
- Detectar errores de integración entre frontend, backend y base de datos.

### Ejemplo conceptual

En una aplicación web, una prueba E2E podría verificar que:

1. El usuario inicia sesión.
2. Accede al panel principal.
3. Crea un registro.
4. Guarda la información correctamente.
5. Ve el resultado esperado en la interfaz.

### Beneficios

- Validan la experiencia real del usuario.
- Detectan fallos de integración.
- Ayudan a reducir riesgos en producción.

### Limitaciones

- Son más lentas que las pruebas unitarias.
- Requieren más infraestructura y configuración.
- No reemplazan completamente las pruebas unitarias.

## 6. Relación entre pruebas unitarias y E2E

Ambas son importantes y se complementan:

- Las pruebas unitarias validan detalles internos del código.
- Las pruebas E2E validan el flujo del sistema como un usuario lo vería.

Una estrategia recomendable es combinar ambas:

- Muchos tests unitarios
- Pocos tests E2E bien seleccionados

Esto permite equilibrar velocidad, cobertura y confianza.

## 7. Buenas prácticas en calidad de software

- Definir requisitos claros.
- Diseñar pruebas desde el inicio.
- Automatizar la ejecución de pruebas.
- Revisar errores y corregir causas reales.
- Mantener documentación actualizada.
- Realizar pruebas de regresión después de cambios.

## 8. Conclusión

La calidad de software no depende solo de que un programa funcione, sino de que cumpla con los requisitos, sea confiable, mantenible y ofrezca una buena experiencia al usuario. Las pruebas unitarias y E2E son herramientas fundamentales para asegurar esa calidad en cada etapa del desarrollo.

## 9. Resumen

- La calidad de software mide el nivel de cumplimiento del sistema.
- Los requisitos son la base del desarrollo.
- Las pruebas permiten detectar fallos y asegurar confiabilidad.
- Los tests unitarios validan pequeñas piezas del código.
- Los tests E2E validan flujos completos del usuario.

---

Este repositorio puede servir como base para estudiar y aplicar principios de calidad de software en proyectos reales.
