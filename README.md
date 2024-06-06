# E2E-NLP-Project

Welcome to the `E2E-NLP-Project` repository! This project demonstrates an end-to-end Natural Language Processing (NLP) pipeline, including API development and containerization with Docker.

## Table of Contents

- [Overview](#overview)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Overview

The `E2E-NLP-Project` aims to provide a comprehensive guide for building and deploying an NLP application from scratch. This includes data preprocessing, model training, API development, and containerization using Docker.

## Requirements

To run this project, you need the following dependencies:

- Python 3.8+
- Docker
- FastAPI
- Transformers (Hugging Face)

## Installation
Clone the repository and install the required packages:

## Usage
### Running the API Locally
1. Start the API server:
    ```bash
    python api.py
2. Call the API using `call_api.py`:
    ```bash
    python call_api.py

## Running with Docker
1. Build the Docker image:
    ```bash
    docker build -t e2e-nlp-project .

2. Run the Docker container:
    ```bash
    docker run -p 8000:8000 e2e-nlp-project

3. Call the API using `call_api.py`:
    ```bash
    python call_api.py

## Project Structure
- `Dockerfile`: Dockerfile for containerizing the NLP application.
- `LICENSE`: Project license.
- `README.md`: Project documentation.
- `api.py`: Python script to run the API server.
- `call_api`.py: Python script to call the API and test the endpoints.
- `requirements.txt`: File listing all the dependencies.

  
## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements, bug fixes, or suggestions.

## License
This project is licensed under the MIT License. See the LICENSE file for details.


---
Happy coding! If you have any questions or need further assistance, feel free to open an issue.
---
