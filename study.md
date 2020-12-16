# Self Learning Study

Read this document and the required readings. Then, respond to all questions
within the code blocks.

In your responses, be sure to cite any relevant sources you consulted in your
search. We ask you to write responses in your own words in order to see how you
process what you've read. Please do not respond with direct quotes from source
material. Instead, digest what you've read and repeat it in your own voice.

## Why Self Learning

![Remember, a few hours of trial and error will save you several minutes of looking at the README](https://media.git.generalassemb.ly/user/16103/files/8ca9fa80-e41b-11e8-96c2-f0f3ae3ad6db)

A developer's learning journey is never finished. No matter what tools you may
know, there are always more to come and more to learn. Being able to effectively
teach yourself new skills and solve problems that arise as you do so will be
invaluable not only to you, but to any employer or client with whom you work.

It is *highly unlikely* that you will arrive at your first job with 100% of the
experience and knowledge required to complete the job. It's *highly likely* that
even the lead developer will spend much of their time researching questions and
documentation in order to solve problems. This is not uncommon, and comes with
the job.

## Required Readings

- [Importance of Learning to Google Efficiently for a Programmer](https://softwareengineering.stackexchange.com/questions/65918/importance-of-learning-to-google-efficiently-for-a-programmer)
  - *Look for the _checked_ answer*
- [Hasty Treat: Reading Documentation](https://syntax.fm/show/073/hasty-treat-reading-documentation)
- [20 Tips for More Efficient Google Searches](https://www.dumblittleman.com/20-tips-for-more-efficient-google/)
- [Google-Fu](https://blog.codinghorror.com/google-fu/)

## Research Formula

Consider the following research formula: _Subject + Verb + Programming Language_

This could be used to write a search like "Add an item to an Array in Javascript",
that has a Subject (Arrays), a Verb to describe what we want to do with them,
and the programming language with which we are working.

Re-write this HTML/jQuery search using that formula:
`"I need to show something on my webpage"`

```md
display element on webpage HTML jQuery
```

## Slimming Down Search Results

Let's say you're trying to search for "insert into ruby array" online. How could
you write your search so that you only are shown results from
[the ruby docs](https://ruby-doc.org)?

```md
ruby-doc.org insert into array
```

## Diving into Docs

Let's say you had to start learning [Meteor](https://docs.meteor.com/) today for
a new job tomorrow. Where would you start? Where would you head next?

```md
The first thing I would do is watch some examples online. This would get me some familiarity with the code.

Next I would look at the documentation. I wouldn't just look at the homepage, I would comb through all the docs to see the breadth of what Meteor had to offer.

If I still didn't feel comfortable with using the app, I would hop into a chat or ask other developer friends how to use it. Additionally, I would watch more examples online.
```

## Params syntax

No two docs are the same, but often they use similar syntax for declaring
required and optional params for API methods so that developers aren't left
guessing.

Based on the following declaration of the jQuery `.on` method, categorize the
parameters here as either required or optional:

```js
.on( events [, selector ] [, data ], handler )
```

```md
Accrording to the following declaration, when you call the '.on' method, you MUST add an events paramater (this is required). You can optionally add a selector or data parameter. You MUST ALSO add a handler paramater.

Required = events & handler
Optional = selector & data

According to this declaration, you would want to put them in that order. I would need to see further documentation to know if there needed to be a specific order.
```

## These Docs SUCK!

Sometimes documentation isn't super helpful. Describe what you might do if you're
trying to learn something, but the documentation is getting you nowhere fast.

```md
The first thing I would do is see if other people have run into issues with the same bit of code I'm trying to learn from the docs - maybe someone else has a great description on how to use this particular part of the code that I'm reading about in the documentation.

If that doesn't prove to shed light on the issue, I would turn to chat rooms or other developers who might know the documentation better or understand how to use this part of the code better.

Lastly, if I do end up finding a solution or know a better way to write about that particular part of the code, I would write into the creators and offer my suggestion to change the documentation.
```

## StackOverflow

StackOverflow is one of the largest sources of community-compiled development
questions-and-answers. What are some ways you can utilize StackOverflow to find
*the best* answers to your questions?

```md
Using Google to narrow your search on stack overflow is something I often do.

Additionally, since there are so many answers given on a certain topic, I make sure to read multiple comments to ensure I'm getting the most useful information to my specific use case.
```

## The Point of All This

What is the point of researching a problem, method, language, or technology?
What should we achieve by the end of our research?

*Hint: It's not "to find the solution"*

```md
For me, it's to better understand how to use the code and learn how to research problems within a particular language. The point ins't to know everything, it's to be able to know where to find it. By researching something, you have a general knowledge of how things work which will allow you to pinpoint certain issues in the future much easier. 
```

## Additional Resources

- [Is It a Good Idea to Always Use Google as the First Step to Solving a Problem](https://softwareengineering.stackexchange.com/questions/114002/is-it-a-good-idea-to-always-use-google-as-the-first-step-to-solving-a-problem)
- [How Do You Learn a New Programming Language](https://softwareengineering.stackexchange.com/questions/3519/how-do-you-learn-a-new-programming-language)
- [How Do I Pick Up a New Language Quickly Given I Know Several Others](https://softwareengineering.stackexchange.com/questions/78175/how-do-i-pick-up-a-new-language-quickly-given-i-know-several-others)
- [What Is the Single Most Effective Thing You Did to Improve Your Programming Skill](https://softwareengineering.stackexchange.com/questions/44177/what-is-the-single-most-effective-thing-you-did-to-improve-your-programming-skil)
- [Best Advice For Junior Developer](https://news.ycombinator.com/item?id=18128477)
