# verb-centrality-nlp
The project models sentences as dependency graphs in order to investigate whether the verbs are the most central words. It compares centrality measures across languages and parts of speech, testing the universality of verb centrality and its relevance for NLP tasks such as parsing and modeling.

Objectives:
Model sentences as dependency graphs
Compute centrality measures: Degree Centrality, Betweenness Centrality, Closeness Centrality
Compare verbs with other parts of speech (nouns, adjectives, adverbs)
Analyze results across multiple languages
Test whether verb centrality is universal or language-dependent

Languages Analyzed
-English
-Hindi
-French
-German

Methodology:
-Parse sentences into dependency structures
-Represent each sentence as a graph
-Compute centrality metrics for each node
-Aggregate results by part-of-speech
-Compare distributions across languages

Key Insights
The analysis shows that verbs generally exhibit higher degree centrality because they connect to multiple dependents in a sentence. However, closeness centrality varies depending on word order, such as SVO versus SOV structures. Additionally, morphologically rich languages tend to display greater variability in centrality patterns. The results also suggest that dependency length minimization plays an important role in shaping these centrality characteristics across languages.

Tools & Libraries
Python
NetworkX
Pandas
Matplotlib
NLP parsing tools (UD treebanks / parsers)
