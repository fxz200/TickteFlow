# TickteFlow

Ticketing Microservice System

```
[User] --> [API Gateway (Go + JWT)] --> 各子服務：
  ├── user-service     (註冊、登入、JWT)
  ├── ticket-service   (票券查詢、下單)
  └── payment-service  (模擬付款、訂單狀態更新)
         |
         └── Redis / PostgreSQL / RabbitMQ
```
