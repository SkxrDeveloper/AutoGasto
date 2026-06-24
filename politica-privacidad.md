# Política de Privacidad — AutoGasto

**Última actualización: 11 de junio de 2026**

AutoGasto («la app», «nosotros») es una aplicación de bienestar financiero que
registra tus gastos e ingresos de forma automática leyendo las notificaciones
de tus apps bancarias, **procesándolas exclusivamente en tu dispositivo**.

Esta política describe qué información accede la app, cómo la trata y cuáles
son tus derechos. La premisa es simple: **ningún dato tuyo sale de tu
teléfono**.

## 1. Datos a los que accede la app

- **Texto de notificaciones bancarias.** Con tu permiso explícito (acceso a
  notificaciones de Android), la app lee únicamente las notificaciones de las
  apps bancarias que tú actives dentro de AutoGasto (lista blanca). Las
  notificaciones de cualquier otra app se ignoran y no se almacenan.
- **Datos derivados.** Del texto de la notificación se extraen localmente el
  monto, el comercio, el tipo de movimiento y el banco, y se asigna una
  categoría. Eso es lo que se guarda.
- **Datos que tú capturas.** Presupuestos por categoría, correcciones
  manuales de categoría, movimientos en efectivo que registres a mano
  (monto, descripción y categoría), y tus pagos próximos y metas de ahorro
  (nombre, monto, fecha y abonos).

La app **no** accede a: SMS, contactos, ubicación, cámara, micrófono,
archivos, credenciales bancarias, ni APIs de Open Banking. No existe registro
de usuario ni cuentas.

## 2. Dónde se guardan y procesan los datos

Todo el procesamiento (lectura, análisis con expresiones regulares y
categorización) ocurre **en tu dispositivo**. Los datos se almacenan en una
base de datos local (Room/SQLite) dentro del almacenamiento privado de la app.

**AutoGasto no declara el permiso de Internet en su manifiesto Android**, por
lo que es técnicamente imposible que la app transmita información a servidores
propios o de terceros. Esto es verificable por cualquier persona inspeccionando
el paquete de la app.

## 3. Datos que se recopilan o comparten

**Ninguno.** No recopilamos, transmitimos, vendemos ni compartimos datos
personales o financieros. No usamos servicios de analítica, publicidad,
rastreo ni informes de fallos de terceros.

## 4. Exportación de datos (controlada por ti)

Puedes exportar tus movimientos a un archivo CSV mediante el selector de
archivos del sistema. Ese archivo se guarda donde tú elijas y queda bajo tu
control y responsabilidad exclusivos.

## 5. Retención y eliminación

Los datos existen solamente mientras la app esté instalada:

- **Borrar movimientos/presupuestos**: desde la propia app.
- **Borrar todo**: Ajustes de Android → Apps → AutoGasto → «Borrar datos», o
  simplemente desinstala la app. No queda copia en ningún servidor porque
  nunca existió.

## 6. Permisos que solicita la app y para qué

| Permiso | Uso |
|---|---|
| Acceso a notificaciones (`NotificationListenerService`) | Leer las notificaciones de los bancos que actives para detectar movimientos. Es la función principal de la app. |
| Notificaciones (`POST_NOTIFICATIONS`) | Avisarte localmente cuando excedes un presupuesto. |

Ambos permisos son revocables en cualquier momento desde los ajustes de
Android; la app sigue funcionando con los datos ya registrados.

## 7. Menores de edad

AutoGasto está dirigida a mayores de 18 años. No recopilamos datos de nadie,
incluidos menores.

## 8. Seguridad

Los datos residen en el almacenamiento privado de la app, protegido por el
aislamiento (sandbox) de Android: otras apps no pueden leerlos en un
dispositivo no modificado (sin root). Recomendamos proteger el teléfono con
bloqueo de pantalla.

## 9. Cambios a esta política

Si la política cambia (por ejemplo, si en el futuro se agregara una función
opcional de respaldo), publicaremos la nueva versión en esta misma URL y
actualizaremos la fecha. Cualquier cambio que implicara transmitir datos fuera
del dispositivo se anunciaría de forma prominente dentro de la app y requeriría
tu consentimiento explícito.

## 10. Aviso conforme a la LFPDPPP (México)

Para efectos de la Ley Federal de Protección de Datos Personales en Posesión
de los Particulares: AutoGasto no recaba ni trata datos personales en
servidores del responsable; el tratamiento ocurre íntegramente en el
dispositivo del titular y bajo su control. Los derechos ARCO (acceso,
rectificación, cancelación y oposición) se ejercen directamente en la app y en
los ajustes del sistema, según se describe en las secciones 4 y 5.

## 11. Contacto

Dudas o solicitudes sobre privacidad: **soporte.autogasto@gmail.com**
