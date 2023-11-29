# Assignment: Ember.js Tabular Data Loading with Dynamic Columns and Efficient API Calls

## Objective
Develop an Ember.js application that dynamically loads tabular data with two dynamic columns.
The data should be fetched asynchronously with minimal API calls, and a loading indicator should be displayed while the data is being loaded.

## Requirements

### 1. Application Setup
- Set up a new Ember.js application.
- Ensure the application uses the latest Ember.js version for compatibility and features.

### 2. Data Model
- Define a data model representing the items to be displayed in the table. The base model should be derived from the 
- Include at least 5-7 fields, two of which should be dynamic and fetched based on the `competitors-data.json`

### 3. API Integration
- Simulate an API using Ember's Mirage or any mock API tool.
- The API should return data in JSON format.
- Design the API to efficiently handle data requests with minimal calls.

### 4. Data Loading and Rendering
- Implement a service or a utility in Ember.js to fetch data from the API.
- Handle asynchronous data loading with promises and/or ember.js native stores.
- Display a loading indicator (e.g., a spinner) on the UI while data is being fetched.

### 5. Dynamic Columns
- Implement logic to dynamically load data that will be added to the table.
- These columns should be based on the data fetched or any other dynamic criteria.

### 6. Table Implementation
- Use Ember components to create a table structure.
- Ensure the table updates to reflect the dynamically determined columns.
- Implement sorting and/or filtering if desired for extra complexity.
- Extra points for implementing a caching strategy.

### 7. Error Handling
- Implement error handling for scenarios where data fetching fails.
- Display appropriate error messages to the user.

### 8. Testing
- Write unit tests for the components and services.
- Ensure tests cover dynamic column functionality and async data loading.

### 9. Documentation
- Provide clear documentation on how to set up and run the application.
- Document any assumptions or design decisions made during development.

### 10. Workflow
- Project should use git as the VCS.
- Git commints should use the semantic git commit message format: https://gist.github.com/joshbuchea/6f47e86d2510bce28f8e7f42ae84c716

## Evaluation Criteria
- Code quality and organization.
- Correct implementation of dynamic columns.
- Efficient API usage with minimal calls.
- Handling of asynchronous operations and loading states.
- Test coverage and documentation.
- Readable and efficient documentation.

## Submission
Candidates should submit their code via a GitHub repository or a zip file containing the Ember.js project. The submission should include all source code, tests, and documentation.

