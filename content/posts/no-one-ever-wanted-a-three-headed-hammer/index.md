+++
title = "\"Back to base-ics\""
date = "2025-08-15"
updated = "2025-08-15"
+++

#### from the desk of [planetnineisaspaceship][planetnine]

# No one ever wanted a three-headed hammer

When I was a kid I got glasses, and since grown ups always like to try connecting to kids through cultural cliches, I heard the old saw more than once, "Do you know when glasses were invented?"
"When somebody needed them."
Necessity _is_ the mother of invention after all.

I like thinking about when things were invented though. 
Like glasses probably benefited a bit from Newton's work in Optics. 
There's the story of Benjamin Franklin inventing bifocals so he could watch French-speaking lips better.
Whether his need there was for diplomacy, or to settle bills with his companions accurately is lost to the, er, annals.

Way back in high school I got into set construction.
I've always loved building stuff, and it definitely scratched the itch. 
It culminated in this masterpiece:

![a twenty foot long skee ball machine built by me and some friends](./skeeball.png)
This bad boy was twenty feet long and twelve feet high, and only broke two light fixtures in the Student Union. 

Building stuff out of wood is somewhat more accessible than programming, though it is certainly nuanced and complex in its own right, so I'm going to use it as a metaphor here.
Specifically we're going to talk about tools. 
Tools have a mother to their invention, but more importantly they're named after what they do, and we forget how beautiful a thing that is.

## Typing class

In programming every thing is a construct.
It might be a construct at different layers in the programming stack, but it's all a construct nonetheless because you and I don't speak in voltages, and that's all the machine "understands."[^1]

One such construct is called a type.
You assign a type to a thing, and that tells all the software running to try and prevent you from making mistakes what that thing is and what you can do with it. 
For example, a DOG type might allow a BARK, but not a MEOW.

In general, the more restrictive the type is, the easier it is to work with, and the less useful it is for mapping things to the real world. 
A classic example of this is how to model names. 
You might be, "oh easy! FIRST NAME and LAST NAME."
Great. 

But what about junior, or the third?
What about multi-part names like Mary Jo or long last name?
What about Prince, Cher, Madonna, and Bono?

I don't want to bore you with why all of this matters, but I'll expand a bit in a footnote for anyone curious.[^2]

Pretty much all programmers like types because other programmers can write programs to check your types and spare you the embarassment of having a bug in your code when you submit it for review.
This is all well and good in the business world where the stuff you code is for specific use cases where the types you have more or less cover contrived business needs in the first place, but the benefit to programmers undermines the more interesting ontological question of what things are.
Or maybe more perniciously, it imbues to the type the notion that it _is_ what the thing _is_, and is not the facsimile of what the thing _is_ that it _is_.

What is a name after all? 
One could imagine an afternoon at the bar, debating the concept, and never reaching a satisfying conclusion.
If you want to make something, you have to define it somehow. 












[planetnine]: https://github.com/planet-nine-app/planet-nine

[^1]: Now that AI is around, I find it necessary to constantly and incessantly remind people that computers are not sentient. They may become so, and it might be the case that saying they are not now is bad, but they aren't sentient as of this writing. 
[^2]: Let's say you want to do something like give everyone with a last name starting with the letter B a dollar. That is pretty easy to do if you have a separate LAST NAME field. On the other hand, on the client side it's much easier to just have a single NAME field and let people enter what they want. If your system is going to be supporting many inputs of names from different places, flexibility reigns. 
