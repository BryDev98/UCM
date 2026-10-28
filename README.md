# UCM — Ultimate Champion Mode

Aplicación de fitness en español para móvil y escritorio. La dirección visual actual es **Dark Arena**: negro obsidiana, carmesí, blanco hueso y detalles metálicos.

## Funciones

- Panel de objetivos diarios de peso, calorías y proteína.
- Perfil editable con edad, estatura, peso, cintura opcional, actividad, experiencia, objetivo y presupuesto.
- Rutina semanal de cuatro sesiones principales de fuerza, dos días ligeros y un día de descanso.
- Sesión interactiva con ejercicios completados, carga en kg, repeticiones realizadas y temporizador de descanso de 90 o 120 segundos.
- Historial de entrenamientos con detalle de ejercicios, cargas y repeticiones.
- Recuento semanal de sesiones de fuerza basado en la semana natural de lunes a domingo.
- Nutrición orientativa, menú de ejemplo y lista de compras para alimentos accesibles en Perú.
- Registro de peso, gráfica de los últimos registros y tendencias simples.
- Fotos de progreso reducidas en el navegador y almacenadas localmente.
- Exportación e importación de copia JSON y eliminación confirmada de datos locales.
- Avatar de campeón 3D procedural con alternativa CSS si WebGL o la descarga de Three.js no están disponibles.
- PWA instalable con icono, manifiesto y caché básica de la interfaz para uso sin conexión.
- Diseño adaptable, navegación inferior, controles con etiquetas accesibles y mensajes de estado.

## Publicar e instalar en el móvil

La app ya incluye manifiesto, icono, botón de instalación y caché básica. Para que el navegador permita instalarla, primero debe servirse desde una URL HTTPS.

1. En GitHub abre este repositorio y entra en **Settings → Pages**. En **Build and deployment**, elige **GitHub Actions** como origen. Es una configuración inicial única; el workflow no intenta cambiar la configuración administrativa.
2. Después de activar Pages, cada actualización de `main` publicará la app. La URL de proyecto esperada es `https://brydev98.github.io/UCM/`, pero solo estará disponible cuando Pages esté habilitado correctamente.
3. En **Android**, abre esa URL desde Chrome. Pulsa **Instalar UCM** dentro de la app cuando el navegador ofrezca la instalación; si no aparece la ventana automática, usa el menú `⋮` → **Instalar aplicación** o **Añadir a pantalla de inicio**.
4. En **iPhone**, abre la URL en Safari, toca **Compartir** y elige **Añadir a pantalla de inicio**.

**Importante sobre repositorios privados:** GitHub Pages está disponible para repositorios privados con GitHub Pro, Team o Enterprise. En GitHub Free solo está disponible para repositorios públicos. No cambies la visibilidad de este repositorio principal sin decidirlo expresamente; si la cuenta no permite Pages privados, hará falta publicar únicamente una copia de distribución o usar otro hosting estático.

Si abres `index.html` como archivo local, podrás probar la interfaz, pero no instalarla como PWA ni usar su service worker.

La primera carga necesita conexión para descargar la biblioteca Three.js del avatar. Si no está disponible, la interfaz conserva una ilustración CSS alternativa.

## Datos y privacidad

El perfil, los entrenamientos, los registros de peso, la lista de compras y las fotos se guardan en el almacenamiento local del navegador del dispositivo. No hay cuentas, sincronización en la nube ni backend en esta versión. La caché de la PWA guarda la interfaz básica; no sincroniza datos entre dispositivos. Exporta una copia antes de cambiar de dispositivo o borrar los datos del navegador. No subas fotos personales al repositorio.

## Límites y seguridad

- Las calorías son una estimación general, no una medición clínica del gasto energético.
- La planificación es una guía general, no un diagnóstico ni una prescripción médica.
- Las imágenes se guardan como referencia; la aplicación no estima de forma fiable la grasa corporal a partir de fotografías.
- No hay conexión con un modelo de IA ni asesoría generativa.
- La sintaxis de JavaScript y la estructura se verifican en el flujo de desarrollo; aún deben realizarse pruebas manuales en navegadores y dispositivos reales antes de considerar la app lista para producción.

## Perfil inicial

La app comienza con valores de ejemplo de 28 años, 170 cm y 78 kg. Revisa esos valores en **Perfil** y confirma el peso real antes de usar los objetivos calculados. Un objetivo de proteína cercano a 1,9 g/kg es una referencia ajustable, no una necesidad universal.
