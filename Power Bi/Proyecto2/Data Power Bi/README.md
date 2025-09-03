# 📑 Diccionario de Datos – Hotel Bookings

Este documento describe las variables contenidas en el dataset `hotel_bookings.csv`.  
El dataset contiene información sobre reservas de hoteles (City Hotel y Resort Hotel), incluyendo datos de clientes, tiempos de reserva, cancelaciones y características de la estadía.

---

## 🏨 Identificación general
| Variable                 | Descripción                                                                 |
|---------------------------|-----------------------------------------------------------------------------|
| `hotel`                  | Tipo de hotel: *City Hotel* o *Resort Hotel*.                               |
| `is_canceled`            | Indica si la reserva fue cancelada (1 = Sí, 0 = No).                        |
| `reservation_status`     | Estado final de la reserva (*Check-Out*, *Canceled*, *No-Show*).            |
| `reservation_status_date`| Fecha en la que ocurrió el estado de la reserva.                            |

---

## 📅 Fechas y tiempos
| Variable                     | Descripción                                                           |
|-------------------------------|-----------------------------------------------------------------------|
| `lead_time`                  | Días entre la fecha de reserva y la fecha de llegada.                  |
| `arrival_date_year`          | Año de llegada.                                                        |
| `arrival_date_month`         | Mes de llegada.                                                        |
| `arrival_date_week_number`   | Número de semana del año de llegada.                                   |
| `arrival_date_day_of_month`  | Día del mes de llegada.                                                |

---

## 👥 Composición de huéspedes
| Variable       | Descripción                                 |
|----------------|---------------------------------------------|
| `adults`       | Número de adultos en la reserva.            |
| `children`     | Número de niños en la reserva.              |
| `babies`       | Número de bebés en la reserva.              |

---

## 📦 Estancia y duración
| Variable                    | Descripción                                                         |
|------------------------------|---------------------------------------------------------------------|
| `stays_in_weekend_nights`    | Número de noches de fin de semana (sábado y domingo).               |
| `stays_in_week_nights`       | Número de noches entre semana.                                      |
| `total_of_special_requests`  | Cantidad de solicitudes especiales (ej.: cama adicional, vista).    |

---

## 💲 Finanzas y tarifas
| Variable | Descripción                                                                 |
|----------|-----------------------------------------------------------------------------|
| `adr`    | Tarifa diaria promedio (ingresos totales de alojamiento ÷ noches ocupadas). |

---

## 🌍 Origen y mercado
| Variable            | Descripción                                                                 |
|----------------------|-----------------------------------------------------------------------------|
| `country`           | País de origen del cliente (código ISO).                                    |
| `market_segment`    | Segmento de mercado (ej.: Online TA, Directo, Corporativo, etc.).           |
| `distribution_channel` | Canal de distribución (ej.: TA/TO = agencias de viajes/tour operadores). |

---

## 🛏️ Habitaciones
| Variable                 | Descripción                                            |
|---------------------------|--------------------------------------------------------|
| `reserved_room_type`      | Tipo de habitación reservada.                          |
| `assigned_room_type`      | Tipo de habitación asignada finalmente.                |
| `required_car_parking_spaces` | Número de espacios de estacionamiento solicitados. |

---

## 📈 Información operativa
| Variable                       | Descripción                                                           |
|--------------------------------|-----------------------------------------------------------------------|
| `previous_cancellations`       | Número de cancelaciones previas del cliente.                          |
| `previous_bookings_not_canceled` | Reservas previas no canceladas.                                      |
| `booking_changes`              | Número de cambios hechos a la reserva.                                |
| `deposit_type`                 | Tipo de depósito (*No Deposit, Non Refund, Refundable*).              |
| `customer_type`                | Tipo de cliente (*Transient, Contract, Group, Transient-Party*).      |
| `agent`                        | ID del agente de viajes que gestionó la reserva.                      |
| `company`                      | ID de la compañía (si aplica).                                        |

---

📌 **Total de variables:** 32  
📌 **Filas del dataset:** cada fila representa una reserva de hotel.
