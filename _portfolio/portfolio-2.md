---
title: "Automated Puncutation Tagging for Medieval Hebrew Manuscripts"
excerpt: "LSTM based tool to automatically punctuate old Hebrew Manuscripts, developed for an education non-profit. [image source](https://beinecke.library.yale.edu/article/hebrew-manuscripts)<br/><img src='/images/manuscript.jpeg'>"


collection: portfolio
---
<img src='/images/manuscript.jpeg'>"
Old Hebrew manuscripts, for historical and cultural reasons, often lacked punctuation. In the modern era, many of thexe texts have been made available online via scanning and OCR, but when students want to study them, as evidenced by the popularity of sites like [Hebrewbooks.org](Hebrewbooks.org)  and [Sefaria.org](Sefaria.org) the lack of punctuation can serve as a barrier.

While working with [Dicta](https://dicta.org.il/), an educational non-profit dedicated to making old Hebrew manuscripts more accessible, I developed a novel tagging algothim to automate punctuation of these texts. The algorithm used LSTMs, and also incorprated severl clever tricks from the structure of Hidden Markov Models, ultimately allowing for the final taggin sequence to be decoded via the Viterbi Algorithm.

The project initially was a submission to a contest, and you can see my submission video below:

<iframe width="560" height="315" src="https://www.youtube.com/embed/BkCKrLf6pvk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

However, since then it has grown to be much more complex and, more importantly, accurate. I am still working with the people at Dicta and Sefaria, and hope it will be launching soon to the public.

For more details, checkout the [github](https://github.com/Jgoldfeder/Scribe).
