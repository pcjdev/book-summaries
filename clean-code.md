# Clean Code: A Handbook of Agile Software Craftsmanship

by Robert C. Martin

* Publisher: Prentice Hall; 1 edition (August 11, 2008)
* ISBN-10: 0132350882
* ISBN-13: 978-0132350884

> Honesty in small things is not a small thing.

This is a book about humble concerns whose value is nonetheless far from small.

> Learning to write clean code is hard work. It requires more than just the knowledge of principles and patterns. You must sweat over it. You must practice it yourself, and watch yourself fail. You must watch others practice it and fail.

## Chapter 1: Clean Code

> *The Grand Redesign in the Sky*
>
> Eventually the team rebels. They inform management that they cannot continue to develop in this odious code base. They demand a redesign. Management does not want to expend the resources on a whole new redesign of the project, but they cannot deny that productivity is terrible. Eventually they bend to the demands of the developers and authorize the grand redesign in the sky.
>
> A new tiger team is selected. Everyone wants to be on this team because it’s a greenfield project. They get to start over and create something truly beautiful. But only the best and brightest are chosen for the tiger team. Everyone else must continue to maintain the current system.
>
> Now the two teams are in a race. The tiger team must build a new system that does everything that the old system does. Not only that, they have to keep up with the changes that are continuously being made to the old system. Management will not replace the old system until the new system can do everything that the old system does.
>
> This race can go on for a very long time. I’ve seen it take 10 years. And by the time it’s done, the original members of the tiger team are long gone, and the current members are demanding that the new system be redesigned because it’s such a mess.
>
> If you have experienced even one small part of the story I just told, then you already know that spending time keeping your code clean is not just cost effective; it’s a matter of professional survival.

Some definitions of *clean code*:

* Grady Booch, author of Object Oriented Analysis and Design with Applications:

> Clean code is simple and direct. Clean code reads like well-written prose. Clean code never obscures the designer’s intent but rather is full of crisp abstractions and straightforward lines of control.

* Dave Thomas, the founder of OTI, godfather of the Eclipse strategy:

> Clean code can be read, and enhanced by a developer other than its original author. It has unit and acceptance tests. It has meaningful names. It provides one way rather than many ways for doing one thing. It has minimal dependencies, which are explicitly defined, and provides a clear and minimal API. Code should be literate since depending on the language, not all necessary information can be expressed clearly in code alone.

* Michael Feathers, author of Working Effectively with Legacy Code:

> I could list all of the qualities that I notice in clean code, but there is one overarching quality that leads to all of them. Clean code always looks like it was written by someone who cares.
> There is nothing obvious that you can do to make it better. All of those things were thought about by the code’s author, and if you try to imagine improvements, you’re led back to where you are, sitting in appreciation of the code someone left for you—code left by someone who cares deeply about the craft.

The Boy Scout Rule:

> Leave the campground cleaner than you found it.

It’s not enough to write the code well. The code has to be kept clean over time.

Remember the old joke about the concert violinist who got lost on his way to a performance:

> He stopped an old man on the corner and asked him how to get to Carnegie Hall.
> The old man looked at the violinist and the violin tucked under his arm, and said: “Practice, son. Practice!”

## Chapter 2: Meaningful Names
