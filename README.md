# Backend Code Challenge

1. Write a simple NodeJS REST API project or just fork one of the existing projects on Github (https://github.com/ealeksandrov/NodeAPI or https://github.com/scotch-io/node-api)

2. Write an API endpoint for saving a JSON object in MongoDB (which can be running in a Docker Container).

- Input: JSON Object
- Output: 200 OK or error code

3. Write an API endpoint for getting a list of all previously saved JSON objects filtered by some field’s value, in pages, N objects per page:

- Input:
  - field’s value
  - page number
- Output: list of JSON objects (no more than N)

4. Write end-to-end test(s) for these 2 endpoints, use the library of your choice. Tests should make real HTTP calls. Make sure to test pagination!

5. The result should be a repository on Github with instructions how to run tests.
