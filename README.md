# Django-LittleLemon-API-Advanced
A comprehensive API solution powering Little Lemon restaurant's digital services, enabling developers to create both web and mobile applications. The system features role-based access control, allowing different users to perform various operations from menu management to order fulfillment.

Features:

System Capabilities

Administrator Powers:
1. Manage user roles by assigning manager positions
2. Secure access to manager functions via admin tokens
3. Control menu content through item addition
4. Create and manage menu categories

Manager Functions:
5. Secure system access through login
6. Daily menu management capabilities
7. Delivery team personnel management
8. Order assignment control for delivery staff

Delivery Team Access:
9. View and manage assigned deliveries
10. Update delivery status of orders

Customer Features:
11. Account creation functionality
12. Secure login system with token authentication
13. Complete category browsing
14. Full menu access and viewing
15. Category-based menu filtering
16. Support for menu pagination
17. Price-based menu sorting
18. Shopping cart item management
19. Persistent cart item storage
20. Order placement capabilities
21. Personal order history tracking


API Endpoints:

---User Registration and Token Generation Endpoints:

•	/api/users
•	/api/users/users/me/
•	/token/login/

---Menu Item Endpoints:

•	/api/menu-items
•	/api/menu-items
•	/api/menu-items/{menuItem}
•	/api/menu-items/{menuItem}
•	/api/menu-items
•	/api/menu-items
•	/api/menu-items/{menuItem}
•	/api/menu-items/{menuItem}
•	/api/menu-items/{menuItem}

---User group management endpoints:

•	/api/groups/manager/users
•	/api/groups/manager/users
•	/api/groups/manager/users/{userId}
•	/api/groups/delivery-crew/users
•	/api/groups/delivery-crew/users
•	/api/groups/delivery-crew/users/{userId}

---Cart management endpoints:

•	/api/cart/menu-items
•	/api/cart/menu-items
•	/api/cart/menu-items

---Order management endpoints:

•	/api/orders
•	/api/orders
•	/api/orders/{orderId}
•	/api/orders
•	/api/orders/{orderId}
•	/api/orders/{orderId}
•	/api/orders
•	/api/orders/{orderId}

