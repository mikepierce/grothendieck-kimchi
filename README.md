# Grothendieck's Kimchi

An English translation of Alexander Grothendieck's writing on kimchi.
I have little to do with its translation; 
I'm just organizing/crowdsourcing/open-sourcing the translation here on GitHub. 
A scan of the original French can be found 
[here on Thibault Damour's website](http://www.ihes.fr/~damour/IMAGE/kimchi_grothendieck.pdf). 
A live version of this translation can be found at 
[math.ucr.edu/~mpierce/kimchi](http://math.ucr.edu/~mpierce/kimchi/).


## TODO / Contributing

The files `six.html` and `seven.html` contain an imperfect OCR parsing 
of the original PDF in French, and still need to be translated. 
If you'd like to claim one of these to be translated, 
open up an Issue for it and let me assign you to that issue.
If you're unfamiliar with all the ins-and-outs of GitHub but want to help, 
feel free to email me a translations of those files 
and I'll deal with the technical stuff ;)


## Suggested Workflow

Each file `one.html` … `seven.html` contains a list of lines to be translated,
each followed by a blank line.

    Le Kimchi est une préparation de légumes fermentés,
    
    par une fermentation "lactique" genre choucroute,
    
    à la façon traditionelle coréenne.
    
These lines are the imperfect OCR parsing of the PDF linked to above. 
Translators should (1) fix any errors in the OCR-parsed French line,
(2) translate the line to English, and (3) comment out the line in French.

    <!-- Le Kimchi est une préparation de légumes fermentés, -->
    Kimchi is a preparation of fermented vegetables,
    <!-- par une fermentation "lactique" genre choucroute, -->
    by a "lactic" fermentation like sauerkraut,
    <!-- à la façon traditionelle coréenne. -->
    in the traditional Korean way.

The original French should be preserved here
to aid in future translations to other languages.


## A Similar Project

To anyone who really likes translating French → English, 
notice this crowdsourced project to [translate Grothendieck's SGA](https://github.com/jmoellermath/translate-SGAI).

