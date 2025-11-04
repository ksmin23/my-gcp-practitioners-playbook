# A Curated Collection of My Work on GCP

A personal playbook for fellow GCP practitioners, born from real-world experience. This curated collection includes practical code samples, architectural patterns, presentation decks, and video tutorials covering Generative AI with Vertex AI, AI Agents, Vertex AI Search for Commerce, Data Analytics, and Data Engineering.

## Open-Source GitHub Projects

### Change Data Capture (CDC) & Data Pipelines
*   [gcp-datastream-cdc-data-pipeline](https://github.com/ksmin23/gcp-datastream-cdc-data-pipeline): A project that builds a data pipeline for CDC from Cloud SQL (MySQL) to BigQuery using Datastream.
*   [gcp-datastream-dataflow-analytics](https://github.com/ksmin23/gcp-datastream-dataflow-analytics): A real-time data analytics platform using Datastream, Dataflow, and BigQuery for real-time data processing and analytics.
*   [gcp-datastream-mysql-cdc-to-gcs](https://github.com/ksmin23/gcp-datastream-mysql-cdc-to-gcs): A data pipeline for replicating data from Cloud SQL for MySQL to Google Cloud Storage (GCS) using Datastream.
*   [gcp-debezium-mysql-to-pubsub-bigquery](https://github.com/ksmin23/gcp-debezium-mysql-to-pubsub-bigquery): A real-time data pipeline that captures Change Data Capture (CDC) events from MySQL using Debezium and streams them to BigQuery via Pub/Sub.
*   [gcp-debezium-server-mysql-cdc-to-redis](https://github.com/ksmin23/gcp-debezium-server-mysql-cdc-to-redis): A real-time data pipeline that captures Change Data Capture (CDC) events from MySQL using the Debezium Server and streams them to Redis.

### Generative AI & Vertex AI
*   [mcp-vertex-ai-retail-search-server](https://github.com/ksmin23/mcp-vertex-ai-retail-search-server): A Python-based server that provides a retail search API using the Google Cloud Vertex AI Search for Retail service.
*   [my-adk-python-samples/gcp-releasenotes-agent-app](https://github.com/ksmin23/my-adk-python-samples/tree/main/gcp-releasenotes-agent-app): A GenAI-powered agent that summarizes Google Cloud release notes.
*   [my-adk-python-samples/RAG](https://github.com/ksmin23/my-adk-python-samples/tree/main/RAG): A collection of Retrieval-Augmented Generation (RAG) samples using various GCP services.
    *   [RAG Engine with Managed DB](https://github.com/ksmin23/my-adk-python-samples/tree/main/RAG/rag-engine-with-managed-db): Implements an Agentic RAG application using the Vertex AI RAG Engine with its own fully managed database.
    *   [RAG Engine with Vector Search](https://github.com/ksmin23/my-adk-python-samples/tree/main/RAG/rag-engine-with-vectorsearch): Implements an Agentic RAG application using the Vertex AI RAG Engine backed by a Vertex AI Vector Search index.
    *   [RAG with AlloyDB](https://github.com/ksmin23/my-adk-python-samples/tree/main/RAG/rag-with-alloydb): An Agentic RAG implementation using the vector search feature of AlloyDB for PostgreSQL.
    *   [RAG with BigQuery](https://github.com/ksmin23/my-adk-python-samples/tree/main/RAG/rag-with-bigquery): An Agentic RAG implementation using BigQuery Vector Search.
    *   [RAG with Spanner](https://github.com/ksmin23/my-adk-python-samples/tree/main/RAG/rag-with-spanner): An Agentic RAG implementation using the vector search feature of Google Cloud Spanner.
    *   [RAG with Vector Search and Datastore](https://github.com/ksmin23/my-adk-python-samples/tree/main/RAG/rag-with-vectorsearch-ds): An Agentic RAG implementation using Vertex AI Vector Search for vector retrieval and Firestore in Datastore mode as the document store.
    *   [RAG with Vector Search and GCS](https://github.com/ksmin23/my-adk-python-samples/tree/main/RAG/rag-with-vectorsearch-gcs): An Agentic RAG implementation using Vertex AI Vector Search for vector retrieval and Google Cloud Storage (GCS) as the document store.
*   [my-adk-python-samples/restaurant-finder](https://github.com/ksmin23/my-adk-python-samples/tree/main/restaurant-finder): A conversational agent for finding restaurants, built with GCP services.
*   [my-adk-python-samples/shop-agent-app](https://github.com/ksmin23/my-adk-python-samples/tree/main/shop-agent-app): A sample shopping agent application.
*   [my-adk-python-samples/shopper-concierge-demo](https://github.com/ksmin23/my-adk-python-samples/tree/main/shopper-concierge-demo): A demonstration of a shopper concierge service using GenAI on GCP.

### Agent Memory
*   [my-adk-python-samples/agent-memory/redis-session-service](https://github.com/ksmin23/my-adk-python-samples/tree/main/agent-memory/redis-session-service): An agent that demonstrates how to use Redis for session state management, allowing for scalable and persistent user sessions.
*   [my-adk-python-samples/agent-memory/redis-memory-service](httpss://github.com/ksmin23/my-adk-python-samples/tree/main/agent-memory/redis-memory-service): An agent demonstrating a custom long-term memory service using Redis Vectorsearch.

### Tooling & Guides
*   [gemini-cli-with-mcp-toolbox-for-databases](https://github.com/ksmin23/gemini-cli-with-mcp-toolbox-for-databases): A guide on using the Gemini CLI with the MCP Toolbox for database management on GCP.
