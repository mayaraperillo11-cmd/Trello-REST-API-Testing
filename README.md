# Trello REST API Testing – Postman

## Project Overview

This project contains a collection of API tests developed with Postman to validate Trello REST API endpoints.

The goal was to practice API testing, HTTP methods, response validation, status codes, and automated test scripts using JavaScript.

## Scope of Testing

The collection covers the following operations:

- **Create:** Boards, lists, and cards.
- **Read:** Retrieve boards, lists, and cards.
- **Update:** Modify board, list, and card information.
- **Archive:** Archive a list.
- **Delete:** Delete cards and boards.
- **Negative Testing:** Verify that deleted resources return the expected 404 response.

## Tools & Technologies

- Postman
- Trello REST API
- JavaScript (Postman test scripts)
- JSON
- HTTP methods (GET, POST, PUT, DELETE)

## Test Validation

The automated assertions validate:

- HTTP status codes.
- Response body content.
- Resource IDs and names.
- Relationships between boards, lists, and cards.
- Persistence of updated information.
- Expected behavior after deletion and archiving.
- Response time (under 1000 ms).

## Project Structure

```text
Trello-REST-API-Testing/
├── Trello APIs.postman_collection.json
└── README.md
```

## How to Run

1. Import the Postman collection.
2. Create a Trello API Key and Token.
3. Configure the required variables in a Postman environment.
4. Select the environment.
5. Run the collection using Postman Collection Runner.

**Note:** API credentials are not included in this repository.

## Project Purpose

This is a personal QA portfolio project developed to practice REST API testing, test automation with Postman, and validation of CRUD operations.
