# Ejercicio CiberKillChain - Defensa

## Alumno

Gaspar Santamarina

## Enunciado

Desarrollar la defensa en función del ataque planteado en orden inverso.

Para cada etapa elegir una sola defensa, la más importante, considerar recursos limitados.

## Resolución

### Objectivo del ataque

Se logró el objetivo de simular un mal funcionamiento del satélite mediante la inyecciónd de telemetría falsa.

### Actions on objectives

Implementar mecanismos de validación y verificación de los datos recibidos de los nodos de usuario y del satélite. Esto puede incluir la comparación de los datos recibidos con fuentes confiables y el uso de técnicas de detección de anomalías para identificar posibles manipulaciones de datos falsos.

[Out-of-Band Communications Channel](https://attack.mitre.org/mitigations/M0810/)

### Command & Control

Implementar firewalls de aplicación para monitorear el tráfico de red y detectar cualquier actividad de comando y control sospechosa. Además, el uso de técnicas de cifrado de extremo a extremo, como SFTP, puede dificultar la interceptación y decodificación del tráfico malicioso.

[Encrypt Network Traffic](https://attack.mitre.org/mitigations/M1009/)

[Filter Network Traffic](https://attack.mitre.org/mitigations/M1037/)

### Installation

La naturaleza de este enfoque de ataque hace que sea difícil de contrarrestar mediante controles preventivos, dado que se aprovecha del uso indebido de las funcionalidades del sistema. Dicho esto, se podrían implementar políticas de seguridad que restrinjan la ejecución automática de programas y scripts en el inicio del sistema.

### Exploitation

Se puede prevenir la ejecución de código malicioso mediante el bloqueo de ejecución de scripts. Además, se deben mantener los sistemas operativos y aplicaciones actualizados con los últimos parches de seguridad.

[Execution Prevention](https://attack.mitre.org/mitigations/M1038/)

### Delivery

Los empleados deben recibir capacitación sobre cómo identificar correos de phishing y no hacer clic en enlaces o descargar archivos adjuntos sospechosos. Además, se deben implementar filtros de correo electrónico y sistemas de detección de amenazas en tiempo real para bloquear correos electrónicos de phishing antes de que lleguen a los destinatarios. Para prevenir el acceso a cuentas de usuario de los empleados, se puede reforzar las prácticas de seguridad para la gestión de contraseñas, como el uso de contraseñas fuertes y la implementación de autenticación de múltiples factores.

[Restrict Web-Based Content](https://attack.mitre.org/mitigations/M1021/)

[Software Configuration](https://attack.mitre.org/mitigations/M1054/)

[Password Policies](https://attack.mitre.org/mitigations/M1027/)

### Weaponization

La defensa contra esta técnica de ataque se vuelve complicada debido a su capacidad para evadir los controles preventivos, ya que se basa en comportamientos que se llevan a cabo fuera del alcance de las defensas y controles establecidos por la empresa.

[ Pre-compromise ](https://attack.mitre.org/mitigations/M1056/)

### Reconnaissance
Se debe minimizar la disponibilidad pública de información sensible sobre el sistema.

[ Pre-compromise ](https://attack.mitre.org/mitigations/M1056/)

