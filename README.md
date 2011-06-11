> "When the wine goes in, strange things come out."
> - Johann Christoph Friedrich von Schiller, The Piccolomini, 1799
>
> "Always do sober what you said you'd do drunk."
> - Ernest Hemingway

The purpose of this tool is to idenify idioms in blocks of text.
Acording to Wikipedia, an idiom "is an expression, word, or phrase
that has a figurative meaning that is comprehended in regard to a
common use of that expression that is separate from the literal
meaning or definition of the words of which it is made."

For the purposes of this program, we define idiom to be analogous to a
cliche. More specifically, it is an expression, word, or phrase that
evokes a sense of malaise in the more techincally inclined or
discerning reader.

Most of the code here is my own creation, but where appripriate, the
original authors have been credited.

To use the code files, you only need to clone the repository:

    $ git clone git@github.com:versionzero/idiom.git

To run the command, you'll need some text, and a terminal:

    $ ./idiom input.txt

Or, if you are using a LaTeX document, you can do the following:

    $ detex input.tex | idiom

If you are not familiar with detex, it is a tool that strips out all
TeX/LaTeX code.  In the future I will attempt to make this tool LaTeX
aware. For now, however, plain text will have to do.

If you have any comments or improvements, just push them my way.
