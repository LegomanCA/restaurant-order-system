# Restaurant Order & Kitchen System

A multi-role restaurant ordering API: waiters take orders, the kitchen updates their status in real time, and cashiers bill the table.

**Status:** in development

## Planned features
- Role-based access (admin, waiter, cook, cashier) with JWT authentication
- Menu and table management
- Order workflow: waiter order, kitchen preparation, serving, billing
- Real-time kitchen and waiter updates with SignalR
- Automated tests and CI

## Tech stack
C#, ASP.NET Core (.NET 10), Entity Framework Core, PostgreSQL, SignalR, xUnit