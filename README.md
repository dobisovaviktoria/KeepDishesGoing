# KeepDishesGoing
This is a meta repository for all the components needed to run the restaurant platform.

## Author
- Viktória Dobišová

## Project Overview
A full-stack food ordering platform where restaurants manage live menus and customers place and track orders in real time, with support for staged menu updates and stock-accurate ordering.

## Components
- Backend: https://github.com/dobisovaviktoria/RestaurantWeb-backend 
- Frontend: https://github.com/dobisovaviktoria/RestaurantWeb-frontend 

## Technologies and Concepts
Backend:
- Concepts of Domain Driven Design with a rich domain, entities, aggregates, value objects, domain events
- A clear context mapping technique between bounded contexts
- Hexagonal Architecture with clear separation, boundaries, infrastructure agnostic uses cases
- Commands/events
- Event sourcing
- Projected data (derived state)
- Snapshotted event-sourced aggregate
- Secured REST endpoints

Frontend:
- React with Functional Components (hooks) and Typescript 
- Asynchronous state library like React Query
- Routing for separate pages 
- Secured application with OAuth

