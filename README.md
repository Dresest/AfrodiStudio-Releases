# AfrodiStudio Desktop — Actualizaciones oficiales

Canal público de distribución de AfrodiStudio Desktop para Windows de 64 bits. El código fuente permanece en el repositorio privado de desarrollo.

Las versiones autorizadas estarán en [Releases](https://github.com/Dresest/AfrodiStudio-Releases/releases). Este canal está en fase piloto; solo se publicarán instaladores validados.

Cada publicación incluye:
- `AfrodiStudio-Setup-VERSION.exe`: instalador.
- `update.json`: manifiesto generado durante la compilación con versión, tamaño, SHA-256 y esquema compatible.

A partir de 0.7.1, AfrodiStudio comprueba versiones por HTTPS, contrasta hashes y tamaños con GitHub, descarga en segundo plano y solicita autorización administrativa antes de instalar al cerrar. Se exige un respaldo local verificado. No se necesitan claves, tokens ni cuentas de GitHub en los computadores de los usuarios.

El canal piloto no utiliza firma digital independiente. SHA-256 comprueba integridad respecto de GitHub, no protege contra el compromiso de la cuenta de publicación. No contiene información de clientes ni bases de datos. No se ha validado todavía el proceso completo de actualización remota ni la distribución comercial.
