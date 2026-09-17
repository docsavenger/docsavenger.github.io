# Understanding and Troubleshooting AcmePay API Errors

API errors provide information about what went wrong with a request.

This guide explains common AcmePay API errors, what they mean, and what developers can do to resolve them.

> **Documentation notice:** AcmePay is a fictional cloud payments platform created as a technical writing portfolio project. The example endpoints cannot be used against a live service.

## How API Errors Work

When an API request fails, the server returns an HTTP status code.

The status code helps identify the type of problem.

For example:

```http
HTTP/1.1 401 Unauthorized
