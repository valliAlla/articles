# articles

PGx Corpus : Manually annotated corpus for pharmacogenomics

Entites  involved  involve in this corpus are drug, genomic, variation, phenotype.

It encompasses all the 3 entities at corpus level and sentence level.
                               
Corpus Construction: 

1) Automatic pre-annotation of named entities
               
Key entity recognition - NER tool
               
extention of annotation.

2) Manual Annotationthat encompasses the correction of pre-annotation &addition of typed relationship b/w named entities .

Tools used:
Abstract Retrival-EDisect tool 

Sentence splitting-GeniaSS

Pre-annotation tool-PubTator

Disease recognized by-BANNER which uses conditional random fields (CRF)

Manual Annotation:
11 Annotators are involved in this study 

Phase 1-independently annotated by 2 annotates.
        
sentence and entity pre-annotations. 
        
correct pre-annotation , add relationship between them  
        
discard sentences that are not related .

Phase 2- compared and revised by senior annotator

Phase 3- homogenization.
         
Two annotators review together in two times 
       
1st time : complete process on annotated sentence to identify source of heterogenecity.
         
2nd time : a) list sentences associated with heterogenecity.
                    
b) reaching consensus.

c) modifying annotation.

This corpus construction is similar to our OpenDeID in setting 2 to the phase 1 and 2 in the PGx corpus. Here in PGx phase 1 and 3, Annotator 1 and 2 are annotation in parellel, which is similar to our setting 2. In pahse 2, senior annotator reviews the annotations from phase 1. Which is similarly done in all of our three settings.




Chia - annotated corpus for clinical eligibility criteria.

The components of CAM (chia’s annotation model) are entities, relationships, annotation graphs. 

Samples are collected from clinicalTrails.gov using an annotation tool called "brat".

2 Annotators are involved in this study 

Thay are given separate set of criteria.

They hand create entities and relationships.

Both the annotators discussed and re-annotated accordingly untill 200 trails.

Modifications suspended after satisfactory model obtained.

Further annotation proceedes till 1000 trails.

Final corpus has summoned and collectively revised work of two annotators

This corpus construction is similar to our OpenDeID in setting 2. Where, each annotator is given seperate set of data and annotates independently. 



