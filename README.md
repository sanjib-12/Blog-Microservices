<div align="center">

# 🚀 Blog Microservices

[![License](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](LICENSE)

### *A microservices architecture for a blog platform.*

</div>

## 📋 Table of Contents

- [Overview](#-overview)
- [Key Features](#-key-features)
- [System Requirements](#-system-requirements)
- [Getting Started](#-getting-started)
- [Usage](#-usage)

## 📖 Overview

Blog Microservices is a modular blog application designed to showcase microservices architecture. It allows users to create, read, update, and delete posts, as well as add comments, moderate content, and query data efficiently. Each component operates as an independent service, enabling scalability and maintainability.

### Why Blog Microservices?

- 🎯 **Modularity**: Each service (posts, comments, query, moderation, event bus) can be developed, deployed, and scaled independently.
- ⚡ **Scalability**: Microservices architecture allows for scaling specific components based on demand.
- 🛡️ **Technology Showcase**: Demonstrates practical implementation of microservices principles and technologies.

## ✨ Key Features

- **Post Management**
  - Create new blog posts
  - Retrieve existing posts
  - Update post content
  - Delete posts

- **Comment Management**
  - Add comments to posts
  - Retrieve comments for a specific post

- **Content Moderation**
  - Automatically moderate comments based on predefined rules

- **Query Service**
  - Efficiently query and retrieve data across multiple services

- **Event Bus**
  - Facilitate communication between services using an event-driven architecture

## 🚀 Getting Started

### Prerequisites

- Docker installed and running.
- Skaffold installed (optional, for easier Kubernetes deployment).

### Installation


```bash
# Clone the repository
git clone https://github.com/sanjib-12/Blog-Microservices.git

# Navigate to project directory
cd Blog-Microservices

#install the submodules
git submodule update --init --recursive

#install dependencies of each services
npm install

#start the application using skaffold
skaffold dev
```

## 📘 Usage

After deploying the application, access the client service through your browser. The client provides a user interface for creating posts and adding comments.  The services communicate with each other in the backend to display posts and comments.

<div align="center">

**Blog Microservices** is maintained by [sanjib-12](https://github.com/sanjib-12).  
If you find it helpful, please consider giving it a ⭐️!

</div>

