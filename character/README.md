# Task 0: Query Specific Character by ID

This task is part of the **Rick and Morty GraphQL API Explorer** project, designed to build foundational GraphQL skills. The goal is to write precise queries that retrieve character data using their unique IDs.

## 📌 Objective

Write GraphQL queries to fetch details of specific characters from the Rick and Morty API using the `character(id: ID!)` field.

## 🔗 Endpoint

All queries are executed against the official Rick and Morty GraphQL endpoint:


## 🧠 Learning Goals

- Understand how to query a single item using arguments.
- Practice selecting only the necessary fields to avoid over-fetching.
- Gain familiarity with GraphQL syntax and structure.

## 📁 File Structure

Each character query and its corresponding output are stored in separate files:

| File Name | Description |
|-----------|-------------|
| `character-id-1.graphql` | Query for character with ID 1 |
| `character-id-1-output.json` | API response for character ID 1 |
| `character-id-2.graphql` | Query for character with ID 2 |
| `character-id-2-output.json` | API response for character ID 2 |
| `character-id-3.graphql` | Query for character with ID 3 |
| `character-id-3-output.json` | API response for character ID 3 |
| `character-id-4.graphql` | Query for character with ID 4 |
| `character-id-4-output.json` | API response for character ID 4 |

## 🧪 Query Format

Each `.graphql` file contains a query like:

```graphql
query {
  character(id: 1) {
    id
    name
    status
    species
    type
    gender
  }
}

## 🧠 Learning Goals

- Understand how to query a single item using arguments.
- Practice selecting only the necessary fields to avoid over-fetching.
- Gain familiarity with GraphQL syntax and structure.

## 📁 File Structure

Each character query and its corresponding output are stored in separate files:

| File Name | Description |
|-----------|-------------|
| `character-id-1.graphql` | Query for character with ID 1 |
| `character-id-1-output.json` | API response for character ID 1 |
| `character-id-2.graphql` | Query for character with ID 2 |
| `character-id-2-output.json` | API response for character ID 2 |
| `character-id-3.graphql` | Query for character with ID 3 |
| `character-id-3-output.json` | API response for character ID 3 |
| `character-id-4.graphql` | Query for character with ID 4 |
| `character-id-4-output.json` | API response for character ID 4 |

## 🧪 Query Format

Each `.graphql` file contains a query like:

```graphql
query {
  character(id: 1) {
    id
    name
    status
    species
    type
    gender
  }
}

---
## 📌 Task 1: Paginated Character List

### Objective
Write GraphQL queries to retrieve a paginated list of characters across four pages.

### Fields Selected
- `id`
- `name`
- `status`
- `image`

### Files
| Filename | Description |
|----------|-------------|
| `characters-page-1.graphql` | Query for characters on page 1 |
| `characters-page-1-output.json` | API response for page 1 |
| `characters-page-2.graphql` | Query for characters on page 2 |
| `characters-page-2-output.json` | API response for page 2 |
| `characters-page-3.graphql` | Query for characters on page 3 |
| `characters-page-3-output.json` | API response for page 3 |
| `characters-page-4.graphql` | Query for characters on page 4 |
| `characters-page-4-output.json` | API response for page 4 |

---

## 🧪 How to Run Queries

You can run each `.graphql` file using:

- [Rick and Morty GraphQL Playground](https://rickandmortyapi.com/graphql)
- A local GraphQL client (e.g., Insomnia, Postman)
- A script using Python or `curl`

Save the full JSON response into the corresponding `.json` output file.

---

## ✅ Completion Checklist

- [x] All `.graphql` files created
- [x] All `.json` output files saved
- [x] Queries return correct fields as specified

---

Happy querying! 🚀