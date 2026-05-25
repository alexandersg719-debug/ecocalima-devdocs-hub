# API de EcoCalima

## Endpoints principales

### Obtener actividades

```http
GET /api/actividades
```

---

### Crear reserva

```http
POST /api/reservas
```

---

### Obtener recompensas

```http
GET /api/recompensas
```

---

## Formato JSON

```json
{
  "usuario": "Alexander",
  "actividad": "Kayak",
  "fecha": "2026-05-24"
}
```

---

## Respuesta esperada

```json
{
  "status": "success",
  "mensaje": "Reserva creada correctamente"
}
```