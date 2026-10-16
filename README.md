# Día a Día — Descargas

Aplicación de diario y apuntes para Ubuntu, Windows 11 y Android 10 o posterior. Los instaladores y sus archivos de actualización están en [Releases](https://github.com/Manolo580/daiil/releases). Este repositorio contiene distribuciones e información pública; no contiene el código fuente de la aplicación ni datos personales.

[Política de privacidad](#política-de-privacidad)

## Política de privacidad

Actualizada el 16 de octubre de 2026. Esta política describe la sincronización central de Google Drive incorporada en la versión 0.8.2.

Día a Día guarda primero en el dispositivo los apuntes, páginas, clases, preferencias y archivos que añade cada persona. Al iniciar sesión en Día a Día, la aplicación sincroniza ese contenido mediante un servidor privado y una cuenta de Google Drive destinada al almacenamiento. Los PDF e imágenes se descargan cuando se necesitan. El administrador de esa cuenta de almacenamiento puede acceder a los archivos almacenados en ella.

Supabase proporciona el inicio de sesión, la base de datos de cuentas y calendario compartido, y el servicio que comprueba los permisos antes de acceder a Drive. Los perfiles personales de sincronización se separan por cuenta de Día a Día. Los participantes de funciones compartidas pueden ver la información compartida correspondiente.

Solo el administrador autoriza la cuenta de almacenamiento de Google. El permiso drive.file limita el acceso a los archivos que utiliza la aplicación. La autorización de Google se conserva cifrada en el servidor; no se distribuye dentro de los instaladores. Cada dispositivo utiliza su sesión de Día a Día, sin pedir acceso a su cuenta personal de Google. Las transferencias usan HTTPS.

El contenido se utiliza para guardar, sincronizar y recuperar los datos de Día a Día. No se vende, no se utiliza para publicidad ni para entrenar modelos de inteligencia artificial. Los registros técnicos se utilizan para diagnosticar errores y proteger el servicio. Google, Supabase y GitHub procesan los datos necesarios para prestar sus respectivos servicios conforme a sus políticas: [Google](https://policies.google.com/privacy), [Supabase](https://supabase.com/privacy) y [GitHub](https://docs.github.com/site-policy/privacy-policies/github-privacy-statement).

La aplicación conserva revisiones y archivos para recuperación y resolución de conflictos. Mover contenido a la papelera, vaciarla o desinstalar la aplicación no elimina necesariamente las revisiones históricas almacenadas en Drive. Para solicitar eliminación definitiva, exportación o resolver dudas de privacidad, contacta por el canal privado habitual con la persona que te proporcionó tu cuenta de Día a Día. No publiques apuntes, contraseñas ni archivos personales en este repositorio.

El administrador puede revocar el acceso de Día a Día desde su cuenta de Google. Si la autorización se revoca o falta espacio, la sincronización se interrumpe y se conservan los cambios locales.
