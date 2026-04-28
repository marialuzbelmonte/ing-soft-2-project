CHAT GPT

Prompt: A partir de este archivo ¿podrías comentarme las ambiguedades que detectas? 

🔎 Ambigüedades detectadas
1. “Cuenta activa, suspendida o dada de baja”
❓ No se especifica:
Qué significa exactamente cada estado
Si “suspendido” permite alguna acción parcial o ninguna
💥 Problema: no queda claro el criterio exacto para mostrar el botón

2. “Mostrar el botón o no según las condiciones”
❓ ¿Qué condiciones exactamente?
Solo el estado del seguro?
También el estado de la cuenta?
💥 Falta de precisión en la lógica de UI

3. “El seguro de vida debe estar activo”
❓ ¿Puede haber más de un seguro por cuenta?
❓ ¿Qué pasa si hay varios y uno está activo?
💥 No está claro el alcance de validación

4. “Fecha de nacimiento (de 1940 en adelante)”
❓ ¿Incluye 1940?
❓ ¿Hay edad mínima/máxima adicional?
💥 Ambigüedad en validación de rango

5. “Sexo (Checkbox)”
❓ Un checkbox implica booleano (sí/no), pero sexo no lo es
💥 Debería ser:
radio button
o lista (masculino, femenino, otro, etc.)

6. “Discapacidad (Checkbox)”
❓ Si se marca:
¿se debe ingresar algún dato adicional?
💥 Falta comportamiento asociado

7. “Porcentaje de beneficio”
❓ No se indica:
tipo de dato (int, decimal)
rango permitido (ej: 1–100)
💥 Puede generar inconsistencias

8. “Persona ya existe en el sistema”
❓ ¿Cómo se determina exactamente?
¿solo por tipo + número documento?
❓ ¿Qué pasa si hay duplicados?
💥 Falta definición de unicidad

9. “Se da por sentado que la persona está viva y activa”
❓ ¿Siempre?
❓ ¿No debería validarse?
💥 Supuesto fuerte sin control

10. Autocompletado y bloqueo de campos
❓ ¿Qué campos se bloquean exactamente?
❓ ¿Se pueden desbloquear?
💥 Falta detalle funcional

11. “Campos obligatorios”
❓ ¿Qué pasa si faltan?
¿mensaje genérico o por campo?
💥 No se define comportamiento de error

12. “CUIT se autogenera”
❓ No se especifica:
algoritmo de generación
💥 Ambigüedad técnica importante

13. “Si no es DNI, deja de ser obligatorio”
❓ ¿Se puede ingresar igual?
❓ ¿Se valida formato?
💥 Regla incompleta

14. Campos de domicilio obligatorios
❓ ¿Formato de código postal?
❓ ¿Validaciones de país/provincia?
💥 Falta definición de validaciones

15. “Porcentaje no debe ser 0”
❓ ¿Puede ser negativo?
❓ ¿Puede ser decimal?
💥 Regla incompleta

16. “Debe sumar 100%”
❓ ¿Se valida en tiempo real o al guardar?
❓ ¿Qué pasa si hay 3 beneficiarios y se modifica uno?
💥 Lógica poco clara

17. “Habilitar edición de beneficiarios existentes”
❓ ¿Siempre?
❓ ¿Solo cuando se agrega uno nuevo?
💥 Ambigüedad en flujo

18. “Mensaje de error”
❓ No se especifica:
contenido
formato
💥 Falta definición UX

19. “Mostrar pantalla de beneficiarios”
❓ ¿Redirección?
❓ ¿Modal?
❓ ¿Listado editable?
💥 Ambigüedad de navegación

20. Valores posibles (listas)
❓ ¿Son fijos o configurables?
❓ ¿Se pueden ampliar?
💥 Falta definición de catálogo



