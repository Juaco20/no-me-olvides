# No Me Olvides · Beta

Prototipo navegable de **No Me Olvides**, una plataforma de bienestar creativo (arte, escritura y lectura) que psicólogos, clínicas y centros de salud ofrecen a sus pacientes como complemento entre sesiones.

Proyecto del ramo Creación de Empresas, Ingeniería Comercial, Universidad Viña del Mar.

## Qué incluye

- **Cuentas reales con Firebase:** ingreso y registro con correo o con Google, recuperación de contraseña y datos sincronizados en vivo en Firestore (región Santiago). Profesionales y pacientes se vinculan con el código del profesional. Cuentas de prueba: `camila@nomeolvides.demo` y `martina@nomeolvides.demo`, clave `demo1234`.
- **Presentación:** modelo B2B2C, valor para cada actor y planes freemium (Gratis, Pro, Centro).
- **Panel profesional:** pacientes, ánimo de los últimos días, señales para la próxima sesión, biblioteca curada e invitaciones con código.
- **App del paciente:** ingreso con código, consentimiento, test de perfil creativo, check-in diario, actividades, diario, comunidad y botón de ayuda (*4141 y 131).

## Importante

Es una beta académica: usa solo datos de prueba, no información real de pacientes. Las reglas de Firestore limitan el acceso para que cada paciente vea solo lo suyo y cada profesional solo a sus pacientes; el diario privado y las notas de sesión no se comparten. No es una terapia ni reemplaza la atención profesional. Los precios son referenciales.

## Publicación

Es un sitio estático (un solo `index.html`). Se publica en Vercel importando este repositorio, sin configuración adicional.
