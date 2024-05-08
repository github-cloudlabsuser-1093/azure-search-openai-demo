# Backend Documentation

## Documentation

The 'app/backend' directory contains the backend code for the Azure Search OpenAI Demo project. It is organized as follows:

- `src/`: Contains the source code files for the backend.
- `tests/`: Contains the unit tests for the backend code.
- `config/`: Contains configuration files for the backend.

To set up the backend locally, follow these steps:

1. Clone the repository: `git clone <repository-url>`
2. Navigate to the 'app/backend' directory: `cd app/backend`
3. Install the dependencies: `npm install`
4. Start the backend server: `npm start`

The backend provides the following functionality:

- API endpoints for interacting with the Azure Search service.
- Integration with the OpenAI GPT-3 language model.

To use the backend, make HTTP requests to the appropriate API endpoints.

The backend requires the following configuration:

- Azure Search service credentials: Update the `config/azureSearchConfig.js` file with your Azure Search service credentials.

Contributions to the backend code are welcome! To contribute, follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature-name`
3. Make your changes and commit them: `git commit -m 'Add your changes'`
4. Push the changes to your forked repository: `git push origin feature/your-feature-name`
5. Open a pull request.

## Requirements

The requirements for the backend are listed in the 'app/backend/requirements.txt' file. Please refer to that file for the specific dependencies and versions required.