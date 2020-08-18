# The Semantics and Collocations Relation in Food Recipes

# Resources:
[Knowledge Acquisition with Natural Language Processing in the Food Domain: Potential and Challenges](https://projet.liris.cnrs.fr/cwc/cwc2012/cwc2012_submission_1.pdf)
(https://www.analyticsvidhya.com/blog/2019/09/introduction-information-extraction-python-spacy/)

# Processing according to the article

1. Web Crawling: Get articles from restaurant ad agency.  
Data:  
  English: https://eater.com/archives; https://ny.eater.com/archives  
  Chinese: https://blog.foodmapnyc.com/  


2. Detect food entities:  
There are many food with strange names, or the resaurant could make up their own name, and the name of that food may be totally different from the resources. So the way of "incorporating generalpurpose ontologies" may not work.
: POS tags => NOUN + machine learning?
+ word2vect?



3. detarmain the relation
  1) Statistical Co-occurrence
    Only depend on the number of Co-occurrence of two term
  2) Pattern-based Approaches:
    Simple pattern detection:
      dish name pattern: "XX XX XX ($14)"
    Learn Patten from the text:
      lable the sentence and the relations, then use maichine learning to learn the pattern
  3) further linguistic analysis?

