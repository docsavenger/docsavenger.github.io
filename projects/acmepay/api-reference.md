# API Reference

The AcmePay API reference provides a structured description of the available API endpoints, authentication requirements, request parameters, responses, and data models.

The API is described using the OpenAPI Specification.

> **Note:** AcmePay is a fictional API created for this technical writing portfolio.

---

## OpenAPI Specification

The complete API definition is available in the following file:

[View the OpenAPI Specification](openapi.yaml)

The specification describes:

- Available API endpoints
- HTTP methods
- Authentication
- Request parameters
- Request bodies
- Response formats
- HTTP status codes
- Data schemas

---

## Available Endpoints

### Account

| Method | Endpoint | Description |
|---|---|---|
| `GET` | `/account` | Retrieve account information. |

### Payments

| Method | Endpoint | Description |
|---|---|---|
| `POST` | `/payments` | Create a payment. |
| `GET` | `/payments/{payment_id}` | Retrieve a payment. |

---

## Authentication

The API uses Bearer authentication.

Include your API credential in the `Authorization` header:

```http
Authorization: Bearer YOUR_API_KEY
