# 0. Write a Query to Get a Specific Character by ID

## Objective
The goal of this task is to write GraphQL queries to retrieve specific character information using the `character(id: ID!)` field from the Rick and Morty API.

## API Endpoint
* **URL:** `https://rickandmortyapi.com/graphql`

## Task Requirements
For characters with IDs **1, 2, 3, and 4**, the queries fetch the following fields:
* `id`
* `name`
* `status`
* `species`
* `type`
* `gender`

## Files Structure

### GraphQL Queries
* **`character-id-1.graphql`**: Query to fetch details for Character ID 1 (Rick Sanchez).
* **`character-id-2.graphql`**: Query to fetch details for Character ID 2 (Morty Smith).
* **`character-id-3.graphql`**: Query to fetch details for Character ID 3 (Summer Smith).
* **`character-id-4.graphql`**: Query to fetch details for Character ID 4 (Beth Smith).

### JSON Outputs
* **`character-id-1-output.json`**: Expected JSON response for Character ID 1.
* **`character-id-2-output.json`**: Expected JSON response for Character ID 2.
* **`character-id-3-output.json`**: Expected JSON response for Character ID 3.
* **`character-id-4-output.json`**: Expected JSON response for Character ID 4.

## Usage
To test these queries, copy the content of a `.graphql` file and run it in a GraphQL playground (like the one provided at the endpoint URL) or use a CLI tool like `curl`.
