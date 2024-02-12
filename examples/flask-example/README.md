# Flash Hello World

This containerised flask application sends data to Kengine with no code changes using the `opentelemetry_instrument` command.

## Getting Started

Install the dependencies

```
poetry install
```

Run the application

```
KENGINE_API_KEY="your-api-key" poetry run opentelemetry-instrument flask run
```
