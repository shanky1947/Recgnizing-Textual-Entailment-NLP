<h1 align="center">
<!--   <a href="https://github.com/umangraval/Smart-Checkout"><img src="./brand_assets/banner.png" width=600 alt="Smart-Checkout"></a> -->
  Recgnizing-Textual-Entailment-NLP
</h1>



<p align="center">

  <a href="">
    <img src="https://forthebadge.com/images/badges/made-with-python.svg"
         alt="HTML">
  </a>
  <a href="">
    <img src="https://forthebadge.com/images/badges/uses-git.svg"
         alt="CSS">
  </a>
  <a href="">
    <img src="https://forthebadge.com/images/badges/open-source.svg"
         alt="Git">
  </a>
    <a href="">
    <img src="https://forthebadge.com/images/badges/for-robots.svg"
         alt="Javascript">
  </a>
</p>


It solves RTE (Recognizing textual entailment) problem using sentence extraction to cover semantic variation by extracting subject, predicate and object from each sentence.

## Dataset
Dataset used is Third Pascal Recognizing Textual Entailment Challenge
(RTE-3) dataset. It has approximately has 800 pairs text (T) and
hypothesis (H) with labels as True or False showing whether T entails H
or not.

## Methodology
* Preprocessing- Formation of parse tree using Stanford NLP library.  Sentence extraction- Used part of speech and parse tree for
sentence extraction.
* Part of sentence extraction- Subject, Predicate and Object- Used part
of speech tag and syntactic parse tree.
* Feature extraction and classifier- TF-IDF is used for word weighing
and feature table is formed. 
* After feature extraction, any classification algorithm can be used to
classify whether the text and hypothesis are entailed or not
