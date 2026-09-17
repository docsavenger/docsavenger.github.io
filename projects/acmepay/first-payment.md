# Making Your First Payment with the AcmePay API

This tutorial walks through the basic workflow for creating a payment with the fictional AcmePay API.

By the end of this tutorial, you will understand how to:

- Authenticate an API request
- Create a payment
- Read the API response
- Handle common errors
- Verify the payment status

> **Documentation notice:** AcmePay is a fictional cloud payments platform created as a technical writing portfolio project. The example endpoints cannot be used to process real payments.

## Before You Start

You should have:

- An AcmePay API key
- Basic knowledge of HTTP requests
- Access to an API client such as Postman

For authentication details, see the [API Authentication](authentication.md) guide.

## Step 1: Authenticate Your Request

AcmePay uses Bearer token authentication.

Include your API key in the `Authorization` header:

```http
Authorization: Bearer YOUR_API_KEY
