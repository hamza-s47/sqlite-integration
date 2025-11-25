## GoFiber + SQLite API
A lightweight and fast REST API built using the GoFiber web framework and SQLite as the database.
This project demonstrates a simple backend setup suitable for small-to-medium applications, prototyping, or learning Go backend development.

## Features:
- Fast HTTP server powered by GoFiber
- SQLite integration using GORM
- CRUD API endpoints
- Clean project structure
- Easy to run and extend

## Tech Stack:
- Go (Golang)
- GoFiber – Web framework
- SQLite – Lightweight embedded database
- GORM

## API Endpoints (Example):
| Method | Endpoint     | Description     |
| ------ | ------------ | --------------- |
| GET    | `/items`     | Get all items   |
| GET    | `/items/:id` | Get item by ID  |
| POST   | `/items`     | Create new item |
| DELETE | `/items/:id` | Delete an item  |
