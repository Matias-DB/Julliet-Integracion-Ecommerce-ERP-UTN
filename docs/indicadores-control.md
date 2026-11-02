# Indicadores de control (KPIs)

Los indicadores son los **estándares** contra los que se mide el módulo (etapa de *Control* del proceso administrativo): se mide, se compara con la meta y, si hay desvío, se corrige.

| Indicador | Fórmula | Meta | Fuente de datos | Frecuencia |
|---|---|---|---|---|
| Operaciones sin intervención manual | Pedidos procesados sin intervención / pedidos totales × 100 | ≥ 98 % | Registro de Sincronización | Semanal |
| Actualización de stock a tiempo | Actualizaciones en menos de 60 s / actualizaciones totales × 100 | ≥ 95 % | Registro de Sincronización | Semanal |
| Ventas sincronizadas | Órdenes del ecommerce presentes en el ERP / órdenes del ecommerce × 100 | ≥ 95 % | Ecommerce vs. ERP | Semanal |
| Cumplimiento del plazo | Semanas reales / semanas planificadas | ≤ 12 semanas | Diagrama de Gantt | Por etapa |
| Cancelaciones por falta de stock | Pedidos cancelados por stock / pedidos totales × 100 | A monitorear | Estado del Pedido | Mensual |
| Tiempo orden → factura | Promedio entre la importación de la orden y la emisión de la factura | A monitorear | Registro de Sincronización | Mensual |

**Acción correctiva:** si un indicador queda fuera de meta, se revisa el Registro de Sincronización para identificar la causa (por ejemplo, demoras en la actualización de stock o errores de facturación) y se ajusta el proceso.
