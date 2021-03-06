# CluedoPredicates
## How to play
Just type this in your console. Make sure you have Python 3 installed!

```python3 init_game.py CLUEDO```

This game also requires you to install the NNF module it's all about, check out how to do that here: https://python-nnf.readthedocs.io/en/stable/.
## What it was all about
So... what was that all about? Well, you just worked with what we call the Negation Normal Form. The Negation Normal Form, 
abbreviated to NNF, is a form of a logic sentence in with predicate logic. You thought you just solved (or didn't solve)
a murder mistery, but what you actually did was set values to True and False. 
Did Miss Scarlet commit the murder? Did Reverend Green? The only thing you did was assigning True's and False's. The same we did at the start of this game, to generate your particular murderer, location and weapon. 
Your assignment of True's and False's was then compared with our predicate logic sentence, and the result was either True or False.
True and False sounds simple enough, but it is the basis for a whole field of Computer Science that covers much from satisfability of algorithms, automatas in discrete mathematics to even the very core of a computer: 1s and 0s.
- So how did we do this?
Well, we used a library that one Jan Verbeek created in his bachelor thesis, a Python libary made especially to easily handle
these kind of predicate sentences. Check it out on https://scripties.uba.uva.nl/search?id=691650.
And the result is your very own randomly generated murder mistery story. Did you get it right? 
