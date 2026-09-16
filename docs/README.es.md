# SwipePhoto · 轻扫相册

[English](../README.md) · [简体中文](README.zh-CN.md) · [Español](README.es.md)

Organizador de fotos sin conexión para **Android 11 o posterior**, creado por **卢文杰**. Revisa una foto a la vez con cuatro gestos. La aplicación admite chino simplificado, inglés y español.

**Gratis para uso personal y no comercial. Sin cuenta, anuncios, compras integradas ni permiso de internet.** Este repositorio solo distribuye el APK y la documentación. No se publica el código fuente de la aplicación; no es una publicación de código abierto.

## Descargar e instalar

**[Descargar SwipePhoto 0.4.0 APK](https://github.com/wenjielogic/SwipePhoto/releases/download/v0.4.0/SwipePhoto-0.4.0.apk)** · [Página de la versión](https://github.com/wenjielogic/SwipePhoto/releases/tag/v0.4.0)

1. Abre el enlace en tu teléfono Android y descarga `SwipePhoto-0.4.0.apk` (unos 3,4 MB).
2. Abre el APK desde las descargas del navegador o el gestor de archivos. Si Android lo pide, permite que ese navegador o gestor instale aplicaciones de esta fuente.
3. Si tienes una versión oficial anterior, instala la actualización encima. **No desinstales primero la versión anterior.**
4. Abre SwipePhoto y permite el acceso a las fotos. En Android 14 o posterior puedes dar acceso solo a las fotos seleccionadas.

Descarga el archivo `.apk`. Los archivos «Source code» generados automáticamente por GitHub contienen la documentación de este repositorio, no el código fuente de la aplicación ni un instalador. Es una **versión de prueba**, no una publicación en Play Store. Empieza con algunas fotos de prueba que no sean importantes.

## Cuatro direcciones

| Dirección | Resultado |
| --- | --- |
| **Izquierda** | Añade la foto a **Eliminar**. Solo se mueve a la papelera del sistema después de confirmar el grupo. |
| **Derecha** | Conserva la foto original sin cambios. |
| **Arriba** | Añade la foto a los **Favoritos** de esta aplicación. No cambia la marca de favorito de la galería del sistema. |
| **Abajo** | Verifica tu identidad, guarda y comprueba las copias cifradas y después pide confirmar la eliminación del original público. |

Los cuatro botones realizan las mismas acciones. Toca la foto para ampliarla y usa dos dedos para ajustar el zoom. **Deshacer** revierte las decisiones locales recientes. El aviso aparece junto a **Todas las fotos** y no tapa el botón. Las fotos ya enviadas a la papelera o transferidas al álbum privado tienen sus propias opciones de restauración o exportación.

Usa **Buscar fotos** para añadir fotos nuevas. El progreso se guarda automáticamente.

## Idioma

Abre **Ajustes → Idioma** y elige **简体中文**, **English** o **Español**. El primer inicio está en chino simplificado: toca **设置 → 语言 → Español**. Se conserva la selección al reiniciar. Los diálogos propios de Android pueden usar el idioma del teléfono.

## Álbum privado y recuperación tras desinstalar

- Abre **Ajustes → Álbum privado**. Usa el código de bloqueo del teléfono o una huella compatible. El álbum se bloquea al salir de la aplicación o después de unos cuatro minutos.
- Los archivos cifrados recuperables se guardan en **Almacenamiento del teléfono → Download → 私密相册**, con la extensión `.swpv`. El nombre de la carpeta permanece en chino con cualquier idioma.
- La contraseña de los archivos cifrados es **`123456`**, fija en esta versión. Es distinta del código de bloqueo del teléfono. Es fácil de adivinar y solo dificulta las miradas casuales.
- El original público sigue visible hasta que apruebes su eliminación. Android solicitará confirmar la **eliminación definitiva**. Las copias en la nube, en la papelera o en otros lugares no se borran automáticamente.
- Elige **Exportar a la galería** para recuperar una foto pública en `Pictures/SwipePhoto`. Se conserva la copia privada.

**Antes de desinstalar, abre Ajustes → Protección al desinstalar y recuperación → Verificar y guardar todas las fotos privadas. Comprueba que no quede nada sin completar.** Es especialmente importante para las fotos importadas con versiones anteriores. Mantén la aplicación en primer plano durante el proceso.

Los archivos cifrados compartidos guardados correctamente normalmente se conservan tras desinstalar, pero **no se descifran automáticamente**. Para recuperarlos:

1. Reinstala el APK oficial y abre **Ajustes → Protección al desinstalar y recuperación → Elegir archivos cifrados para recuperar**.
2. Selecciona los archivos `.swpv` de `Download/私密相册`. Mantén pulsado para elegir varios o usa la opción Seleccionar todo del selector de archivos.
3. Introduce **`123456`** y verifica tu identidad en el teléfono.
4. Abre las fotos recuperadas en **Álbum privado** o expórtalas a la galería.

Al desinstalar se borran los datos internos y las copias privadas que no se hayan guardado correctamente en la carpeta compartida. Borrar estos archivos, perder el teléfono o restablecerlo puede causar pérdida de fotos. Copia la carpeta cifrada a otro dispositivo como respaldo. La galería no muestra las fotos cifradas, pero el gestor de archivos puede ver los archivos.

## Aviso de uso gratuito y prohibición de uso comercial

**Creador: 卢文杰. Esta herramienta se ofrece públicamente de forma gratuita. Se prohíben el uso comercial, la distribución de pago, la reventa, la monetización y la eliminación o sustitución de la atribución del creador sin su autorización previa por escrito.**

Puedes descargar, instalar y compartir gratuitamente el APK oficial sin modificar para uso personal y no comercial, conservando la atribución y los avisos. Consulta la [licencia y el aviso en tres idiomas](../LICENSE.md). Los componentes de terceros mantienen sus propias licencias.

## Autenticidad y pruebas

- Versión: **0.4.0**; paquete: `dev.local.swipephoto`; sistema mínimo: Android 11.
- SHA-256 del APK: `e6567b5d1e41b938226f4a127a125c25c5599cd9eb6eb5a600f6d6b75323e22d`.
- SHA-256 del certificado de firma: `818b0c29f9fa5338f8e6228d5491a6ef8802c0602aa94cfa35836d3b4afdf560`.
- Conserva el certificado de prueba oficial anterior para permitir actualizar sin desinstalar. La compilación distribuida tiene la depuración desactivada y el código ofuscado.
- Incluye marcas del creador y comprobaciones de firma y atribución. Ayudan a detectar modificaciones comunes, pero no garantizan que nadie pueda quitar las comprobaciones o volver a empaquetar la aplicación.
- Superó 30 pruebas JVM y las comprobaciones de idioma, deshacer y actualización de fotos privadas en emuladores de Android 11 y 14. También se detectaron APK con firma cambiada o marca modificada. Esto no garantiza compatibilidad con todos los teléfonos ni sustituye las copias de respaldo.

Para informar de un problema reproducible, abre un [Issue](https://github.com/wenjielogic/SwipePhoto/issues) con la versión de Android, el modelo y los pasos. No publiques fotos privadas, álbumes cifrados ni contraseñas.
