# Building a GPT from scratch


## What this is ##

It's a GPT built from scratch following Karparhy's lecture on youtube. It reads Shakespeare, trains
on it and outputs something resembling Shakespeare. It cannot actually write story.

Why I built it --- Since learning how to properly use Claude code and skills I created my own app, a life dashboard 
called the Sanctum. My continued interest in AI got me very curious about how models actually work. I had a general 
idea before starting this project but I wanted to deepen my understanding. Having prior coding experience in C++ 
logic I thought it would not be that hard to comprehend Karpathy's lecture.

## Running --- October 27th 2026 ##

I imprisonable.

KING EDWARD IV:
Woe, but to the day in the earth,
Who trebt to each an hot; never nor
That herein eyes nor the tongue of the reapiness
In the no, Considelen was for the
This ready: the day may she had.

LADY CAPULET:
Good my lord, for your goods, 'tis heart.

HENRY BOLINGBROKE:
Marry, and pardon'd in this wife were that your father's
for Richmond.

KING RICHARD II:
We are more, sir, if your liberty, here artter;
And brother, when to sit the found that's new very friaends?

QUEEN

## What I learned ##
I learned how to tokenize. Frontier models obviously tokenize differently than my nanoGPT does,
but building an understanding of how you actually encode and decode tokens really helped me wrap my head around how
AI models work in the backend. I also learned what self-attention is and how ABSOLUTELY crucial it is. Weighing how 
important elements of input are by using vectors query, key and value. This was really hard to understand at first, 
and to be honest, it still is. My current understanding of linear algebra guided me along but I understand why 
it took so much time to figure out AI. Speaking of, watching Karpathy sift through numerous papers during his 
lecture also taught me to appreciate how much time it took for us to get here. Just my small model required so many
years, people working diligently and with so much passion. Karpathy's way of teaching made it clear how many 
roadblocks it takes before getting somewhere sensible. It was also wild to realize that what I am doing is 
actually building GPT, just smaller, very surreal.

## What confused me ##
When I mentioned I came in thinking I would be fine piggybacking off of C++, I was partially 
correct. The abundance of new functions springing up out of PyTorch felt like being blindfolded in a corn maze and
spun 30 times. The underlying python logic was very easy to comprehend but the bottleneck was definitely learning 
what all the functions do, being familiar with these would have certainly been a plus. A lot of the optimizations
Karpathy's would make to lower Loss also confused me. Of course I'm nowhere near the level of a succcessful
software engineer but that was part of the fun. :)

## What I'd do next ## 
I want to keep playing around in Karpathy's code to better understand it. I'm also really
looking forward to training nanoGPT on a dataset of my choosing, I haven't picked anything yet but I'm thinking
of using something with a wider variety of characters. I would also like to keep playing around with python, I had
a lot of fun trying to learn the logic behind Karpathy's code, trying being the key word. Being more familiar with
C++, the basics were easy to understand. With that being said, I'd like to find the grey area where I can learn
complex python and work my way up to fully grasping Karpathy's lecture.
