# Contributing

The overarching goals of this project are to 
(1) translate Grothendieck's essay from French to various other languages,
and (2) typeset those translations nicely online.
Regarding contributing to the second goal, it's the wild west:
Feel free to open an [issue](https://github.com/mikepierce/grothendieck-kimchi/issues) 
or start a [discussion](https://github.com/mikepierce/grothendieck-kimchi/discussions),
or just fork then edit then make a merge request and hope I like it 😉
Regarding the first goal though, 
there are some guidelines we should adhere to to keep organized.


## Guidelines on Translating

To keep an organized translation workflow,
here are a few things I'd prefer contributors keep in mind:

  - **When translating, respect the linesbreaks.** 
    This way, between the files containing the French and English 
    and any future translations, we can compare the text line-by-line.

  - If there is a word or phrase that you're unsure 
    of the translation for, feel free to leave it untranslated 
    and mark it with a sidenote using this syntax from Tufte CSS:
    
        <label for="sn-TAG" class="margin-toggle sidenote-number"></label>
        <input type="checkbox" id="sn-TAG" class="margin-toggle"/>
        <span class="sidenote">SIDENOTE TEXT HERE</span>

    But, respecting line-breaks, that entire block should be kept inline.
    Also consider creating an [issues](https://github.com/mikepierce/grothendieck-kimchi/issues)
    for it.

  - If you'd like to start/create a new translation,
    please translate from the original French.
    This is so that we don't indavertantly accumulate 
    drastic changes in the meaning of the writing.
    ([à la the telephone game](https://en.wikipedia.org/wiki/Telephone_(game))).
    The French version can be found [scanned here](http://www.ihes.fr/~damour/IMAGE/kimchi_grothendieck.pdf) 
    or [dubiously transcribed here](https://mikepierce.github.io/grothendieck-kimchi/translations/french/).
    If you translate from the English, that's okay
    but we should start an issue requesting that someone who also knows French
    can proofread it.

  - If you'd like to talk about the accuracy of an existing translation,
    bring it up on the [discussions page](https://github.com/mikepierce/grothendieck-kimchi/discussions).
