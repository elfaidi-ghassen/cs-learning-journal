# A Student's Journey Into CS and Life

I'm a third year software engineering student in Tunisia, I'm writing this because a stranger on the internet shared their learning journey in a README file, and it gave me so much hope and excitement that I kept going. We need more of this.

(work in progress...)

# Reviews

## Table of Contents

## Reviews

1. [Computer Networking: A Top Down Approach](#computer-networking-a-top-down-approach)
2. [Uncommon Sense Teaching](#uncommon-sense-teaching)
3. [UML Distilled](#uml-distilled)
4. [Machine Learning Specialization](#machine-learning-specialization)
5. [Head First Git](#head-first-git)

## Learning Tips and Reflections

- [On the Command Line](#on-the-command-line)
- [Why Some Learners Really Don't Like the Command Line](#why-some-learners-really-dont-like-the-command-line)
- [Wrong Advice Could Work Sometimes](#wrong-advice-could-work-sometimes)

## Systematic Program Design

Also known as How to Code: Simple/Complex data.

This course is weird, it's really good, but you won't realize how important it is immediately.
I often heard this, you should learn functional programming because it will change the way you think about programming and so on, but I never found someone explains why explicitely.

I think this course taught me how to think, and one cannot think well without good words, the course teaches the difference between values and expression -- and what evaluation even means.

Really fundamental concepts, but everything is built on top of them.
Later you will understand that functions are expressions that evaluate to a value, and then closures will start to make sense.

When I see a new piece of code, my brain now immediately asks: Wait a minute, how does that evaluate, what does it evaluate to?

```python
results = df
            .filter(col("city") == "New York")
            .select("name", "age")
```

my mind errors out. what does `col("city") == "New York"` evaluate to?!
it can't be a boolean, it's a useless information to the filter method.
it must be evaluate to some sort of an object or function, so it uses operator overloading.

Functional programming also taught me that we can think of everything as a function. Combined with the previous point about evaluation, it completely changed my perspective.

Here's an example: I was recently learning about promises in JavaScript -- a quite challenging concept --. I would see some code like

```javascript
let p = fetch(URL).then(f1).then(f2);
```

It didn't click; most tutorials didn't explain what was going on. and I didn't even blame myself for not understanding, I felt, man those tutorials are doing something wrong! they didn't explain how things evaluate.
what I was seeing is the following

```
let p = dot(dot(fetch(URL), then(f1)), then(f2))
```

I kept asking myself: what does fetch(URL) evaluate to? And what happens when I call then(f1) on whatever that evaluates to, and so on? After some time and thanks to some good resources, I clicked.

Systematic Program Design (and Programming Languages course -- see next) taught me to _ask the right questions_ and to feel deeply unsatisfied when I don't fully understand how expressions are evaluated.

A year later, I noticed that this course even changed the way I see math.
For example in my Optimization class at university, we studied tons of Linear Programming problems, when I'm faced with a homework problem or in exam, I spend like 10 minutes trying to _understand the data_.
here a simple example, let's say we have a graph G=(V, E)
I start to think, what does V and E evaluate to?
I see it as:
G=({1, 2, 3, 4}, {{1, 2}, {2, 3}})
and then writing the following seems obvious:
for all e in V, for all i, j in E
I found understand the shape of data actually helps in problem solving.
Which is a fundamental concept in SPD.

I actually believe my math skills in genral improved because of that course.
I remember I was stuck in a problem in some probability exam, it was hard, then I started making examples, imagining the "data", the shape of input, and suddenly it clicked -- at that moment SPD immediately crossed my mind and I smiled.

You should trust the course, take it slow and enjoy it, the professor, Gregor Kiczales isn't that kind of professor who says "this course will change how you think forever", he is way too nice!

Finally, I think studying that course will help you get the most out of the _Dan Grossman's Programming Languages_ course (next), which is by far the _best and most useful course I have ever taken_.

So trust the teacher! learning is a relationship, it's not self learning, if you can't trust the teacher and material, it's harder to learn well.
I still remember when I was taking SPD in the summer of first year at university, I would see some of my friends and classmates studying React and talking about fancy new technology. honestly it was painful and sometimes I'd feel I'm wasting my time. I think I could have learned more, or at the very least, had more fun while learning.

## Programming Languages: Parts A, B and c

"But if you have big ideas, you have to use big words to express them, haven't you?" -- Anne of Green Gabes

This one of my favorite online course.
Dan Grossman is such a great teacher

ML, Racket and Ruby

This course will take what you learned in Systematic Program Design,

and since then I've read it twice.

> A value is an expression that evaluates to itself

That is my favorite definition in CS. it's so elagant.

The course is super enjoyable and covers a lot of ground
static vs dynamic typing

After completing it, I printed all the lecture notes and went to a library to bind them into a book.

concepts like lazy evaluations and streams are essential and keep showing up in other languages.

I mistake I made is not studying some OOP before, I highly recommend that you learn the basics of OOP in some statically typed language before you embark into the third course.

the course uses Emacs

I wrote this question
C put my understanding of programming to the limit :D
https://stackoverflow.com/questions/79537353/how-does-the-left-hand-side-lhs-of-an-assignment-evaluate-in-c

## Computer Networking: A Top Down Approach

Computer networking is one of the most rewarding subjects in computer science, you suddenly start to understand those terms you hear everywhere.
Suddenly it's almost hard to remember life where you didn't know those terms and concepts!
I wasn't very satisfied with my university's approach to computer networks, it was a buttom-approach and kind of boring.
So I picked up Computer Networking: A Top Down Approach, and boy I'm glad I did, it's one of the most rich learning experiences I've had in computer science, in fact it's when I suddenly thought, "I love computer science".

The book is accompnied by A LOT of extra content, the Wireshark labs in particular were amazing, I highly recommend that you print the labs and annotate them, it's much more fun.

I highly recommend the book, the first two chapters alone are enough for most programmers, in fact by chapter 2, if you do the projects, you'd have built a HTTP server, SMTP server, UDP ping, and a proxy server from scratch using socket programming.
This book has a special place in my heart, when I was reading it I realized [I've finally become passionate about CS](#the-day-i-fell-in-love-with-computer-science).

Some advice:

- when you read the DNS section in chapter 2, buy a domain name
  - it's around $10 per year, but what you learn with stick with you forever.
  - if you're a student try getting a domain in Githuab Education Pack for free.
  - you can for instance host a static website on github pages, it will give you something like yourname.github.io. You can then create a CNAME record to point your domain to it.
  - remember, if you buy a domain like yourname.com, you can add as many prefixes as you want, you can create sub domains like blog.yourname.com or basically ANYTHING.yourname.com, and even an email address like pm@yourname.com
  - Also, at some point later it might be also worth getting a VPS for a month where you can practice even more.

Chapters:

Chapter 7: Wireless Networks
wireless networks are everywhere, and having a some understanding of them to very helpful. I've always been puzzeled by how WiFi networks in large places like universities works, this chapter answered all of my questions and more! The chapter will answer two important questions, How does WiFi and 4G networks work? you in the back seat if a car or bus, watching a youtube video using a cellular network, each of those network towers (base stations) have limited range, so you certainly pass through multiple of them in your journey, yet the video experience is seemless, you don't see any interruption, how does that work?

## Operating Systems: Three Easy Pieces

Studying Operating Systems is extremely important because it gives you a concrete example of all the concepts you see in CS.
for example at some point you learn that a compiler is a program that translates the given code to another representation.
That's absolutely correct and a beautiful defintion.
If you think about it, you could build a machine that you give it a piece of paper of instructions, and it prints another piece of paper.
that's a compiler.
But studying OS will give you more concepts that your mind can use to reason about new thigns.
For example, you'll start to think that a compiler is just a program (i.e. a file in the filesystem that contains instuctions) that you can run using the OS sys calls, so it becomes a process, the absraction of a running program, that process will simply read() the source code file and do some transformations to it, then write them back to another file.

The book is divided into three parts.

1. Virtualization
   You will learn about two really important cocnepts, the process and memory abstractions. really important stuff.
   also explains system calls and kernel mode.
   Limited Direct Execution...
   I didn't find the CPU schudeling interesting, I just skimmed them, we studied them a lot in college.
   After completing this part, I HIGHLY recommend building a shell, the course has a github repo with projcets, building a shell is EXTREMELY rewarding, you'll see processes differently.
   The project was in C, and my C skills were rusty, so I chose python.

2. Concurrency

3. Persistance

## Nand2Tetris: part 1

the projects and part 1 of the book are freely available at /Projects section of the website.
I finished it in less than around 2 weeks, at that point I had already taken courses at univeristy that teaches bolean algebra and computer architecture concepts, the concepts are actually advanced from N2T, I've studied transistors in depth an electronics class, how we build logic gates from them, for instance we studied K-Maps and sequential logic in depth... yet I didn't understand how a computer works!
That's perhaps one of the problems of education, at least at my university, courses are disconnected, a sea of islands.
Nand
I documented the journey of building the CPU, and I even computer the number of transistors, ended up with 15K transistor CPU, and the 16K registers memory... contained a couple of MILLION CPUs.
As the course notes hints, building memory using demultiplexors isn't probably a good idea.

This is where I first understood the concept of "abstraction" and API.
It's a very powerfl and central topic in computer science yet it not always explicitely explained.
Abstraction is complex topic in other fields like philosophy, but in programming it's fairely straightforward.

> Abstraction is thinking about WHAT and not HOW.

why it's hard to accept the definition of API.
same reason why it's hard to accept the definition of what server is.

I tried this.
go to a first year CS student, tell them what an API is they would feel it's vague.
what's worse is the online explanations like "it's like conctract between two systems". The use of analogies sometimes doesn't help.
the concept of abstraction only makes sense after seeing a lot of examples of concreteness.

I had a class in college about basic information theory and image processing. one of key concepts is the idea of an alphabet.
an alphabet is a finite set of symbols.
it took me quite a while to accept that it's just an abstraction?
a symbol can by ANYTHING.
this mathematical abstraction is very powerful. it makes math useful in different contexts, you'd just to need to prove it's a language or it's a linear map (in linear algebra), then you could use all the theorems and cool stuff built on top of it.
I think that's part of the so called "mathematical maturity"
it's like implementing an interface in OOP. once you implement the interface, your class can be used in methods that deal with that interface.

The most extreme level of abstraction I've seen what in a Analysis 3 which was all topology concepts. math feels like it's strating to break down and everything concept is falling apart, even the concept of distance is abstract.

At some point I suddently felt comfortable dealing with abstractions and understanding the point of using terms like "name" instead of "variable", like when we say a name is bound to a value, it's like forgetting all the implementation details and thinking soley about the higher order concept of naming things, something humans like to do.



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

## Machine Learning

This was a very enjoyable course, one of the most gentle courses I've taken.
I created small web projects to try things out, I built simple API points for a simple hand digit recognition website with a friend; and a movie recommended.
You can apply what you learn instantly.
The course also cleared some misconseptions from my mind, I used to think machine learning is a very mathematical field, but it turned out it's very expiermental nowadays, you change params, reevaluate, etc.
also I used to think that neural networks are heavily inspired by how the brain works, but Andrew explained how it's actually very different, and we still don't really know how the brain works yet.
I really like how Andrew is down to earth, one time he explained how he deep learning is just... neural networks, and he was so surprised back in the day on the impact of the "re-branding" of neural networks as deep learning.
and on other occasion he explained why training robots is hard, and we stil fail to create robots that generalize well -- the path to AGI is very difficult. and hence if you see a cool robotics videos, it doesn't mean they're actually useful.
Or how reinforcement learning is great when it comes to simluations, but isn't quite practical in real life and way too hard to get it right.
This kind of knowledge is important, it's important to understand the limits of the current tools.
I think we can't aspire for a better future if our understanding of present time is distorted. the journey is long we still have a long way to go.

But machine learning is SO COOL in itself, we don't need hype!

My only complain with the course is how gentle it is. The programming assignments are extremely easy -- and hence a bit unsatisfying.

You don't need much math for the couse, high school math is more than enough, the toughest math is doing a partial derivate -- in an optional section of the course.

Andrew is a great teacher, he explains concepts intuitively.
my only complaint is that I didn't feel there was enough practice and challenge.

## Meta Version Control

This course is targeted for absolute beginners who want to know about it.
Avoid such courses, they leave you with shallow knowledge that you can't apply, this course is the opposite of down-to-earth teaching.
It's shot in a cool looking studio where every piece of furnature and decor is placed with utmost care -- yet it's hollow.
I don't recommend it. It is similar to the Object-Oriented Design course, that say so much yet nothing, at same time

## Head First Git

I love the Head First series, even though it's full of silly drawings that I don't really care for. The content itself is often superb and very down to earth -- and not shallow at all. This book contains some of the best explanations and analogies for Git, I left the book with clear mental model of how Git really works and how to use Git and Github in practice.

I tried two learn Git around three times before, In High school I watched some youtube videos, and later I even did the Meta Version Control course -- which wasn't helpful. Each time, I'd learn the commands, have some commits and push something to github, then I forget about it -- until it's the next summer.

I thought it was enough, I was determined to learn Git in depth, I spend a month to read the entire book and practice the concepts, for the first time I felt I'm getting the hand of it.
But I felt... none of my friends use Git! if I don't use it slowly I'm going to forget how to use it.
So I send a message to my roommates -- "I'm going to force you to learn Git, whether you want it or not!"
And I did so, it was a very fun experience and I learned so much about git in the process.

The book focuses on Git, branching, conflicts and fixing mistakes, the best practices and also have a good coverage of Github -- although it's not the main focus.

The "there are no DUMB QUESTIONS" sections were my favorite, they always answer all the dumb questions that cross my mind!

It also did something really smart which is not using code, but just plain text for all examples, which instills the idea that you can basically use Git for _anything_.

If you want to learn how git works and immediately start contributing to open source and working with others, this is the book.
Git really makes programming much more fun.

## Object-Oriented Design

> longer than a winter's night -- Tunisian proverb

I had multiple UML classes in college, they were full of... words.
It is where I coined the term "audiobook lecture". at some point it feels like ASMR, reminds me of how I felt like a kid, sleeping in my mother's arms, listening to her talking on the phone or with someone...
This one is not different.
Don't take this course.

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

# Tips and Reflections

#### On the command line

After learning Git in the summer, I went to my some of my friends and classmates who study CS and told them: "I'm going to force you to learn Git". I don't want to work alone!
One thing kept happening over and over: whenever I explained how branches work and how we switch branches, and I showed them how files do change in the working directory (using ls command -- in either WSL or git bash), they nodded and thought it made sense. Then I open the file explorer (finder) and show them that the files DO change; they go quiet for a second, "wow" they say. It's as if the command line isn't something concrete.
The way I see it is that Windows does things for convenience that kind of distorts one's understanding, like, before I used to believe file extensions were something special
when I was starting out I used to think it's impossible to name a python file "script.mp4", how could that be! even VS code won't color it for you! -- I think it has something to do with what happens when you change the file extension in the file explorer you get a popup saying your change would make the file unusable.

I recommend getting comfortable with command line as early as possible, it doesn't just improve your productivity, but it also offers you more opportunities for learning.
If you're a windows user and don't want to switch, try having a dual boot, and make sure to install WSL. I use a custom shortcut Ctrl + Shift + V to start WSL using autohotkey.

#### Why some learners really don't like the command line

When I realized the power of command line, I went to pretty much anyone I knew and installed zoxide and fzf for them.
I created a /projects folder, and told them they can simply use z proj to go to it, and create a folder for each project, and simply open it in VS code (code .)
And Windows users like me have an itch for opening the explorer (finder) for some reason, so I created an alias called opend which opens the current directory in the explorer.
That alone made them enjoy using the command line and motivated them to learn it more.
So based on my observation, I believe that many people detest the command line simply because they never saw a real workflow, something concrete that makes them feel it's worth learning.

#### Wrong Advice Could Work Sometimes

The idea of left-brain people who are analytical and right-brain people who are creative is heavily debunked and considered a pop science myth.
The thing is, I noticed in many contexts how an advice that's based on myths could actually be beneficial -- for the wrong reasons!

For example, one of the best drawing books is Drawing on The Right Side of The Brain, it's completely based on the idea of left-brain vs right-brain, it's pretty much complete nonesense, yet the exercices in the book are extremely helpful and actually can make you draw better!

Another example I saw was in Head First Java, taking breaks is proven to be helpful in improving learning, but it's not because of left vs right brain activities!

> Don't work one part of the brain for too long a stretch at one time. Working just the left side of the brain for more than 30 minutes is like working just your left arm for 30 minutes. Give each side of your brain a break by switching sides at regular intervals.

What I gather from this that:
If you apply an advice and you feel benefits from it, it doesn't necessarily mean the explanation is correct.

#### What works for you might (not) work for others

Let's say someone struggled studying something, or perhaps someone struggled emotionally for years because of something, perhaps they didn't accept themselves or had low self esteem, at some point, they might have rich life experiences, read good books or listen to people of knowledge, and it helpes them tremendously in their growth.
but one problem one may fall into is starting to think every single problem others habe must be fixed that way, "if only people accepted themselves!" or "if only people did this or that".
The thing is, people's problems are complicated, people's struggle for so many reasons and often we assume we get other's problems, but we might not see the full picture.
It is a trap I fell into, and I don't want you to fall into.
Especially when it's not one's area of expertise, one has to be humble and accept it's just the start of the journey.
It does not mean not sharing one's opinions and reflections -- but it changes how we approach sharing them.

#### How to take notes on computer

I really like Obsidian, by anything will do.
Try not to get into the loop of trying out different tools. Lots of videos on youtube that almost feel like those "self-help" books.
I remember starting this journey in high school, starting with Notion, it was great. But then... the heck, why not use open source tools like Logseq! and so, Logseq it was, I really like it, then I tried OneNote for some reason, and finally landed on Obsidian.
The thing is, all of them will do, spending time comparing them is kind of a waste of time, unless it's a hobby for you.
I use google keep on mobile, sometimes I need a write a quick note and and it's conventient easily on my laptop.

Also, I have noticed that note taking could turn into an illusion of learning (todo: add link here).

The Pragmatic Programmer recommends having an Engineering Daybook, an actual notebook, it's where I draw and take notes about things I'm learning and quotes I love, sometimes observations and insights from real life, it's not for productivity, it's also that I want to enjoy the journey of learning and life.

#### Some ways to have fun

There are many ways to have fun!
Documentaries could be a great way to both enjoy your time and get out of them with a new perpective. This is a list of documentaries I really like

- [Schooling the World](#link)
- [The True Cost](#link)
- [Revolution OS](#link)
- [A Trip to Infinity](#link)

Reading novels could be a really fun.
In Japan they had a famous animated series called World Masterpiece Theater, which is animated works that are based on the classics of literature -- like Anne of Green Gables and Heidi, both directed by the famous Ghibli director. The animated works themselves are great, but I've been reading the originals works and it's so fun!
I recommend reading A Little Princess -- Hodgson Burnett

I rarely watch movies, because whenver I do it often turns out to be a waste of time, but some movies were worth it

- The Flavor of Green Tea Over Rice -- Ozu
- 12 Angry Men
- Ikiru
- My Neighbors the Yamadas

Another really fun activity I've came across is identifying plants! iNaturalist is a great app to help you identify plants you see in your daily life, knowing the names of the plants and flowers you see everyday makes each walk a more rich experience, you'd start to notice how plants change from season to season.

## The day I fell in love with Computer Science

Around two years into my CS studies, I was reading Computer Networking: A Top Down Approach, at the end of chapter 2 it contained a list of project ideas to do. I was hooked.

I still remember the thrill I had, disabling the firewall (in the settings) on my laptop (later I realized the client doesn't need to disable the firewall :D) Creating a python script that sends "hello" via TCP, and running the "server" (which is just a python program) on my friend's laptop, the server makes it uppercase, and sends "HELLO" back. a week later I had built a simple multithreaded http server. I changed the router setting to do port forwarding to my laptop, so that anyone can use my (insecure) HTTP server anywhere, successfully putting all the files on my laptop in risk :D

At that moment everything started to click, everything is bunch of files and programs. I thought... "I love computer science", and I literally had tears in my eyes.

In high school I studied some introductory computer science classes, in one of them we were taught some very basic PHP and MySQL, we installed MySQL just by pressing "next" in the setup, and suddenly, our PHP code is storing data in the "database". I was puzzled... like "professor, where is the database", he didn't understand my question, "I mean where is this stuff stored?" It was kind of tough question indeed, but he answered me "don't worry it's just some files". I didn't buy it, but it set my heart at ease at least... at least it's on the hard disk!

After studying operating systems, databases and computer networking, I finally understood where the database is. in some sense, it's just bunch of files and some TCP socket on the top. In fact, pretty much everything is just a bunch of files and running programs. he was correct.

This all also reminds me a quote I read in one of Barbara Oakley's articles

we rapidly remember what interests us, but what interests us takes time to develop

Passion is never a pre-requisite for learning programming, in fact passion is the fruit of your efforts.
Good teachers, good books, and small projects slowly built that passion over time.

#### Most useful things I've learned so far

- Learning theory, taking Learning How to Learn and Uncommon Sense Teaching has had a compounding effect.
- English as a second language, I spend two years studying english extensively in highschool from good online resources, it helped me tremendously throughout my journey, being able to easily understand english technical content is invaluable in this field.

If I had a child, for the academic side, I'd focus on learning theory, solid mathematical foundation, and languages. langauges are awesome.

It's fascinating how a bad education system raises someone who doesn't know how to learn independently, hate math and can't speak french well -- even though having studying it since second grade.
I had to learn all that _on my own_ in college.

#### The myth of _self_-taught

I heard this insight in a group on telegram, and I find it fascinating and worth sharing. There is a subtle problem a term like "self-taught" or saying I've learned something "on my own", it's forgetting that actually there someone who taught you, the book or course you took, there are people behind it, years of work, years of experience.
Perhaps we need to re-think the concept of learning and teaching...

#### Important Meta-skill: chunking

It's a very important try to identify the important _chunks_ of knowledge in the subject you're learning. I have learned about this concept of chunks from Learning How to Learn and I think it's worth discussing here.
For example, let's say you are studying CSS. There are some chucks of knowedge that should become automatic. (and when I say "knowledge" it's pretty much same as "skill", for they are two faces of the same coint)

For example, one of key CSS skills is that when you see any website or design, **you start to see everything as boxes**, you can imagine how you wrap the sidebar and main section into a parent element and setting the parent to display flex _without_ thinking about it, it becomes automatic.
For example when you deeply understand positioning in CSS, you'd write something like this without thinking about it:

```css
.notification-dot::after {
  content: "";
  display: block;
  width: 10px;
  height: 10px;
  border-radius: 50%;
  background-color: red;
  position: absolute;
}
```

Then quicly go .notification-dot and set its position to relative.
That's a chunk, I don't even need to think about it anymore.
Those skills some of the skills that make me write CSS _really fast_, it's not the memorization of css properties, it's actually drill that produces understanding and understanding that amplifies the drill.

This cannot be reached (efficiently) without two main components

- good "declarative" explanations from a good teacher who deeply understands the subject and explaisn it well.
- a lot of practice, "drill to skill"

I also remember studying a network class, we were studying IPv6.
I noticed the professor was discussing the parts of the 128 bit address so smoothly, "let's take 48 bits of the address" then immediately highlight three segments of the address.
But my brain didn't create that chunk yet, that a part of the ip is 4 characters i.e. 16 bits.
It slows you down if you don't internalize it. It's a small example but I think it's the same pattern, missing some chunks could be why someone is struggling at something at the start.

Since I've been obsessed by noticing the things that take me a moment to figure out, while not necessary, but I love thinking about this, children often a great source to understand what chunks you have that you might not even be aware of.
If you'd ask me before how many months between March and October, or what's the month after 3 months from April.

It takes me a couple a while to answer it, the answer isn't clean in my mind.
That's a missing chunk
the months were never drilled to the point where each one has a direct number → name and name → number bindings.
I tried fixing this as a learning expirement, I literally made flashcards name → number and number → name and didn't take much to remember them.
And speaking of flashcards:

#### The magic of flashcards

I LOVE flashcards, like, they are my favorite learning tool.
I've been consistently using Anki since 2023.

![Anki Heatmap](/media/anki-heatmap.jpg)

Flashcards aren't perfect and it's better to think of them as one tool in your aresenal as a learner. I find flashcards to be the best and most efficient way to memorize something and be able to _respond to a cue_.
I also find flashcards useful to review concepts and not just memroization, for example I have computer networking questions like "Explain how DNS work, let's say you write google.com and press enter, what happens", the idea here is not to memorize the answer but to do retrieval practice and explain a concept, I usually explain the concept outloud and have a pen and paper where I sketch the concept.

Many people find using flashcards to be useful for computer science and I think you might find them helpful.
You can use flashcards for anything, from memorizing the names of flowers, preparing to a driving test, to computer networking classes at university (I kept getting straight As in those clases using just flashcards, I literally take notes in class, go back home, turn the notes into flashcards, and throw the notes in trash -- which might be an act of disrespect to knowledge, but I'm not sure and... I find it satisfying!)

I want to mention some mistakes I made along my journey of creating flashcards.

- Don't mix flashcards that are very unrelated, like flashcards about computer networking and security in the same deck.
  - If you mix unrelated flashcards you'd miss the benefits of _interleaving_.
- Do not keep taking notes forever then start to create flashcards: it's much better to make flashcards along the way, and review them constantly.
- You're not expected to review ALL flashcards that are due, consistency is what matters, and this is why the previous point is important, just the act of creating flashcards and reviewing them isntantly can boost you learning A LOT.
- It might be better to avoid using AI tools to make flashcards, there is a lot to learn just by trying to formulate a good question.
- If you're on windows, you might find the ShareX, an open source tool to take screen shots, quite helpful, I use it to remove parts of an image or annotate them then immediately take screen shots, it's like a tool to edit the screenshots on the fly.

#### The forgotten side of learning from teachers

I have seen this in college, for instance, I had a Linear Algebra professor who as _extremely_ organized, from lecture notes to the way he teaches. it was inspiring.
I also had a Control Theory professor who would apologize when he interrupts a student while discussing, "sorry to interrupt you", or "I aplogize for interuppting you earlier, you may speak"
I didn't use to apologize when interrputing people, I said, ha, that's a nice thing to do.

I learned a lot online too.
I have taken many courses from the same person, he reapeats some stories a lot across courses, but he does something clever that somehow makes repetition doesn't feel bad, he says "I know I repeat this story a lot" or "I really like re-telling this story again and a gain", it makes a difference. it's a good storytelling technique.

Also, from PLABC, when Dan Grossman said "people often confuse higher order functions and first class function, so we won't care either", that had a lasting impact on how I deal with terminology.

There is a lot to learn from good (and even bad) teachers, the way they handle tough questions, how they handle problems, how they inspire, intellectual humility.
This is another reason for I don't like some courses like OOD or Meta's Version Control course, it's stripped from the human exeprience.


#### Cultural Insight about *work*
One of the most beautiful terms in our Tunisian dialect is the term "خدمة" (/Khid.ma/), which literally means "service", as in serving someone.
So to say you are working today, one literally say they're serving today.

I feel that it is always a reminder of the value of real work, that it is something that contributes to society and moves life, Whatever our job and field (engineer, carpenter, doctor...) in the end we are providing a "service" to the community.

It just makes me smile when I hear someone complaining "There are no jobs nowadays" in Tunisian dialect.

But also it's kind of sad that the origin of expressions we use lose their meaning over time.