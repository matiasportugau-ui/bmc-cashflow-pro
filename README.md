# BMC Cashflow Pro

**Cashflow visual y funcional para BMC Uruguay (METALOG SAS) · Panelin Finance**

Proyección de caja interactiva hecha a medida para el negocio de paneles de aislamiento.

## Características

- **3 escenarios** listos: Conservador / Base / Agresivo
- Estacionalidad real de la construcción en Uruguay (alta Oct–Mar)
- Lag de cobro (AR days) realista para B2B obras
- COGS % de paneles + fijaciones + selladores
- Flete, costos fijos, IVA neto, Capex, cuotas
- **What-if en vivo**: editá las ventas de cualquier mes y se recalcula todo
- Gráficos Chart.js (caja acumulada + inflows/outflows)
- KPIs + alertas de stress de caja
- Export CSV · Guardar en localStorage · Print
- Toggle USD ↔ UYU con tipo de cambio

## Cómo usar

1. Abrí el `index.html` en cualquier navegador (o la URL de Vercel).
2. Ajustá la **caja inicial** (BROU + efectivo).
3. Elegí escenario o ajustá los inputs de la izquierda.
4. Editá celdas de ventas en la tabla para simular un gran proyecto o retraso.
5. Exportá CSV para Excel o imprimí para la reunión.

## Defaults (Base)

| Parámetro | Valor |
|-----------|-------|
| Caja inicial | US$ 45.000 |
| Ventas base | US$ 28.000 / mes |
| Crecimiento | 3.5% mensual |
| COGS | 62% |
| Fijos | US$ 8.500 |
| AR | 35 días |
| Flete | 6% |

Hecho para que sea **realmente útil** en planeación de stock de paneles, timing de fletes y detección temprana de meses rojos.

---
METALOG SAS · BMC Uruguay · RUT 120403430012 · Maldonado
