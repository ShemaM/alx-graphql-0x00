# GraphQuest: The Rick and Morty GraphQL API Explorer

## Project Overview
GraphQuest is a multi-phase learning journey designed to build proficiency in GraphQL, from writing basic queries to integrating them into a modern, full-stack React application. This project uses the [Rick and Morty API](https://rickandmortyapi.com/graphql) as its data source, providing a fun and engaging context for learning.

The work is segmented into distinct directories, each representing a progressive level of complexity:
* **Level 0:** `alx-graphql-0x00` (Fundamentals)
* **Level 1 & 2:** `alx-graphql-0x01` / `alx-graphql-0x02` (Frontend Integration)



## Learning Objectives

### Level 0: GraphQL Fundamentals
* **Construct Queries:** Write precise GraphQL queries to request specific data.
* **Arguments & Filtering:** Understand and use arguments (e.g., `id`, `page`) to filter results.
* **Optimization:** Structure queries to include only necessary fields to avoid over-fetching.
* **Data Structures:** Differentiate between querying for a single item versus a paginated list.

### Level 1 & 2: Frontend Integration
* **Setup:** Initialize a Next.js application with TypeScript, Apollo Client, and Tailwind CSS.
* **Apollo Configuration:** Connect a React application to a GraphQL endpoint using Apollo Client.
* **Hooks:** Use the `useQuery` hook to execute GraphQL operations within components.
* **State Management:** Manage local component state (e.g., pagination) and refetch data.
* **Architecture:** Structure a React app with clear separation of concerns (queries, interfaces, components).



## Key Concepts

* **GraphQL Query Language:** The syntax for defining data requirements, replacing multiple REST endpoints with a single flexible endpoint.
* **Schema and Types:** Understanding the specific data shapes (`Character`, `Episode`, `Info`) defined by the API.
* **Apollo Client:** A comprehensive state management library that handles caching, loading states, and error states for GraphQL data.
* **React Integration:** Using `ApolloProvider` and hooks to seamlessly manage data within the component tree.
* **TypeScript:** Using static type definitions and Interfaces to ensure code reliability and better autocompletion.

## Technologies & Tools

| Category | Tool | Description |
| :--- | :--- | :--- |
| **Runtime** | Node.js | JavaScript runtime environment |
| **Framework** | Next.js | React framework with SSR and optimizations |
| **Language** | TypeScript | Superset of JavaScript with static typing |
| **Client** | Apollo Client | State management and query execution |
| **Styling** | Tailwind CSS | Utility-first CSS framework |
| **API** | Rick and Morty API | The GraphQL data source |

## Real-World Application
This project mimics the architecture of modern content-driven web applications, such as:
1.  **E-commerce:** Querying product details or paginated catalogs.
2.  **Content Platforms:** Fetching blogs or news articles (analogous to Episodes).
3.  **Dashboards:** Displaying filtered and paginated data from complex backends.

## Usage
### Level 0 (Fundamentals)
Navigate to `alx-graphql-0x00` to find `.graphql` query files and their corresponding `.json` outputs.

### Level 1 & 2 (Application)
Navigate to the respective directories to run the Next.js application:

```bash
# Install dependencies
npm install

# Run the development server
npm run dev
