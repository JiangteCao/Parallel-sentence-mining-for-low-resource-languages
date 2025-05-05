# Parallel-sentence-mining-for-low-resource-languages

Project Highlights

- Parallel corpus: Upper Sorbian ↔ German (aligned sentence pairs)
- Sentence embeddings generated using LaBSE, Glot500, and XLM-R
- Clustering via KMeans and topic visualization (e.g., using PCA)
- Cross-lingual cluster consistency analysis

Structure


├── utils/                            ##### Preprocessing

├── embeddings/                       ##### Model-specific embedding scripts

├── clustering/                       ##### KMeans, cluster analysis, topic labeling

├── visualization/                    ##### PCA plotting scripts

└──  crosslingual/                    ##### Cross-language evaluation (consistency check, mapping)


