# School Management API — Postman Collection

Postman collection for testing the School Management API.

## Import
1. Download `School_Management_API.postman_collection.json`
2. Open Postman → Import → upload the file

## Base URL
https://school-api-production-24e5.up.railway.app
## Requests Included
| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/` | Health check |
| POST | `/addSchool` | Add a new school |
| POST | `/addSchool` | Validation error example |
| GET | `/listSchools?latitude=28.6139&longitude=77.2090` | List schools by proximity |
| GET | `/listSchools` | Missing params error example |
