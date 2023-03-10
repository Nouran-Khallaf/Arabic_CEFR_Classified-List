# Arabic_CEFR_Classified-List
Building a list of Arabic lemmas classified according to CEFR manually is an expensive task in terms of time and effort. Therefore, compiling automatic readability ranked list was reasonable at this stage. This involves creating a dictionary of common words across the available lists to develop a common dataset with better word coverage. This is done by merging the three lists to compile an Arabic list containing only MSA variety. Hence, considering only MSA words from Buckwalter and KELLY's list. A comparison between these two lists shows inconsistency between the lemmas entries, making it difficult to align them. Though, to validate the results, the words presented in all lists were analysed by MADAMira. Merging the lists and aligning them with the MADAMira lemmatiser led to the new wide-coverage Arabic frequency list, which can be used to predict difficulty as the Entropy of the probability distribution of each label in a sentence.
The result of previous analysis of each list urge us to rely on KELLY’s list classification for the words that do not exist in the ‘Al-Kitaab' list. For the compilation of the final list, the following steps:

1. Removing all dialectical words (70, 95 words from Buckwalter's list and 95 from KELLY's list, respectively)
2.	Removing duplicated entries to get unique values (777, 1708 from Buckwalter list and KELLY's list, respectively)
3.	Started compiling the list according to the Arabic linguistics classification 'Al-Kitaab' book chapters by adding 4024 words that added 1947 new lemmas to the final list. 
4.	Then averaged 3669 intersected lemmas in both KELLY's and Buckwalter lists.
5.	 After that, manually classify 525 and 616 lemmas from KELLY's and Buckwalter lists, respectively. 

This resulted in a new classified Arabic Vocabulary list consisting of 8834 distinct lemmas, as illustrated below. The list is classified according to the six CEFR levels (A1, A2, B1, B2, C1, C2) presented as “lemmas” (the lemma is the best representation for Arabic word forms (Knowles and Don, 2004)). This list is the first step in building such an Arabic language profile based on CEFR Level classification. It is an essential resource for sentence readability measurement, and it proved to be effective as one of the sentence features that can rely on measuring sentence readability. Enables selecting sentences from large corpora to represent each language proficiency level.
![image](https://user-images.githubusercontent.com/63323128/217347229-bfddfade-6c6e-4c1c-ba99-5b6cf339eacb.png)

