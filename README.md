
ProductOrder

## 🧩 Microservices Included

| Service Name        | Description | Port |
|---------------------|-------------|------|
| `discovery-server`  | Eureka server; service registry for all services | `8761` |
| `api-gateway`       | Routes traffic to microservices | `8080` |
| `OrderService`      | Places order, communicates with Inventory | `8081` |
| `InventoryService`  | Manages product stock | `8082` |
| `ProductService`    | Handles product details | `8083` |

-----------------------------------------------------------------------------------

## 🔧 Tech Stack

| Category        | Technology Used |
|-----------------|------------------|
| Backend         | Spring Boot (Java 17) |
| Cloud / Infra   | Spring Cloud 2024.0.0 |
| Service Registry | Eureka Discovery Server |
| Routing         | Spring Cloud API Gateway |
| Communication   | Feign Client / REST |
| Build Tool      | Maven (Multi-Module) |
| Repo Owner      | krrtk |

-----------------------------------------------------------------------------------



