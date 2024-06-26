---

# BotFlow - Backend

An advanced project to manage and analyze customer interactions using machine learning techniques, MongoDB, and a GUI for creating and managing bot states, classes, and dispositions.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Introduction

This project aims to process and analyze conversations between customers and salesmen to assess their efficiency. The application uses Python with FastAPI for the backend, MongoDB for the database, and integrates machine learning models to provide insights. A user-friendly GUI is provided for creating and managing bot states, classes, and dispositions.

## Features

- Efficient processing of large audio files and their transcripts.
- RESTful API with FastAPI.
- MongoDB for storing and managing conversation data.
- GUI for creating and managing bot states, classes, and dispositions.
- Scalable and containerized deployment using Docker.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.8 or higher
- Conda package manager
- MongoDB database
- Docker (optional for containerized deployment)

## Installation

### Setting Up the Environment

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. Create and activate a Conda environment:
   ```bash
   conda create -n your-env-name python=3.8
   conda activate your-env-name
   ```

3. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

### Setting Up MongoDB

Ensure that your MongoDB database is running. You can use the following command to start MongoDB (assuming it's installed locally):

```bash
mongod
```

## Usage

1. Run the application using Uvicorn:
   ```bash
   uvicorn app:app --reload
   ```

2. Access the API documentation and test the endpoints at:
   ```
   http://127.0.0.1:8000/docs
   ```

3. Access the GUI to create and manage bot states, classes, and dispositions at:
   ```
   http://127.0.0.1:8000/gui
   ```

## Bot Management with GUI

### States

- **Definition**: States represent different stages in the bot's interaction flow.
- **Management**: Use the GUI to create, update, and delete states. Each state can have associated actions and transitions.

### Classes

- **Definition**: Classes categorize various elements within the bot's workflow, such as customer intents or response types.
- **Management**: Classes can be defined and managed through the GUI to organize and streamline bot interactions.

### Dispositions

- **Definition**: Dispositions refer to the outcomes or statuses of interactions, such as resolved, escalated, or pending.
- **Management**: The GUI allows for the easy creation and management of dispositions to track and analyze interaction results.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a Pull Request.

## License

This project is licensed under the IdrakAI License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Special thanks to the open-source community for their invaluable contributions.
- [FastAPI](https://fastapi.tiangolo.com/) for providing an excellent framework for building APIs.
- [MongoDB](https://www.mongodb.com/) for the robust and scalable database solution.

---

Feel free to customize this README with the specific details and branding of your project. Let me know if there are any other sections you'd like to include!
