# Title
Garantizar la seguridad de la información personal de los usuarios y la integridad de los datos.

# Context
Inicialmente el requerimiento es para cientos de usuarios que necesitan recuperar las mascotas, pero en un corto plazo se necesitan extender a un numero de 1000 usuarios por lo que se necesita que el usuario sea fácil de mantener y modificar a lo largo del tiempo.

# State
Propuesto

# Decision taken:
Mantenibilidad: Realizar un diseño modular con componentes independientes que permita una mayor facilidad para mantener un modificar partes individuales del sistema sin que afecte las otras funcionalidades. Se generará una documentación exhaustiva que describa la arquitectura, los componentes, las interfaces y las decisiones de diseño tomadas. Con ello ayudará a futuros desarrolladores a comprender el sistema y facilitará el mantenimiento y la evolución del software. Versionar el código para gestionar los cambios realizados permitiendo una colaboración efectiva entre los miembros del equipo y facilitará la reversión de cambios si es necesario.

# Alternatives considered:
Capacidad para realizar pruebas automatizadas de forma continua y detectar problemas rápidamente. Implementar patrones de diseño para abordar la concurrencia de problemas.
# Consequences of the above decisions:
Mantener y modificar el código fuente a medida que evolucionan los requisitos y se agregan nuevas funcionalidades. Mejor comprensión de código para los desarrolladores actuales y futuros.

# Current state & Monitoring:
Aceptado

