# Start from Microsoft’s official Java 17 dev container image
FROM mcr.microsoft.com/vscode/devcontainers/java:17

# Install Gradle (and any other dependencies Freeplane needs)
RUN apt-get update && \
    apt-get install -y --no-install-recommends gradle && \
    rm -rf /var/lib/apt/lists/*
