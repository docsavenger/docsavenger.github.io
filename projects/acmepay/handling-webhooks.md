# Handling Payment Webhooks with AcmePay

This tutorial explains how a developer can receive and process payment events from the fictional AcmePay API.

By the end of this tutorial, you will understand how to:

- Create a webhook endpoint
- Receive payment events
- Identify different event types
- Handle duplicate events
- Verify webhook requests
- Troubleshoot common webhook problems

> **Documentation notice:** AcmePay is a fictional cloud payments platform created as a technical writing portfolio project. The example endpoints cannot receive real events.

## Before You Start

You should have:

- Basic knowledge of HTTP requests
- A web endpoint that can receive HTTP POST requests
- Familiarity with JSON
- An AcmePay API account in a real implementation

For the concepts behind AcmePay webhooks, see the [Webhooks](webhooks.md) reference.

## Step 1: Create a Webhook Endpoint

Create an endpoint on your application that can receive HTTP POST requests.

For example:

```text
https://example.com/webhooks/acmepay
