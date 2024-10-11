1. Use the cramer project's 256k news corpus and run LDA
2. Use Manas corpus to view collocation


## Literature to review
In the field of Natural Language Processing (NLP), common approaches to disambiguate homonyms include the use of context-sensitive classifiers, domain-specific word vectors, mutual information, and neural network models. Here's a summary of some prominent methods:

1. **Context-Sensitive Classifiers**: Techniques such as weighting feature vectors based on word position and context are often used. For example, in the disambiguation of gene and protein names, weighting by word positions in the context outperformed standard classifiers like Naive Bayes [(Ginter et al., 2004)](https://consensus.app/papers/techniques-disambiguation-natural-language-their-ginter/651c886ffd435867a849f6e86ef54a1c/?utm_source=chatgpt).

2. **Domain-Specific Word Vectors**: In biomedical applications, aggregating word vectors from domain-specific models enhances discrimination of homonyms compared to general models. This method achieved a high AUC score, indicating effective disambiguation [(Toddenroth, 2022)](https://consensus.app/papers/evaluation-domainspecific-word-vectors-biomedical-word-toddenroth/4cb36be60e885d21996234b9719a86c2/?utm_source=chatgpt).

3. **Mutual Information and Sense-Tagged Dictionaries**: Combining mutual information and sense-tagged compound noun dictionaries provides high precision in homonym sense disambiguation. This method leverages association measures between words and uses weights derived from mutual information values and sense frequency [(Heo et al., 2006)](https://consensus.app/papers/homonym-disambiguation-based-mutual-information-heo/a2364917bde15b3d8369f11faac10f6e/?utm_source=chatgpt).

4. **Neural Networks**: Deep neural networks (DNNs) are used for complex homonym and synonym classification, outperforming methods like Support Vector Machines (SVM) and Decision Trees in multiple performance metrics [(Firdaus et al., 2021)](https://consensus.app/papers/network-technique-structure-improving-author-homonym-firdaus/e0931707e452540ca795fdc3a6635b86/?utm_source=chatgpt).

5. **Genetic and Memetic Algorithms**: These algorithms are applied to word sense disambiguation problems, such as for the Arabic language, and have shown to outperform naive Bayes classifiers in precision [(Menai, 2014)](https://consensus.app/papers/word-sense-disambiguation-using-application-arabic-menai/cfbeba2acfd150ec834f55e9fbcab6c5/?utm_source=chatgpt).

In conclusion, NLP researchers use a combination of feature-based classifiers, neural networks, domain-specific word vectors, and genetic algorithms to disambiguate homonyms effectively.

### Another list (with possible duplicates)
Here are several academic papers focusing on **homonyms disambiguation**:

1. **Light Diacritic Restoration to Disambiguate Homographs in Modern Arabic Texts**
   - Authors: Azmi Aqil M., Alnefaie Rehab M., Aboalsamh Hatim A.
   - Published: December 13, 2021
   - This paper discusses techniques for restoring diacritics in Arabic texts to improve the disambiguation of homographs, which are words that are spelled the same but have different meanings[1].

2. **Homonym Disambiguation based on Mutual Information and Sense-Tagged Compound Noun Dictionary**
   - This research presents a method for automatic homonym disambiguation using Mutual Information (MI) alongside a sense-tagged dictionary. The approach aims to enhance the accuracy of understanding context-specific meanings of homonyms in various texts[3].

3. **Research on the Homonyms Disambiguation Based on Mongolian Nouns Semantic Network**
   - This study explores a semantic network approach for disambiguating homonyms in the Mongolian language, focusing on noun usage and context[4][6].

4. **A Formal Approach for Measuring the Lexical Ambiguity Degree in Natural Language Requirement Specification**
   - This paper provides insights into measuring lexical ambiguity, including homonyms, across different languages. It discusses methodologies for addressing ambiguity in natural language processing tasks[5].

5. **Using LSA to Compute Word Sense Frequencies**
   - This document discusses the challenges of disambiguating polysemes and homonyms, emphasizing the difficulties even human interpreters face when distinguishing meanings based on context[2].

These papers collectively cover various methodologies and approaches to tackle the complexities of homonym disambiguation across different languages and contexts.

Citations:
[1] https://dl.acm.org/doi/10.1145/3486675
[2] https://apps.dtic.mil/sti/tr/pdf/ADA481969.pdf
[3] https://www.semanticscholar.org/paper/Homonym-Disambiguation-based-on-Mutual-Information-Heo-Seo/226cb9cd839257667384e7acf1bc6210ffe6749d
[4] https://colab.ws/articles/10.1109%2FICINIS.2013.69
[5] https://www.researchgate.net/publication/271467859_A_formal_approach_for_measuring_the_lexical_ambiguity_degree_in_natural_language_requirement_specification_Polysemes_and_Homonyms_focused
[6] https://www.researchgate.net/scientific-contributions/Hasi-2088194504
[7] https://arxiv.org/pdf/1811.04860.pdf
[8] https://ensani.ir/fa/article/download/501279