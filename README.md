Objective
---------

I finished the 2017 Advent of Code puzzles on December 28, as a tool to teach myself Python. I've been a coder for a long time, but an old crank Perl holdout who steadfastly refused to use Python, until an upcoming client project required it. When I was finished, I felt like I was approaching Python idiomatically, thinking in list comprehensions and generators. I decided to take some bench time to run through the puzzles again, this time as a tool to teach myself the Wolfram language.

Why on Earth?
-------------

I've used WolframAlpha for a while now, and grew to love it as a tool for playing with equations or real world data. I recently branched out to using [Wolfram Programming Lab](https://lab.wolframcloud.com/app/), learning the Woflram language (which seems to basically be Mathematica), and even watching Stephen Wolfram chew out his design team on his [Twitch channel](https://www.twitch.tv/stephen_wolfram/).

Takeaways
---------
- Wolfram has a function for everything, from creating an Ulam spiral, to finding a Postman Tour of a graph, to deblurring images, to fetching and parsing Wikipedia data. The standard library is like any other language with dozens of addons imported.
- Wolfram is black-box, and very pay-for-play. I could have sped up my solutions quite a bit by subscribing to use their offline tool. Neither of those things sit well with me for personal use, but if I were running a large enterprise of some sort, it would probably be well worth the money.
- Graph problems are the devil. Not really, but they're more low level comp-sci than my brain has to deal with in my day job of writing web apps. But they're fun, if frustrating.
- On many of the problems, the same input was close enough to the Wolfram language that I could get away with doing some regexing and converting the strings to expressions... basically an eval(), which I know is evil and will send me to programmer purgatory.
- Wolfram uses it's own brand of regex-like patterns everywhere, and studying up on them can make you very productive. I'll spare you any contrived examples, but patterns are littered throughout these notebook files.
- If you want to learn Wolfram, be prepared to spend a lot of time [here](http://reference.wolfram.com/language/).

Enjoy!
