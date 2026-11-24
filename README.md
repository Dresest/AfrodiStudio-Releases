# AfrodiStudio Desktop — Actualizaciones oficiales

Este repositorio público es exclusivamente el canal de distribución de AfrodiStudio Desktop para Windows de 64 bits. El repositorio de desarrollo permanece privado.

## Descargas

Las versiones autorizadas se publicarán en [Releases](https://github.com/Dresest/AfrodiStudio-Releases/releases). Actualmente el canal está en preparación; no hay instaladores publicados ni una versión comercial validada.

Cada actualización estable incluirá:

- `AfrodiStudio-Setup-VERSION.exe`: instalador.
- `update.json`: manifiesto con versión, tamaño, SHA-256 y compatibilidad de esquema.
- `update.sig`: firma digital Ed25519 del manifiesto.

El programa verificará la firma y la integridad del instalador con una clave pública incorporada. Si las descargas automáticas están habilitadas, la instalación requerirá confirmación administrativa y un respaldo local previo. No se almacenan credenciales, información de clientes ni bases de datos en este repositorio.

La firma del manifiesto no equivale a una firma Authenticode de Windows. Utiliza exclusivamente las versiones autorizadas y consulta las notas de cada publicación.
