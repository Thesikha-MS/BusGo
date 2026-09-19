# BusGo

A lightweight, zero-dependency single-page web application for searching bus routes, selecting seats via an interactive layout, simulating payment, and generating printable booking confirmations.

---

## Features

- **Dynamic Route Filtering:** Auto-updates available destinations and buses based on chosen origins.
- **Schedule Validation:** Suggests and validates travel dates according to specific weekday schedules within a rolling 30-day booking window.
- **Interactive 48-Seat Layout:** Visual 2x2 seat grid with deterministic pseudorandom bookings per route and date.
- **Local Persistence:** Retains completed bookings across page reloads using browser `localStorage`.
- **Demo Payment Flow:** Client-side validation ensuring exact fare match before processing.
- **Printable Ticket Stub:** Clean confirmation layout with dedicated CSS print rules that hide UI elements and format the ticket for paper/PDF.
- **Zero Build Dependencies:** Written in vanilla HTML5, CSS3, and standard JavaScript with Google Fonts integration.

---

## Project Structure

```text
.
└── index.html    # Standalone application containing markup, styles, and logic
