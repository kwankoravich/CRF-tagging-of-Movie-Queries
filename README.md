# CRF tagging of Movie Queries
 


This project will consider and explore Movie Queries of any name of movies and using CRF tagging for BIO Tagging 

What is BIO Tagging
 BIO or IOB format is commonly used for tagging tokens in computational liguistic especially, Natural Language Processing. 
 
 B-prefix indicates that beginning of a chunk
 I-prefix indicates that the tag inside the chunk
 O indicated that the tag token has no chunk
 
 B- tag is used only when a tag is followed by a tag of the same type without O tokens between them
 
 This example will illustrate how BIO tag apply in use case.
 
  Alex I-PER
  
  is O
  
  going O
  
  to O
  
  Los I-LOC
  
  Angeles I-LOC
  
  in O
  
  California I-LOC
  
  Source: https://en.wikipedia.org/wiki/Inside%E2%80%93outside%E2%80%93beginning_(tagging)
  
