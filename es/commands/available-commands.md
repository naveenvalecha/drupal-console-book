# Comandos Drupal Console disponibles

**Nota:** Comandos de Drupal Console que *deben* ser ejecutados desde una instalación de Drupal 8.

Comando de Drupal Console | Detalles
------------ | -------------
[about](about.md) | Muestra información básica sobre el proyecto Drupal Console
[chain](chain.md) | Ejecución de comandos en secuencia
[help](help.md) | Displays help for a command
[settings:init](settings-init.md) | Copiar archivos de configuración al directorio home del usuario.
[list](list.md) | Enlista comandos
[server](server.md) | Lanza el servidor web PHP interno
**cache**  |
[cache:rebuild](cache-rebuild.md) | Reconstruye y limpia todas las cachés del sitio.
**config**  |
[config:debug](config-debug.md) | Muestra la configuración actual.
[config:diff](config-diff.md) | Ouput configuration items that are different in active configuration compared with a directory.
[config:edit](config-edit.md) | Editar la configuración seleccionada.
[config:export](config-export.md) | Exporta la configuración actual de la aplicación.
[config:export:content:type](config-export-content-type.md) | Exporta un tipo de contenido determinado y todos sus campos.
[config:export:single](config-export-single.md) | Exportar configuración única como archivo YAML.
[config:export:view](config-export-view.md) | Exporta una vista en formato YAML dentro de un módulo para ser reutilizado en otro sitio.
[config:import](config-import.md) | Importa la configuración del estado actual de la aplicación.
[config:import:single](config-import-single.md) | Importar la configuración seleccionada.
[config:override](config-override.md) | Sobreescribir valor de la configuración activa.
[config:settings:debug](config-settings-debug.md) | Displays current key:value on settings file.
**container**  |
[container:debug](container-debug.md) | Muestra los servicios actuales de la aplicación.
**create**  |
[create:nodes](create-nodes.md) | Crea nodos de relleno para su Drupal 8.
[create:terms](create-terms.md) | Crea términos de relleno para tu Drupal 8.
[create:users](create-users.md) | Crea usuarios de prueba para tu Drupal 8.
[create:vocabularies](create-vocabularies.md) | Crea vocabularios de prueba para tu Drupal 8.
**cron**  |
[cron:debug](cron-debug.md) | Listado de módulos que implementan una llamada al cron
[cron:execute](cron-execute.md) | Ejecutar implementación de cron desde un módulo específico o todos para ejecutar todas las implementaciones
[cron:release](cron-release.md) | Desbloquea al cron para volver a ejecutarlo
**database**  |
[database:client](database-client.md) | Lanzar un cliente de base de datos si está disponible
[database:connect](database-connect.md) | Lanzar un cliente de base de datos si está disponible
[database:dump](database-dump.md) | Volcado de la estructura y contenidos de las bases de datos y tablas MySQL
[database:log:clear](database-log-clear.md) | Eliminar eventos de la tabla DBLog, filtros disponibles
[database:log:debug](database-log-debug.md) | Desplegar eventos registrados al momento para la aplicación
[database:restore](database-restore.md) | Restaurar la estructura y los contenidos de bases de datos y tablas MySQL
[database:table:debug](database-table-debug.md) | Muestra todas las tablas de una base de datos dada.
[database:table:drop](database-table-drop.md) | Elimina todas las tablas de una base de datos dada.
**generate**  |
[generate:authentication:provider](generate-authentication-provider.md) | Generar un Proveedor de Autenticación
[generate:command](generate-command.md) | Genera un comando para la consola.
[generate:controller](generate-controller.md) | Generar y registrar un controlador
[generate:doc:dash](generate-doc-dash.md) | Generar el paquete DrupalConsole.docset para Dash
[generate:doc:gitbook](generate-doc-gitbook.md) | Generar documentaciones para Comandos
[generate:entity:bundle](generate-entity-bundle.md) | Genera un nuevo tipo de contenido (nodo / bundle de entidad)
[generate:entity:config](generate-entity-config.md) | Generar una nueva entidad de configuración
[generate:entity:content](generate-entity-content.md) | Generar una nueva entidad de contenido
[generate:event:subscriber](generate-event-subscriber.md) | Genera un suscriptor de eventos
[generate:form](generate-form.md) | Generar un nuevo "FormBase"
[generate:form:alter](generate-form-alter.md) | Genera una implementación de hook_form_alter() o hook_form_FORM_ID_alter
[generate:form:config](generate-form-config.md) | Generar un nuevo "ConfigFormBase"
[generate:module](generate-module.md) | Generar a modulo.
[generate:permissions](generate-permissions.md) | Genera los permisos del módulo
[generate:plugin:block](generate-plugin-block.md) | Genera un plugin de bloque
[generate:plugin:condition](generate-plugin-condition.md) | Genera un plugin de condición.
[generate:plugin:field](generate-plugin-field.md) | Genera plugins de widget, formateador y tipo de campo.
[generate:plugin:fieldformatter](generate-plugin-fieldformatter.md) | Genera un plugin de formateador de campo.
[generate:plugin:fieldtype](generate-plugin-fieldtype.md) | Genera plugins de tipo de campo.
[generate:plugin:fieldwidget](generate-plugin-fieldwidget.md) | Genera un plugin de widget de campo.
[generate:plugin:imageeffect](generate-plugin-imageeffect.md) | Genera un plugin de efecto de imagen.
[generate:plugin:imageformatter](generate-plugin-imageformatter.md) | Genera plugins de formateador de imagen.
[generate:plugin:rest:resource](generate-plugin-rest-resource.md) | Genera un plugin de recurso rest
[generate:plugin:rulesaction](generate-plugin-rulesaction.md) | Genera un plugin de acción de rules
[generate:plugin:type:annotation](generate-plugin-type-annotation.md) | Genera un tipo de plugin con descubrimiento de anotaciones
[generate:plugin:type:yaml](generate-plugin-type-yaml.md) | Genera un tipo de plugin con descubrimiento YAML
[generate:plugin:views:field](generate-plugin-views-field.md) | Genera un plugin de campo de vista personalizado.
[generate:profile](generate-profile.md) | Generate a profile.
[generate:routesubscriber](generate-routesubscriber.md) | Generar un RouteSubscriber
[generate:service](generate-service.md) | Genera un servicio
[generate:theme](generate-theme.md) | Genera un tema.
**locale**  |
[locale:language:add](locale-language-add.md) | Agregar un idioma para ser soportado por el sitio
[locale:language:delete](locale-language-delete.md) | Eliminar un idioma soportado en el sitio
[locale:translation:status](locale-translation-status.md) | Lista de traducciones disponibles actualizadas
**migrate**  |
[migrate:debug](migrate-debug.md) | Muestra la migración actual disponible para la aplicación
[migrate:execute](migrate-execute.md) | Ejecuta una migración que esté disponible para la aplicación
[migrate:setup](migrate-setup.md) | Cargar y crear las migraciones pertinentes para una base de datos heredada
**module**  |
[module:debug](module-debug.md) | Muestra los módulos actualmente disponibles para la aplicación
[module:download](module-download.md) | Descarga un módulo o varios en la aplicación
[module:install](module-install.md) | Instala un módulo o varios en la aplicación
[module:uninstall](module-uninstall.md) | Desinstala un módulo o varios en la aplicación
**multisite**  |
[multisite:debug](multisite-debug.md) | Lista todos los sitios múltiples disponibles en el sistema
**rest**  |
[rest:debug](rest-debug.md) | Muestra el actual recurso rest para la aplicación
[rest:disable](rest-disable.md) | Deshabilita un recurso rest en la aplicación
[rest:enable](rest-enable.md) | Habilita un recurso rest para la aplicación
**router**  |
[router:debug](router-debug.md) | Muestra las rutas actuales de la aplicación
[router:rebuild](router-rebuild.md) | Reconstruye las rutas de la aplicación
**settings**  |
[settings:debug](settings-debug.md) | List user Drupal Console settings.
[settings:init](settings-init.md) | Copiar archivos de configuración al directorio home del usuario.
[settings:set](settings-set.md) | Change a specific setting value in DrupalConsole config file
**site**  |
[site:debug](site-debug.md) | Enlista todos los sitios, locales y remotos, conocidos.
[site:install](site-install.md) | Instala un proyecto Drupal
[site:maintenance](site-maintenance.md) | Poner el sitio en modo mantenimiento
[site:mode](site-mode.md) | Cambiar la configuración de rendimiento del sistema
[site:new](site-new.md) | Crea un nuevo proyecto Drupal
[site:statistics](site-statistics.md) | Show the current statistics of website.
[site:status](site-status.md) | Ver el estatus de la instalación actual de Drupal
**state**  |
[state:debug](state-debug.md) | Muestra las claves de Estado actual.
[state:override](state-override.md) | Sobreescribir una clave de Estado.
**test**  |
[test:debug](test-debug.md) | Lista los tests unitarios disponibles para la aplicación.
[test:run](test-run.md) | Ejecuta un test unitario de los disponibles en la aplicación
**theme**  |
[theme:debug](theme-debug.md) | Despliega los temas actuales para la aplicación
[theme:download](theme-download.md) | Descarga un tema para la aplicación
[theme:install](theme-install.md) | Instalar tema o temas en la aplicación
[theme:uninstall](theme-uninstall.md) | Desinstalar tema o temas en la aplicación
**translation**  |
[translation:cleanup](translation-cleanup.md) | Clenaup translation files
[translation:pending](translation-pending.md) | Determine pending translation string in a language or a specific file in a language
[translation:stats](translation-stats.md) | Generate translate stats
[translation:sync](translation-sync.md) | Sync translation files
**update**  |
[update:debug](update-debug.md) | Muestra las actualizaciones actualmente disponibles para la aplicación
[update:execute](update-execute.md) | Ejecuta una función específica de Actualizar N dentro de un módulo, o ejecutarlos todos
**user**  |
[user:debug](user-debug.md) | Muestra los usuarios actuales del sitio
[user:delete](user-delete.md) | Eliminar usuarios del sitio
[user:login:clear:attempts](user-login-clear-attempts.md) | Limpia intentos de inicio de sesión fallidos para una cuenta.
[user:login:url](user-login-url.md) | Crea una url de login de usuario de uso único.
[user:password:hash](user-password-hash.md) | Crea un hash a partir de una contraseña en texto plano.
[user:password:reset](user-password-reset.md) | Restablece la contraseña de un usuario específico.
**views**  |
[views:debug](views-debug.md) | Muestra los recursos actuales de vistas para la aplicación
[views:disable](views-disable.md) | Deshabilita una vista
[views:enable](views-enable.md) | Habilita una vista
**yaml**  |
[yaml:diff](yaml-diff.md) | Compara dos archivos YAML para encontrar las diferencias entre ambos
[yaml:merge](yaml-merge.md) | Combinar uno o más archivos de YAML en un nuevo archivo YAML. Se conservarán los valores del archivo más a la izquierda del merge.
[yaml:split](yaml-split.md) | Divide un archivo YAML usando la indentación como criterio de separación
[yaml:update:key](yaml-update-key.md) | Reemplaza una clave en un archivo YAML.
[yaml:update:value](yaml-update-value.md) | Actualiza un valor de una clave específica en un archivo YAML.

## Opciones disponibles
Opción | Detalles
-------|-------------
--help | Muestra este mensaje de ayuda
--quiet | No mostrar ningún mensaje
--verbose | Aumentar el detalle de los mensajes: 1 para salida normal, 2 para una salida más explícita y 3 para debug
--version | Muestra la versión de esta aplicación
--ansi | Forzar salida ANSI
--no-ansi | Deshabilitar salida ANSI
--no-interaction | No hacer ninguna pregunta interactiva
--env | Nombre del ambiente.
--root | Define la raíz de Drupal que se utilizará en la ejecución de los comandos
--no-debug | Desactivar el modo de depuración.
--learning | Generar código con explicaciones.
--generate-chain | Imprimir opciones y argumentos como YAML para ser usado el comando chain
--generate-inline | Imprimir opciones y argumentos de ejecución como llamada inline para ser usados en el futuro
--generate-doc | Shows command options and arguments as markdown
--target | Site name you want to interact with (for local or remote sites)
--uri | URI del sitio en Drupal que se usará (para ambientes en multi-site o cuando esta usando un puerto alternativo)
--yes | Skip confirmation and proceed

## Argumentos disponibles
Argumento | Detalles
---------|-------------
command | El comando a ejecutar
