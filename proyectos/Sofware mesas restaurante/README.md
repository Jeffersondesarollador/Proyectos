# Software Web – Gestión de Mesas y Reservas de Restaurante

Aplicación web desarrollada para la gestión de mesas y reservas en un restaurante.  
El sistema es completamente funcional y maneja la persistencia de datos mediante localStorage.

---

## 🛠 Tecnologías utilizadas
- HTML5
- CSS3
- JavaScript
- localStorage
- Librería externa para control de tiempo
- setInterval para actualización en tiempo real

---

## 📌 Requerimientos Funcionales

### RF1: Gestión de Mesas
- Inicialización de un arreglo de mesas en localStorage al cargar la aplicación.
- Cada mesa contiene:
  - `id`
  - `capacidad`
  - `ubicacion`
  - `estado` (Disponible, Ocupada, Deshabilitada)

---

### RF2: Gestión de Reservas
- Creación de reservas con los siguientes datos:
  - idReserva
  - nombreCliente
  - numeroPersonas
  - fechaReserva
  - horaReserva
  - ocasionEspecial (opcional)
  - notasAdicionales (opcional)
  - idMesaAsignada
  - estado (Pendiente, Confirmada, Cancelada, Finalizada, No Show)

---

### RF3: Validaciones
- Validación de campos obligatorios
- Validación de fechas futuras
- Validación de horario (8:00 AM – 8:00 PM)
- Validación de disponibilidad de mesas

---

### RF4: Visualización
- Plano visual del restaurante mediante cards:
  - Verde: Disponible
  - Azul: Ocupada
  - Negro: Deshabilitada
- Acciones por mesa:
  - Editar
  - Reservar
  - Eliminar
- Visualización de reservas en tarjetas
- Lista desplegable de mesas disponibles
- Lista de ocasiones especiales (mínimo 8), con imagen según la ocasión
- Acciones por reserva:
  - Editar
  - Pagar
  - Eliminar

---

### RF5: Modificación de Reservas
- Cambio de estado de la reserva
- Cancelación de reservas

---

### RF6: Filtros
- Filtro por fecha
- Filtro por estado

---

## 📌 Requerimientos No Funcionales

- Interfaz intuitiva
- Formularios en modales
- Persistencia de datos con localStorage
- Manejo de errores con mensajes claros (sin alertas del navegador)

---

## Estado del proyecto
✅ Funcional
