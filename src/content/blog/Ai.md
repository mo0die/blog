---
title: "AI The Great Textbook"
description: "How I use AI to learn "
pubDate: "April 06 2025"
---

Currently, I'm building a CLI application for work using Go.

The packages I'm using are:

- Cobra
- Viper
- Bubbletea

I have never written a single line of code in Go before and to be honest I have no idea how Go works (for now).

But I managed to build a framework for myself using Cursor, though not in the way that most people would.

I am trying to become a better engineer, and vibe coding the CLI app for work doesn't achieve that.

I feel the need to know what all the files are doing within my code, so I can immediately identify where to go if I see an issue.

### HOW I USE AI TO LEARN

The best thing that has happened to me is being able to talk to an AI that
understands what an app does.

In this case, I'm using Cursor with Claude 3.5 and an open-source project:
[gh-dash](https://github.com/dlvhdr/gh-dash).

This project uses the same stack that I want to learn.

I wanted to understand how they built their framework for the app in a way
that is scalable and organized. The goal is that if a fellow coworker were
to work on this app, they could simply read the `README.md` and be ready to
add features or fix issues with the CLI app I want to build.

I add the prompt:

```bash
"DO NOT WRITE ANY CODE, USE THE CURRENT REPO AS REFRENCE
TO GUIDE ME TO BUILD MY OWN APP"
```

This probably needs a bit more work, but so far it has been good.

Current app

![CLI-MAIN](src/content/images/ai-textbook/photo-2.png)

![CLI-TEST](src/content/images/ai-textbook/photo-1.png)

While I am happy that I managed to build this in a short period and built it in such a way that I think I can build out the rest of the app by the end of the month and test it in production.

![KODAK](src/content/images/ai-textbook/i-hope-so-kodak-black.gif)

the issue I'm running into right now is that I am still limited by the AI's knowledge, which is not ideal.

I want to get into a position with Go where I do not need the AI anymore.

So, to help with that, I'm going to use "Learning Go" by Jon Bodner and go through the examples in BubbleTea, as this is the main package I want to get comfortable with when using go.

### FINAL THOUGHTS

Overall, I believe AI is a great way to deconstruct open-source projects and help synthesize information about the project, allowing someone (like me) to learn from and utilize those findings in their own project.

I don't like the idea of "vibe coding" or telling the AI to keep fixing issues. I think we have to fix the issues ourselves while still building the applications, but I think using AI in _this_ way might be more beneficial.

There was a quote in the Lex Fridman podcast featuring ThePrimeagen where Lex mentions that coding with AI feels less lonely because we can talk to someone, and I could not agree more. The ability to "talk" to a project is amazing, and I'm able to learn a lot better this way.

If you've read this far, I really recommend taking a look at any open-source project in the same framework you want to work with or currently work with, and see if you can learn something new.

I hope this was insightful or useful in some way.

Please feel free to message me on [X](https://x.com/Mo0diie). I would love to hear from you, and if you have different ways of using AI to learn, I would love to know about that as well.

Moodie
