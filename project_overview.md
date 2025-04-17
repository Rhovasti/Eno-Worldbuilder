# Project Overview

## Purpose
The goal of this project is to develop a a Program that builds and developes a fantasy World that acts as a backdrop for a narrative gaming experience. There are additional components in this Project: "Eno-Backend" and "Eno-Frontend". This component should act directly with "Eno-Backend" component to expand and specify entities with in the game World.

## Objectives
- Read the current state of the World
- Write new entries to the Atlas of the gameworld of Eno
- Store and update relevant world knowledge in a knowledge graph.
- Maintain a vector database for storing textual context and references.
- Ensure proper interaction between the backend, and the world model.

## Project Components

### 1. Atlas of Eno
- Maintain Human readable Atlas of the gameworld including important places, character, concepts, history, mechanics and rules of the World.
- Retrieve content from the knowledge graph and vector database to update the content of the Atlas.
- Write entries to the Atlas based on the content of the internal data storage systems
- Update the internal data storage system based on the Worldbuilding progress.

### 2. Knowledge Graph
- Represent entities (characters, locations, events) as nodes.
- Define relationships between entities as edges.
- Maintain a temporal structure to track changes over time.
- Update the graph dynamically as new posts and generated content appear.

### 3. Vector Database
- Store textual references relevant to the game world.
- Retrieve similar content for context-aware responses.
- Maintain a balance between immediate conversation and long-term world-building.

### 4. Backend System
- Process retrieved posts and analyze their content.
- Interact with both the knowledge graph and the vector database.
- Generate coherent and engaging replies.
- Optimize performance to handle multiple interactions efficiently.

## Current Progress
- Initial commit.

## Next Steps
- Evaluate and review the Project to determine next course of action.

## Project Management
To track goals and milestones:
- Use this document to outline features and track progress.
- Implement a task management system (e.g., GitHub Issues, Trello, or Notion).
- Define key deliverables and deadlines.

## Suggestions from the User
- The Atlas of the World of Eno could be build using Obsidian and relevant publishing systems.
- Atlas should include a Map using leaflet or similar technology.
- The Map includes Geospatial information that should be linked to relevant data in the Atlas
- Atlas should also indluce a temporal aspect so that historical events and characters can be handled efficiently.
- Note: The "GIS" folder is unoptimized data including everything. To efficiently hande the map only the relevant data should be included in the Map itself.
 
This document will be updated as the project progresses.

