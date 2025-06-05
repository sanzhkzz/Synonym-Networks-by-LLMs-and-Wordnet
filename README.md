# Synonym-Networks-by-LLMs-and-Wordnet

This project compares synonym networks built using Mistral-7B (LLM) and WordNet (lexical database).  
We analyzed the structure, connectivity, and semantic clustering of both networks using a set of 240 adjectives.

## 🧠 Key Insights
- LLM network: 2,668 nodes, denser and highly interconnected.
- WordNet: 2,122 nodes, more segmented and semantically precise.
- Degree distribution, clustering, and subgraph examples included.

## 📄 Paper
The full technical report can be found in `/Paper`.

## 📂 Code
The scripts to build, analyze, and visualize both networks are in `/Code`.

## 📊 Graph Outputs
Visualizations of degree distributions and semantic spread of example words like "heavy" are stored in `/Graphs`.

## 💬 Citation
> Sailaubek, S. (2025). *Comparing Lexical Structures: A Network Analysis of WordNet and LLM-Generated Synonyms*. Cognitive Data Science (University of Trento).

## 🔗 Related
- Mistral-7B model: https://huggingface.co/mistralai/Mistral-7B-Instruct-v0.1
- WordNet via NLTK: https://www.nltk.org/howto/wordnet.html
