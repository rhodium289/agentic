# Agentic LLM Systems Investigation

This project aims to investigate agentic LLM (Language Learning Model) systems using various technologies such as Poetry, Docker, LangChain, LangGraph, and Ollama3.

## Prerequisites

Before getting started, make sure you have the following installed:

- [Python](https://www.python.org/downloads/)
- [Poetry](https://python-poetry.org/docs/#installation)
- [Docker](https://www.docker.com/get-started)

## Installation

1. Clone this repository:

    ```shell
    git clone https://github.com/your-username/agentic-llm-systems.git
    ```

2. Change into the project directory:

    ```shell
    cd agentic-llm-systems
    ```

3. Install the project dependencies using Poetry:

    ```shell
    poetry install
    ```

## Usage

1. Start the Docker containers for LangChain, LangGraph, and Ollama3:

    ```shell
    docker-compose up -d
    ```

2. Run the agentic LLM system:

    ```shell
    poetry run python main.py
    ```

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).