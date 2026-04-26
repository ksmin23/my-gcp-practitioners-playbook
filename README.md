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
*   [lightrag-spanner](https://github.com/ksmin23/lightrag-spanner): A Google Cloud Spanner storage plugin for LightRAG. It provides KV, Vector, Graph, and DocStatus storage classes as an external plugin — no modifications to LightRAG source code required.
*   [lightrag-bigquery](https://github.com/ksmin23/lightrag-bigquery): A Google Cloud BigQuery storage plugin for LightRAG. It provides KV, Vector, Graph, and DocStatus storage classes as an external plugin — no modifications to LightRAG source code required.
*   [PathRAG](https://github.com/ksmin23/PathRAG): A Path-based Retrieval-Augmented Generation (PathRAG) library. **Contributed the Google Cloud Spanner storage backend (Graph, Vector, KV) and LiteLLM/Gemini model support to the original framework.**
*   [pathrag-bigquery](https://github.com/ksmin23/pathrag-bigquery): A Google Cloud BigQuery storage plugin for PathRAG. It provides KV, Vector, and Graph storage classes as an external plugin — no modifications to PathRAG source code required.
*   [langchain-bigquery-hybridsearch](https://github.com/ksmin23/langchain-bigquery-hybridsearch): BigQuery Hybrid Search extension for langchain-google-community. Combines BigQuery VECTOR_SEARCH() (semantic similarity) with SEARCH() (full-text keyword matching) into a single retrieval step.
*   [my-adk-python-samples/gcp-releasenotes-agent-app](https://github.com/ksmin23/my-adk-python-samples/tree/main/gcp-releasenotes-agent-app): A GenAI-powered agent that summarizes Google Cloud release notes.
*   [my-adk-python-samples/RAG](https://github.com/ksmin23/my-adk-python-samples/tree/main/RAG): A collection of Retrieval-Augmented Generation (RAG) samples using various GCP services.
    *   [RAG Engine with Managed DB](https://github.com/ksmin23/my-adk-python-samples/tree/main/RAG/rag-engine-with-managed-db): Implements an Agentic RAG application using the Vertex AI RAG Engine with its own fully managed database.
    *   [RAG Engine with Vector Search](https://github.com/ksmin23/my-adk-python-samples/tree/main/RAG/rag-engine-with-vectorsearch): Implements an Agentic RAG application using the Vertex AI RAG Engine backed by a Vertex AI Vector Search index.
    *   [RAG with AlloyDB](https://github.com/ksmin23/my-adk-python-samples/tree/main/RAG/rag-with-alloydb): An Agentic RAG implementation using the vector search feature of AlloyDB for PostgreSQL.
    *   [RAG with BigQuery](https://github.com/ksmin23/my-adk-python-samples/tree/main/RAG/rag-with-bigquery): An Agentic RAG implementation using BigQuery Vector Search.
    *   [RAG with BigQuery Hybrid Search](https://github.com/ksmin23/my-adk-python-samples/tree/main/RAG/rag-with-bigquery-hybridsearch): An Agentic RAG implementation using [**BigQuery Hybrid Search**](https://github.com/ksmin23/langchain-bigquery-hybridsearch) (combining VECTOR_SEARCH and SEARCH) with Reciprocal Rank Fusion (RRF).
    *   [DEO Negation-Aware RAG with BigQuery](https://github.com/ksmin23/my-adk-python-samples/tree/main/RAG/deo-rag-with-bigquery): An Agentic RAG implementation using [**DEO (Direct Embedding Optimization)**](https://arxiv.org/abs/2603.09185) for negation-aware retrieval with BigQuery Vector Search.
    *   [RAG with Spanner](https://github.com/ksmin23/my-adk-python-samples/tree/main/RAG/rag-with-spanner): An Agentic RAG implementation using the vector search feature of Google Cloud Spanner.
    *   [RAG with Vector Search and Datastore](https://github.com/ksmin23/my-adk-python-samples/tree/main/RAG/rag-with-vectorsearch-ds): An Agentic RAG implementation using Vertex AI Vector Search for vector retrieval and Firestore in Datastore mode as the document store.
    *   [RAG with Vector Search and GCS](https://github.com/ksmin23/my-adk-python-samples/tree/main/RAG/rag-with-vectorsearch-gcs): An Agentic RAG implementation using Vertex AI Vector Search for vector retrieval and Google Cloud Storage (GCS) as the document store.
    *   [RAG with Vector Search 2.0](https://github.com/ksmin23/my-adk-python-samples/tree/main/RAG/rag-with-vectorsearch-2.0): An Agentic RAG implementation using **Vertex AI Vector Search 2.0**. Features unified data storage, auto-embeddings, and hybrid search (Semantic + Keyword) with RRF ranking.
    *   [RAG with Gemini File Search](https://github.com/ksmin23/my-adk-python-samples/tree/main/RAG/rag-with-file-search): An Agentic RAG implementation using **Gemini File Search**, a fully managed RAG system. Features hands-off file search store management, auto-ingestion, session isolation, and MIME type patching.
*   [my-adk-python-samples/Graph-RAG](https://github.com/ksmin23/my-adk-python-samples/tree/main/Graph-RAG): A collection of Graph Retrieval-Augmented Generation (Graph RAG) samples.
    *   [Graph RAG with Spanner](https://github.com/ksmin23/my-adk-python-samples/tree/main/Graph-RAG/graph-rag-with-spanner): An agent that implements the Graph RAG pattern using Google Cloud Spanner Graph for knowledge graph storage and retrieval.
    *   [PathRAG with Spanner](https://github.com/ksmin23/my-adk-python-samples/tree/main/Graph-RAG/pathrag-with-spanner): An agent that implements the PathRAG pattern using the PathRAG library with Google Cloud Spanner.
    *   [PathRAG with BigQuery](https://github.com/ksmin23/my-adk-python-samples/tree/main/Graph-RAG/pathrag-with-bigquery): An agent that implements the PathRAG pattern using the PathRAG library with Google Cloud BigQuery.
    *   [LightRAG with Spanner](https://github.com/ksmin23/my-adk-python-samples/tree/main/Graph-RAG/lightrag-with-spanner): An agent that implements the LightRAG pattern using the Agent Development Kit (ADK) with Google Cloud Spanner.
    *   [LightRAG with BigQuery](https://github.com/ksmin23/my-adk-python-samples/tree/main/Graph-RAG/lightrag-with-bigquery): An agent that implements the LightRAG pattern using the Agent Development Kit (ADK) with Google Cloud BigQuery.
*   [my-adk-python-samples/restaurant-finder](https://github.com/ksmin23/my-adk-python-samples/tree/main/restaurant-finder): A conversational agent for finding restaurants, built with GCP services.
*   [my-adk-python-samples/shop-agent-app](https://github.com/ksmin23/my-adk-python-samples/tree/main/shop-agent-app): A sample shopping agent application.
*   [my-adk-python-samples/shopper-concierge-demo](https://github.com/ksmin23/my-adk-python-samples/tree/main/shopper-concierge-demo): A demonstration of a shopper concierge service using GenAI on GCP.
*   [my-adk-python-samples/dynamic-tool-search-tool](https://github.com/ksmin23/my-adk-python-samples/tree/main/dynamic-tool-search-tool): An advanced agent demonstrating dynamic discovery and loading of tools from Google Managed MCP servers using a "Search & Load" pattern with BM25 search.

### Agent Memory
*   [my-adk-python-samples/agent-memory/redis-session-service](https://github.com/ksmin23/my-adk-python-samples/tree/main/agent-memory/redis-session-service): An agent that demonstrates how to use Redis for session state management, allowing for scalable and persistent user sessions.
*   [my-adk-python-samples/agent-memory/redis-memory-service](https://github.com/ksmin23/my-adk-python-samples/tree/main/agent-memory/redis-memory-service): An agent demonstrating a custom long-term memory service using Redis Vector Store.
*   [my-adk-python-samples/agent-memory/bigquery-data-agent-with-dynamic-context](https://github.com/ksmin23/my-adk-python-samples/tree/main/agent-memory/bigquery-data-agent-with-dynamic-context): A self-learning BigQuery agent that leverages Vertex AI Agent Engine Memory Bank to convert natural language to SQL, execute queries, and store them with dynamic scopes (user/team) for future retrieval.

### Observability
*   [my-adk-python-samples/plugins/bigquery-logging-plugin](https://github.com/ksmin23/my-adk-python-samples/tree/main/plugins/bigquery-logging-plugin): A plugin for the Python ADK that captures and streams agent operational events (like requests, responses, and tool calls) to BigQuery for analysis and monitoring.

### Tooling & Guides
*   [gemini-cli-with-mcp-toolbox-for-databases](https://github.com/ksmin23/gemini-cli-with-mcp-toolbox-for-databases): A guide on using the Gemini CLI with the MCP Toolbox for database management on GCP.

## References

-   [ADK Official Docs](https://google.github.io/adk-docs/)
    -   [ADK Python Repository](https://github.com/google/adk-python)
    - [ADK Crash Course - From Beginner To Expert](https://codelabs.developers.google.com/onramp/instructions#0)
    - [Google ADK Masterclass](https://github.com/arjunprabhulal/google-adk-masterclass)
-   [ADK Python Community Contributions](https://github.com/google/adk-python-community)
-   [ADK Samples Repo](https://github.com/google/adk-samples)
-   [Agentic Design Patterns](https://docs.google.com/document/d/1rsaK53T3Lg5KoGwvf8ukOUvbELRtH-V0LnOIFDxBryE/preview?tab=t.0#heading=h.pxcur8v2qagu)
-   [ADK Web Book by Amulya Bhatia](https://iamulya.one/tags/agent-development-kit/)
