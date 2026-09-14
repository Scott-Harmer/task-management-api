# Task Management API

A docs-as-code portfolio project demonstrating how functional API requirements can be transformed into structured, developer-facing reference documentation using OpenAPI, JSON, GitHub, and Redocly.

## Project Overview

This project documents a fictional Task Management API for creating, retrieving, updating, filtering, and deleting tasks.

The documentation was developed as an OpenAPI 3.1 specification, validated with Redocly CLI, bundled into JSON, and rendered as an HTML API reference.

## API Operations

The API includes five documented operations:

- `POST /tasks` to create a task
- `GET /tasks` to retrieve and filter tasks
- `GET /tasks/{taskId}` to retrieve a specific task
- `PATCH /tasks/{taskId}` to update a task
- `DELETE /tasks/{taskId}` to delete a task

## Docs-as-Code Workflow

The project uses a docs-as-code workflow in which the API documentation is stored as version-controlled source files.

The workflow included:

1. Translating functional requirements into API operations
2. Writing the OpenAPI specification in YAML
3. Defining request and response structures
4. Adding reusable schemas and authentication
5. Validating the specification with Redocly CLI
6. Bundling the specification into JSON
7. Rendering the API reference as HTML
8. Tracking changes through GitHub commits

## Validation

The OpenAPI specification was linted using Redocly CLI with the recommended ruleset.

Final validation result:

**0 errors and 0 warnings**

## Repository Structure

```text
task-management-api/
├── openapi/
│   └── openapi.yaml
├── api-reference.html
├── openapi.json
├── redocly.yaml
└── README.md
