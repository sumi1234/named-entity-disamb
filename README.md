named-entity-disamb
===================
This piece of code seeks to find the context for a named entity in a stream of news articles. e.g. find out if 'apple' means apple the company or the fruit.

We use the raw wiki markup and the mediawiki api for wikipedia to determine the possible contexts of a particular entity.
After that using an article similarity measure, we determine the most closely matching disambiguation of the entity.

The code was initially prototyped in python and then made in Java using the stanford CoreNLP library.
