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

Now there is a pretty significant cost to this seemingly simple piece of information, which is that users hate having to fill out forms, and having to figure out how to fill them out is even worse. 
If you, like me, have ever wondered why you have to fill out these stupid forms all the time, it's because people, like me, can't agree on what things are.
Like a lot of things, you can trace this argument back to ancient philosophers, and at least a few of them were as good as modern day data "architects." 

![a ridiculous onboarding form from Yahoo](./yahoo.jpg)

This whole user experience, called onboarding in the biz, is one of the largest, and arguably most important part of the customer acquisition funnel. 
Make it _too_ annoying, and people bounce off and leave, make it too easy and you don't gather enough information from them to incessently spam them with advertising. 

This has an interesting side effect on software products over time. 
The product is built out behind the onboarding, adding feature upon feature without that necessarily being the best thing. 
Ostensibly this makes you "competitive," but at what cost?

## Drills and sewing kits

Super gigachad programmers like me use a little program called vi to write code. 
It came out in 1976, and hasn't changed much from that year. 
It is, for me, the most useful tool that I "own," and it asks nothing of me. 
It doesn't know my name, it doesn't know my email, it just sits there waiting to help me achieve my dreams. 

This is how machines should work.

Back a decade and a half ago or so, I got rid of most everything I owned, and moved across the country. 
Three platic bins were all I took with me.
Most of that was clothes, and electronics, but I brought two tools with me: a drill, and a sewing kit.

I've gotten more utility out of those two items than most anything else I've owned. 
To be fair, I use the drill more than the sewing kit now that I can afford furniture and clothes, but for my twenties I could not so the drill put together cheapo tables and shelving, and the sewing kit kept my two pairs of trousers going. 

Here's the thing.
I don't really know how to "use" the drill, and I don't really know how to "sew."
For that matter, I'm sure there are people who would say I don't know how to "program" either.

But I am not in the business of impressing people with my sewing, programming, and, in most contexts, drilling ability.
I'm in the business of getting things done, and for that I use the tools as I can, not necessarily as they were meant to be used.

![A picture of a flattened stone resting atop a small pile of dirt](./hammerstone.jpg)
This bad boy is a 3.3 million year old hammerstone. [Carrier bags may have come first,][carrier-bag] but not by much I'd imagine. 

3.3 million years ago, long before humans arrived on the scene, some hominins got the bright idea to start hitting things with flat rocks. 
Somewhere between then and 600 years ago or so, someone tied the rocks to a stick, and the hammering really started. 
Then 600 years ago, someone added the claw, and the modern hammer was born.

Three "product innovations" in 3.3 million years.
Do you have a hammer in your home?
I'll bet you dollars to donuts it has a hammerin' side and a pryin' side, and that's it.

Because no one, in 3.3 million years, has ever wanted a three-headed hammer.

## The legislature problem

If you put a bunch of people in a room and tell them their job is to make laws, they will, despite their best efforts not to, make laws.
Whether the laws are necessary or not is immaterial because the job is to make laws, not decide on whether or not laws get made. 
If there's no way to give this group of people something else to do, they'll just keep making laws. 

I call this the legislature problem. 

In software, it's not uncommon to have a product team, or a feature development team, and that team's job is to work on the product. 
Most of the time this means churning out features regardless of whether or not the features are needed. 

There are many problems with this approach, and the ones I have to deal with at work aren't worth talking about.
What is worth talking about is how, over time, pretty much all software becomes unusable garbage. 
And when I say unusable, I don't mean people can't use what they already know how to use, I mean people just give up on trying all the new "features" that companies are adding. 

The last twenty years or so have given us a very skewed idea of what success for a product looks like. 
There's never before been a globally available distribution system for that's consistent for the number of users who now have smartphones that can access the internet. 
Facebook claims two billion monthly active users.

How many do you think hammers have?

Meta has tens of thousands of employees. 
Their product is selling your eyeballs to advertisers. 
So the "features" they're working on are ones that get you to spend _more_ time in Facebook. 

Nothing to really do about that, Meta can do what they want even if it's horrible so long as it doesn't break too many of the laws that actual legislatures churn out at around the pace of Facebook releases.
The problem is that they've convinced a bunch of visionary CEOs that this is how software is to be made.
So now when you go to write a grocery list you have to wait for your phone to sync, and have different header font weights, and three dots, and hamburger buttons, and fabs, and uuuugggghhhh.

I've deployed a fair number of apps, and every single one of them was meant to help humans complete a task that was necessary for what they needed or wanted to do--that is, they were tools and not media.
Every single one had people who wanted us to find ways to keep people in the app.

You know what you call a hammer that makes you hammer longer than you need to be hammering?

A bad hammer.

But if your hammer development team is just employed forever to add things to your hammer, they're gonna add that third head even if no one wants or needs it.
The thing that keeps that from happening is that other people make hammers, and it's real easy to make a hammer that's better than a three-headed hammer.

So what's the two-headed hammer for Facebook?

## Content is king

A hammer is a tool, tools want to get the job done as quickly as possible. 
Social media (heretofor referred to as SoMa) isn't a tool to do tasks. 
It is a way to fill idle time, so figuring out how to compete with it isn't as straight forward as just doing it "better."

But if we consider use cases where time is limited, we can think of some metric.
More or less all SoMa platforms are divided into three types of posts: posts you've elected to seei (P), posts the platform presents to you to try and keep you engaged (E), and advertising (🤮). 
The goal being to have P provide enough dopamine hits that you suffer through E and 🤮. 

 









[planetnine]: https://github.com/planet-nine-app/planet-nine

[^1]: Now that AI is around, I find it necessary to constantly and incessantly remind people that computers are not sentient. They may become so, and it might be the case that saying they are not now is bad, but they aren't sentient as of this writing. 
[^2]: Let's say you want to do something like give everyone with a last name starting with the letter B a dollar. That is pretty easy to do if you have a separate LAST NAME field. On the other hand, on the client side it's much easier to just have a single NAME field and let people enter what they want. If your system is going to be supporting many inputs of names from different places, flexibility reigns. 
