# A Student's Journey Into CS and Life

(work in progress...)

I'm a third year software engineering student in Tunisia. I'm writing this because a stranger on the internet shared their learning journey in a [README file](https://github.com/spamegg1/reviews), and it gave me so much excitement and hope that I kept going. We need more of this.

## Table of Contents

- Tips and Reflections
  - [Short Story: The Day I Fell in Love with CS](#short-story-the-day-i-fell-in-love-with-cs)
  - [Learning Tips](#learning-tips)
    - [Most useful things I've learned so far](#most-useful-things-ive-learned-so-far)
    - [Chunking in Computer Science](#chunking-in-computer-science)
  - [Practical Tips](#practical-tips)
    - [Don't Neglect Code Style](#dont-neglect-code-style)
    - [Use a REPL](#use-a-repl)
  - [Insights about Learning and Education](#insights-about-learning-and-education)
    - [Rethinking _self_-taught](#rethinking-self-taught)
- Courses and Books
  - [Systematic Program Design](#systematic-program-design)
  - [Programming Languages: Parts A, B and C](#programming-languages-parts-a-b-and-c)
  - [Computer Networking: A Top Down Approach](#computer-networking-a-top-down-approach)
  - [Operating Systems: Three Easy Pieces](#operating-systems-three-easy-pieces)
  - [Nand2Tetris: Part 1](#nand2tetris-part-1)
  - [Learning How to Learn](#learning-how-to-learn)
  - [Mindshift](#mindshift)
  - [Uncommon Sense Teaching](#uncommon-sense-teaching)
  - [Machine Learning Specialization](#machine-learning)
  - [Meta Version Control](#meta-version-control)
  - [Head First Git](#head-first-git)
  - [Object-Oriented Design](#object-oriented-design----alberta)
  - [UML Distilled](#uml-distilled)

## Tips and Reflections

### Short story: The day I fell in love with CS

Around two years into my CS studies, I was reading [Computer Networking: A Top Down Approach](#computer-networking-a-top-down-approach), at the end of chapter 2 it contained a list of project ideas to do. I was hooked.

I still remember the thrill I had, disabling the firewall (in the settings) on my laptop (later I realized the client doesn't need to disable the firewall :D) Creating a python script that sends "hello" via TCP, and running the "server" (which is just a python program) on my friend's laptop, the server makes it uppercase, and sends "HELLO" back. A week later I had built a simple multithreaded http server. I changed the router setting to do port forwarding to my laptop, so that anyone can use my (insecure) HTTP server anywhere, successfully putting all the files on my laptop in risk :D

At that moment everything started to click, everything is bunch of files and programs. I thought... "I love computer science", and I literally had tears in my eyes.

In high school I studied some introductory computer science classes, in one of them we were taught some very basic PHP and MySQL, we installed MySQL just by pressing "next" in the setup, and suddenly, our PHP code is storing data in the "database". I was puzzled... like "professor, where is the database", he didn't understand my question, "I mean where is this stuff stored?" It was kind of tough question indeed, but he answered me "don't worry it's just some files". I didn't buy it, but it set my heart at ease at least... at least it's on the hard disk!

After studying operating systems, databases and computer networking, I finally understood where the database is. in some sense, it's just bunch of files and some TCP socket on the top. In fact, pretty much everything is just a bunch of files and running programs. he was correct.

This all also reminds me a quote I read in one of Barbara Oakley's articles

> we rapidly remember what interests us, but what interests us takes time to develop

Passion is never a pre-requisite for learning programming, in fact passion is the fruit of your efforts.
Good teachers, good books, and small projects slowly built that passion over time.

### Learning Tips

#### Chunking in Computer Science

> Mathematics is amazingly compressible. You may struggle a long time, step by step, to work through the same process or idea from several different approaches. But once you really understand it and have the mental perspective to see it as a whole, there is often a tremendous mental compression. You can file it away, recall it quickly and completely when you need it, and use it as just one step in some other mental process. -- William Thurston

It's a very good skill to be able identify the important _chunks_ of knowledge in the subject you're learning. I have learned about this concept of chunks from Learning How to Learn and I think it's worth discussing here. (I must say that a complete beginner in a subject might not be able to identify the missing chunks, that's the role of a good teacher -- to create scaffolding i.e. divide the subject into small chunks and have students master them one by one)

For example, let's say you are studying CSS. There are some chunks that should become automatic. (and when I say "knowledge" it's pretty much same as "skill", for they are two faces of the same coin)

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

Then quickly go .notification-dot and set its position to relative.
That's a chunk, I don't even need to think about it anymore.
Those are some of the skills that make me write CSS _really fast_, it's not the memorization of css properties, it's actually drill that produces understanding and understanding that amplifies the drill.

This cannot be reached (efficiently) without two main components

- good "declarative" explanations from a good teacher who deeply understands the subject and explains it well.
- a lot of practice, "drill to skill"

Another example is one of the networking class I took, we were studying IPv6.
I noticed the professor was discussing the parts of the 128 bit address so smoothly, "let's take 48 bits of the address" then immediately highlight three segments of the address.
But my brain didn't create that chunk yet, that a part of the ip is 4 characters i.e. 16 bits.
It slows you down if you don't internalize it. It's a small example but I think it's the same pattern, missing some chunks could be why someone is struggling at something at the start.

It has become almost a habit (or a hobby!) to notice the things that take me time to figure out -- "Oh, I must be missing a chunk!". And it's not just about computer science, this concept of chunking is very general.

Here is an example, Arabic speakers use two calendar systems, The Gregorian Solar calendar and [Lunar Hijri](https://en.wikipedia.org/wiki/Islamic_calendar?useskin=vector), each have different month names. Many great books in our literature would use Lunar Hijri months, and I never learned them since we don't use them in my country, I never created that "chunk of knowledge".
The thing is, without that, when I read a book, let's say a history book, I have a vague understanding of months and I couldn't quickly map ideas to months, or intuitively understand how much time has passed, I need make more cognitive efforts to do so.
This may seem like a trivial thing but I think it actually matters.

#### Most useful things I've learned so far

- **Meta-cognition**, taking Learning [How to Learn](#learning-how-to-learn) had such a compounding effect. I've described it in more details in the reviews section, but I'd add here: understanding how we learn gives you _EMPATHY_ for yourself and your learning challenges. Being able to see my struggles from above, to ask good questions on why I struggle at something and how to solve it, all while having _mercy_ on myself and struggles.
- English as a second language, I spent two years studying english extensively in highschool from good online resources, it helped me _tremendously_ throughout my journey, to easily read books, watch lectures, and understand nerdy jokes! I keep telling my roommate who's working on his English "it's the programming language of the future!" -- and we would laugh every time. Seriously, it's very important in this field.
- Learning Git early has helped me tremendously in so many different and unexpected ways.

### Practical Tips

#### Don't Neglect Code Style

I remember watching the first couple of lectures of CS50 (though I didn't complete it) at summer after high school, the instructor David Malan just pointed out briefly that he puts the colon right after the end of the if statement, with no spaces
i.e. `if some_condition` and not `if some_condition:`
It was the first time I think about it and I just started to notice how people write code and how it differs from one language to another (and even between people using the same language).
There are indeed tools like linters that automatically format your code but I think it's worth getting in the habit of writing organized code. In first years of college, a friend of mine sometimes would write code like this:

```py
if x==10 and y< 15  :
  print("hello" )
```

I convinced him it's kind of a problem by saying "imagine writing such code in a coding interview". He told me it was a bit challenging at first to change the writing habits.
That's why I think the earlier you realize that there are some "good" code writing habits, the better.

#### Use a REPL

It's basically like the JS console on the browser dev tools or when you write "python" in the terminal and press enter. That interactive shell is called a REPL (Read Eval Print Loop).
You should use a REPL, most languages have ones! even statically typed languages like C# and Java! They are great to test small pieces of code, Regular Expressions, date functions, ASCII codes, etc.
They are extremely helpful to quickly verify what an expression _evaluate_ to.

### Insights about learning and education

#### Rethinking _self_-taught

(I first heard this in a telegram programming group)

There is a subtle problem with expressions like "self-taught" or "I've learned something _on my own_". The book or the course you took, there are real people behind it! years of work, of honing their teaching skills... Saying you're self-taught is a bit unfair to them.

#### The forgotten side of learning from teachers

I had a Control Theory professor who would apologize when he interrupted a student in a discussion, "I'm so sorry for interrupting you", or "I apologize for interrupting you earlier, you may speak"
I didn't use to apologize when interrupting people! I said, ha! that's a nice thing to do, I'll start doing it too!

Even in online courses, one such moment was in PLABC, when Dan Grossman said "people often confuse higher-order functions and first class function, _so we won't care either_", that had a lasting impact on how I deal with terminology.

One could learn much more than the course content. When you see a teacher accepting disrespectful critique and you see in their eyes that they are seriously thinking about it, whether there is some truth in it, or when they defend the partial truth in a claim they disagree with.

There is a lot to learn from good (and even bad) teachers, and it's hard (if not impossible) to learn such things from a book.

---

## Course & Book Reviews

## Systematic Program Design

Also known as How to Code: Simple/Complex data.

This course is weird, it's really good, but you won't realize how important it is immediately.
I often heard this, you should learn functional programming because it will change the way you think about programming and so on, but I never found someone explains why explicitly.

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

Systematic Program Design (AND Programming Languages course -- see next) taught me to _ask the right questions_ and to feel deeply unsatisfied when I don't fully understand how expressions are evaluated.

A year later, I noticed that this course even changed the way I see math.
For example in my Optimization class at university, we studied tons of Linear Programming problems, when I'm faced with a homework problem or in exam, I spend like 10 minutes trying to _understand the data_.
here a _simple_ example, let's say we have a graph G=(V, E)
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

This course will take the foundation and intuitions you built in Systematic Program Design and offer you a mesmerizing experience through the realm of programming languages.
This is probably the most _useful_ online course I have taken yet, Dan Grossman is such a great teacher, his love for programming and programming languages is contagious.
The course uses three languages ML, Racket and Ruby to teach so many programming concepts.

The course starts off with some _really_ important definition like what's an expression, a value.

> A value is an expression that evaluates to itself

That is one of my favorite defitions in computer science, it's so beautiful and elegant.

Make sure to focus on those new terms and understand their defintion well.
Everything is built on that foundation.
Also, the first time I hear the term "binding" was in this course.
For example an statement like `x = 10`
I'm used to hear terms like "assignment" or "we assign x the value 10", but professor Dan used the term "binding" or "to bind x to the value 10" or "x is bound to 10".
Basically a binding is a mapping, i.e. "to map x the value 10", this is important because we can bind _names_ to _value_, it's a more general concept than assignement.
For example, when you define a function, you are creating a binding. Same when you import a function in python for instance:
`from math import sqrt`
that statement creates a binding, i.e. it maps the name sqrt to the function (and functions are values themselves)
If this seems confusing it will be crystal clear once you understand the concept of enviroment (often called "Context" in the JavaScript world)

I didn't study OOP in depth well before PLABC, so it was my first serious contact with OOP, it was quite challenging, some specific concepts didn't click much, I had to redo the part and read the lecture notes again while studying Java, and it made much more sense.
I recommend learning OOP in a statically typed language liek Java or C# first.

One of my favorite thing about the course is how precise it is when it comes to explaining _evaluation rules_, the method lookup is a great example of that.

I printed all the lecture notes of the course and went to some library to bind them, I've read it twice since then and each time I blows my mind, it convers a lot of ground from static vs dynamic typing, to streams and lazy evaluation

#todo: add picture here#

One of the other benefits of the course is that it helps you build a powerful vocabulary of terms and concepts to discuss programming languages and programming problems with high precision.
For instance I wrote this [question](https://stackoverflow.com/questions/79537353/how-does-the-left-hand-side-lhs-of-an-assignment-evaluate-in-c) on StackOverflow a while ago trying to discuss a problem I found when trying to understand how pointers evaluate in C (I use to think C is a normal language :D)

TLDR: Just take this course, it's such a unique learning experience.

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

## Learning How to Learn

Many resources online contain learning tips, how to use the pomodoro technique and why it matters, the learning mindset and how to approach learning as an adventure, and all that.
I remember spending some time reading [How to Be a Great Student](todo) back in highschool and watching some videos on learning tips, on how to take good notes, etc.

I think while it wasn't life changing, it exposed me a new world I didn't know about, that it's a good idea to think about how you learn and try to improve the process.
This is also one of the unexpected benefits of "self help" books for some people, some spend their lives never thinking about how they live, and a self help book, even when it's not based on science and full of horrible advice, it can expose someone to a new world; that it's important to think about yourself and how to improve it.

At some point I decided to Learning How to Learn and boy it was different from everything else. It wasn't just about teaching some tips, it's an entire mental framework on how the human brains learn that helps you diagnose your own learning problems.
Learning How to Learn has a deep impact on my entire journey -- and even this README.
I started to find myself always writing notes and reflections about my learning and try to understand why people struggle at some specific concepts.

The course contains some interview with many interesting people including Scott Young -- known for his books and [MIT challege](https://www.scotthyoung.com/blog/myprojects/mit-challenge-2/), I really enjoyed these.

You should take it!

## Mindshift

This course is not about learning techniques, but on how to think about having a learning life style. I discusses topics like passion and why it's important to understand the real world constraints around you and not blindly "follow your passion".

The point about passion and [how passion is a reflection of what you're good](#the-day-i-fell-in-love-with-computer-science) at right now stayed with me.

> What you feel you are best at isn't necessarily **all** that you can be best at

The course also discusses the value of your past knwoledge and experiences, it made me realize that even if the jobs "AI replaces programming jobs", I've learned -- and still learning -- a LOT from this field of study.

> Seemingly unconnected knowledge from your past can bring unexpected assets to your work in the present

It also convers why it's important to have second skills

It also mentions some interesting problems in western education that I found fascinating.

> As an overreaction to the extreme "learning equals memorization" idea that has endured for thousands of years, western education has become wedded to the idea that conceptual understanding is the golden key to learning. -- Barbara Oakley

This is discussed in more depth in a 40 page article called [The Memory Paradox](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5250447) that I highly recommend.

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
Again, my only complaint is that I didn't feel there was enough practice and challenge.

## Meta Version Control

This course is targeted for absolute beginners who want to know about it.
Avoid such courses, they leave you with shallow knowledge that you can't apply, this course is the opposite of down-to-earth teaching.
It's shot in a cool looking studio where every piece of furniture and decor is placed with utmost care -- yet it's hollow.
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

## Object-Oriented Design -- Alberta

NOTE: I did not complete the course

> longer than a winter's night -- Tunisian proverb

I had multiple UML classes in college, they were full of... words.

It is where I coined the term "audiobook lecture". At some point it feels like ASMR, reminds me of how I felt like a kid, sleeping in my mother's arms, listening to her talking on the phone or with someone...

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
  - waterfall = you break down development into a sequence of activities, e.g. requirements analysis, design, coding, and testing, you can for instance allocate a couple of months for each activity.
  - iterative = the development is divided into "iterations", each iteration you pick some feature and finish it, you test it and make sure it's slmost production-ready.
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

I have asked two students at my university who got some of the best graduation projects, I got the same answer:

> For challenging tasks, I made diagrams, for architecture and flow, just to understand what to do, but I did serious UML only after finishing the project. -- A.

so it's basically a form of documentation?
In some of my projects at university we were _asked_ to create analysis phase class and sequence diagrams that are "language independent". As Fowler said, it's probably just a waste of time.
