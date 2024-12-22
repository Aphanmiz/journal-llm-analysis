# **Journal Data Analysis and Visualization with LLMs**

This project demonstrates how to analyze and visualize daily journal data using embeddings, dimensionality reduction, clustering, and an LLM for querying insights. It transforms structured journal entries into actionable narratives.

## **Features**

- Load and preprocess journal data from a CSV file.
- Generate vector embeddings using `OllamaEmbeddings`.
- Apply PCA for dimensionality reduction and visualize clusters in 3D.
- Perform K-Means clustering to identify patterns in journal entries.
- Store embeddings in a vector database with Chroma.
- Query insights interactively using a locally hosted LLM.

## Usage
- Prepare Journal Data: Save your daily logs in a CSV file (e.g., `daily_track_records_2024.csv`).
- Run Notebook: Follow the structured steps in the notebook:
- Load data and preprocess entries.
- Generate embeddings and perform clustering.
- Visualize journal data in 3D.
- Interact with the journal via LLM queries.

## Query Example:
```
query = "What new skills or habits did I develop this year?"
response = chat_with_journal(query, vectorstore, llm)
print("LLM Response:", response)
```

## Visualization
- Explore 3D scatter plots of PCA-reduced embeddings with clusters.
- Hover over points for detailed task information.

  
## Acknowledgments
Inspired by daily journaling practices and leveraging the power of AI for personal reflection.
