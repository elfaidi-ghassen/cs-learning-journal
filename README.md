# A Student's Journey Into CS and Life

work in progress...

# Reviews

## Table of Contents

1. [Computer Networking: A Top Down Approach](#computer-networking-a-top-down-approach)
2. [Uncommon Sense Teaching](#uncommon-sense-teaching)
3. [UML Distilled](#uml-distilled)

## Computer Networking: A Top Down Approach

Computer networking is one of the most rewarding subjects in computer science, you suddenly start to understand those terms you hear everywhere.
Suddenly it's almost hard to remember life where you didn't know those terms and concepts!
I wasn't very satisfied with my university's approach to computer networks, it was a buttom-approach and kind of boring.
So I picked up Computer Networking: A Top Down Approach, and boy I'm glad I did, it's one of the most rich learning experiences I've had in computer science, in fact it's when I suddenly thought, "I love computer science".

The book is accompnied by A LOT of extra content, the Wireshark labs in particular were amazing, I highly recommend that you print the labs and annotate them, it's much more fun.

I highly recommend the book, the first two chapters alone are enough for most programmers, in fact by chapter 2, if you do the projects, you'd have built a HTTP server, SMTP server, UDP ping, and a proxy server from scratch using socket programming.

I still remember the thrill I had, disabling the firewall (in the settings) on my laptop (later I realized the client doesn't need to disable the firewall :D)
, creating a python script that sends "hello" via TCP, and running the "server" (which is just a python program) on my friend's laptop, the server makes turns it into "HELLO" and sends it back.
a week later I've finished building my multithreaded http server.
I configured my router (which is... just changing its setting) to do port forwrding to my laptop, so that I can use anyone can use my (insecure) HTTP server anywhere, succesfully putting all the files on my laptop in risk :D, Apache HTTP server is a couple million lines of code for a reason!

At that moment everything started to click, everything is bunch of files and programs, and I thought, "I love computer science".

In highschool, in Tunisia can study some computer science classes, in of them we were taught some very basic PHP and MySQL, we installed MySQL just by pressing "next" in the setup, and suddenly, our PHP code is storing data in the "database". I was puzzeled... like "sir, where is the database", "I mean where is this stuff stored?"
It was a tough question, but he answer me "it's just some files".
I didn't buy it, but it set my heart at ease at least, it least it's on the hard disk and not in some other dimension!

After study operating systems, databases and computer networing, I finally understood where is the database. it's just bunch of files and some TCP socket on the top. he was correct.

Some advice:

- when you read the DNS section in chapter 2, buy a domain name
  - it's around $10 per year, but what you learn with stick with you forever.
  - if you're a student try getting a domain in Githuab Education Pack for free.
  - you can for instance host a static website on github pages, and create a CNAME record to point your domain to it.
  - remember, if you buy a domain like yourname.com, you can add as many prefixes as you want, you can create sub domains like blog.yourname.com or ANYTHING.yourname.com, and even an email address like pm@yourname.com
  - Also, at some point later it might be also worth getting a VPS for a month where you can practice even more.

## Uncommon Sense Teaching

> "Learning isn't always fun"

When I was in high school, for some reason I wanted to become a history teacher, I hated my history class so much that I thought if I become a teacher teacher I'll make it so fun!
So I've been kind of into teaching, I really enjoy it when I explain a concept to someone and see them getting it.
I ended up in the software world, but one of the nice things about this field is that you can basically combine it with anything and end up with something interesting. That's why I wanted to get a more in depth look at teaching skills. It's a cool skill that seems very transferrable to any other field.

In Uncommon Sense Teaching, an engineer, a neuroscientist and a teacher teamed up to created one of the online learning experiences I've ever had the pleasure to see.
I remember once taking a course about creativity (I had to take it), but the course was SO BORING AND UNCREATIVE.
Uncommon Sense Teaching is so different, it actually applies the advice it gives in the course itself!

The course also taught me about the trends in education, and how it's really complicated issue.
I still remember in primary school when one of my teachers said "The student is the center of the educational process", I didn't know it would be related to the Construtivism movmeent in the West!
The course contains a lot more content that Learning How to Learn, more teaching concepts scaffolding and differentiation are well explained, some information about child's development, classroom management and many insights from Neuroscience, the difference between Declarative Learning (hippucampus and neocortex) and Procedural System (Basal Ganglia)...etc.

The course was also full of great tips and teaching techniques, I really liked "My Favorite No".

> The art of teaching is making learning seem worth the effort, even when it's difficult.

The course was full of "uncommon sense", advice that is based on research and not jargon and "self-help" books.

> Students give up in their studies not because they don't have 'growth mindset' or are 'distracted by technology'—they don't know how to learn

The section about anti-bullying programs was so shocking to me. I almost couldn't believe it!
To see that instutions would implement programs that are not tested, and sometimes proved to be not helpful or even do harm. I was thinking... why don't we care enough about what we claim we care about?!
The course was so full of amazing insights that are rarely talked about.

> "Beware of training programs that don't work. Just because 'everyone' is doing the program or it's conducted by a professor from a prestigious university does not mean it is properly vetted or helpful."

One thing I also really liked about the course is the sheer amount of recommended resources, tons of books, videos, research paper.
Kinda a bummer I can't spend too much time on all of that!

The connection with Machine Learning was nice, esp. The Procedural Learning system, where we might end up having deep inctricate connections --which leads to implicit knowledge that experts have and often don't know how to explaint to others -- is like how we don't know how exactly happen in the the hidden layers.

I really like such courses that teach some fundamental skills that are extremely useful and transferrable, whether you need to explain something at work, helping a child study, diagonising your own learning problems, it's amazing!

If you only need to take one course on teaching, this is probably it.

Note: you should also join Barara's mailing list, it's very nice.

## UML Distilled

When you start learning something like UML, you'd be surprised by the amount of boring nonesense -- words words words -- it's kind of ridiculous at times.
But UML distilled is so different, it's quite practical.

Take aways from the book:

- why do we need such diagrams? communication and understanding
  - and they UML is kind of standardized, so you don't have to explain what the symbols mean, etc, that's whole point.
- UML could be many things, but according to he author, think of it just a language of sketching ideas.
- the two most useful parts of the UML: class diagrams and sequence diagrams.
  - even if you don't want to draw them, it's good to be familiar with them.
- there are multiple ways people use UML -- and they have strong opinions
  - 1.  as a sketch, something you draw on paper or whiteboard to explain something to your team
  - 2.  as blueprint: i.e. our goal is to be comprehensive, we care a lot about the deatils and correctness of the diagrams -- not recommended at all.

- some people say that we should create diagrams that are programming language independet
  - a complete waste of time

> I need to make my biases clear. Almost all the time, my use of the UML is as sketches.

> I'm not a fan of detailed forward-engineered blueprints; **I believe that it's too difficult to do well and slows down a development effort**.

> Blueprinting to a level of subsystem interfaces is reasonable, but even then you should expect to change those interfaces as developers implement the interactions across the interface

> One of my concerns with blueprints is my own observation that it's very hard to get them right, even for a good designer. **I often find that my own designs do not survive contact with coding intact**.

- iterative vs waterfall
  - Iterative development has many other names, incremental, spiral, etc. some authors make distinctions between them, but... it doesn't matter. [see the section about terminology]
    - boy do they love terminology and words in this field!
  - waterfall =
  - iterative =
  - many projects claim to do iterative development but are really doing waterfall.
    - example: "This iteration's code is very buggy, but we'll clean it up at the end."
    - iterative: each iteration produces a almost-production level code, that is well tested

- important note about making UML diagrams in analysis phase -- i.e. the phase of understanding the business domain and the problem you're trying to solve:
  - you may end up making diagrams that domain experts don't fully understand
  - "A diagram that isn't understood by the people who know the domain is worse than useless; all it does is breed a false sense of confidence for the development team."

- if you have to draw UML digitally, I like draw.io, it's pretty simple and flexible.

- use case diagrams aren't useful, but use cases themselves are useful

One note about use cases and Use case diagrams:

- "Many people find this kind of diagram useful. However, I must stress that you don't need to draw a diagram to use use cases. One of the most effective projects I know that used use cases involved keeping each one on an index card and sorting the cards into piles to show what needed building in each iteration."

Notes about class Diagrams

Notes about Sequence Diagrams

I have asked two people at uni, two brilliant students who got great graduation projects, I got the same answer:

> For challenging tasks, I made diagrams, for architecture and flow, just to understand what to do, but I did serious UML only after finishing the project. -- A.

so basically a form of documentation?
In some of my projects at uni we were asked to create analysis phase class and sequence diagrams that are "language independent". As Fowler said, it's probably just a waste of time.

# Reflection
