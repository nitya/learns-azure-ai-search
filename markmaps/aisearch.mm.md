# Azure AI Search Documentation

---

## 1. Overview
### 1.1 What's Azure AI Search?
### 1.2 New in Search
### 1.3 Features
### 1.4 Try search for free
### 1.5 FAQ

---

## 2. Quickstarts 

### 2.1 Vector search
### 2.2 Generative search (RAG)
### 2.3 Full text search
### 2.4 Semantic ranking
### 2.5 Chat with your data
### 2.6 Connect without keys
### 2.7 Azure Portal
#### 2.7.1 Keyword search wizard
#### 2.7.2 Vector search wizard
#### 2.7.3 Image search wizard
#### 2.7.4 Create a demo app
#### 2.7.5 Create a skillset
#### 2.7.6 Create a knowledge store
#### 2.7.7 Query with Search Explorer
### 2.8 REST
### 2.9 PowerShell
### 2.10 Deployment
#### 2.10.1 ARM template
#### 2.10.2 Bicep
#### 2.10.3 Terraform

---

## 3. Tutorials

### 3.1 Dev Tutorials
#### 3.1.1 Add search to ASP.NET Core (MVC)
#### 3.1.2 Add search to static web apps
##### 3.1.2.1 Overview 
##### 3.1.2.2 Create a search index
##### 3.1.2.3 Deploy static web app
##### 3.1.2.4 Explore the code
#### 3.1.3 Query from Power Apps

### 3.2 Indexing Tutorials
#### 3.2.1 Index any data 
#### 3.2.2 Index at scale (Apache Spark)
#### 3.2.3 Index Azure SQL database
#### 3.2.4 Index JSON in Azure blobs
#### 3.2.5 Index Markdown in Azure blobs
#### 3.2.6 Index multiple Azure data sources
#### 3.2.7 Index encrypted blobs
#### 3.2.8 Create a custom analyzer

### 3.3 RAG Tutorials
#### 3.3.1 Build a RAG solution
#### 3.3.2 Choose models
#### 3.3.3 Design an index
#### 3.3.4 Build an indexing pipeline
#### 3.3.5 Search & generate answers
#### 3.3.6 Maximize relevance
#### 3.3.7 Minimize storage and costs

### 3.4 Skills Tutorials
#### 3.4.1 C#
#### 3.4.2 REST
#### 3.4.3 Debug a skillset


---

## 4. Samples

### 4.1 C# Samples
### 4.2 Java Samples
### 4.3 JavaScript Samples
### 4.4 Python Samples
### 4.5 REST Samples
### 4.6 Vector Samples

---

## 5. Concepts

### 5.1 Data
#### 5.1.1 Search index
#### 5.1.2 Vector store
#### 5.1.3 Knowledge store
#### 5.1.4 Data import strategies
#### 5.1.5 Indexers

### 5.2 Applied AI
#### 5.2.1 Built-in vectorization
#### 5.2.2 AI enrichment during indexing
#### 5.2.3 Enrichment cache
#### 5.2.4 Skillsets

### 5.3 Retrieval
#### 5.3.1 Full-text search
#### 5.3.2 Vector search
#### 5.3.3 Hybrid search
#### 5.3.4 Retrieval Augmented Generation (RAG)
#### 5.3.5 Other query types

### 5.4 Relevance
#### 5.4.1 Semantic ranking
#### 5.4.2 BM25 ranking
#### 5.4.3 Vector ranking
#### 5.4.4 Hybird ranking (RRF)

### 5.5 Security
#### 5.5.1 Security overview
#### 5.4.2 Secure access to external data
#### 5.4.3 Security controls by Azure Policy
#### 5.4.4 Security baseline

---

## 6. How-to Guides

### 6.1 Service management
#### 6.1.1 Create a search service
#### 6.1.2 Choose a region
#### 6.1.3 Choose a tier
#### 6.1.4 Service limits
#### 6.1.5 Plan and manage capacity
#### 6.1.6 Plan and manage costs
#### 6.1.7 Reliability and recovery
#### 6.1.8 Availability zone migration guide
#### 6.1.9 Multi-tenancy
#### 6.1.10 Manage
##### 6.1.10.1 Manage in the Azure portal
##### 6.1.10.2 Manage with Power Shell
##### 6.1.10.3 Manage with Azure CLI
##### 6.1.10.4 Manage with REST
##### 6.1.10.5 Move servie across regions

