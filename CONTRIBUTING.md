# CONTRIBUTING

## How to run the Dockerfile locally

```
docker run -dp 5005:5000 -w /app -v "$(pwd):/app" IMAGE_NAME sh -c "flask run"
```

## When you clone the project

> Create .env file your self 