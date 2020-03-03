# Location Phrase Dataset

This dataset was created for the research described in this LREC 2020 paper:

Paul McNamee, James Mayfield, Cash Costello, Caitlyn Bishop, Shelby
Anderson, 'Tagging Location Phrases in Text'. Proceedings LREC 2020,
Marseille, France, 11-16 May, 2020

These annotations are of named and non-named locations in news text.  Over 50k tokens are
annotated in both English and Russian.  Each zipfile unpacks into
three directories (plain, conll, and annotations)
* *plain*: UTF8 text.  Not sentence split
* *conll*: A header (TOKEN) and one token per line with spaces between 'sentences'
* *annotations*: TSV files with a TOKEN and a TAG separated by a tab
character.  IOB2 format.
Note, there are sentence splitting errors in some of the data.

The seven tags are: LAND, ADJ, DIF, GAG, SI, DIR, and O.  Annotations guidelines are described in the paper.

## English
The data are from two sources, SETimes news articles (58k tokens), and Voice of
America (7k tokens).

### Southeast European Times
The SETimes site ended service in 2015.  The articles were obtained from this [aligned bitext] (http://nlp.ffzg.hr/resources/corpora/setimes/setimes.bg-en.tmx.gz) file in TMX format.

That corpus is published under the [CC-BY-SA] (https://creativecommons.org/licenses/by-sa/3.0/) license.

### [Voice of America] (https://www.voanews.com)
16 news stories from 2015/2016

## Russian
The data are from two sources, RadioLiberty (49k tokens) and Voice of America (6k tokens).

### [RadioLiberty (Russian)] (https://www.rferl.org/Russia)
26 news stories from 2019.

### [Voice of America (Russian)] (https://golos-ameriki.ru)
The same 16 news stories used in the English dataset.

## Contact
For questions about the dataset you can contact the first author on
the LREC paper.

