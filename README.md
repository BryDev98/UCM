# UCM — Ultimate Champion Mode

Aplicación web móvil en español para organizar entrenamiento de gimnasio, registrar el peso y seguir hábitos de nutrición y progreso.

## Estado actual

Primera versión funcional construida como sitio estático en `index.html`. No requiere instalación de dependencias ni claves de API.

### Funciones incluidas
- Perfil físico editable: edad, estatura, peso, objetivo, experiencia y disponibilidad.
- Rutina semanal de ejemplo para principiante, con ejercicios, series y repeticiones.
- Registro de sesiones y peso corporal.
- Historial local y exportación de datos en JSON.
- Referencia visual inicial y objetivo guardadas localmente en el navegador.
- Guía de nutrición con ideas de alimentos accesibles en Perú.
- Interfaz adaptable a pantallas móviles.

## Ejecutar

Abre `index.html` en un navegador o activa GitHub Pages en **Settings → Pages**, seleccionando la rama `main` y la carpeta `/(root)`.

## Limitaciones importantes
- Los datos y las fotos permanecen en el almacenamiento local del navegador de ese dispositivo; no hay cuenta de usuario ni sincronización entre dispositivos.
- Las recomendaciones nutricionales son orientativas y no sustituyen atención profesional.
- Las fotografías se usan como referencia visual; la app no estima con precisión grasa corporal ni medidas a partir de imágenes.
- Los registros de entrenamientos no incluyen todavía una bitácora detallada por ejercicio/carga.
- No hay backend ni entrenador generativo conectado a un modelo de IA en esta versión.

## Próximos pasos sugeridos
1. Probar el flujo en móvil y corregir errores.
2. Añadir registro de series, repeticiones y cargas por ejercicio.
3. Implementar autenticación y base de datos para sincronizar el progreso con seguridad.
4. Añadir revisión de accesibilidad y pruebas automatizadas.
5. Conectar funciones de IA solo después de definir proveedor, privacidad, costes y límites de uso.

## Privacidad
No subir fotos personales al repositorio. En esta versión las fotos se seleccionan desde el dispositivo y se almacenan en el navegador del usuario.
