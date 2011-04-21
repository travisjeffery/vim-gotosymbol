# Go to Symbol for Vim

## Sell

Hey, ever used TextMate and discovered the great *Go to Symbol* feature, but
was disheartened that it was one of the last features that hadn't been
duplicated for Vim?

Well now it's here.

## What

For those that don't know what I'm talking about, the feature lists all
symbols, functions, or variables, in the file, and pressing return will go to
the position of the file of the symbol.

## Install

Install it like any other Vim plugin. Either drag the files to their respective
directories in your Vim directory, or something like pathogen.

## Using

Then to use just use your mapping or call the function and type in the
beginning of your symbol and press Tab to complete the symbol if there is only
one that matches, or all matches if are more than one. For example let's say
I'm editing a Ruby file and I have an initialize method, then I would just do
`:GotoSymbol ini<Tab>` or `,T ini<Tab>` if I have the function mapped, see
below, and it will complete to initialize and press enter to be taken to the
symbol in your file.

Also recommended is to add a mapping to call the function quickly, e.g. 
this is in my .vimrc: `nmap <leader>T :GotoSymbol `.

## Author

Original author of Taglist by Yegappan Lakshmanan, and Go to Symbol feature
added by Travis Jeffery.
