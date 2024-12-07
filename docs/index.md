# Learning Roadmap

Starting a new learning journey can feel overwhelming. That's why I love using [markmaps](https://markmap.js.org/) to plot my course. I can see the big picture of what I want to cover, but collapse or expand each stage (node) as I go. This way, I can focus on one thing at a time, but always see how it fits into the larger picture.

!!! tip "1. Azure AI Services Markmap: Click to expand" 

    The markmap is interactive. Zoom in/out for details. Circles indicate nodes with children. Click a filled circle to expand the subtree. Click an empty circle to collapse the subtree.

    ```markmap
    # [Docs](https://learn.microsoft.com/azure/search/)

    ## 1. Introduction

    ### 1.1 [What is AI Search](https://learn.microsoft.com/azure/search/search-what-is-azure-search#inside-a-search-service)

    - Search & Retrieval System
    - Enterprise-grade Service
    - High-Performance & Scale
    - Recommended RAG on Azure

    ### 1.2 [What does it provide?](https://learn.microsoft.com/azure/search/search-what-is-azure-search#inside-a-search-service)

    - Search engine (vector, full-text, hybrid)
    - Rich indexing (extract & transform content)
    - Rich querying (incl. fuzzy search, autocomplete)
    - Relevance & performance tuning (incl. semantic ranking)

    ### 1.3 [How does it work?](https://learn.microsoft.com/azure/search/search-what-is-azure-search#inside-a-search-service)

    - Search service sits between data (store) & client (query)
    - AI Search APIs provide enhanced search & retrieval features
    - AI Search _indexers_ automate ingestion from various Data sources
    - AI Search _skillsets_ integrate consumable AI from AI Services

    ![Inside a search service](https://learn.microsoft.com/azure/search/media/search-what-is-azure-search/azure-search.svg)

    ### 1.4 [What are core workloads?](https://learn.microsoft.com/azure/search/search-what-is-azure-search#inside-a-search-service)

    - Indexing = load text/vector content, make it searchable
    - Applied AI = extend to smart indexing with _skillsets_
    - Querying = search populated index, return matching results
    - Integrated Vectorization = use vector search by similarity
    - Semantic Ranking = re-evaluate and order results by relevance

    ### 1.5 [Why use AI Search?](https://learn.microsoft.com/azure/search/search-what-is-azure-search#why-use-azure-ai-search)

    - Full-text search - by keyword **and** by similarity
    - Consolidated index - vectors & text, under user control
    - Integrated data chunking & vectorization - RAG-ready
    - Granular access control - at document level
    - Make blobs searchable - with _indexers_ and _skillsets_
    - Add linguistic or custom text analysis - with _analyzers_ 

    ### 1.6 [How to get started?](https://learn.microsoft.com/azure/search/search-what-is-azure-search#how-to-get-started)

    - [Use Azure Portal](https://learn.microsoft.com/azure/search/search-what-is-azure-search#use-the-azure-portal)
        - Decide on region, tier - from web UI
        - Create search service - from web UI
        - Add data with Import data wizard
        - Query data with Search Explorer

    - [Use APIs](https://learn.microsoft.com/en-us/azure/search/search-what-is-azure-search#use-apis)
        - Create search index - from SDK
        - Upload content ("push" JSON or "pull" with indexers)
        - Query index - from SDK
        - Use Async APIs for long-running tasks
        - See: [Azure AI Search SDK for Python](https://learn.microsoft.com/python/api/overview/azure/search-documents-readme?view=azure-python)

    - [Use Accelerators](https://learn.microsoft.com/azure/search/search-what-is-azure-search#use-accelerators)
        - Chat with your data = custom RAG
        - Coversational knowledge mining = actionable insights
        - Document knowledge mining = extract metadata, entities
        - Build your own copilot (Generic, Advisor, Assistant)

    ### 1.7 [How does it compare?](https://learn.microsoft.com/azure/search/search-what-is-azure-search#compare-search-options)
    
    - Microsoft Search = focus on Sharepoint (vs. Azure, JSON)
    - Bing Search = indexes Bing.com (vs. your content, your control)
    - Azure SQL or Cosmos DB Search = base text/vector search (vs. advanced capabilities)
    - with Dedicated Solutions = (strongest for vector, keyword, hybrid workloads)

    ---


    ## 2. Features

    ### 2.1 [Indexing](https://learn.microsoft.com/en-us/azure/search/search-features-list#indexing-features)
     - Any data source (as JSON), indexers (for automation)
     - Complex data types (hierarchical, nested data structures)
     - Linguistic analysis (language analyzers, custom lexical analyzers)

    ### 2.2 [Vector & Hybrid Search](https://learn.microsoft.com/en-us/azure/search/search-features-list#vector-and-hybrid-search)
    ### 2.3 [Applied AI & Knowledge Mining](https://learn.microsoft.com/en-us/azure/search/search-features-list#applied-ai-and-knowledge-mining)
    ### 2.4 [Full Text & Other Query Forms](https://learn.microsoft.com/en-us/azure/search/search-features-list#full-text-and-other-query-forms)
    ### 2.5 [Security](https://learn.microsoft.com/en-us/azure/search/search-features-list#security-features)
    ### 2.6 [Portal](https://learn.microsoft.com/en-us/azure/search/search-features-list#portal-features)
    ### 2.7 [Programmability](https://learn.microsoft.com/en-us/azure/search/search-features-list#programmability)

    ```

