# Gabarito (Carnaval BH) - Schedule Management Platform

A full-stack web application for managing and sharing custom carnival event schedules (gabaritos) in Belo Horizonte. Users can discover street carnival blocos, create personalized schedules, and share them with friends. Made by 2 developers with the help of an UI/UX designer.

## Overview

This platform allows carnival enthusiasts to:
- Browse through hundreds of blocos with detailed information (dates, locations, music styles, crowd size)
- Create custom schedules ("gabaritos") with selected blocos
- Share schedules with unique short codes for easy access
- Collaborate with others through role-based permissions (owner, editor, viewer)
- Filter blocos by preferences (LGBT-friendly, kid-friendly, music style, neighborhood)
- View blocos on an interactive map with routes and concentration points

## Tech Stack

### Backend
- **Node.js** + **Express** + **TypeScript**
- **Prisma ORM** with **PostgreSQL**
- JWT authentication with security questions
- RESTful API architecture

### Frontend
- **Next.js 16** (React 19)
- **TypeScript**
- **Tailwind CSS**
- **Leaflet** (interactive maps)
- **Zustand** (state management)
- **Axios** (API client)

### Infrastructure
- Docker & Docker Compose
- Google Cloud Platform ready

## Key Features

- ✅ User authentication with security questions recovery
- ✅ Public and private schedule sharing
- ✅ Creator/Ambassador accounts for verified content
- ✅ Interactive map visualization with route coordinates
- ✅ Export schedules as images
- ✅ Real-time schedule collaboration

# Where to access

- The app was launched on January 30th and it's been upgraded continuously by CD and can be accessed at https://seugabarito.com/
