# UCM — Ultimate Champion Mode

Aplicación web de fitness en español, diseñada para móvil y escritorio. Reúne planificación de fuerza, nutrición orientativa y seguimiento personal en una interfaz oscura de alto contraste con acentos lima.

## Funciones de esta versión

- Panel diario con objetivos de peso, calorías, proteína y sesiones.
- Perfil editable con edad, estatura, peso, sexo opcional para estimación energética, actividad, objetivo y presupuesto.
- Rutina semanal: cuatro sesiones principales de fuerza, dos días ligeros y un día de descanso.
- Sesión interactiva: marcar ejercicios completados y guardar el entrenamiento.
- Nutrición con menú de ejemplo y lista de compras basada en alimentos accesibles en Perú.
- Registro de peso, historial y gráfica de los últimos registros.
- Fotos de progreso reducidas en el navegador y guardadas localmente.
- Exportación e importación de copia JSON, y eliminación confirmada de datos locales.
- Diseño adaptable a móviles, navegación inferior, validación básica y mensajes de estado.

## Abrir la aplicación

Abre `index.html` en un navegador moderno. Para una URL web pública, configura GitHub Pages desde **Settings → Pages**, seleccionando la rama `main` y la carpeta raíz `/(root)`.

## Datos y privacidad

El perfil, los registros y las fotos se guardan en el almacenamiento local del navegador del dispositivo. No hay cuentas, sincronización en la nube ni backend en esta versión. Exporta una copia antes de cambiar de dispositivo o borrar los datos del navegador. No subas fotos personales al repositorio.

## Límites

- Las calorías son una estimación inicial mediante una ecuación general y un factor de actividad editable; no son una medición clínica del gasto energético.
- La planificación es una guía general, no un diagnóstico ni una prescripción médica.
- Las imágenes se guardan como referencia; la aplicación no estima de forma fiable grasa corporal a partir de fotografías.
- No hay conexión con un modelo de IA ni asesoría generativa.
- La app necesita pruebas manuales en los navegadores objetivo antes de considerarse una versión de producción.

## Enfoque inicial de UCM

Para el perfil provisional de 28 años, 170 cm y 78 kg, con trabajo de pie/caminando, la aplicación propone una referencia calórica ajustable y un objetivo de proteína cercano a 1,9 g/kg. Confirma el peso real y revisa tendencias de peso, cintura, energía y rendimiento después de 2–3 semanas antes de modificar el objetivo.