# Java Multi-Threaded Socket Server

A simple Java project demonstrating the implementation of multi-threaded client-server application using TCP sockets.

## Overview

This repository contains basic client-server model to illustrate core networking concepts:

**Multi-Threaded**: A robust server that spawns a new thread for each incoming client connection. This allows it to handle multiple clients concurrently, which is essential for real-world applications. The accompanying client can simulate multiple concurrent connections to test the server's capabilities.

## Features

-   **Concurrent Client Handling**: The multi-threaded server can manage multiple client sessions simultaneously.
-   **Simple Protocol**: Demonstrates a basic request-response text-based communication.
-   **Modern Java**: Uses lambdas for concise threading and `try-with-resources` for safe, automatic closing of sockets and streams.
-   **Test Client**: Includes a multi-threaded client to simulate load and test server concurrency.

## Prerequisites

-   Java Development Kit (JDK) 8 or newer.

## Getting Started

### 1. Clone the Repository

```bash
git clone <your-repository-url>
cd <repository-name>
