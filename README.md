# Abstract

My thesis examines the relationships between XML schemas and documents, to determine the degree of correspondence between two different documents. However, comparing XMLs is challenging due to structural complexity, naming conflicts and scalability issues. To address these, I have tried several methods in my thesis, including simple search techniques and fuzzy search algorithms.

Of the simple search methods, exact matching performed very poorly, however, approximate matching was used to find results in principle. Fuzzy search using Levenshtein distance improved performance by identifying approximate matches, handling small mistakes. In addition, the Ratcliff/Obershelp algorithm was utilized for the "One-to-One Match" method, which further improved accuracy by focusing on pairwise label comparisons.

During the implementation, I used Python frameworks such as FuzzyWuzzy and difflib for efficient analysis. The results show that Approximate matching provide a quite good solutions for XML schema comparison. Further development options include hybrid models and deep learning models to automate and refine relation detection.
