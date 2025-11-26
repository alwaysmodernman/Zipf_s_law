An example to verify zipf's law, inspired from an YouTube video 'The Zifp Mystery', by 'Vsauce' channel.

So what's zifp's law?

Zipf's law is an empirical law that states that the frequency of a particular observation is inversely proportional to its rank in a frequency-ordered set. For example, the most common word in a language is roughly twice as frequent as the second most common word, three times as frequent as the third, and so on. It is frequently observed in the distributions of word frequencies in text, city sizes, and other phenomena. 

Key principles

Inverse proportionality: The core of the law is the relationship between an item's rank and its frequency. As the rank increases, the frequency decreases at a constant rate.

Mathematical representation: It can be expressed as: \(Frequency\propto \frac{1}{Rank}\). In a more general form, this becomes \(p_{r}=\frac{A}{r^{a}}\), where \(p_{r}\) is the probability of an item with rank \(r\), and \(A\) and \(a\) are constants.

Examples in practice

Language: In a corpus of text, the most frequent word (e.g., "the") is used approximately twice as often as the second most frequent word (e.g., "a") and three times as often as the third (e.g., "and").

City size: The population of cities often follows this law, where the largest city is approximately twice the size of the second largest, three times larger than the third largest, and so forth. 

Origins

While the law is named after the American linguist George Zipf, who popularized it, it was first observed by others, including the French stenographer Jean-Baptiste Estoup, physicist Felix Auerbach, and statistician G. Dewey. 

Explanations

Principle of least effort: One proposed explanation is that the distribution results from a compromise between the tendency for speakers to economize their effort (favoring short, simple words) and the need for listeners to receive clear and unambiguous information. 

So how to run it?

Step 1: Download the .zip file and then extract the downloaded .zip file (.zip is a file extension, which is different from zifp :) ).
Step 2: Open the .ipynb file either in google colab or jyputer notebook.
Step 3: Upload the pdf or the text file(.txt extension) into google drive for colab; or upload in the same folder as .ipynb file, if in jupyter notebook.
Step 4: Open the .ipynb file, and run it by following the instructions (comments) given.

Tools needed:

Jupyter notebook or
Gooogle Colab and Drive
