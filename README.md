# Eno worldbuilding System

A narrative gaming worldbuilding system that generates content and entries in the Atlas using Knowledge Graph and Vector Database components and updates the used components to the current data.

## Components

### 1. Knowledge Graph

- Stores entities like characters, locations, and events as nodes
- Maintains relationships between entities
- Provides context for narrative generation
- Based on Neo4j

### 2. Vector Database

- Stores narrative memories and textual context
- Enables semantic search for relevant context
- Supports memory management with importance and expiration
- Based on ChromaDB

### 3. Atlas

- Human readable Wikipage about the World of Eno
- Uses the Knowledge Graph and Vector Database for context
- Integrates with LLM services (OpenAI by default)

### 4. Map

- Links Atlas to geospatial data.

### 5. Chronicle

- Links Atlas to temporal data.


## Installation


## Usage

### Running the Backend System

## Development

This project follows Python code style guidelines outlined in PEP 8. See `CLAUDE.md` for additional development guidelines.

### Project Structure

- `/Eno-Frontend`: Frontend component for reference
- `/Eno-Backend`: Backend component for reference
- `/GIS`: Raw GIS data for reference
- `/Data_Retrieve_Save_From_to_database`: Database to Atlas Atlas to Database
- `/tools`: Utility tools for various purposes

## License

This project is licensed under the terms of the included LICENSE file.

This document will be updated as the project progresses.

## License

This project is licensed under the terms of the included LICENSE file.
