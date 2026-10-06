# Política de seguridad

## Estado y alcance

`valeriasaa-lgtm/serena-mcp` está en etapa de documentación y prototipo. La presentación Startup describe una arquitectura en validación; no acredita un servidor MCP remoto de producción ni controles de seguridad ya implementados. Esta política no declara versiones soportadas ni plazos de respuesta o resolución.

Entran en alcance los riesgos de seguridad en los archivos, ejemplos y prototipos mantenidos en este repositorio:

- Exposición de credenciales o datos privados.
- Instrucciones o configuraciones inseguras.
- Fallos que puedan comprometer permisos, confirmaciones, trazabilidad o control del sistema.

Indicá si el hallazgo es conceptual o reproducible en una implementación concreta.

Los servicios y despliegues de terceros siguen sus propias políticas. Los defectos de integración atribuibles a este repositorio sí entran en alcance.

## Cómo reportar de forma privada

1. Abrí https://github.com/valeriasaa-lgtm/serena-mcp/security. Si aparece **Report a vulnerability**, usá ese formulario para enviar el reporte privado.
2. Si la opción no está disponible, abrí únicamente una Issue solicitando habilitar los reportes privados o indicar un canal privado. No incluyas detalles del hallazgo. Esperá a que se establezca ese canal antes de compartirlos.
3. Si las Issues tampoco están disponibles, será necesario que los responsables habiliten un canal privado. No publiques información sensible por otra vía pública.
4. Los responsables con permisos suficientes pueden crear un borrador de **GitHub Security Advisory** e invitar al informante para analizar el caso en privado.

La existencia de este archivo no activa los reportes privados de GitHub.

En el canal privado, incluí el archivo o componente afectado, commit o referencia, impacto, condiciones y pasos mínimos de reproducción, si corresponde. Usá datos de prueba y ocultá la información sensible en las evidencias.

**No publiques secretos, tokens, claves, datos privados, registros sensibles ni detalles explotables en Issues, Pull Requests, comentarios o adjuntos públicos.**

Si detectás un secreto expuesto, indicá su ubicación de forma privada sin copiar su valor. Su titular debe revocarlo o rotarlo: borrar el texto publicado no invalida la credencial.

Coordiná la divulgación de los detalles con los responsables mediante el canal privado. Esta política no autoriza pruebas sobre sistemas ajenos ni acceso a datos de otras personas.

Guía de GitHub:
https://docs.github.com/en/code-security/how-tos/report-and-fix-vulnerabilities/report-privately

## Cuando exista una implementación ejecutable

Antes de ofrecer un servidor MCP remoto, esta política deberá actualizarse para identificar:

- Los componentes y endpoints oficiales.
- Las versiones efectivamente soportadas.
- Un canal privado operativo.
- El procedimiento para comunicar correcciones y actualizaciones de seguridad.

El alcance deberá incluir autenticación y autorización por herramienta, aislamiento de datos, permisos y confirmaciones para acciones externas, manejo de secretos, validación de entradas, ejecución de herramientas y trazabilidad sin exposición de información sensible.

Estos son requisitos para esa etapa futura, no garantías de funciones disponibles hoy.
