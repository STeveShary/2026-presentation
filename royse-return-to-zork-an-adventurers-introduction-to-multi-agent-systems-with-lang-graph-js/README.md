# Return to Zork - An Adventurer’s Introduction to Multi-Agent Systems with LangGraph.js

Guy Royse &mdash; *Developer Advocate at Redis*

- [LinkedIn](https://www.linkedin.com/in/groyse)
- [X (Twitter)](https://x.com/guyroyse)
- [Website](https://guy.dev/blog)

## Bio

Guy works for Redis as a Developer Advocate. Combining his decades of experience in writing software with a passion for learning—and for sharing what he has learned—Guy explores interesting topics and spreads the knowledge he has gained around developer communities worldwide.

Teaching and community have long been a focus for Guy. He ran a local JavaScript meetup in Ohio for more than a decade and has served on the selection committees of numerous conferences. He'll happily speak anywhere that will have him and has even has helped teach programming at a prison in Central Ohio.

In his personal life, Guy is a hard-boiled geek interested in role-playing games, science fiction, and technology. He also has a slightly less geeky interest in history and linguistics. He has an entire wall of role-playing games and science fiction books, speaks Spanish like a two-year old, and is a ham radio operator—callsign W8GUY.

Guy lives in Ohio with his wife. His three sons are adults now and are all moved out. He is immensely proud of the men they have become.

## Abstract

If you played Zork in the 80s like I did, you remember how compelling of an experience it was. It wasn’t like the other video games. It was just a prompt. You could type at the computer—in English—and it would respond back. And it all worked in *kilobytes* of memory. Amazing!

Of course I always wanted to build a Zork of my own. But building this sort of application the traditional way—with if statements and loops and polymorphism to anticipate every possible player action—is, well, really hard. And as an application like this grows, it gets worse; you end up lost in a maze of recursion and if-thickets. The more you add, the messier it gets until it feels like you’re about to be eaten by a grue—you know something’s wrong, there’s a feeling of dread, but you’re just fumbling around in the dark.

AI, of course, changes this. Flash forward a couple of decades, and I find myself typing at a computer once again—in English—and it’s responding back again. But this time, it’s much, much smarter. And this made me wonder: could I recreate Zork with AI? And I’m not talking about using AI to write Zork. I’m talking about writing a Zork that uses AI to replace all of those ifs and loops and polymorphism.

But maybe I could take it a step further. What if all the entities in the game—the brass lantern, the white house, even the mailbox—could individually contribute to the response? All of the entities could have their own perspectives and voices. They could be, well, agents.

So I built this. I used LangGraph.js to do it. I learned a lot. I’m going to share what I learned. We’ll get started with the LangChain.js essentials you need to understand to use LangGraph.js. Then we’ll focus on LangGraph.js itself, showing how to write agents, build a graph, and run it to play the game. I’ll show you all the code along the way. And, of course, we’ll play the game!

When the learning and playing are over, you’ll understand how to use LangGraph.js to coordinate agents to handle sophisticated interactions. And you’ll have a working example you can adapt for your own adventures—be they exploring the Great Underground Empire or some boring work thing!

- **Level**: Introductory and overview
- **Tags**: AI - Dev Tools, Languages & Frameworks
