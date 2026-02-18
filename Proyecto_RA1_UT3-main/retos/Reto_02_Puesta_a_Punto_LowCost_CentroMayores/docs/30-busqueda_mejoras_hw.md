# 30 — Búsqueda y selección de mejoras de **hardware**

## Objetivo
Identificar **mejoras mínimas de hardware** que permitan que los equipos del lote sean **usables** en un centro de mayores (web, correo, videollamadas y ofimática online), respetando los escenarios **S0/S1/S2** y un presupuesto muy ajustado.

---

## 1) Piezas candidatas (con enlaces y capturas)

> Capturas guardadas en `../assets/img/30-hw/` con URL completa y fecha/hora visibles.

### Almacenamiento (SSD 2.5")
| Categoría | Marca / Modelo | Capacidad | Precio (€) | Tienda | URL | Captura |
|---|---|---:|---:|---|---|---|
| SSD | KingDian S280 | 120 GB | 14,99 | Amazon ES | https://www.amazon.es/ | ![SSD](../assets/img/30-hw/51Vl3OYn4HL._AC_SY300_SX300_QL70_ML2_.jpg "SSD") |
| SSD | Goodram CX400 | 128 GB | 16,90 | PcComponentes | https://www.pccomponentes.com/ | ![SSD](../assets/img/30-hw/a.png "SSD") |

### Memoria RAM (DDR2)
| Categoría | Marca / Modelo | Capacidad | Frecuencia | Precio (€) | Tienda | URL | Captura |
|---|---|---:|---:|---:|---|---|---|
| RAM | Kingston ValueRAM | 2 GB | DDR2-800 | 8,00 | Wallapop (2ª mano) | https://es.wallapop.com/ | ![RAM](../assets/img/30-hw/aa.png "RAM") |
| RAM | Samsung OEM | 2 GB | DDR2-667 | 7,50 | Wallapop (2ª mano) | https://es.wallapop.com/ | ![RAM](../assets/img/30-hw/aaa.png "RAM") |

### Mantenimiento
| Categoría | Marca / Modelo | Descripción | Precio (€) | Tienda | URL | Captura |
|---|---|---|---:|---|---|---|
| Pasta térmica | Arctic MX-4 | Jeringa 4 g | 2,00 | Amazon ES | https://www.amazon.es/ | ![Pasta](../assets/img/30-hw/aaaaa.png "Pasta térmica") |
| Adaptador | 2.5" → 3.5" | Caddy / bandeja metálica | 2,50 | PcComponentes | https://www.pccomponentes.com/ | ![Adaptador](../assets/img/30-hw/aaaa.png "Adaptador") |

### Otros (si procede)
| Categoría | Marca / Modelo | Descripción | Precio (€) | Tienda | URL | Captura |
|---|---|---|---:|---|---|---|
| Wi-Fi USB | TP-Link TL-WN725N | USB 2.0 · 150 Mbps | 6,00 | Amazon ES | https://www.amazon.es/ | ![WiFi](../assets/img/30-hw/aaaaaa.png "Adaptador Wi-Fi") |

---

## 2) Compatibilidad técnica (justificación)

- **RAM:**  
  La placa HP Compaq 7800 utiliza **DDR2 DIMM**, con hasta **4 slots** y soporte típico de hasta **8 GB**. Los módulos propuestos (DDR2-667 / DDR2-800, 1.8 V) son compatibles con el chipset **Intel Q35** y procesadores Core 2 Duo.  
  *Fuente:* manual y hoja técnica de la placa base (captura incluida).

- **SSD:**  
  Los equipos disponen de interfaz **SATA (SATA II)**. Los SSD **2.5" SATA** son totalmente compatibles y retrocompatibles. Para su instalación se utiliza un **adaptador 2.5" → 3.5"**.  
  *Fuente:* especificaciones del fabricante del SSD (captura incluida).

- **Otros:**  
  El adaptador **Wi-Fi USB** requiere un puerto USB 2.0 libre, disponible en los equipos analizados. No existen conflictos de espacio ni de alimentación.

---

## 3) Mini-estimación de impacto

- **HDD → SSD:**  
  Mejora notable en tiempos de arranque y apertura de aplicaciones, pasando de minutos a segundos. Incremento claro de la fluidez general del sistema.

- **RAM (1–2 GB → 4 GB):**  
  Reducción de bloqueos y uso de memoria virtual. Mejora la multitarea ligera (navegador, correo y videollamadas).

- **Mantenimiento (pasta térmica / limpieza):**  
  Disminución de temperatura y ruido, mejor estabilidad y mayor vida útil del equipo.

---

## 4) Escenario elegido y desglose de gasto (S1)

| Escenario | Pieza | Precio (€) | Unidades | Subtotal (€) | Nota |
|---|---|---:|---:|---:|---|
| S1 | SSD 120 GB | 15,00 | 1 | 15,00 | Oferta / 2ª mano |
| S1 | Pasta térmica | 2,00 | 1 | 2,00 | Tubo compartido |
| S1 | Adaptador 2.5" → 3.5" | 2,50 | 1 | 2,50 | Necesario para montaje |
|  |  |  |  |  |  |
| **Total HW** |  |  |  | **19,50 €** | Dentro del presupuesto |

> El **Total HW** se trasladará a `75-plan_presupuesto_hw_y_roi.md` para el cálculo de costes y ROI.
