# Awesome-RAG

- [Topics](#topics)
  - [General](#general)
    - [Patterns](#patterns)
  - [Routing](#routing)
  - [LLM Models](#llm-models)
    - [Finetuning and Pretraining](#finetuning-and-retraining)
  - [Retrieval](#retrieval)
    - [Chunking](#chunking)
    - [Search](#search)
  - [Prompts](#prompts)
    - [Prompting strategies](#prompting-strategies)
      - [Multi-Modal RAG](#multi-modal-rag)
      - [Multi-index RAG](#multi-index-rag)
      - [Multi-Document](#multi-document)
      - [FLARE](#flare)
      - [Chain-of-Verification](#chain-of-verification) 
    -  [Automated prompt optimization](#automated-prompt-optimization)
    - [Context](#context)
      - [Long context RAG](#long-context-rag)
      - [Knowledge and Knowledge Graphs](#knowledge-and-knowledge-graphs)
  - [Generation](#generation)
    - [Hallucination](#hallucination)
    - [Guardrails](#guardrails)
  - [Evaluation](#evaluation)
  - [Performance and cost](#performance-and-cost)
  - [Privacy](#privacy)
  - [Security](#security)
    - [Overloading context](#overloading-context)
    - [Injections](#security)
- [Series](#series)
- [Sandbox](#sandbox)
- [Tools](#tools)
- [Vendor-specific examples](#vendor-specific-examples)
  - [Elastcisearch + OpenAI](#elastcisearch-openai)
  - [Vespa](#vespa)
  - [Qdrant](#qdrant)


## Topics

### General

- [Retrieval Augmented Generation — Intuitively and Exhaustively Explained](https://towardsdatascience.com/retrieval-augmented-generation-intuitively-and-exhaustively-explain-6a39d6fe6fc9)
- [GraphRAG - Microsoft Research Blog Post](https://www.microsoft.com/en-us/research/blog/graphrag-unlocking-llm-discovery-on-narrative-private-data/)

#### Patterns

- [Generative AI Lifecycle Patterns](https://dr-arsanjani.medium.com/the-generative-ai-lifecycle-1b0c7d9463ec)
- [Why do RAG pipelines fail? Advanced RAG Patterns — Part1
Ozgur Guler](https://cloudatlas.me/why-do-rag-pipelines-fail-advanced-rag-patterns-part1-841faad8b3c2)
- [How to improve RAG peformance — Advanced RAG Patterns — Part2](https://cloudatlas.me/how-to-improve-rag-peformance-advanced-rag-patterns-part2-0c84e2df66e6)
- [Patterns for Building LLM-based Systems & Products](https://eugeneyan.com/writing/llm-patterns/)
- [AI Engineer Summit - Building Blocks for LLM Systems & Products](https://eugeneyan.com/speaking/ai-eng-summit/)
- [Technical Considerations for Complex RAG](https://medium.com/enterprise-rag/a-first-intro-to-complex-rag-retrieval-augmented-generation-a8624d70090f)

### Routing

- [Routing in RAG-Driven Applications](https://towardsdatascience.com/routing-in-rag-driven-applications-a685460a7220)

### LLM Models

#### Finetuning and Pretraining

- [Fine-Tuning Llama 2.0 with Single GPU Magic](https://ai.plainenglish.io/fine-tuning-llama2-0-with-qloras-single-gpu-magic-1b6a6679d436)
- [Practitioners guide to fine-tune LLMs for domain-specific use case](https://cismography.medium.com/practitioners-guide-to-fine-tune-llms-for-domain-specific-use-case-part-1-4561714d874f)
- [Are You Pre-training your RAG Models on Your Raw Text?](https://medium.com/thirdai-blog/are-you-pre-training-your-rag-models-on-your-raw-text-40f832d87703)
- [Combine Multiple LoRA Adapters for Llama 2](https://towardsdatascience.com/combine-multiple-lora-adapters-for-llama-2-ea0bef9025cf)


### Retrieval

- [Boosting RAG: Picking the Best Embedding & Reranker models](https://blog.llamaindex.ai/boosting-rag-picking-the-best-embedding-reranker-models-42d079022e83)
- [Improving RAG (Retrieval Augmented Generation) Answer Quality with Re-ranker](https://medium.com/towards-generative-ai/improving-rag-retrieval-augmented-generation-answer-quality-with-re-ranker-55a19931325)
- [From Search to Synthesis: Enhancing RAG with BM25 and Reciprocal Rank Fusion](https://medium.com/@kachari.bikram42/from-search-to-synthesis-enhancing-rag-with-bm25-and-reciprocal-rank-fusion-872d21dc4ca7)
- [Build a search engine, not a vector DB](https://blog.elicit.com/search-vs-vector-db/)

#### Chunking

- [Chunking Strategies for LLM Applications](https://www.pinecone.io/learn/chunking-strategies/)
- [Evaluating the Ideal Chunk Size for a RAG System using LlamaIndex](https://blog.llamaindex.ai/evaluating-the-ideal-chunk-size-for-a-rag-system-using-llamaindex-6207e5d3fec5)
- [How to Chunk Text Data — A Comparative Analysis](https://towardsdatascience.com/how-to-chunk-text-data-a-comparative-analysis-3858c4a0997a)

#### Search

- [Awesome Search](https://github.com/frutik/awesome-search)
- [Advanced RAG Retrieval Strategies: Sentence Window Retrieval](https://generativeai.pub/advanced-rag-retrieval-strategies-sentence-window-retrieval-b6964b6e56f7)

### Prompts

- [Emerging RAG & Prompt Engineering Architectures for LLMs](https://cobusgreyling.medium.com/updated-emerging-rag-prompt-engineering-architectures-for-llms-17ee62e5cbd9)
- [How to Cut RAG Costs by 80% Using Prompt Compression](https://towardsdatascience.com/how-to-cut-rag-costs-by-80-using-prompt-compression-877a07c6bedb)

#### Prompting strategies

#### Multi-Modal RAG

- [Multi-Modal RAG](https://blog.llamaindex.ai/multi-modal-rag-621de7525fea)

#### Multi-index RAG

- [Having all of your data stored in one collection isn't always the best for RAG apps](https://twitter.com/ecardenas300/status/1724829560041038072)

#### Multi-Document

- [Advanced RAG — Multi-Documents Agent with LlamaIndex](https://blog.gopenai.com/advanced-rag-multi-documents-agent-with-llamaindex-43b604f84909)

#### FLARE

- [Better RAG with Active Retrieval Augmented Generation FLARE](https://blog.lancedb.com/better-rag-with-active-retrieval-augmented-generation-flare-3b66646e2a9f)


##### Chain-of-Verification

- [in-Of-Verification Reduces Hallucination in LLMs](https://cobusgreyling.medium.com/chain-of-verification-reduces-hallucination-in-llms-20af5ea67672)

##### Chain-Of-Thought

- [Chain-Of-Thought Prompting In LLMs](https://cobusgreyling.medium.com/chain-of-thought-prompting-in-llms-1077164edf97)

#### Context

- [The Needle In a Haystack Test](https://towardsdatascience.com/the-needle-in-a-haystack-test-a94974c1ad38)
- [Conversational Memory for LLMs with Langchain](https://www.pinecone.io/learn/series/langchain/langchain-conversational-memory/)

##### Long context RAG

- [The next generation of RAG: Long-Context RAG](https://twitter.com/ecardenas300/status/1724129722492142048)
- [NVIDIA Research: RAG with Long Context LLMs](https://blog.llamaindex.ai/nvidia-research-rag-with-long-context-llms-7d94d40090c4)


##### Knowledge and Knowledge Graphs

- [Graph RAG: Unleashing the Power of Knowledge Graphs with LLM](https://medium.com/@nebulagraph/graph-rag-the-new-llm-stack-with-knowledge-graphs-e1e902c504ed)
- [Embeddings + Knowledge Graphs: The Ultimate Tools for RAG Systems](https://towardsdatascience.com/embeddings-knowledge-graphs-the-ultimate-tools-for-rag-systems-cbbcca29f0fd)
- [The Practical Benefits to Grounding an LLM in a Knowledge Graph
Daniel Bukowski](https://medium.com/@bukowski.daniel/the-practical-benefits-to-grounding-an-llm-in-a-knowledge-graph-919918eb493)
- [Implement RAG with Knowledge Graph and Llama-Index](https://medium.aiplanet.com/implement-rag-with-knowledge-graph-and-llama-index-6a3370e93cdd)

- [Awesome Knowledge Graphs](https://github.com/frutik/awesome-knowledge-graphs)
- [HippoRAG: Neurobiologically Inspired Long-Term Memory for Large Language Models](https://arxiv.org/abs/2405.14831)
  
## Generation

### Hallucination

- [How to Detect Hallucinations in LLMs](https://towardsdatascience.com/real-time-llm-hallucination-detection-9a68bb292698)
- [Measuring Hallucinations in RAG Systems](https://vectara.com/measuring-hallucinations-in-rag-systems/)

### Guardrails

- [Safeguarding LLMs with Guardrails](https://towardsdatascience.com/safeguarding-llms-with-guardrails-4f5d9f57cff2)
- [NeMo Guardrails: The Missing Manual](https://www.pinecone.io/learn/nemo-guardrails-intro/)

### Evaluation

- [RAG Evaluation](https://cobusgreyling.medium.com/rag-evaluation-9813a931b3d4)
- [Evaluating RAG: A journey through metrics](https://www.elastic.co/search-labs/blog/articles/evaluating-rag-metrics)


### Performance and cost

- [Secrets to Optimizing RAG LLM Apps for Better Performance, Accuracy and Lower Costs!](https://medium.com/madhukarkumar/secrets-to-optimizing-rag-llm-apps-for-better-accuracy-performance-and-lower-cost-da1014127c0a)

### Various

- [Vector Search Is Not All You Need](https://towardsdatascience.com/vector-search-is-not-all-you-need-ecd0f16ad65e)
- [Improve RAG Pipelines With These 3 Indexing Methods](https://levelup.gitconnected.com/improve-rag-pipelines-with-these-3-indexing-methods-83317e972676)

## Security

- [Hijacking Chatbots: Dangerous Methods Manipulating GPTs](https://medium.com/@jankammerath/hijacking-chatbots-dangerous-methods-manipulating-gpts-52342f4f88b8)

## Series

### Heiko Hotz

- [RAG vs Finetuning — Which Is the Best Tool to Boost Your LLM Application?](https://towardsdatascience.com/rag-vs-finetuning-which-is-the-best-tool-to-boost-your-llm-application-94654b1eaba7)

### Kelvin Lu

- [Compare PDF Question Answering Systems Build with OpenAI and Google VertexAI](https://medium.com/@kelvin.lu.au/compare-pdf-question-answering-with-openai-and-google-vertexai-46638d62327b)
- [What We Need to Know Before Adopting a Vector Database](https://medium.com/@kelvin.lu.au/what-we-need-to-know-before-adopting-a-vector-database-85e137570fbb)
- [Disadvantages of RAG](https://medium.com/@kelvin.lu.au/disadvantages-of-rag-5024692f2c53)

### Wenqi Glantz

#### Building

- [Building Production-Ready LLM Apps with LlamaIndex: Document Metadata for Higher Accuracy Retrieval](https://betterprogramming.pub/building-production-ready-llm-apps-with-llamaindex-document-metadata-for-higher-accuracy-retrieval-a8ceca641fb5)
- [Building Production-Ready LLM Apps With LlamaIndex: Recursive Document Agents for Dynamic Retrieval](https://betterprogramming.pub/building-production-ready-llm-apps-with-llamaindex-recursive-document-agents-for-dynamic-retrieval-1f4b25287918)


#### Evaluation

- [Exploring End-to-End Evaluation of RAG Pipelines](https://betterprogramming.pub/exploring-end-to-end-evaluation-of-rag-pipelines-e4c03221429)
- [Evaluation Driven Development, the Swiss Army Knife for RAG Pipelines](https://levelup.gitconnected.com/evaluation-driven-development-the-swiss-army-knife-for-rag-pipelines-dba24218d47e)

#### Privacy

- [Masking PII Data in RAG Pipeline](https://betterprogramming.pub/masking-pii-data-in-rag-pipeline-326d2d330336)

### Ravi Theja

#### Evaluation

- [Evaluating the Ideal Chunk Size for a RAG System using LlamaIndex](https://blog.llamaindex.ai/evaluating-the-ideal-chunk-size-for-a-rag-system-using-llamaindex-6207e5d3fec5)

## Tools

- [Langchain is NOT for production use. Here is why ..](https://medium.com/@aldendorosario/langchain-is-not-for-production-use-here-is-why-9f1eca6cce80)
- [Three Open-Source RAG Tools You Need to Know About](https://medium.com/programmers-journey/three-open-source-rag-tools-you-need-to-know-about-331c3f28ab22)
- [LlamaIndex](https://github.com/run-llama/llama_index)
- [Langchain](https://github.com/langchain-ai/langchain)
- [HayStack](https://github.com/deepset-ai/haystack)
- [RAGAS](https://github.com/explodinggradients/ragas)
- [AutoRAG](https://github.com/Marker-Inc-Korea/AutoRAG) - AutoML tool for RAG. Automatically optimize RAG pipeline with single YAML file.

## Vendor-specific examples

- [RAG Pipeline with Mistral 7B Instruct Model in Colab: A Step-by-Step Guide
Qendel AI GoPenAI](https://blog.gopenai.com/rag-pipeline-with-mistral-7b-instruct-model-a-step-by-step-guide-138df378a0c2)


### Elastcisearch + OpenAI


### Vespa

- [Hands-On RAG guide for personal data with Vespa and LLamaIndex](https://blog.vespa.ai/scaling-personal-ai-assistants-with-streaming-mode/)

### Qdrant

## Sandbox

- [Innovations In Retrieval Augmented Generation](https://medium.com/emalpha/innovations-in-retrieval-augmented-generation-8e6e70f95629)  
- [Automating Hyperparameter Tuning with LlamaIndex. Exploring ParamTuner for RAG pipelines](https://levelup.gitconnected.com/automating-hyperparameter-tuning-with-llamaindex-72fdd68e3b90)
- [A Guide on 12 Tuning Strategies for Production-Ready RAG Applications](https://towardsdatascience.com/a-guide-on-12-tuning-strategies-for-production-ready-rag-applications-7ca646833439)
- [Structured Knowledge Extraction: from DbPedia Queries to Llama Index Knowledge Graphs](https://python.plainenglish.io/structured-knowledge-extraction-from-dbpedia-queries-to-llama-index-knowledge-graphs-47899c38e767)
- [The Power of Retrieval Augmented Generation: A Comparison between Base and RAG LLMs with Llama2](https://towardsdatascience.com/the-power-of-retrieval-augmented-generation-a-comparison-between-base-and-rag-llms-with-llama2-368865762c0d)
- [How to Build Long-term Corporate Memory for Your Organisation Using ChatGPT](https://ai.plainenglish.io/how-to-build-long-term-corproate-memory-for-your-organisation-using-chatgpt-d213804d4176)
