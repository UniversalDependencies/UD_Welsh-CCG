# Summary

UD Welsh-CCG (Corpws Cystrawennol y Gymraeg) is a treebank of Welsh,
annotated according to the Universal Dependencies guidelines.


# Introduction

The main part of the annotated sentences come from the Welsh Wikipedia. 
Some sentences have been taken from the Corpus of the Welsh Assembly, 
from websites of Welsh speaking organisations (Cymdeithas yr Iaith Gymraeg, University of Wales), 
News (y Golwg, local Welsh language newspapers, BBC Cymru) and Welsh language blogs.
A few example sentences are taken from Welsh Grammars (Gramaded Cymraeg Cyfoes: Gareth King, Modern Welsh).

# Acknowledgements

If you use this treebank in your work, please cite:

```
@inproceedings{heinecke2019,
  author = {Heinecke, Johannes and Tyers, Francis M.},
  title = {{Development of a Universal Dependencies treebank for Welsh}},
  year = {2019},
  booktitle = {{Proceedings of the Celtic Language Technology Workshop}},
  publisher = {European Association for Machine Translation},
  address = {Dublin},
  pages = {21--31},
  url = {https://www.aclweb.org/anthology/W19-6904},
}
```

# Changelog

2025-04-12 v2.16
  * adding missing `ExtPos` features
  * subject heads corrected
2024-10-03 v2.15
  * new sentences (train)
  * removed problems shown by latest version validator.py
2024-02-25 v2.14
  * new sentences (train)
2023-05-09 v2.12
  * English translations continued
2022-11-14 v2.11
  * new sentences
  * (lexical) errors corrected (gender)
  * tokenization of times corrected
  * added `NumForm` and `NumType` to `NUM` tokens
2022-04-24 v2.10
  * new sentences
  * duplicated deleted
2021-11-03 v2.9
  * new sentences
  * minor corrections
2021-05-10 v2.8
  * yr+AUX retokenized as MWT
  * *pawb*, *neb* tagged as `PRON`
  * applied language specific validation script
  * relative clauses revisited
  * added `VerbForm=Fin` to finite verb forms
  * added missing `PronType`
  * added feature `NumType=Ord` to ADJ which are ordinals
2020-11-06 v2.7
  * new sentences
2020-05-10 v2.6
  * new sentences
2019-11-10 v2.5
  * new sentences
  * corrections
  * corrected feature `Person=Impers` to `Person=0` to comply with guidelines
  * corrected lemma for conjunction `ac` to `a`
  * somme lemmas corrected (mutation errors)
2019-05-15 v2.4
  * initial version
2019-05-30
  * mutations corrected (or feature Mutation=)
2019-09-15
  * lemma for conjunction "ac" normalised to "a", number + "o" + noun  corrected



<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.4
License: CC BY-SA 4.0
Includes text: yes
Genre: grammar-examples wiki nonfiction fiction news
Lemmas: converted from manual
UPOS: converted from manual
XPOS: manual native
Features: converted from manual
Relations: manual native
Contributors: Heinecke, Johannes; Tyers, Francis; 
Contributing: elsewhere
Contact: johannes.heinecke@orange.com
===============================================================================
</pre>
