---
layout: post
title:  "Criticizing Computers"
date:   2022-11-05 12:00:00 -0600
author: "Anna-Sofia Lesiv"
header: "http://annasofia.xyz/assets/softcomp.jpg"
---
![comp](/assets/softcomp.jpg)

Do you ever get really mad at your computer? Are you frustrated by how everything works these days? Do you get angry not knowing who to complain to when programs or applications break down? Well, you're certainly not the only one.

Computers and applications are our gods now. They operate in an invisible ether and live *out there* on some distant, mysterious Mount Olympus — better known to us as a data center. Their mercurial whims dictate our moods and our fortunes. We plead with them, but have no idea if they are listening.

Of course, it wasn't always this way. Computers used to be small and straight forward. They used to be cute! Now they are big and scary and mind boggling. Now they are so complex that barely anyone alive understands how they work in their entirety. 

We were warned about this. We were warned about the dangers of too much complexity, but we didn't care. Now, rather than understanding how the thing works and what to do to fix it, we basically cross our fingers anytime we boot up our computer or open an app. These criticisms aren't original to me, I am just a messenger. 

The history of cursing modern computation is storied and exciting, and below is a summary of some of the most biting critiques issued by the most brilliant minds in the field.

**1. Good hardware is masking *really* bad software.**

The processors in our laptops are over 1,000 times faster than they were thirty years ago. So it's natural to ask, as [Joe Armstrong](https://youtu.be/lKXe3HUG2l4?t=410) does, why our programs don't run 1,000 times faster.

