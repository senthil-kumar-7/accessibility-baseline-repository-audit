# Architecture

## Monorepo boundaries

### Client
`client/` contains browser/UI code, accessibility behavior, forms, and API calls.

### Server
`server/` contains HTTP endpoints, validation, and business logic.

### Docs
`docs/` contains architecture decisions, setup notes, and diagrams.

### Tests
`tests/` contains automated and integration test documentation/tests.

## First vertical feature slice

```text
User
  |
  v
Client form
  |
  | HTTP request
  v
Server API
  |
  v
Validation / business logic
  |
  v
JSON response
  |
  v
Client success/error state
```

## Local setup

1. Install Node.js LTS.
2. Install dependencies after selecting the client/server framework.
3. Start client and server separately.
4. Configure environment variables in local `.env` files.
5. Run tests before committing.

## Accessibility boundary

Accessibility is primarily enforced in the client UI, but server-side validation must not rely on client-side validation alone.