### 6.2 Index management
#### 6.2.1 Create an index
#### 6.2.2 Load an index
#### 6.2.3 Index via import data wizards
#### 6.2.4 Update or rebuild an index
#### 6.2.5 Alias an index
#### 6.2.6 Import large data sets

#### 6.2.7 Indexers
##### 6.2.7.1 Create an indexer
##### 6.2.7.2 Run or reset indexers
##### 6.2.7.3 Schedule an indexer
##### 6.2.7.4 Define field mappings
##### 6.2.7.5 Indexing whole files
##### 6.2.7.5.1 Content metadata properties
##### 6.2.7.5.2 Index one-to-many
##### 6.2.7.5.3 Index plain text
##### 6.2.7.5.4 Index CSV
##### 6.2.7.5.5 Index JSON
##### 6.2.7.5.6 Index Markdown
##### 6.2.7.6 Troubleshooting guidance
##### 6.2.7.7 Troubleshoot indexer errors & warnings

#### 6.2.8 Data source (indexers)

##### 6.2.8.1 Data sources gallery
##### 6.2.8.2 Azure Storage
###### 6.2.8.2.1 Search over blobs
###### 6.2.8.2.2 ADLS Gen2
###### 6.2.8.2.3 Blobs
###### 6.2.8.2.4 Files
###### 6.2.8.2.5 Tables
###### 6.2.8.2.6 Index changed and deleted content
##### 6.2.8.3 Azure Cosmos DB
###### 6.2.8.3.1 Azure CosmosDB for NoSQL
###### 6.2.8.3.2 Azure CosmosDB for MongoDB
###### 6.2.8.3.3 Azure CosmosDB for Apache Gremlin
##### 6.2.8.4 Azure DB for MySQL
##### 6.2.8.5 Azure SQL
###### 6.2.8.5.1 Azure SQL Databases
###### 6.2.8.5.2 Azure SQL Managed Instances
###### 6.2.8.5.3 Azure SQL Server VMs
##### 6.2.8.6 OneLake files
##### 6.2.8.7 SharePoint and OneDrive

#### 6.2.9 Skillsets
##### 6.2.9.1 Create a skillset
##### 6.2.9.2 Attach an Azure AI resource
##### 6.2.9.3 Define an index projection
##### 6.2.9.4 Debug sessions overview
##### 6.2.9.5 Debug a skillset
##### 6.2.9.6 Reference a skill output
##### 6.2.9.7 Map to index fields
##### 6.2.9.8 Process image files
##### 6.2.9.9 Cache (incremental) enrichment
##### 6.2.9.10 Design tips
##### 6.2.9.11 Custom Skills
###### 6.2.9.11.1 Integrate Custom Skills
###### 6.2.9.11.2 Scale out Custom Skills
###### 6.2.9.11.3 Example - Bing Entity Search
 
### 6.3 Vector search

### 6.4 Keyword search

### 6.5 Hybrid search

### 6.6 Ranking and Relevance

### 6.7 Security

### 6.8 Development
#### 6.8.1
#### 6.8.2
#### 6.8.3
#### 6.8.4
#### 6.8.5
#### 6.8.6
#### 6.8.7

### 6.9 Monitoring & Performance
#### 6.9.1 Monitor
#### 6.9.2 Monitor queries
#### 6.9.3 Monitor indexer-based indexing
#### 6.9.4 Monitor client-side interactions
#### 6.9.5 Visualize resource logos
#### 6.9.6 Performance analysis
#### 6.9.7 Performance benchmarks
#### 6.9.8 Tips for better performance

### 6.10 Knowledge store
#### 6.10.1 Knowledge store overview
#### 6.10.2 Knowledge store projections overview
#### 6.10.3 Create using REST
#### 6.10.4 Shape data
#### 6.10.5 Define projections
#### 6.10.6 Projection example
#### 6.10.7 Connect with Power BI

---

## 7. Responsible AI
### 7.1. Transparency note