Jonathan Blow [answers](https://youtu.be/pW-SOdj4Kkk?t=1095) because software is in decline, even though it looks like it's flourishing. Software has been free-riding on hardware for decades and actually, software technology has not improved in years. 

He [says](https://youtu.be/pW-SOdj4Kkk) that "today, we simply don't expect software to work anymore. ... 'The Five 9s' used to be a very common phrase in the 90s when people wanted to sell you software or a hardware system. What it means is "this system is up and working and available 99.999% of the time." We don't use this anymore. In part because the number of 9s would be going down, and we can't make them go up again. We've even lost the rhetoric of quality that we used to have."

**2. All the bad code is piling up, and we don't know how to get rid of it.**

Joe Armstrong says that in the last 40 years, we have written billions of lines of code that will keep programmers employed for trillions of man hours in the next few thousand years to maintain and debug the code we've written. 

On the one hand, software engineers should be thanked for this incredible jobs program they've created. On the other hand, to the extent that implementing software was intended as a solution to reduce labor costs, it seems that implementing software may have inadvertently increased them?

If, as the brilliant mathematician Edsger Dijkstra [said](https://www.youtube.com/watch?v=lKXe3HUG2l4), "computing is about controlling complexity," then the body of work produced by the computer industry's programmers has entirely failed.

In the past, when computers only had so much memory, programmers had to be selective about which programs would live on in memory. These constraints imposed a strict discipline on programmers, and overtime, a process of natural selection retained the good programs while weeding out the bad. 

Today, memory is not an issue! We have more memory than we know what to do with. Rather than natural selection, we have a regime of hoarding. All the bad code can live on to torment and confuse the programmers of the future.

**3. Programs used to be pipeable. Now, GUIs are killing pipes.**

There already exists a programming philosophy with ideas on how to tame entropy and ensure that computers *actually* control complexity, instead of increase it. Those ideas are [summarized](http://www.catb.org/~esr/writings/taoup/html/ch01s06.html) in the Unix philosophy, which I've added below for convenience:

1. Write programs that do one thing and do it well.
2. Write programs to work together.
3. Write programs to handle text streams, because that is a universal interface.
<br>
<br>

If you think about programs as modular units of computation, then you can think about combining or *piping* these programs together to do all sorts of new things. That way, you never have to re-program anything when you’re just trying to create a new combination of functions, and if something goes wrong in your program — it’s easy to debug since every component of your program only ever does one thing. Furthermore, because the input and output of every program is just *text* we can even pipe together programs written in different languages!

Pipeable programs promised a golden world of future possibilities. Combine programs together in any way you like to have the computer do whatever you ask of it! You are the master of your destiny and the computer is the ship that takes you there!

The only problem is that most of the programs we use [aren't pipeable](https://youtu.be/rmueBVrLKcY?t=2026). Usually, when I'm using an app, I am interacting with it through a graphical user interface (GUI). I click on a button, and then the app does some function. Maybe I click on the weather app to ask what temperature it will be tomorrow. The weather app will not give me my answer in a convenient output format that I can pipe into another program. The weather app might just display a number on my screen that I then have to remember and re-type in elsewhere. 

**4. Computers are telling me what to do, but I can't tell them what to do.**

It's not an exaggeration to say that today, computers have more sway over human behavior than humans do over computer behavior. This, actually, was the whole idea behind the design of modern personal computers. The big idea was that users *shouldn't* have the ability to tinker with how their file system is organized or change the appearance or function of their operating systems. It's an idea that then spread to the entire world of computer application. Now it is entirely the norm to give users non-programmable interfaces where they cannot change *anything* about the programs that they interact with!

**5. Software is not technology. It is ideology.**

"With ideas come the politics of ideas. There are thousands of computer ideas and so there are thousands of computer religions. Every faction wants to pull you in. Every faction wants you to think that they are the wave of the future and because there are no objective criteria, as in religion, there are thousands of sects and splinter groups. Everyone has a favorite language and they're fanatical about it! C++, Perl, Python, Ruby, PCP, C#, Lisp — but which Lisp? — East Coast Unix versus West Coast Unix. But — who gets to decide what methods will be used? What ideas will be followed in creating software? Ah — that's the politics of the computer world."

"In Hollywood, they have it down to a system. They determine who directs. In the computer world, everyone wants to design software, but they don't call it creative control. In software, it's the same issue as in Hollywood, but nobody recognizes it. And that's partly because interactive software is really a kind of movie. What is a movie? A movie is events on a screen that affect the heart and mind of the viewer. What is interactive software? Events on a screen that affect the heart and mind of the user."

"As long as the industry thinks that software is technology, the process will not improve." — [Ted Nelson](https://youtu.be/hZ3gmh-d9oI?t=460)

**6. Computers are fast, but in the dumbest way possible.**

"The semiconductor guys don’t know much about computers so they’ve copied a bunch of ancient architectures. So what we have in the personal computers is creaky old architectures with this wonderful (semiconductor) technology. So the people driving the technology don’t know anything about systems and the people who have built traditional large computer systems haven’t participated in the (semiconductor) technology revolution. Supercomputers are an extremely inefficient use of power and space. They just brute-forced it. They said we’re not going to use any cleverness at all, we’re just going to pour the coal to it and see how fast we can make it run. So they just turn up the knob and go for it. And you end up with these giant steam engines that blow off all this heat. It doesn’t make any sense at all from any point of view. But, you see, the situation is actually much better than that. And that’s the part nobody counts. I mean if you take today’s technology and use it to do a really novel architecture you can get a factor of 10,000 right now. Today.” — [Carver Mead](http://worrydream.com/refs/Mead%20-%20Gene%20Youngblood%20Interview.pdf)

**7. No one knows what they're doing, and it's a civilizational problem.**

Jonathan Blow [says](https://youtu.be/pW-SOdj4Kkk?t=908) it takes a lot of energy to communicate information from generation to generation and that "without generational transfer of knowledge, civilizations can die because the technology that those civilizations depend on degrades and fails." 

Well, most people can't program without help from Google and Stack Overflow, and as mentioned, basically no one understands how the computer works in its entirety, so we've really screwed up our chances for educating the next generation in how computers really work. 

One of the greatest programmers in history, who did indeed understand every component of the computer from the software down to the chip, Niklaus Wirth, [wrote](https://cr.yp.to/bib/1995/wirth.pdf) "the belief that complex systems require armies of designers and programmers is wrong. A system that is not understood in its entirety, or at least to a significant degree of detail by a single individual, should probably not be built." Not only have we built such systems, all our collective livelihoods depend on them!

I guess the best we can do is pray to the computing gods that everything works out!