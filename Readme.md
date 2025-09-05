This repo contains contains a flashcard deck for the app [AnkiDroid](https://f-droid.org/en/packages/com.ichi2.anki/), whose goal is to learn the 5000 most used english words.

The deck is stored as a CSV format with 5000 lines (1line = 1 flash card).

Each flash card contains the french translation ov a given word, the english word itself, and an example of english sentence. 

**NB : The translation has been made by an IA LLM model (Ollama) that ran locally, so the performance of the model is not 100% accurate. Some translations are wrong, or not optimal**

To suggest a correction, feel free to make a pull request : go to the CSV file you want to modify, for ex [https://github.com/rangeonnicolas/ankidroid-flash-cards/blob/main/deck.csv](https://github.com/rangeonnicolas/ankidroid-flash-cards/blob/main/deck.csv) and click on the pen "edit this file" on the right side.

**The python code can be adapted to generate flashacrd for an other language than french (just modify the variable 'lang' in the .ipynb python notebook : the language name can be spelled as you wish as it will be included to a propt given to the LLM)**

I got the 5000 most frequent english words from [frequencylist.com](https://frequencylist.com/).
