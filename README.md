# 🎬 Movie Search – Assignment 1

Semantic search on movie plots using **SentenceTransformers**.

---

##  Project Overview
This repository contains my submission for **Assignment 1: Semantic Search on Movie Plots**.

The task was to design a semantic search engine that can find the most relevant movies based on a text query.  
- Movie summaries are encoded into vector embeddings with **SentenceTransformers (all-MiniLM-L6-v2)**.  
- Queries are also converted into embeddings.  
- **Cosine similarity** is used to measure relevance between the query and each movie plot.  
- The system returns the top matching movies.

---



##  Usage Example

```python
from movie_search import search_movies

print(search_movies("spy thriller in Paris", top_n=3))
```

---

## Repository Structure

```
movie-search-assignment/
│── AI_Systems_Development_Assignment_1_rithwik_eluri_221020426.ipynb   
│── movie_search.py                                              implementation
│── test_movie_search.py                                          
│── movies.csv                                                    
│── requirements.txt                                             
│── README.md                                                    
```
