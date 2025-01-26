# Dictionanki

Create your English Anki flashcards from macOS system Oxford Dictionary

## Features

- Does not require internet connection.
- Can hide words from example sentences. Useful when you want to guess words from their definitions.
- Can italicize and dim example sentences and labels (e.g. *[with object], archaic, mainly British, North American, Biology*, ...).
- Can prune extra information like comparative and superlative form information, plural form information, regular verb conjugation forms information, *ORIGIN* part, and more specific definitions that are starting with "•".
- Can be configured as you'd like to. Check out the options in the first few lines of [dictionanki.js](https://github.com/seungwoochoe/dictionanki/blob/main/dictionanki.js).

## How to use

<img src="https://github.com/seungwoochoe/dictionanki/blob/main/images/1.jpg" width="350">  

After the [setup](https://github.com/seungwoochoe/dictionanki?tab=readme-ov-file#setup), right click on a word that you want to put into Anki and then click Dictionanki.
(You can also assign a shortcut for Dictionanki in macOS System Settings.)

<img src="https://github.com/seungwoochoe/dictionanki/blob/main/images/2.png" width="550">  

Then a processed text will be written on an opened (or new) text file. You can add more of them and put them into Anki at once. To prevent TextEdit popping up every time, minimize (⌘M) the TextEdit window.

<img src="https://github.com/seungwoochoe/dictionanki/blob/main/images/3-1.png" width="600">  

Save the text file and import it into Anki. This is what cards will look like after being imported.

## Setup

Download *Dictionanki.workflow.zip* from [Releases](https://github.com/seungwoochoe/dictionanki/releases) and install the workflow by double clicking it.

And voilà, you're done!

Optionally, you can set some options by opening the workflow located in "~/Library (hidden folder, press `⌘⇧.`to reveal)/Services" and modifying the JavaScript inside. Available options are listed at the beginning of [dictionanki.js](https://github.com/seungwoochoe/dictionanki/blob/main/dictionanki.js).

If you'd like to create a Quick Action by yourself, you can reference the [Quick Action example](https://github.com/seungwoochoe/dictionanki#quick-action-example) below.

## Limitations

- Cannot hide most of past and past participle forms of irregular verbs.
- Cannot get second+ definitions of homonym words like *bat2*.
- Doesn't work with open compound words like *ice cream*.
- Doesn't work with phrases and phrasal verbs.
- Formatting is not perfect in a few cases.

## Quick Action example

Automator - new Quick Action  

<img src="https://github.com/seungwoochoe/dictionanki/blob/main/images/4.png" width="800">  
  
Save
  
Then assign a shortcut to this Quick Action (.workflow).
