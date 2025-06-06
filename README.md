# Tibia-ME.net locales

* Use formal language only.


* No slang.


* Do not shorten where it's not necessary.


* %s, %d, %1$s, etc. are variables (that will be replaced with some number or word, e.g. "%s books" can be displayed as "5 books", "12 books", "white books", etc.), do not add or remove them.<br/>
%d are numbers, %s are any characters.<br/><br/>
Parsed with PHP sprintf() http://www.php.net/sprintf<br/><br/>

    * If there's only one variable in a string - you can move it anywhere along the text. (i.e. "books: %d" and "%d books" are both valid)
    * If there are more than one variable in a string - you can still move them BUT PLEASE KEEP THEIR ORDER (ex. if you replace "%d oranges, %s apples" with "%s apples, %d oranges" - it will not work as %s should stay after %d)
    * Generally you don't need to move any words so there shouldn't be any problem with this, unless some language construction requires it
    <br/><br/>
* Please don't forget CAPITAL LETTERS, dots, commas, etc. If original string ends with dot, translated string most likely (but not always) should end with dot as well.
  <br/><br/>

# Poedit
http://poedit.net/download.php
<br/><br/>
"Open" and "Save" buttons are all you need. If Poedit asks you to specify your name and email you may do so, but don't change any other settings please.