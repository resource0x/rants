## Understanding is all you need

The other day, I had a funny dialog with chatGPT.

I asked chatGPT whether it can compute the Galois group of a polynomial. The answer was yes.

I asked about the Galois group of polynomial x^5-1. The response contained some reasonable fragments but ended with a totally unreasonable conclusion. 

I tested the bot on some other polynomials, and each time getting a different non-sequitur.

At that point, it dawned on me that, left to its own devices, the bot is incapable of saying "I don't know". It "thinks" it knows how to compute Galois groups
because there are tons of examples on the internet where people are computing Galois groups. 
By stringing words and phrases taken from different examples, it produces logical gibberish. 
There's no technical reason for it for saying "I don't know".

Now - an interesting part. 

Suppose some next version of chatGPT gets "special-cased" for this sort of question: when asked about Galois groups, 
it will invoke a specialized python program. Let's suppose it's doable. 
But there will always remain another class of questions where the bot, having no understanding of the subject, 
still *doesn't know it doesn't know* the answer, and will remain in a state of delusion until the programmers add a special case for this class of questions. 
However, this doesn't scale: the number of such special cases is potentially infinite. 
Since the phenomenon of "understanding" is not captured by the language model, we reach a dead end here. 

WDYT? 