---

## 8. Reference

### 8.1 REST API Reference
#### 8.1.1 Search REST API
#### 8.1.2 Management REST API

### 8.2 Azure SDK Reference
#### 8.2.1 .NET
##### 8.2.1.1 Azure.Search.Documents
##### 8.2.1.2 Azure.ResourceManager.Search
#### 8.2.2 Java
##### 8.2.2.1 com.azure.search.documents
##### 8.2.2.2 com.azure.resourcemanager.search
#### 8.2.3 JavaScript
##### 8.2.3.1 azure/search-documents
##### 8.2.3.2 azure/arm-search
#### 8.2.4 Python
##### 8.2.4.1 azure-search-documents
##### 8.2.4.2 azure-mgmt-search

### 8.3 Data Reference
#### 8.3.1 Data types
#### 8.3.2 Data types for indexer data sources
#### 8.3.3 Stopwords reference

### 8.4 Query Reference
#### 8.4.1 Simple query syntax
#### 8.4.2 Full Lucene query syntax
#### 8.4.3 moreLikeThis
#### 8.4.4 OData language reference
##### 8.4.4.1 Overview
##### 8.4.4.2 $filter
##### 8.4.4.3 $orderby
##### 8.4.4.4 $select
##### 8.4.4.5 any, all
##### 8.4.4.6 eq, ne, gt, ge, lt, le
##### 8.4.4.7 search.ismatch, search.ismatchscoring
##### 8.4.4.8 geo.distance, geo.intersects
##### 8.4.4.9 and, or, not
##### 8.4.4.10 search.in
##### 8.4.4.11 search.score
##### 8.4.4.12 OData Language Grammar

### 8.5 Resource management
#### 8.5.1 Azure CLI
#### 8.5.2 Azure PowerShell
#### 8.5.3 Azure Resource Manager template
#### 8.5.4 Azure Policy built-ins
#### 8.5.5 Monitoring data reference

### 8.6 Skills Reference
#### 8.6.1 Overview
#### 8.6.2 Annotation reference language
#### 8.6.3 Azure AI resource skills
##### 8.6.3.1 Document Layout skill
##### 8.6.3.2 Entity Linking (v3)
##### 8.6.3.3 Entity Recognition (v3)
##### 8.6.3.4 Image Analysis 
##### 8.6.3.5 Key Phrase Extraction
##### 8.6.3.6 language Detection
##### 8.6.3.7 OCR
##### 8.6.3.8 PII Detection
##### 8.6.3.9 Sentiment (v3)
##### 8.6.3.10 Text Translation
##### 8.6.3.11 AI Vision multimodal embeddings

#### 8.6.4 Azure AI Search utility skills (nonbillable)
##### 8.6.4.1 Conditional
##### 8.6.4.2 Document Extraction
##### 8.6.4.3 Shaper
##### 8.6.4.4 Text Merger
##### 8.6.4.5 Text Split

#### 8.6.5 Azure OpenAI Skills
##### 8.6.5.1 Azure OpenAI Embedding

#### 8.6.6 Custom skills
##### 8.6.6.1 Azure Machine Learning (AML)
##### 8.6.6.2 Custom Entity Lookup
##### 8.6.6.3 Custom Web API

#### 8.6.7 Deprecated skills
##### 8.6.7.1 Deprecated skills
##### 8.6.7.2 Named Entity Recognition (v2)
##### 8.6.7.3 Entity Recognition (v2)
##### 8.6.7.4 Sentiment (v2)

### 8.7 Vectorizers Reference
#### 8.7.1 Azure OpenAI
#### 8.7.2 Azure AI Vision
#### 8.7.3 Azure AI Foundry model catalog
#### 8.7.4 Custom Web API

---

## 9. Resources
### 9.1 Stack Overflow
### 9.2 Azure pricing calculator
### 9.3 Azure products by region
### 9.4 Compliance and certification
### 9.5 Demos, tools and training
#### 9.5.1 Demo sites
#### 9.5.2 Tools and accelerators
#### 9.5.3 Training
### 9.6 Partner solutions
#### 9.6.1 Partner spotlight
#### 9.6.2 Partner data sources (Terms of Use)

---