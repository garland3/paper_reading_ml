# From_Local_To_Global_A_Graph_RAG_Approach_To_Query_Focused_Summarization

* Paper from Microsoft

[Link](https://arxiv.org/abs/2404.16130v1)


## TLDR

    This work proposes a Graph RAG approach to question answering over private text corpora that scales with both the generality of user questions and the quantity of source text to be indexed, and shows that Graph RAG leads to substantial improvements over a na\"ive RAG baseline for both the comprehensiveness and diversity of generated answers


## Abstract. 

    The use of retrieval-augmented generation (RAG) to retrieve relevant informa-
    tion from an external knowledge source enables large language models (LLMs)
    to answer questions over private and/or previously unseen document collections.
    However, RAG fails on global questions directed at an entire text corpus, such
    as “What are the main themes in the dataset?”, since this is inherently a query-
    focused summarization (QFS) task, rather than an explicit retrieval task. Prior
    QFS methods, meanwhile, fail to scale to the quantities of text indexed by typical
    RAG systems. To combine the strengths of these contrasting methods, we propose
    a Graph RAG approach to question answering over private text corpora that scales
    with both the generality of user questions and the quantity of source text to be in-
    dexed. Our approach uses an LLM to build a graph-based text index in two stages:
    first to derive an entity knowledge graph from the source documents, then to pre-
    generate community summaries for all groups of closely-related entities. Given a
    question, each community summary is used to generate a partial response, before
    all partial responses are again summarized in a final response to the user. For a
    class of global sensemaking questions over datasets in the 1 million token range,
    we show that Graph RAG leads to substantial improvements over a na ̈ıve RAG
    baseline for both the comprehensiveness and diversity of generated answers. An
    open-source, Python-based implementation of both global and local Graph RAG
    approaches is forthcoming at


 ## Helpful links

* [Downloaded paper](data/graph_rag.pdf)
* [Semantic Scholar](https://www.semanticscholar.org/paper/From-Local-to-Global%3A-A-Graph-RAG-Approach-to-Edge-Trinh/c1799bf28d1ae93e1631be5b59196ee1e568f538)
* [A reading group video](https://www.youtube.com/watch?v=r09tJfON6kE)