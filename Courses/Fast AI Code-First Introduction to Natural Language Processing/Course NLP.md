# 1. What is NLP?

## What can you do with NLP?

NLP is a broad field, encompassing a variety of tasks, including:

- Part-of-speech tagging: identify if each word is a noun, verb, adjective, etc.)
- Named entity recognition NER): identify person names, organizations, locations, medical codes, time expressions, quantities, monetary values, etc)
- Question answering
- Speech recognition
- Text-to-speech and Speech-to-text
- Topic modeling
- Sentiment classification
- Language modeling
- Translation

Many techniques from NLP are useful in a variety of places, for instance, you may have text within your tabular data.

There are also interesting techniques that let you go between text and images:

![[Pasted image 20220606095342.png | 750]]

from [Lesson 9](http://course18.fast.ai/lessons/lesson11.html) of Practical Deep Learning for Coders 2018.

## This course

In this course, we will cover these applications:
- Topic modeling
- Sentiment classification
- Language modeling
- Translation

### Top-down teaching approach
I'll be using a _top-down_ teaching method, which is different from how most CS/math courses operate. Typically, in a _bottom-up_ approach, you first learn all the separate components you will be using, and then you gradually build them up into more complex structures. The problems with this are that students often lose motivation, don't have a sense of the "big picture", and don't know what they'll need.

If you took the fast.ai deep learning course, that is what we used. You can hear more about my teaching philosophy [in this blog post](http://www.fast.ai/2016/10/08/teaching-philosophy/) or [in this talk](https://vimeo.com/214233053).

Harvard Professor David Perkins has a book, [Making Learning Whole](https://www.amazon.com/Making-Learning-Whole-Principles-Transform/dp/0470633719) in which he uses baseball as an analogy. We don't require kids to memorize all the rules of baseball and understand all the technical details before we let them play the game. Rather, they start playing with a just general sense of it, and then gradually learn more rules/details as time goes on.

All that to say, don't worry if you don't understand everything at first! You're not supposed to. We will start using some "black boxes" that haven't yet been explained, and then we'll dig into the lower level details later. The goal is to get experience working with interesting applications, which will motivate you to learn more about the underlying structures as time goes on.

To start, focus on what things DO, not what they ARE.

## A changing field

### Case study: spell checkers

