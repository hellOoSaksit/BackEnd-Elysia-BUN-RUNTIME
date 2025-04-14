🚀 Backend 
-
Authentication API (JWT, RBAC, Refresh Token, Redis)
A secure and scalable authentication system built for modern web applications.
Includes features like JWT-based authentication, Role-Based Access Control, Session Management, and Refresh Token logic, powered by Redis for performance.




## Tech Stack
**Server:** Nest.Js , Redis , Postgresql


## .ENV
```
DATABASE_URL=""
JWT_SECRET = ""
JWT_EXPIRESIN = "5m" 
JWT_REFRESH = ""
JWT_REFRESH_EXPIRESIN = "7d"
COOKIE_SECRET = ""
BULL_HOST = 'localhost'
BULL_PORT = Number
REDIS_HOST = 'localhost'
REDIS_PORT = Number
AUTHMEMBER_TTL = Number

```
## 📌 Features


✅ User Registration & Login

✅ Role-Based Access Control (RBAC) — (Admin / User)

✅ JWT Access Token + Refresh Token System

✅ Secure Session with HTTP-only Cookies

✅ Redis for Token Storage and Caching

✅ Authentication Middleware

✅ Input Validation & Error Handling

✅ API Documentation with Swagger (optional)

✅ Project Structure Ready for Scaling



## ⚙️ Optimizations

- **Redis-powered Job Queue for Registration**  
   Used Redis to offload registration-related tasks such as sending emails and 
   storing audit logs into background jobs. This significantly improved 
   response time and reduced load on the main thread.



### API EXAMPLE
