---
output:
  pdf_document:
      latex_engine: xelatex
  html_document: default
---
# **SMART-seq** _Switching Mechanism At the end of the 5′-end of the RNA Transcript_


## Technology

**SMART-seq** uses a mechanism called _Template Switching_ to generate cDNA libraries. It relies on the Retro Transcriptase (RT) of Moloney Murine Leukemia Virus (MMLV) which adds extra _deoxyC’s_ to the template, allowing the annealing of _Template Switching Oligo’s_ (TSO) and the switching of the _RT MMLV_ to the TSO’s. Tagging and fragmentation of cDNA happens at once through _Tagmentation_ to further construct sequencing libraries.


## Application

By reducing the cost per sample and increasing the throughput, numerous applications become possible, for example the isolation of single cells from different regions of a primary tumour to obtain information on cellular heterogeneity.


## Statistics

Some popular methods assume a negative binomial count distribution across biological replicates. However, in single cell data including **SMART-seq2**, excessive zeros are usually observed compared to the bulk RNA, many methods also use zero-inflated negative binomial models.


### References 

- Picelli, S., Björklund, Å. K., Faridani, O. R., Sagasser, S., Winberg, G., & Sandberg, R. (2013). [Smart-seq2 for sensitive full-length transcriptome profiling in single cells.](https://www.nature.com/articles/nmeth.2639) Nature methods, 10(11), 1096-1098.  
- Picelli, S., Faridani, O. R., Björklund, Å. K., Winberg, G., Sagasser, S., & Sandberg, R. (2014). [Full-length RNA-seq from single cells using Smart-seq2.](https://www.nature.com/articles/nprot.2014.006) Nature protocols, 9(1), 171-181.

---

### Group members

- Anja Estermann: eanja
- Tadas Bareikis: tadasbar
- Xiao Yi: pikkaa215
- Karla Cervantes: KCervaG
- Philipp Niggli: philniggli
- Zhixuan Li: Lillyakasiken

