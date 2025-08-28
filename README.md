# Movie Ticket Booking App (MERN)

> Full-stack Movie Ticket Booking application built with React, Node/Express, MongoDB — based on the tutorial video. :contentReference[oaicite:1]{index=1}

## Table of contents
- [Project Overview](#project-overview)
- [Demo](#demo)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Prerequisites](#prerequisites)
- [Project structure](#project-structure)
- [Setup & Installation](#setup--installation)
  - [Backend](#backend)
  - [Frontend](#frontend)
- [Environment variables](#environment-variables)
- [Database seeding / sample data](#database-seeding--sample-data)
- [Running the app (development)](#running-the-app-development)
- [Build & Deploy](#build--deploy)
- [API Endpoints (example)](#api-endpoints-example)
- [Authentication & Security](#authentication--security)
- [Payments (optional)](#payments-optional)
- [Testing](#testing)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## Project overview
This repository contains a full-stack Movie Ticket Booking application with separate **backend (Node + Express + MongoDB)** and **frontend (React)**. The app supports browsing movies, selecting showtimes, booking seats, user authentication, and (optionally) payment integration. The project is based on the tutorial video linked above. :contentReference[oaicite:2]{index=2}

## Demo
- Video walkthrough & deploy instructions: https://quickshow-client-steel.vercel.app. :contentReference[oaicite:3]{index=3}

## Features
- User registration & login (JWT)
- Browse movies, view details and showtimes
- Select seats and book tickets
- User booking history
- Admin area to add/update movies & shows (typical)
- Optional payment integration (Stripe recommended)
- RESTful API + React frontend

## Tech stack
- Frontend: React (create-react-app or Vite), React Router, Axios
- Backend: Node.js, Express
- Database: MongoDB (Atlas or local)
- Auth: JWT (JSON Web Tokens)
- Payment (optional): Stripe
- Deployment: Vercel / Netlify for frontend, Heroku / Render / Railway for backend, MongoDB Atlas

## Prerequisites
- Node.js (v16+ recommended)
- npm or yarn
- MongoDB (Atlas account or local instance)
- (Optional) Stripe account for payments

## Project structure (recommended)
