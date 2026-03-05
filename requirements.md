# Backend Requirement Specifications

## 1. User Authentication

**Endpoints**
- `POST /api/v1/auth/register`  
- `POST /api/v1/auth/login`  
- `POST /api/v1/auth/logout`  
- `POST /api/v1/auth/forgot-password`

**Input example (register)**  
```json
{
  "email": "user@example.com",
  "password": "securePass123!",
  "first_name": "Korkou",
  "last_name": "Justus",
  "role": "guest"          // or "host"
}
