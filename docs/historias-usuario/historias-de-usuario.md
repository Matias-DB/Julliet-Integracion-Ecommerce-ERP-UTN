# Historias de usuario 

Formato: **Como** [usuario], **quiero** [funcionalidad], **para** [beneficio].
Estados del tablero: *Por Hacer* → *En Progreso* → *Listo*.

## HU-1 · Importar órdenes del ecommerce sin duplicarlas
**Como** responsable de Administración de Julliet, **quiero** que las órdenes de compra del ecommerce se importen automáticamente al ERP sin duplicarse, **para** eliminar la carga manual de pedidos y evitar errores de tipeo.

**Criterios de aceptación**
- Cada orden nueva aparece en el ERP como Pedido en estado *Pendiente*.
- Si la orden ya fue importada, se descarta y se registra como duplicada.
- Cada importación queda asentada en el Registro de Sincronización.

**Prioridad:** Alta

## HU-2 · Validar y reservar stock
**Como** encargado/a del Depósito Ecommerce, **quiero** que el sistema valide y reserve el stock al ingresar un pedido y me indique qué preparar, **para** no vender productos sin stock y despachar más rápido.

**Criterios de aceptación**
- Si hay stock, se reserva y el pedido pasa a *Preparando*.
- Si no hay stock, el pedido pasa a *Cancelado* y se notifica a la clienta.
- El stock actualizado se refleja en el ecommerce en menos de 60 segundos.

**Prioridad:** Alta

## HU-3 · Facturar y comunicar el estado de la compra
**Como** clienta de Julliet, **quiero** recibir mi factura y el estado de mi compra en la tienda online, **para** tener mi comprobante y saber que mi pedido fue procesado.

**Criterios de aceptación**
- Al confirmarse la preparación, el ERP emite la factura.
- Si la factura se emite correctamente, el pedido pasa a *Facturado* y el comprobante se envía a la clienta.
- Si la emisión falla, se genera una alerta para revisión manual de Administración.

**Prioridad:** Media
