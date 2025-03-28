# Posts_Comments

This repository provides a basic structure for a posts and comments system. The system is modular and includes multiple services such as posts, comments, moderation, and event bus for asynchronous communication.

## Features

- **Posts Service**: Manages the creation, update, and retrieval of posts.
- **Comments Service**: Manages user comments for each post.
- **Moderation Service**: Ensures comments comply with moderation rules.
- **Event Bus**: Used for inter-service communication to ensure seamless operations between services.

## Technologies Used

- JavaScript
- Docker
- Kubernetes (K8s)
- HTML

## Folder Structure

- **client**: Contains the client-side code for the posts and comments services.
- **comments**: Service for managing comments.
- **event-bus**: Handles inter-service communication.
- **infra/k8s**: Kubernetes configurations for deploying the services.
- **moderation**: Handles content moderation.
- **posts**: Service for managing posts.
- **query**: Query handling logic for fetching posts and comments.

