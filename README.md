# Learning Integrations

A minimal FastAPI application with no database.

Run all commands from the project directory.

The commands are the same on Windows, macOS, and Linux. Docker must be installed and running. On Windows, use Docker Desktop in Linux containers mode; the commands can be run in PowerShell.

## Running with Docker

Build the image:

```bash
docker build -t learning-integrations .
```

Start the container:

```bash
docker run --rm -p 8000:8000 learning-integrations
```

## Checking that it works

- Application: http://localhost:8000
- Swagger: http://localhost:8000/docs

The `GET /` route returns `{"message": "Hello, world!"}`.

To stop the application, press `Ctrl+C` in the terminal where it is running.
