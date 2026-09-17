# Webhooks

Webhooks allow AcmePay to notify your application when an event occurs.

Unlike a traditional API request, where your application asks the API for information, a webhook allows AcmePay to send information to your application automatically.

> **Note:** AcmePay is a fictional API created for this technical writing portfolio.

---

## How Webhooks Work

A typical webhook workflow looks like this:

```text id="k2xj7v"
Payment Event
     |
     v
AcmePay
     |
     v
Webhook Request
     |
     v
Your Application
     |
     v
HTTP Response
