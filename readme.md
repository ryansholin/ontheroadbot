# On The Road Bot
A Twitter bot, tweeting Jack Kerouac's _On The Road_ one line at a time.

## Colophon, Resources, Inspiration
#### [Everywordbot](https://github.com/aparrish/everywordbot)
This is where you go to find out how to tweet a file, line-by-line, in order. I'm doing it on Webfaction, with a bash script and a cron job as described in the above link. I couldn't figure out how to tweet each line in order on Heroku, because ephemeral file systems are ephemeral and so it's challenging to increment the index. (Host a text file with literally one number in it on S3 if that's easy or pleasant for you to do.)
#### [Textblob](https://textblob.readthedocs.io/en/dev/)
So you have a giant text file of a book and you'd like to break it into 140-character chunks, and maybe, say, spellcheck to find the repeated errors caused by terrible OCR? Textblob is for you, and it also does a bunch of cool tricks that I'd like to use soon to analyze the text a bit more and build some cutesy graphics to get across how many times Paradise/Kerouac describes Moriarty/Cassady as doing something "manically" ugh so many adverbs.
#### [This blog post about using Textblob on War and Peace](http://adamdynamic.com/war-and-peace/)
_War in Pieces_ is where you'll find useful code to implement Textblob as described above.
#### [@HowlTweeter](https://twitter.com/howltweeter)
An account that tweets Allen Ginsberg's _Howl_ one line at a time, on a loop. I'd love to see their stats on most favorited and retweeted lines.
