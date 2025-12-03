# API Automation Demo - Postman

Postman API test automation suite for Notes endpoints: https://practice.expandtesting.com/notes/api/api-docs/

## Setup

Import the following in Postman:
1) Environments
2) Globals
3) Collections

## Running Tests

Run the collection manually:
1. Click **Collections** in sidebar.
2. Select the **Collection**.
3. Click **Run**.
4. Uncheck POST login user.
5. Choose **Run manually** in Functional tab.
6. Click **Run Notes API**

## Project Structure

- **postman/collections/** - API collections (*.json)
- **postman/environments/** - Environments & variables (*.json)
- **postman/globals/** - Global workspace variables (*.json)

## Test Scenarios

- Create notes - POST call - functional & schema validations
- Get notes    - GET call -  functional & response validation
- Update note  - PUT call - funtional & response validation
- Delete note  - DELETE call - functional, deleted, invalid req validato

## Tech Stack

- **Postman**
- **Javascript**