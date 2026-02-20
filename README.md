# Administracion-de-permisos-de-usuario-en-linux

IMPORTANCIA DE LA GESTION DE PERMISOS EN CIBERSEGURIDAD

La administración de permisos en Linux es un pilar crítico de la seguridad informática por las siguientes razones:

PRINCIPIO DE MENOR PRIVILEGIO (POLP)
Garantiza que los usuarios y procesos tengan únicamente los permisos necesarios para realizar sus tareas específicas. Esto limita el radio de acción de un atacante en caso de que una cuenta sea comprometida.
+2

PREVENCION DE ESCALADA DE PRIVILEGIOS
El uso controlado de sudo y la restricción de permisos de ejecución (x) en directorios sensibles evitan que usuarios no autorizados obtengan acceso de root o ejecuten scripts maliciosos.
+1

PROTECCION DE DATOS SENSIBLES
Mediante el control de lectura (r) y escritura (w), se asegura que la información confidencial, como registros de sesiones o archivos de bonos, solo sea accesible por el propietario o el grupo de seguridad correspondiente.
+2

CONTROL Y AUDITORIA DE CUENTAS
La capacidad de bloquear cuentas (-L), modificar directorios de inicio (-d) o eliminar usuarios y sus archivos (-r) permite una respuesta rápida ante incidentes y una gestión eficiente del ciclo de vida de los usuarios en el sistema.
