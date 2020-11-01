# Summary

UD Karelian-KKPP is a manually annotated new corpus of Karelian made in
Universal dependencies annotation scheme. The data is collected from
[VepKar corpora](http://dictorpus.krc.karelia.ru/en/corpus/text) and consists of
mostly modern news texts but also some stories and educational texts.

# Introduction

UD Karelian-KKPP is a manually annotated new corpus of Karelian made in
Universal dependencies annotation scheme. The data is collected from
[VepKar corpora](http://dictorpus.krc.karelia.ru/en/corpus/text) and consists of
mostly modern news texts but also some stories and educational texts. We have
based many decisions in the dependency annotations on pre-existing
Finnish treebanks. The morphological annotations and grammar are based on the
refered books (Zaikov, Ahtia) and the [Karelian
dictionary](http://kaino.kotus.fi/cgi-bin/kks/karjala.cgi), with necessary
orthographical modernisations.

# Acknowledgments

Finnish treebank developers for a good reference treebank and also [SETS
dep search](http://bionlp-www.utu.fi/dep_search/) which has been very useful in
finding equivalent examples from Finnish treebanks.

## References

* Zaikov, Pekka. *Vienankarjalan kielioppi. Lisänä harjotukšie ta lukemisto*
  (2013).
* Ahtia, Edvard Vilhelm. *Karjalan kielioppi.* Karjalan Kansalaisseura, (1938).
* [Karjalan kielen
   verkkosanakirja](http://kaino.kotus.fi/cgi-bin/kks/kks_etusivu.cgi)

# Cite as

If you use the treebank, please cite the UDW 2019 paper:

```bibtex
@inproceedings{pirinen2019building,
  title={Building minority dependency treebanks, dictionaries and computational
        grammars at the same time—an experiment in Karelian treebanking},
  author={Pirinen, Tommi A},
  booktitle={Proceedings of the Third Workshop on Universal Dependencies (UDW,
             SyntaxFest 2019)},
  pages={132--136},
  year={2019}
}
```

# MISC annotations

The treebank has been created by manually selecting and re-annotating a corpus
created with the annotation toolkit introduced in *Pirinen (2019)*. The
annotations of the source analyser that did not match potential UD features may
have been left in the MISC column by the cleanup script:

* `Gender=Masc|Fem` is used in the source analyser for proper nouns; there is no
  grammatical gender in Karelian
* `PropnType=Geo|First|Last` is used for categorising proper nouns
* `Weight=` is used by the WFST analyser and the dependency suggester
* some values that are used in traditional grammars but do not match UD feature
  value pairs may appear, e.g. `PronType=Qu` for "quantifier" pronoun

# Changelog

* 2019-05-15 v2.4
  * Initial release in Universal Dependencies.

<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.4
License: CC BY-SA 4.0
Includes text: yes
Genre: nonfiction news web
Lemmas: manual native
UPOS: manual native
XPOS: not available
Features: manual native
Relations: manual native
Contributors: Pirinen, Tommi A
Contributing: elsewhere
Contact: tommi.antero.pirinen@uni-hamburg.de
===============================================================================
</pre>
