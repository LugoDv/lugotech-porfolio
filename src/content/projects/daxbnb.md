---
title: "Daxbnb - Airbnb Clone"
description: "Desarrollé un sistema completo de alquiler vacacional donde el desafío principal fue la lógica de disponibilidad. Implementé un motor de reservas en tiempo real que previene conflictos de fechas y un sistema de filtros avanzados que permite segmentar búsquedas por precio, ubicación y características, garantizando una respuesta inmediata del servidor."
image: "../../assets/images/daxbnb.png"
projectUrl: "https://github.com/yourusername/daxbnb"
technologies: ["Java", "MySQL", "Bootstrap", "Docker"]
featured: true
publishedDate: 2024-10-15
order: 1
icon: "house"
---

# Daxbnb - Vacation Rental Platform

A comprehensive vacation rental platform inspired by Airbnb, featuring a modern UI and robust backend infrastructure.

## Key Features

- **Property Listings:** Browse and search available properties with advanced filters
- **User Authentication:** Secure login/signup with JWT tokens
- **Booking System:** Real-time availability calendar and instant booking
- **Payment Integration:** Secure payments with Stripe
- **Reviews & Ratings:** Users can leave reviews and ratings for properties
- **Responsive Design:** Fully responsive across all device sizes

## Technical Highlights

- Built with React and TypeScript for type safety
- Node.js/Express backend with PostgreSQL database
- RESTful API architecture
- Tailwind CSS for modern, responsive styling
- JWT-based authentication
- Real-time notifications

## Challenges & Solutions

One of the main challenges was implementing the real-time booking calendar to prevent double bookings. This was solved using database transactions and optimistic locking.
