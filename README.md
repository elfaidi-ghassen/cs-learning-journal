# A Student's Journey Into CS and Life

(work in progress...)

I'm currently a third year software engineering student in Tunisia. I have many reasons to write this. But what got me thinking seriously into writing it is a stranger on the internet who once shared their learning journey in a [README file](https://github.com/spamegg1/reviews). Reading it gave me so much excitement and hope that I kept going. We need more of this.

Many of the courses I've taken are part of the [OSSU curriculum](https://github.com/ossu/computer-science), if you've never heard about it before, give it a look.

This is not a roadmaps. It's just my personal experiences and the resources I went through.

## Table of Contents

- [Tips and Reflections](#tips-and-reflections)
  - [Short Story: The Day I Fell in Love with CS](#short-story-the-day-i-fell-in-love-with-cs)
  - [Insights about Learning and Education](#insights-about-learning-and-education)
    - [The Trap of Projection](#the-trap-of-projection)
    - [Rethinking _self_-taught](#rethinking-self-taught)
    - [It's all about good teachers](#its-all-about-good-teachers)
    - [Learning compounds](#learning-compounds)
    - [The forgotten side of learning from teachers](#the-forgotten-side-of-learning-from-teachers)
    - [Do certificates matter?](#do-certificates-matter)
  - [Learning Tips](#learning-tips)
    - [Reflect on Your Journey](#reflect-on-your-journey)
    - [Enjoy small wins](#enjoy-small-wins)
    - [Most useful things I've learned so far](#most-useful-things-ive-learned-so-far)
    - [Chunking in Computer Science](#chunking-in-computer-science)
    - [No perfect roadmap](#no-perfect-roadmap)
  - [Practical Tips](#practical-tips)
    - [Don't Neglect Code Style](#dont-neglect-code-style)
    - [Use a REPL](#use-a-repl)
    - [Using Flashcards](#using-flashcards-anki)
    - [Taking notes](#taking-notes)
    - [Using the command line](#using-the-command-line)
    - [Some ways to have fun](#some-ways-to-have-fun)
- [Courses and Books](#course-and-book-reviews)
  - [Systematic Program Design](#systematic-program-design)
  - [Programming Languages: Parts A, B and C](#programming-languages-parts-a-b-and-c)
  - [Operating Systems: Three Easy Pieces](#operating-systems-three-easy-pieces)
  - [Computer Networking: A Top Down Approach](#computer-networking-a-top-down-approach)
  - [The Missing Semester](#the-missing-semester)
  - [Nand2Tetris: Part 1](#nand2tetris-part-1)
  - [Learning How to Learn](#learning-how-to-learn)
  - [Mindshift](#mindshift)
  - [Uncommon Sense Teaching](#uncommon-sense-teaching)
  - [Other Courses on Learning](#other-courses-on-learning)
  - [Machine Learning Specialization](#machine-learning)
  - [Meta Version Control](#meta-version-control)
  - [Head First Git](#head-first-git)
  - [Object-Oriented Design](#object-oriented-design----alberta)
  - [UML Distilled](#uml-distilled)
  - [Java MOOC](#java-mooc)
  - [Writing in The Sciences](#writing-in-the-sciences)
  - [Data and Reality](#data-and-reality)
  - [Introduction to Web Accessibility](#introduction-to-web-accessibilitya11y)
- [Footnotes](#footnotes)

## Tips and Reflections

### Short story: The day I fell in love with CS

Around two years into my CS studies, I was reading [Computer Networking: A Top Down Approach](#computer-networking-a-top-down-approach), at the end of chapter 2 it contained a list of project ideas to do. I was hooked.

I still remember the thrill I had that day. Disabling the firewall in the settings on my laptop (at some point later I realized the client doesn't need to disable the firewall :D) and creating a python script that sends "hello" via TCP. Then running the server -- which is just a python program -- on my friend's laptop that receives the string, makes it uppercase, and sends back "HELLO".

A week later, I had built a simple multithreaded HTTP server. I changed the router setting to use port forwarding -- to my laptop, so that anyone in the world can use my (insecure) HTTP server anywhere -- successfully putting all the files on my device at risk :D

At that moment, everything started to click, there were fireworks inside my brain, _wait... so everything is bunch of files and running programs_! At that moment I thought..."_I love computer science_", -- I literally had tears in my eyes.

In my high school days, I studied some introductory computer science classes, one of them taught us some very basic PHP and MySQL, we installed MySQL just by pressing "next" on the setup wizard; suddenly, our PHP code is storing data in the "database". I was puzzled! like, "professor, _where_ is the database" -- he didn't understand my question. I continued "I mean where is this stuff stored?". It was a tough question honestly, yet he answered me "don't worry it's just some files". I didn't buy it. But at least it set my heart at ease. At least it's on the hard disk!

After studying operating systems, databases and computer networking: I finally understood where the database is. In some sense, it's just a bunch of files and some TCP socket on the top. In fact, pretty much everything is just a bunch of files and running programs. \*he was correct.

This all also reminds me of a quote I read in one of Barbara Oakley's articles

> we rapidly remember what interests us, but what interests us takes time to develop

Passion is never a pre-requisite for learning CS and programming. In fact, passion is the fruit of your efforts. It's the thrill you have when you see you're slowly improving over time, you're starting too the full picture.
Good teachers, good books, and small projects slowly build that passion over time.

### Insights about learning and education

#### Rethinking _self_-taught[^self-taught]

There is a subtle problem with expressions like "self-taught" or "I've learned something _on my own_". The book or the course you took, there are real people behind it! years of work, of honing their teaching skills... Saying you're self-taught is a bit unfair to them.

#### It's all about good teachers

I'm quite good at a couple of things, and whenever someone asks me how I got good at them, my answer is almost always the same: a good teacher (or a good course, book, or mentor).
If the teacher isn't good, or if their way of teaching doesn't work, it becomes much harder to get anything meaningful from the experience.
Of course other factors matter in any learning, but I've developed some strong opinions about this over time: I'm truly convinced that the teacher is far more important than the course itself.

Over time, I've realized many things about learning and teaching.
Sometimes I find myself deeply moved by sincerity and subtle acts of kindness I see around me, those things really captivate me (and even bring me to tears)
It moves me when I notice that someone has put genuine effort into teaching well and making a subject less intimidating.
I often call it "Down to earth teaching". It's when someone isn't trying to impress you with jargon or show off how much they know. Instead, they're genuinely trying to help you understand. It always fills my heart with happiness when I see it.

What moves me isn't the jokes that lighten the mood or a particular teaching style, it's the human effort behind it, the invisible work. The fact that this person has actually thought carefully about how to teach this and didn't want me to feel intimidated.
And behind it all some sort of subtle respect to learners that's hard to describe in words.

This realization led me to another thought: we often forget to thank good teachers.
At some point I started sending emails to good teachers, at university or online, and even book authors. I was surprised by how many replied and how happy they were to hear that their work had helped someone.

#### Learning Compounds

We often hear the generic "focus on the fundamentals" advice because it's important. For some reason I believed that advice even before I understood why it matters, it just sounds like common sense, and fortunately it turned out to be true.

Here is the _key idea_: Two different people can study the same material from the same teacher or book, and leave with completely different experience, because of the existing knowledge they have.

"Previous knowledge" makes learning new things much more fun, because you're not starting from scratch every time! when you haven't internalized the key fundamental chunks of knowledge, every new problem you face, it's completely new to you, so it's much more painful. But what's worse, is that you learn less from the experience itself. Without a well-organized base of knowledge, new information has nowhere meaningful to attach, so much of it is quickly forgotten.

Let's make this concrete, imagine a kid, let's call her Sara, she's learning the multiplication table[^memory-paradox], but she doesn't internalize it and think it's useless. Later when she studies division, she doesn't have any "baggage" with her, nothing in her brain, no structure that could help. when she sees 12/4 she does't "feel" it's 3, she never built that connection between 3, 4 and 12.
A more common example is trying to study physics without having good math skills, each physics problem becomes a two layer of suffering, you have to struggle through the math to finally reach the physics part, which itself might be challenging.
In CS this could trying to study Algorithms without having a good knowledge in discrete math, it's very painful.

When I'm learning something in FSO, I start to connect it to my HTTP knowledge and the toy server I built, I start to ask better questions and often end up new learning things and make connections that aren't explicitly included in the course itself.
And fundamental knowledge give you the power of surprise, and I'd like to quote my highschool math teacher[^math-teacher]:

> The problem with not having good fundamentals is that you can't differentiate between easy and hard problems on exam, everything is equally impenetrable.

That's what I mean by "power of surprise", it's when you start to notice behavior that first seems doesn't align with the knowledge and mental model you have built.

Which connects with the last point, strong fundamentals makes every new learning reinforce what you know, remember Sara? if she masters the multiplication table, later when she learns division (or more advanced concepts) that becomes itself a reinforcement of the fundamentals, and her knowledge quickly gets richer an richer.
Also, think about someone who studies grammar for instance, reading itself becomes a way to reinforce the grammar concepts!

So, TLDR: good learning might be slow, but it compounds really fast: the more you learn, the more you absorb from new experiences.

#### The forgotten side of learning from teachers

I had a Control Theory professor who would apologize when he interrupted a student in a discussion, "I'm so sorry for interrupting you", or "I apologize for interrupting you earlier, you may speak"
I didn't use to apologize when interrupting people! I said, ha! that's a nice thing to do, I'll start doing it too!

Even in online courses, one such moment was in [Programming Languages](#programming-languages-parts-a-b-and-c), when Dan Grossman said "people often confuse higher-order functions and first class function, _so we won't care either_", that had a lasting impact on how I deal with terminology.

One could learn much more than the course content. When you see a teacher accepting disrespectful critique and you see in their eyes that they are seriously thinking about it, whether there is some truth in it, or when they defend the partial truth in a claim they disagree with.

There is a lot to learn from good (and even bad) teachers, and it's hard (if not impossible) to learn such things from a book.

#### Do certificates matter?

You probably know that answer which is _no_, they don't matter much.

But I think that's not the complete picture.

Certificates could be a really good source of motivation. Human beings tend to love collecting stuff, that's why we love Pokémon for instance, and why kids love collecting badges in class, it's human nature.

After a long course, it feels nice to receive a certificate with your name on it. At least, it does for me. Maybe it's a weakness or some guilty pleasure, but I'm okay with that.

Some people don't care about that. They believe knowledge is worth pursuing in itself, and the real joy is in learning and seeing yourself getting better. Those are cool people, I'd love to be friends with them! but I'm not one of them.

So if having a certificate at the end of a course helps motivate you to complete a _good_ course, then paying for that certificate might be worth it. The value is not in the certificate itself. The value is in the motivation it provides.

I also found sharing certificates on Linkedin to be a little bit helpful. To some extent it says that you're at least putting some effort in your learning and maybe you take it seriously.

Having said that, don't overdo it, I see no meaning in sharing too many certificates, and for some reason the more courses I take, the less urge I feel to share about it, it's funny now remembering that I felt so happy that I complete the Systematic Program Design that I printed the certificate. But I'm glad such silly things makes me happy[^heidi].

Edit: After learning more about teaching and how we learn, it turned out _extrinsic_ and _intrinsic_ motivation aren't opposites. Extrinsic means of motivation like badges, certificates or praise from a teacher does have an great impact on the learner's motivation and gives them a reason to continue. At some point the learner won't need the external motivation anymore because they started to enjoy the material itself.
Barbara Oakley gives a sweet example which is how she motivated her young daughter Rachel to start reading books. She did something simple, whenever Rachel completes a book she would give her _money_.
Sometimes simple solutions do magic.

Because wasn't used to reading books, reading itself is painful, it's a fun activity -- but money makes it bearable. The key idea is that reading gets easier the more you read, and at some point it even becomes fun. And then, Barbara simply stopped rewarding her, there is no need for it anymore, she's already hooked into reading!

It makes so much sense when you think about it. So try to find the external means that could motivate you and make use of it.

#### The Trap of Projection

When we struggle for years because of something, maybe we had a healing journey and experienced immense emotional or intellectual growth --it's a great experience, something to be grateful for. But there is a subtle "bias": a trap one could easily fall into. It's when one thinks they "figured it out" and start to project their own past experiences onto other people's struggles. One would start to think _If only people did this or that_ (that is, reading a book, taking a course or changing their way of thinking in some certain way), that certainly would fix the problem!

I first heard this described by a psychologist I follow on YouTube, he was a bit harsh about it; he believes that such bad or incomplete advice could actually hurt others. It's oblivious of the fact that people's problems are so complex and different, whether in education, social problems or psychology. One has to be humble and accept the complexity of life's problems, _even if what we think actually has some truth in it_, we shouldn't assume we figured it out just because it worked for us.

It's a complicated feeling because when something helps you immensely, often you feel "I want everyone to experience this". But one has to take it easy, leave things to experts when possible and when sharing advice, we need to be more thoughtful about it.

Here are some examples I've seen: I recently read someone saying that "people are _depressed_ because of the toxic environments we live in, that's why people can't heal, that's why depression drugs won't work. If we want to be cured we need to change environment."

Anyone with some knowledge on _depression_ -- the actual depression disorder that is diagnosed by a professional -- would know that things aren't that simple. It's much more complicated than that and it takes experts to hopefully figure it out, each case could be different. And there is a distinction between prevention and treatment.

I caught myself doing this recently while writing a review for the [Web Accessibility](#introduction-to-web-accessibilitya11y) course. There is a clear projection of my own past struggles on other people's struggles.

One nice lesson I learned is that knowing the bias exists doesn't mean you won't fall into the trap :D.

This can also be seen in education, in course recommendations, for instance if you struggle with a topic you might think that's why other people struggle, but the reasons could be deeper.

### Learning Tips

#### Reflect on Your Journey

I heard about this quote from Dijkstra in Remzi Arpaci-Dusseau amazing [last lecture](https://youtu.be/sKTyhqvTUBU?si=QXNsu16k9FsAomPU&t=1079)of OS class, when Dijkstra said that _experience is not the same as wisdom_, to have wisdom you need both experience and _reflection_.
And it's easy to forget about reflecting on one's experiences (and life in general), sometimes it feels we've never been this distant from ourselves.
One of the reasons I wrote this entire README file was to reflect, I've spent three years in college and I wanted to know, where am I in this my journey in life.

I recommend reflecting a lot on your learning and the experiences you're going through, not only it makes learning itself more meaningful and fun, it also makes you appreciate the things you have, the teachers you learned from.

#### Enjoy small wins

> "Nothing more or less than the experience of experience itself" -- Eva Hoffman

Don't forget to enjoy small wins, whether you understand some new algorithm or concept, completing an assignment, it's worth some celebration. **Don't keep chasing completion and think you'll only feel happy when you finish the course.**
I'm speaking from my experience. I often find myself thinking about what to do next and forget to appreciate the present moment. Sometimes it's excitement, sometimes it's fear that I'm not doing enough.

> "People where you live," the little prince said, "grow five thousand roses in one garden... yet they don't find what they're looking for..." -- The Little Prince, Antoine de Saint-Exupéry

We often give this advice in a context I'm not fond of: "enjoy small moments" because it improves _productivity_. It's similar to telling someone to sleep well so they can work better. But that's not really what we're talking about. We're talking about the experience of living itself.

We often tell each other "take care" but we rarely stop and think what it means.
Don't be a person who never notices how good the food tastes because they're already thinking about what to do next.
Take care of yourself.

#### Most useful things I've learned so far

- **Meta-cognition**, taking Learning [How to Learn](#learning-how-to-learn) had such a compounding effect. I've described it in more details in the reviews section, but I'd add here: understanding how we learn gives you _EMPATHY_ for yourself and your learning challenges. Being able to see my struggles from above, to ask good questions about why I struggle at something and how to solve it, all while having _mercy_ on myself and struggles.
- English as a second language, I spent two years studying english extensively in highschool from good online resources, it helped me _tremendously_ throughout my journey, to easily read books, watch lectures, and understand nerdy jokes! I keep telling my roommate who's working on his English "it's the programming language of the future!" --[^dash] and we would laugh every time. Seriously, it's very important in this field.
- Learning Git early has helped me tremendously in so many different and unexpected ways.

#### Chunking in Computer Science

> Mathematics is amazingly compressible. You may struggle a long time, step by step, to work through the same process or idea from several different approaches. But once you really understand it and have the mental perspective to see it as a whole, there is often a tremendous mental compression. You can file it away, recall it quickly and completely when you need it, and use it as just one step in some other mental process. -- William Thurston

It's a very good skill to be able to identify the important _chunks_ of knowledge in the subject you're learning. I have learned about this concept of chunks from [Learning How to Learn](#learning-how-to-learn) and I think it's worth discussing here. (I must say that a complete beginner in a subject might not be able to identify the missing chunks, that's the role of a good teacher -- to create scaffolding i.e. divide the subject into small chunks and have students master them one by one)

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

Then go quickly to .notification-dot and set its position to relative.
That's a chunk, I don't even need to think about it anymore.
Those are some of the skills that make me write CSS really fast[^fast-css], it's not the memorization of css properties, it's actually drill that produces understanding and understanding that amplifies the drill.

This cannot be reached (efficiently) without two main components

- good "declarative" explanations from a good teacher who deeply understands the subject and explains it well.
- a lot of practice, "drill to skill"

Another example is one of the networking class I took, we were studying IPv6.
I noticed the professor was discussing the parts of the 128 bit address so smoothly, "let's take 48 bits of the address" then immediately highlight three segments of the address.
But my brain didn't create that chunk yet, that a part of the ip is 4 characters i.e. 16 bits.
It slows you down if you don't internalize it. It's a small example but I think it's the same pattern, missing some chunks could be why someone is struggling at something at the start.

It has become almost a habit (or a hobby!) to notice the things that take me time to figure out -- "Oh, I must be missing a chunk!". And it's not just about computer science, this concept of chunking is very general.

Here is an example, Arabic speakers use two calendar systems, The Gregorian Solar calendar and [Lunar Hijri](https://en.wikipedia.org/wiki/Islamic_calendar?useskin=vector), each have different month names. Many great books in our literature would use Lunar Hijri months, and I never learned them since we don't use them in my country, I never created that "chunk of knowledge".
The thing is, without that, when I read a book, let's say a history book, I have a vague understanding of months and I couldn't quickly map ideas to months, or intuitively understand how much time has passed, I need to make more cognitive efforts to do so.
This may seem like a trivial thing but I think it actually matters.

#### No perfect roadmap

> Information hunger, when it consumes a person, drives them to read everything trying to know everything—and they end up knowing nothing — Elmessiri

I have long lists of courses about everything, sometimes my friends joke about how when I talk to someone about anything, I'm probably gonna suggest a course, "oh right, that day I saw this free typography course", "last night I've seen this awesome course about children learning problems", "ooh! did you see this new free Helsinki course?" well, it's kind of a hobby -- almost.
And especially when the first year in college, I felt really, really distracted, I felt had a million thing to learn, I keep planning and planning and imagining the "perfect roadmap" that I'll use this summer, I keep comparing courses endlessly.
It took me a while to realize that I'll never find this perfect roadmap. what matters at the end of the day is that you pick some high quality course taught by a good instructor, and stick with it. that's it. there is no point in overthinking it. It's important to accept the fact that you won't learn everything, and there is no course that will teach you everything about something, there is no point in endless comparisons.

### Practical Tips

#### Don't Neglect Code Style

I remember watching the first couple of lectures of CS50 at summer after high school (though I didn't complete it), the instructor David Malan just pointed out briefly that he puts the colon right after the end of the if statement, with no spaces
i.e. `if some_condition:` and not `if some_condition :`
It was the first time I thought about it and I just started to notice how people write code and how it differs from one language to another (and even between people using the same language).
There are indeed tools like linters and code formatters that automatically format your code but I think it's worth getting in the habit of writing organized code. In first years of college, a friend of mine sometimes would write code like this:

```py
if x==10 and y< 15  :
  print("hello" )
```

I convinced him it's kind of a problem by saying "imagine writing such code in a coding interview". He told me it was a bit challenging at first to change the writing habits.
That's why I think the earlier you realize that there are some "good" code writing habits, the better.

Another is realizing that consistency is looks so pretty, that's why we have conventions, try to start noticing in people's code, files, etc. for instance I prefer filenames to be lowercase with dashes, e.g. `integration-test.js`, I've heard some consider a bit ugly, but that does't matter because when you have tens of files following the same convention, somehow it starts to look so pretty and organized. Same goes for git commits too.

#### Use a REPL

It's basically like the JS console on the browser dev tools or when you write "python" in the terminal and press enter. That interactive shell is called a REPL (Read Eval Print Loop).
You should use a REPL, most languages have ones! even statically typed languages! Java has JShell and C# has a REPL integrated in Visual Studio. They are great for testing small pieces of code, Regular Expressions, date functions, ASCII codes, etc.
They are extremely helpful to quickly verify what an expression _evaluate_ to, which is very helpful especially when learning a new language.

#### Using Flashcards (Anki)

I LOVE flashcards, like, they are my favorite learning tool.
I've been consistently using Anki since 2023.

![Anki Heatmap](/media/anki-heatmap.jpg)
(you can install the HeatMap extension to see a graph like this in Anki)

[Flashcards aren't perfect](https://youtu.be/ZIGrHI353no?si=E2RK8erEaAiKGr82) and it's better to think of them as one tool in your arsenal as a learner. I find flashcards to be the best and most efficient way to memorize something and be able to _respond to a cue_.

But I also find flashcards useful to review concepts and not just memorization, for example I have computer networking questions like "Explain how DNS works, let's say you write google.com and press enter, what happens", the idea here is not to memorize the answer but to do retrieval practice and explain a concept, I usually explain the concept out loud and have a pen and paper where I sketch the concept. Flashcards are also often [recommended for interview prep](https://github.com/jwasham/coding-interview-university#2-use-flashcard).

Many people find using flashcards to be useful for computer science and I think you might find them helpful.
You can use flashcards for anything, from memorizing the names of flowers, preparing for a driving test, to computer networking classes at university (I kept getting perfect grades in those classes using just flashcards, and for _some_ classes I literally take notes in class, go back home, turn the notes into flashcards, and throw the notes in trash -- which might be an act of disrespect to knowledge, but I'm not sure and... I find it satisfying!)

I want to mention some mistakes I made along my journey of creating flashcards.

- Don't mix flashcards that are very unrelated, like flashcards about computer networking and security in the same deck.
  - If you mix too unrelated flashcards you'd miss the benefits of _interleaving_.
- Do not keep taking notes forever then start to create flashcards: it's much better to make flashcards along the way, and review them constantly.
  - DO NOT let flashcards become an illusion of learning, oh I made flashcards, I'll review them later! Do retrieval practice _as you're studying_, stop the video you're watching or the chapter you're reading and try to recall the key ideas from memory.
- You're not expected to review ALL flashcards that are due, consistency is what matters, and this is why the previous point is important, just the act of creating good flashcards and reviewing them instantly can boost your learning a lot.
- It might be better to avoid using AI tools to make flashcards, there is a lot to learn just by trying to formulate a good question.

One tool I find very helpful for making flashcards is [ShareX](https://github.com/sharex/sharex), a free and open source screenshot tool. It has a "Smart Eraser" feature that lets you annotate or remove parts of an image on the fly, which makes creating image-based flashcards a lot faster.

IMPORTANT NOTE: You don't _need to_ use Anki
I realized after someone sent me a message telling me she was struggling with Anki and needs advice, and the message felt heavy -- as if she felt bad for not liking Anki. And it's understandable because when you're starting out and you see someone saying "I LOVE Anki and it changed my life" it's natural to feel you're missing out something important.

Please don't burden yourself, if you end up not liking Anki that's totally fine. It's just a tool and there are so many different techniques for learning.
That said, if you haven't used flashcards before, I do recommend trying Anki.

#### Taking notes

I recommend that you take notes on your computer sometimes, while research says taking notes on paper leads to better learning, but I think it's useful to take notes on computer occasionally. I really like Obsidian, markdown is awesome. I also take notes (README files) in VS code, if you do make sure you install the linter like `markdownlint` and maybe a spell checker, they help a lot.
Don't worry too much about finding the perfect writing system, you can spend weeks trying different note taking tools and systems and comparing them, I spend some time in that rabbit hole, going from tool to tool, but it's not worth it.
Also, a quick note: while taking a course, be careful not to just copy paste things from the course into your notes, that's an illusion of learning, equivalent to highlighting everything a book you're reading.

I also found it to help you get used to writing on computers in general.
I write quite well on computer (around 60 WPM) and I think it's partially because I spend a lot of time taking notes on my computer.
I've noticed that many students still look at the keyboard while typing, it's normal at first but it's really worth trying to get used to blind typing.
A friend of mine told me he used a website (link) to improve his speed and in a couple of months he's as fast as me (but it took me years :D)
So it's very learnable with some good instruction and practice.

Finally, The Pragmatic Programmer recommends having an Engineering Daybook you always keep with you, basically a notebook where you write stuff you learn, problems you face and tips and tricks. I found it really useful and makes learning more fun.

#### Using the command line

After learning Git in the summer, I went to some of my friends and classmates who study CS and told them: "I'm going to force you to learn Git". I don't want to work alone!
One thing kept happening over and over: whenever I explain how branches work and how we switch branches, and I show them how files do change in the working directory (using `ls` command -- in either WSL or git bash), they would nod and think it makes sense. Then I open the file explorer (finder) and show them that the files DO change; they go quiet for a second, _WOW!_ they says (in fact I had the exact same experience when I first started learning git). It's as if the command line isn't something concrete.
The way I see it is that Windows does things for convenience that kind of distorts one's understanding, like, before I used to believe file extensions were something special
when I was starting out I used to think it's impossible to name a python file "script.mp4", how could that be! even VS code won't color it for you! -- I think it has something to do with what happens when you change the file extension in the file explorer you get a popup saying your change would make the file unusable.

I recommend getting comfortable with command line as early as possible, it doesn't just improve your productivity, but it also offers you more opportunities for learning.
If you're a Windows user and don't want to switch, try having a dual boot (i.e. installing both Windows and Linux on the same machine, you get to choose which one to start), and make sure to install [WSL](https://learn.microsoft.com/en-us/windows/wsl/install). I use a custom shortcut Ctrl + Shift + V to start WSL using [AutoHotkey](https://www.autohotkey.com/).

When I realized the power of command line, I went to pretty much anyone I knew and installed zoxide and fzf for them. (seriously, you should try them out)
I created a /projects folder, and told them they can simply type `z proj` to go to it and create a folder for each project, and simply open it in VS code (code .)
And Windows users like me have an itch for opening the explorer (finder) for some reason, so I created an alias called `opend` which opens the current directory in the explorer.
That alone made them enjoy using the command line and motivated them to learn it more.
So based on my observation, I believe that many people detest the command line simply because they never saw a real workflow, even a simple one, anything concrete that makes them feel it's worth learning.

#### Some ways to have fun

I think having fun is an important part of learning, one shouldn't spend all of their time studying or they'll burn out, which isn't good -- _not_ because it reduces performance in long term -- but simply because it's not good for a human being to feel burned out.

There are many ways to have fun, I won't share the usual stuff, but small things I found enjoyable:

- **Documentaries** could be a great way to both enjoy and learn new things about the world we live in. Here are some documentaries you might like:
  - [Schooling the World](https://youtu.be/oDxYWspiN-8?si=-yFHsgKSNJOepC4c)
  - [The True Cost](https://youtu.be/rwp0Bx0awoE?si=aoELpl9FEzc9Y5l6)
  - [Revolution OS](https://youtu.be/k0RYQVkQmWU?si=Yk1SoEyUWCdlCXcU)
  - [A Trip to Infinity](https://youtu.be/CNFm_DzHDaE?si=NNK-PDkLVEYLCgGJ)
- I rarely watch movies anymore, I can't remember the last time I watched one actually, but these movies have a special place in my heart.
  - The Flavor of Green Tea Over Rice (1952) -- Ozu
  - 12 Angry Men (1957)
  - My Neighbors the Yamadas (1999)
- Plant Identification:
  - Another really fun activity I've come across is identifying plants! iNaturalist is a great app to help you identify plants you see in your daily life (Be aware that other people may be able to see the location of the pictures you take)
  - Knowing the names of the plants and flowers you see everyday makes each walk a more rich experience[^flowers], you'd start to notice how plants change from season to season. All of this even reminded me of how when you learn CS concepts and terms (e.g. abstraction or evaluation) you start to see things differently!

## Course and Book Reviews

### Systematic Program Design

Also known as [How to Code: Simple Data](https://www.edx.org/learn/coding/university-of-british-columbia-how-to-code-simple-data) and [Complex data](https://www.edx.org/learn/coding/university-of-british-columbia-how-to-code-complex-data).

I'll start with a vent, when we tell a beginner "you should think like a programmer" or "focus on problem solving and not syntax", we're not helping them! It sounds like a good advice but it's useless!

Ok, This course is really amazing, I didn't realize how important it was immediately.
I used to hear that "you should learn functional programming because it will change the way you think about programming" and so on, but I never found someone explains why explicitly. After taking this course and observing what changed after completing the course, I think I have a pretty good idea about what's going on. Yeah, functional programming -- and this course -- might rewire your brain!

This course taught me how to _think_ as a programmer, and one important ingredient for good thinking is a set of good words.
The course teaches very fundamental concepts, the difference between _values_ and _expression_, and what _evaluation_ means. It's really fascinating how pretty much everything else is built on top of those simple concepts!

I noticed that now when I see a new piece of code, my brain now immediately asks: wait a minute! how does that evaluate, what does it evaluate to?

```python
results = df
    .filter(col("city") == "Tunis")
    .select("name", "age")
```

Recently I was learning the basics of SparkSQL in Python, when I first saw that expression, my mind errored out!. What does `col("city") == "New York"` evaluate to?!
It _can't_ be a boolean, it would be useless information to the filter method.
It must evaluate to some sort of an object or function! Suddenly it doesn't seem like magic.

Functional programming also taught me that we can think of everything as a function. Combined with the previous point about evaluation, it completely changed my perspective about many things.

Here's an example: In my second year into CS, I was learning about promises in JavaScript -- a quite challenging concept -- I would see some code like

```javascript
let p = fetch(URL).then(f1).then(f2);
```

It didn't click; most tutorials didn't explain what was going on. and I didn't even blame myself for not understanding, I felt, man those tutorials are doing something wrong! _they don't explain how things evaluate!_

what I was seeing is the following:

```
let p = dot(dot(fetch(URL), then(f1)), then(f2))
```

I kept asking myself: what does `fetch(URL)` evaluate to? And what happens when I call `then(f1)` on whatever that evaluates to, and so on? After some time and thanks to some good resources, it clicked. And once I understood how things evaluate, everything made sense, it became really simple: I was even capable of writing my [own version of Promise.all function](https://gist.github.com/elfaidi-ghassen/afcbe60ca9039d74be93d568c01bc19e), which is considered a quite advanced.

Systematic Program Design (_AND_ the [Programming Languages](#programming-languages-parts-a-b-and-c) course -- see next) taught me to _ask the right questions_ and to feel deeply unsatisfied when I don't fully understand how expressions are evaluated.

A year after taking SPD, I noticed that it even changed the way I see math.
For example in my Optimization class at university, we studied tons of Linear Programming problems, when I'm faced with a homework problem or in exam, I found myself spending like 10 minutes trying to _understand the data_ (a key idea in SPD)

Here a very simple example, let's say we have a graph `G=(V, E)`
I start to think, what does V and E evaluate to?
I see it as `G=({1, 2, 3, 4}, {{1, 2}, {2, 3}})`

And then writing the following seems obvious:

> for all e in V, for all i, j in E, ...

Understand the shape of data actually helps in problem solving.

I also believe my math skills in general improved a bit thanks to that course.
I remember I was stuck in a problem in a probability exam, it was hard, then I started _making examples_ (another key concept in SPD), imagining the "data", the shape of input, and suddenly it clicked -- at that moment SPD immediately crossed my mind and I felt so happy.

Finally, at the very least, I think studying that course will help you get the most out of the Dan Grossman's Programming Languages course, which is by far the one of the best and most useful course I have ever taken.

Gregor Kiczales isn't that kind of professor who says "this course will change how you think forever", it seems he is way too nice![^nice-gregor] he's not a marketing guy.
But you should trust the teacher! learning is a relationship, you're not "self-taught", if you can't trust the teacher and material, it's harder to learn well.

I still remember when I was taking this course in the summer of first year at university, I would see some of my friends and classmates studying React and talking about fancy new technologies. Honestly it was painful and sometimes I'd feel I'm wasting my time. I think I could have learned even more, or at the very least, had more fun while learning, if I trusted the material more.

_The Bottom Line_: I think this is one of the best introductions to programming one could have.

### Programming Languages: Parts A, B and C

> but if you have big ideas, you have to use big words to express them, haven't you? -- Anne of Green Gables

This course will take the foundation and intuitions you built in Systematic Program Design and offer you a mesmerizing experience through the realm of programming languages.
This is probably the most _useful_ online course I have taken yet. Dan Grossman is such a great teacher, his love for programming and programming languages is contagious!

The course uses three languages ML, Racket and Ruby to teach so many important ideas and concepts in programming languages. By the end of the course you'd start to see programming languages very differently.

The course starts off with some _really_ important definition like what's an expression, a value.

> A value is an expression that evaluates to itself

That is one of my favorite definitions in computer science, it's so beautiful and elegant.

**Tip**: Make sure you focus on those new terms and understand their definition well, everything is built on that foundation.

Also, the first time I hear the term _binding_ was in this course, and I didn't get it at first.
For example a statement like `x = 10`
I'm used to hear terms like _assignment_ or _we assign x the value 10_, but professor Dan used the term _binding_ or _to bind x to the value 10_ or _x is bound to 10_.

Basically a binding is a _mapping_ (which is also a very useful term in CS and Math, think of a hash map or dictionary, you _map_ keys to values), i.e. "to map x the value 10", this is important because we can bind _names_ to _value_, it's a _more general_ concept than assignment.

For example, when you define a function, you're also creating a binding. Same when you import a function in python for instance:
`from math import sqrt`
That statement creates a binding, i.e. it maps the name sqrt to the function (object).

This will become even clearer when the concept of _environment_ is explained. (It's often called "context" instead in the JavaScript world)

One of benefits of the course is that it helps you build a powerful vocabulary of terms and concepts to discuss programming languages and programming problems with high precision, I felt like I'm a more mature programmer after the course.
For instance I wrote this [question](https://stackoverflow.com/questions/79537353/how-does-the-left-hand-side-lhs-of-an-assignment-evaluate-in-c) on StackOverflow trying to discuss a problem I found when trying to understand how pointers evaluate in C (I used to think C is a normal language :D), I didn't use to be able to articulate my thoughts about programs like that before, it's a learnable skill.

Warning: I didn't study OOP in depth well before PLABC, so it was my first serious contact with OOP and I must say it was quite challenging, some particular concepts didn't click much, I had to redo some parts of the third course while studying Java later, and it made much more sense. So unlike what the course suggest, I actually recommend learning OOP in some statically typed language like Java or C# first, I think it would improve you learning experience.

I really love this course, and perhaps this review won't do it justice, I loved it so much that I printed all the lecture notes (around 200 pages) and went to some library to bind them so that I can keep it with me. I've read it twice since then and each time it blows my mind.

![alt text](/media/plabc.jpg)

> The purpose of software is to take simple language constructs and combine them with human ingenuity to create complex systems. -- Dan Grossman

_The Bottom Line_: Just take this course! it's such a unique learning experience.

### Operating Systems: Three Easy Pieces

Book by Remzi Arpaci-Dusseau and Andrea Arpaci-Dusseau.

- [Book website](https://pages.cs.wisc.edu/~remzi/OSTEP/)
- [Lecture videos](https://pages.cs.wisc.edu/~remzi/Classes/537/Spring2018/Discussion/videos.html)

The OS is such fascinating piece of software, it's very complex and full of engineering wisdom. That's why studying Operating Systems is an extremely important part of CS education.

I'll give you an example why studying OS is helpful, at some point in other courses you might learn what the definition of a compiler is:

> a compiler is a software that _translates_ the source code into a different representation (target code).

That's an absolutely correct and beautiful definition in my opinion, but it's very abstract (in a meaningful way)

But I found that studying OS gave a new lense to look though when it comes to thinking about other concepts.
For example, you'll start to see clearly that a compiler is just a _program_ (i.e. a file in the filesystem that contains instructions), that you can _run_ it using the APIs provided by the OS. So the program becomes a process (a running program), and that running program will simply `read` the source code file and do some transformations to it, then `write` it back to another file.
It takes time to build this understanding but at some point it becomes automatic. Whenever you see a new piece of software or idea, you start using the concepts you learned in Operating Systems to reason about it.

OSTEP is a very great book, it's very lighthearted and made me laugh out loud so many times, it has succeeded in turning a topic that's often considered boring into a very fun experience.

The book is divided into three parts.

1. Virtualization

- You will learn about two really important concepts, the process and memory abstractions...
- I didn't find the CPU scheduling part that interesting, I just skimmed them (I've already studied those algorithms a lot in a OS class I took in college, it was SO boring!)
- After completing this part, I _HIGHLY_ recommend building a _shell_ (e.g. in Python). Building a shell is a very rewarding experience, you'll start to see processes differently!

2. Concurrency

> It is a wonderful and hard problem, and should make your mind hurt (a bit). If it doesn’t, then you don’t understand! Keep working until your head hurts; you then know you’re headed in the right direction. At that point, take a break; we don’t want your head hurting too much. -- OSTEP

- I took a more advanced OS class in college and it focused a lot on concurrency and sadly I didn't understand much from it. I really needed to pass that class, so I decided to focus read the concurrency chapter, it was challenging but really fun to read. I remember spending an entire week reading it like crazy, each time someone knocks the door and asks me what I'm doing -- "I'm studying OSTEP!" -- I remember even skipping the class a couple of times, I'd tell my roommate "You go understand what's going on there, I'll keep reading OSTEP", then we would meet, and try to understand this puzzle. It was really fun, and OSTEP is actually very accessible and down to earth.
- I absolutely think you should read this chapter, it contains some very important concepts and terms (e.g. thread-safe, atomic operations, etc) that you should know. The book starts with a great example (incrementing a global counter that has a special place in my heart, that example made everything fit together and made me realize what a wicked problem we're dealing with)

3. Persistance

- It's all about I/O, how we store data persistently, e.g. in HDD, and the software part in OS that handles all that. It also explains the file system API, I found it pretty neat.
- I especially loved the first sections on how I/O devices actually work, I really liked the mental model, that is, seeing how devices like hard disks or a mouse actually contains registers, and how the CPU will read and write to those registers to issue operations, etc. (Similar to how keyboard and screen work in Nand2Tetris)
- For this part I also watched some lecture videos instead of reading some sections, the lectures were a pleasure to watch, they cut to the chase and Remzi's teaching style (and humor) is top notch.

Overall, OSTEP does an amazing job at building intuitions and making intimidating OS concepts to feel really straightforward, you see it everywhere in the book, and I think that's what good teaching is about.

_The Bottom Line_: This book somehow managed to make a topic like Operating Systems... fun! and that's no small achievement!

### Computer Networking: A Top Down Approach

Computer networking is one of the most rewarding topics to study in computer science, you get the benefits _instantly_! you suddenly start to understand those networking terms you hear everywhere. It's almost hard for me now to remember life where I didn't know those terms and concepts!

I wasn't very satisfied with my university's approach to computer networks, it was a bottom-approach and kind of boring.
So I picked up Computer Networking: A Top Down Approach, and boy I'm glad I did, it's one of the most the best learning experiences I've had in computer science (I think I've said that too many times in my reviews! but hey! perhaps that's a good thing!)

The book is accompanied by A LOT of extra content, the [wireshark labs](https://gaia.cs.umass.edu/kurose_ross/wireshark.php) in particular are a must, I highly recommend that you print the labs and annotate them, it's much more fun! (I actually think a printer is a great investment for learners!)

I highly recommend the book (or the [videos](https://gaia.cs.umass.edu/kurose_ross/lectures.php)), I think the first two chapters alone are more than enough to have a very good understanding of networks, in fact by chapter 2, if you do the [projects](https://gaia.cs.umass.edu/kurose_ross/programming.php), you'd have built a HTTP server, SMTP server, UDP ping, and a proxy server from scratch using socket programming.
This book has a special place in my heart, when I was reading it I realized [I love computer science.](#short-story-the-day-i-fell-in-love-with-cs).

Here are some things you can learn from the course:

- When you type `google.com` and press enter, you'll know exactly what happens behind the scenes.
- You'll understand those terms you keep hearing everywhere, Router, MAC, IP, DNS, etc
- You'll deeply understand what's is a server, you'll even implement your own servers, and understand what it means for an application to be on the internet?
- You'll understand what the internet is and how it works
- You'll learn about protocols and realize they're just a bunch of standardized text files, and that people implement them (e.g. browser implements the HTTP protocol)

Some Tips:

- When you read the DNS section in chapter 2, buy a domain name from a registrar (e.g. Namecheap)
  - It's around $10 per year, but what you learn with stick with you forever!
  - If you're a student at some university try getting a domain in [Github Education Pack](https://education.github.com/pack) for free.
  - You can for instance host a static website on Github Pages or Cloudflare Pages (for free!), they'll give you something like `yourusername.github.io`. You can easily change it to the domain you bought, you can think of it as pointing your domain to that default domain github gave you.
  - remember, if you buy a domain like `yourname.com`, you can add as many prefixes as you want, you can create sub domains like `blog.yourname.com` or basically `ANYTHING.yourname.com`, and even an email address like `pm@yourname.com`
  - Also, at some point later it might be also worth getting a VPS (basically a server you can SSH into) where you can practice even more.
    - [landchad](https://landchad.net/) is a nice little resource that explains how to do it and the basics of managing a VPS and hosting whatever you want.

_The Bottom Line_: What can I say? this book is so dear to me, and I can't recommend it enough!

### The Missing Semester

So, the course is great, but here are some practical tips that might help.

- If you are a Windows user, it's recommend that you install linux alongside Windows (it's called Dual boot), you'd be able to choose which OS to run when you start your computer.
- Or at the very least, install WSL. (like seriously, you must[^must] do that)
- Make it the default shell in the terminal so that when you open the terminal app it's there
- make the terminal maximized by default
- install AutoHotKey and create a shortcut e.g. Control + Shift + Enter to open the terminal, it's very convenient.

```
^+Enter::
    Run, wt.exe ; windows terminal
```

- understand the difference between the Shell and Terminal
- understanding how PATH works is **VERY** important, it's a key idea.
- I highly recommend building a shell (at some point), it really helped me internalize the concept of a process (from OSTEP)
- you probably should install _zoxide_ (I can't count the number of people I know who started to love command line just by trying zoxide)

![alt text](/media/zoxide.gif)

- you can open vscode in the current folder using `code .`
- I really like `tldr` command, much simpler than the man command, it cuts to the chase and more than enough for most cases.
- I mainly use bash on WSL, you can also try zsh + ohmyzsh, it's cool, but it's really slow on WSL.
- The notes in the first lecture contains other cool commands you can install like `bat` and `eza`
  - remember you can create aliases for instance to make `ls` execute `eza`
- If you use Windows Terminal, it has lots of nice shortcuts for splitting the panes, it's very useful and much better than having multiple tabs, I found this useful especially in web development.

![terminal](/media/terminal.jpg)

- Don't forget to use `tab` for auto completion, you need to consciously use it at first until it becomes a habit.
- You need some way to open files from terminal, you can do it like this in WSL: `alias open='cmd.exe /c start'`
- I have an alias called `opend` which is same as `explorer.exe .`
  - It's useful sometimes to open the current directory, e.g. you want to drag and drop a file to some site.

### Nand2Tetris: part 1

The part 1 projects and learning material are freely available on the [course website](https://www.nand2tetris.org/course).
I finished it in less than around 2 weeks for a simple reason: at that point I had already taken many courses at university that teach boolean algebra and computer architecture concepts that are more advanced than N2T, I've studied transistors in depth in electronics classes, how we build logic gates using CMOS technology, using K-Maps, and sequential logic in more depth. _Yet... I didn't understand how a computer works_!

(That's perhaps one of the problems of CS education: how courses are often disconnected and leave students confused; This course made me feel _deeply sad_ about the state of education in my country)

So, in a spring break I thought it's time to understand what's going on here.
The course starts by explaining a _very_ important concept in computer science -- abstraction, and basically gives you a taste of every layer of abstraction starting from basic logic gates. The course connected the missing dots and suddenly computer science became really pretty.
(NOTE: You _do not_ need previous knowledge on boolean algebra and logic gates to study this course)

I documented the journey of building the CPU in my notebook, and I even counted the number of transistors (A NAND gate can be built from 4 CMOS transistors, and from there you can count the transistors bottom-up)
I ended up with 15912 transistors for the CPU and 24 MILLION transistors for the 16K memory!

This is where I first understood the concept of _abstraction_ and APIs.
It's a very powerful and central topic in computer science yet it's rarely explicitly explained.
Abstraction is a complex topic in other fields like philosophy, but in programming it's fairly straightforward, but it's not simple from the perspective of a beginner!

I think I understand why it's hard to accept the definition of an API.
I tried this before: go to a first year CS student, tell them a common definition of an API or abstraction, they probably would feel it's vague and unclear.
And I think it's also in part a problem in how it's often explained, some explanations would say "it's like a contract between two systems", some use analogies, but I don't think really helps.
It seems to me that the concept of abstraction doesn't really click only after seeing a lot of examples of abstractions in Computer Science (with an initial good explanation of what abstraction in CS is all about)

I had this class in college about basic information theory (and some image processing). One of key concepts was the idea of an alphabet.

> an alphabet is a finite set of symbols.

It took me _quite a while_ to fully get it, there was some dissatisfaction in my mind for some reason, then I realized, it's all about abstraction!
a symbol can be ANYTHING. And that abstraction is very powerful because once you prove something is an alphabet (it's straightforward here), you can use everything all the properties of an alphabet and the nice ideas built on top of it, for instance you get the idea of strings for free.
This is analogous to _implementing_ an interface in a OOP, once you do that you can pass an instance of that class to any method that expects that interface type, for free!

This idea of mathematical abstraction is very powerful. It makes the math useful in so many different contexts, you'd just need to _prove_ it's a language or it's a linear map (in linear algebra), then you could use all the theorems and cool stuff built on top of it. 3Blue1Brown explains it beautifully in [this video](https://youtu.be/TgKwz5Ikpc8?si=-K7ctr-oQN93NbMI).

At some point, after seeing so many abstractions, I suddenly felt comfortable dealing with it and started to appreciate it instead of finding it threatening.
For instance, using term _name_ instead of _variable_ (like when we say a _name_ is bound to a value), it's like forgetting all the implementation details and only thinking about the higher order concept of naming things, something humans like to do.

_The Bottom Line_: Understanding how a computer works and going through the layers of abstraction is one of the best parts of CS education.

### Learning How to Learn

- [Coursera](https://www.coursera.org/learn/learning-how-to-learn)
- Based on the book [A Mind for Numbers](https://www.amazon.com/Mind-Numbers-Science-Flunked-Algebra/dp/039916524X)

Back in highschool, I remember spending some time watching Youtube videos on learning tips, on how to take good notes, the pomodoro technique, best note taking app, and even reading [some books](https://www.amazon.com/Great-Student-Kimberly-Hatch-Harrison/dp/B091PR82QF) on learning tips.

It wasn't "life changing", but it exposed me a new world I didn't know about! before, I didn't even know it's a good idea to think about how you learn and try to improve the process.

In the summer after my first year at college I took Learning How to Learn, I was very surprised that it was different from everything else. It wasn't just some random tips, it's an entire mental framework on how the human brains learn that helps you diagnose your own learning problems.
Learning How to Learn had a deep impact on my entire learning journey -- and even this README itself.

After taking it, I started to find myself always taking notes and reflections about my learning (a process often called Metacognition) and trying to understand why we struggle at some specific concepts.

The course contains some interview with many interesting people including Scott Young -- known for his books and the awesome [MIT challege](https://www.scotthyoung.com/blog/myprojects/mit-challenge-2/), I really enjoyed these.

And I know that correlation does not mean causation, just after completing this course in summer, my grades the next year really improved and I somehow managed to get the second in my class.

_The Bottom Line_: A great course that helps you build a mental framework to understand how you learn and why you struggle at times. Highly recommended!

### Mindshift

- [Coursera](https://www.coursera.org/learn/mindshift)

The full title is _Mindshift: Break Through Obstacles to Learning and Discover Your Hidden Potential_...
My God! isn't that a cheesy subtitle, it hurts my heart!
But rest assured that the course itself is actually excellent.

This course is not about learning techniques, but on having a learning life style. It discusses topics like passion and why it's important to understand the real world constraints around you (And not blindly "follow your passion")

> What you feel you are best at isn't necessarily **all** that you can be best at

The course also discusses the value of your past knowledge and experiences, it made me realize that even if programming skills won't be needed in the future (perhaps because of AI), I already learned -- and still learning -- a lot of things from this field.

> Seemingly unconnected knowledge from your past can bring unexpected assets to your work in the present

It also covers why it's important to have second skills, and normalize the idea that you might actually end up doing something else, and maybe have a Plan B.
Knowing that you have a backup plan actually helps you focus more on what you're currently studying!

_The Bottom Line_: Full of interesting insights I've never heard before, a very mature take on passion and learning in general, I recommend it!

### Uncommon Sense Teaching

<https://www.coursera.org/specializations/uncommon-sense-teaching-certificate>

> "Learning isn't always fun"

When I was in high school, for some reason I wanted to become a history teacher -- I literally hated my history class so much that I thought if I become a teacher I want to make it more fun!
But yeah, teaching history doesn't bring food on the table.
But I've been into teaching, I really enjoy it when I explain a concept to someone and they understand.

I had many reasons to take this course, not only I wanted to have a better understanding of good teaching and education, I really believe improving one's teaching skill is a great idea because we're all teachers in a way or another, be it at work explaining something to a colleagues or at home understanding why your children are stuggling at something.

In Uncommon Sense Teaching, an engineer, a neuroscientist and a teacher teamed up to create one of the coolest learning experiences I've ever had the pleasure to see.
I remember once having to take a small course about creativity, but the course was SO BORING AND UNCREATIVE.
Uncommon Sense Teaching is different! it actually applies the teaching advice it gives in the course itself!

The course also taught me about the trends in education, and how it's really complicated issue.
I still remember in primary school when one of my teachers said "The student is at the center of the educational process", I had no idea it would be related to the Constructivism movement in the West!
It's fascinating how ideologies and philosophies affect our lives without even knowing about it.

The course contains a lot more content that Learning How to Learn, more teaching concepts scaffolding and differentiation are well explained, some information about child's development, classroom management and many insights from Neuroscience.

> The art of teaching is making learning seem worth the effort, even when it's difficult.

The course was full of "uncommon sense", advice that is based on research.

> Students give up in their studies not because they don't have 'growth mindset' or are 'distracted by technology'—they don't know how to learn

The section about anti-bullying programs was so shocking to me. To see that institutions implement untested programs that are unhelpful or even harmful made me wonder: why don't we care enough about what we claim we care about?

> "Beware of training programs that don't work. Just because 'everyone' is doing the program or it's conducted by a professor from a prestigious university does not mean it is properly vetted or helpful."

One thing I also really liked about the course is the sheer amount of recommended resources, tons of books, videos, research paper.
Kinda a bummer I can't spend too much time on all of that!

_The Bottom Line_: If you only need to take one course on teaching, this probably is the one.

### Making Math Click

> My problem was not with math, my problem was that nobody told me how the brain works and that it's totally normal not to get something the first time you see it -- Barbara Oakley

Another nice course from Barbara Oakley and John Mighton, the course touches on many of concepts taught in learning How to Learn and Uncommon Sense Teaching, there are very few new insights honestly, but seeing the ideas again but applied to math is really interesting. Though the examples are very basic -- how we should correctly teach basic elementary math and geometry, but I think the advice can be applied in more advanced topics.

_The Bottom Line_: It's a very good short course, but if you've taken the other courses you might find the repetition a bit boring. It's seems to me it's mainly for teachers and parents who want to help their children with math.

### Machine Learning

<https://www.coursera.org/specializations/machine-learning-introduction>

This was a very enjoyable course, one of the most gentle courses I've taken. It gives you a taste of all the major ideas in machine learning, and what you learn is instantly applicable, while taking the course I was also starting to get into web development, so I actually built simple API endpoints for a handwritten digit recognition website with a friend, we even deployed it -- it was a fun little experience.

The course cleared up some major misconceptions for me:

- I used to think Machine Learning is all about math, but it turns out it's very experimental nowadays, the libraries abstract away many details and you can simply think in terms of the API the library gives you and tweak the model parameters. (The course also teaches model evaluation and how to improve the performance in great details!)
- I used to think that neural networks in machine learning were heavily inspired by how the brain works. Andrew explained how different they actually are, and how still to this day don't really know how the brain works.

I really appreciate how down-to-earth Andrew Ng is as an instructor. He openly shares the reality of Machine Learning in industry without the hype. One time he explained how he Deep Learning is just pretty much a re-branding of neural networks, and how surprised he was back in the day by the powerful impact of the re-branding.

He also gave me a better understanding of current limits of AI. In one of the optional interviews in the course, it was explained why training robots is actually extremely hard, and we still fail to create robots that generalize well -- the path to AGI is very difficult. If you see a cool robotics video online, it doesn't mean they're actually practical yet. The same goes for reinforcement learning; it's amazing in simulations but incredibly hard to get right in real life.

I think this kind of knowledge is crucial, it's important to understand the limits of the current tools. How can we aspire for a "better future" if our understanding of reality is distorted, we still have a long way to go. And honestly Machine Learning is so cool and useful on its own, we don't need the hype!

You don't need much math for the course, high school math is more than enough, the toughest it gets is doing some partial derivate, and even that is in an optional section on the course.
I also recommend keeping some notes on the notation, write down the formulas and explain what each symbol mean, it's easy to get lost reading formulas because of those superscripts and subscripts!

Andrew explains the concepts really well, my only real complaint is how gentle the course is. Sometimes the programming assignments were extremely easy, which left me feeling a bit unsatisfied. But if you think of it as an serious introduction to machine learning, it's really good.

_The Bottom Line_: An very gentle introduction to Machine Learning, it's very enjoyable, and Andrew is great at explaining concepts intuitively.

### Meta Version Control

While this course is targeted for absolute beginners (I was the target audience!) yet it's too shallow and won't make you better at Git, there are many better [alternatives](#head-first-git) out there.

I'd say this course is the opposite of "down-to-earth teaching" I keep praising in other reviews. It feels like it's shot in a cool looking studio where every piece of furniture and decor was placed with utmost care -- yet the content itself is hollow, and leaves you with this feeling of emptiness I can't describe.
It reminds me a lot of the Alberta's Object-Oriented Design course: it says so much yet nothing, at same time.

_The Bottom Line_: Avoid this one.

### Head First Git

I love the Head First series, even though it's full of silly drawings that I don't really care for. The content itself is often superb! Head First Git contains some of the best explanations and analogies for Git I've ever seen, I left the book with clear mental model of how Git really works and how to actually use Git and Github in practice. Since then, I've even started to collaborate on open source projects!

I tried to learn Git around three times before, In High school I watched some youtube playlists, and later I did the Meta Version Control course (which wasn't that helpful). Each time, I'd learn the commands, have some commits and push something to github, then I forget about it -- until it's the next summer.

I thought enough is enough! I was determined to learn Git in depth, so I spent a month in summer to read the entire book and practice everything in it, and for the first time I felt I'm getting the hang of it.
But I felt... most of my friends don't use Git! if I don't use it much I might get rusty!
So, as I said in the command line section, I send a message to my roommates: "_I'm going to force you to learn Git, whether you want it or not!_. And I did just that. It was a very fun experience and I learned so much about git in the process.

The book focuses on Git, branching, conflicts and fixing mistakes, collaborating with others using different branches, and even how to collaborate within the same branch, It also covers some of best practices and also has a pretty good coverage Github -- although it's not the main focus of the book.

After reading the book I was able to carry out what I like call "git surgery", I once worked on a little game project in a team of 6 people. Even though we agreed on a workflow and all, there were some big problems (later it turned out it was _because_ of the [workflow](/extras/workflow.md), which I later fixed).The book gave me enough knowledge to start reasoning about problems we faced and ask the right questions (I noticed while writing these reviews that a sign of good learning resource is that it teaches you how to reason well about problems)

I especially loved the "_there are no_ **DUMB QUESTIONS**" sections were my favorite, they always answer all the dumb questions that cross my mind!

The book also did something really smart which is not using programs but just plain text for all examples, which instills the idea that you can basically use Git for ANYTHING.

_The Bottom Line_: If you want to learn how git really works and immediately start to work with others and contribute to open source, this is a great option.

### Object-Oriented Design -- Alberta

NOTE: _I did not complete the course_

> longer than a winter's night -- Tunisian proverb

I had multiple UML classes in college, they were full of... words[^words].

It is where I coined the term "audiobook lecture". At some point it feels like ASMR, reminds me of how I felt like a kid, sleeping in my mother's arms, listening to her talking on the phone or with someone...

This one is not different.

_The Bottom Line_: Don't take this course.

### UML Distilled

When you start learning something like UML, you'd be surprised by the amount of boring nonsense, it's kind of ridiculous at times.

But Martin Fowler's [UML distilled](https://martinfowler.com/books/uml.html) (_third_ edition) is so different, it's very practical book, I've been using it as a reference and it's been great!
What makes it special is that Martin speaks out of his experience, he simply says "I tried this approach but it didn't work well".

If you keep wondering what's going on with UML, here are some takeaways from the book:

- why do we need such diagrams? communication and understanding
  - UML is kind of standardized, so you don't have to explain what the symbols mean, everybody gets it, that's whole point.
- UML could be many things, but according to the author, think of it just a language of sketching ideas.
- the two most useful parts of the UML: class diagrams and sequence diagrams.
  - even if you don't want to draw them, it's good to be familiar with them.
- there are multiple ways people use UML -- and they have strong opinions
  - 1. as a sketch, something you draw on paper or whiteboard to explain something to your team
  - 2. as blueprint: i.e. our goal is to be comprehensive, we care a lot about the details and correctness of the diagrams -- not recommended.

- some people say that we should create diagrams that are programming language independent => a complete waste of time

> I need to make my biases clear. Almost all the time, my use of the UML is as sketches.

> I'm not a fan of detailed forward-engineered blueprints; **I believe that it's too difficult to do well and slows down a development effort**.

> Blueprinting to a level of subsystem interfaces is reasonable, but _even then_ you should expect to change those interfaces as developers implement the interactions across the interface

> One of my concerns with blueprints is my own observation that it's very hard to get them right, even for a good designer. **I often find that my own designs do not survive contact with coding intact**.

In some of my projects at university we were _asked_ to create analysis phase class and sequence diagrams that are "language independent". As Fowler said, it's probably just a waste of time.

And I've asked two students from my university who got some of the best graduation projects, I got the same answer:

> For challenging tasks, I made diagrams, for architecture and flow, just to understand what to do, but I only did serious UML [e.g. language independent diagrams] after finishing the project. -- A.

> Nope, like most people I just kept working on the project and adding new features, then at the end I spent some time creating the diagrams. -- Z.

_The Bottom Line_: A really good book about UML, distilled from all the nonsense.

### Java MOOC

The University of Helsinki has a great set free online courses, I highly recommend checking their platform, they have so many great [free courses](https://www.mooc.fi/en/) (they give free certificates -- sometimes even university credits!)
So, I was taking a Java class at college, it was nice, I liked the professor, but I thought, well, why not take this course on the side, especially that it has lots of practice exercises and more advanced topics. I completed this course over the semester and solved most exercise (and received two certificates, one for each part)

The course is divided into two parts, part 1 is very fundamentals of programming in Java, the second gets into more depth (Data structures, generics, etc)
In this course it was the first time I ever implemented a HashMap, it was a really cool mini-project.

There is one thing I really don't like about Java, is how they start with an IDE that makes you feel uncomfortable -- even something simple as "packages" don't make much sense at first, it's a weird way of doing things, at least that's how I see it.
And many things in Java world won't make any sense if you approach them the wrong way, you have to accept the idea of "convention over configuration" and accept the behind the scene magic of Java. It's just like that, leave or take, and I don't like it honestly.

There are many great resources for learning Java, I spent some time on Head First Java and I found it to be EXCELLENT, and it's great that it doesn't tell you to use an IDE, just a bunch of text files. While the book is full of pictures it's actually really nice, for instance it explains the difference between FP and OOP really well, and how it makes adding new kinds of data easy (although it doesn't explain when FP shines), it's better than this course.
The Java MOOC also explains packages really well, something never didn't click for me, especially that weird naming convention (like that revered domain convention `com.company.project`).
But if someday I wanted to be a serious Java Programmer, I'll probably quickly go through that book and learn more (btw the book also covers some socket programming and multithreading, which awesome, and no wonder why people love the book)

Java MOOC also contains some wisdom about dealing with UML, it made me feel so happy when first read it! It's so satisfying.

> Often a class diagram is drawn on a whiteboard or a large sheet of paper during the design phase. Class diagrams should be thought of as helpful tools to build a program, **which can be thrown away afterwards**. You should not use too much energy to think about the correctness and details of the modeling language

_The Bottom Line_: A good course with a lot of practice, it covers all the main concepts you need to get started with Java. It has its nice moments, but for some reason I didn't find the course to be a memorable experience.

### Writing in the Sciences

I thought it would be a shame to spend years at college yet not understand much about scientific writing, so I took this course.
It contained many nice writing tips, and some important ideas in academic writing.
I learned a couple of nice ideas in it, for instance the importance of showing both _relative risk_ and _absolute risk_ when talking to non experts.
Because if you tell people "We discovered that this drug has will double your chance of some disease" you're gonna scare people! But if you tell people it increases the changes of the disease from 0.001 to 0.002, it's not as scary.
But at the same time it's misleading to only include the absolute percentage because an increase from 0.001 to 0.002 is _devastating_ when you have hundreds of thousands of people taking the drug.

But overall, I still don't feel confident in my academic writing yet, and so I plan to take another course which has a capstone project where you actually write a paper about a topic you like, I need more practice.

_The Bottom Line_: it's fine, not sure it's worth your time

### Data and Reality

> If you're confused, it just proves you've been paying attention. -- Data and Reality

I don't like this book, but it's thought provoking. It's pretty much a philosophy book with a lot of unanswered questions.
I feel it's hard to explain my experience with the book without an example.
Early on, the book explains some interesting concepts in data modeling like _categories_, _oneness_ and _sameness_.
Think of categories as UML diagrams, we have some sort of problem and we're trying to represent things in the diagram.
Getting oneness and sameness right is the hard part.
Oneness is trying to find a clear and precise explanation of what we're talking about.
Basically, answering the question: what's a "one thing"?  
Here is an example:
You want to store books on a database. An author wrote two books, so we have two records in the database, a record for each book. simple enough.

_But wait a minute_, what is _a_ book? what's a _one_ book? is it something with a hard cover? but are manuals books? comics and manga? are they books?

_But wait a minute_... forget about that! a "book" can be printed into many parts called "volumes", is each volume a book?

_But wait!_ sometimes we see this idea of "collected works" when several books are made into "one" book, is it a _one_ book?

Then we have the concept of _sameness_: sometimes we have conflicting views of the same thing. We need to deal with that.
Let's say a person had two jobs at a company, on two different shifts. Is that one or two employees?
The book also gives some really wild examples: Say you and I keep exchanging car parts, part by part. At some point we'll basically end up exchanging our cars (and perhaps we need to do some paper work because now we have different cars), but question is when? which part exactly? the engine? well, who knows!

One of the key ideas of the book is that we don't see reality as it is, rather, we see it through a cognitive framework that makes us focus on things others do not see, while causing us to overlook things that others do see. (The book even mentions the Sapir-Whorf hypothesis!)

The book has many interesting insights, but especially at the end I felt quite unsatisfied, I felt the writer is really struggling with the meaning of reality and life. Each problem described leads to another problem, and there is no answer, sometimes it's insightful or funny, sometimes it just leaves you feeling empty.

The book of course doesn't say "there is not reality, everything is relative".[^relative] As the author quoted, simply: "the map is not the territory", but the territory itself exists.
Yet it doesn't give you the feeling of a wise man telling you "Kid, the world is complicated, and we can do nothing about it. But I'll give you some knowledge and wisdom to handle it as best as you can", I wish it were like that.

_The Bottom Line_: It's not an enjoyable read, but I'm glad I read it because it made me think about problems I didn't know existed.

### Introduction to Web Accessibility[^a11y]

This is an introductory course on web accessibility topics, it explores some important concepts in accessibility and dealing with disabilities.
I kept wresting with some ideas in this course, especially as someone who had to learn that it's okay to ask for help, that it's not strength to think "I don't want to owe them anything", having been raised in a world that teaches us that needing help is a weakness.

The course also promotes this idea:

> Disability is caused by a mismatch between the design and the person.

When I heard such statement I felt unsure how to feel about it, in some way it ignores the actual struggle, and it feels like it reduces everything into a design optimization problem. It seems to me that disability is much more than that, it an entire human experience, with its unique challenges and pains, with hopes and joys. The model certainly has good intent and may have some truth to it, but it doesn't seem to me that the model captures the complexity of disability[^social-model].

This all reminds me of a discussion I had in a UX course, the professor gave us an accessibility problem: we want to design a tool to help a blind person to navigate a large place (like a Mall) using technology.
Everyone went brainstorming and there were plenty of ideas, some were ok, but many of them impractical and limited.
But at the end I kept thinking and then asked: "professor what about using human support instead? a human companion or caretaker? someone of their choice and they like and enjoy their presence?"
He was surprised by my question for some reason, and explained it's a matter of independence and autonomy. I didn't push further but the question stayed with me.

Why is independence always the goal? Why is needing someone almost depicted a something shameful. We all need each other's help, _interdependence_ it's part of being human.
So why is needing help so bad. Being interdependent is not something we can escape from. And more importantly it is _not_ something one would want to escape from in a healthy society. We all need each other, and it's totally fine.

I really think it's important to develop tools that help people, it's the best part of software development after all. but I feel the framing is problematic. Why not use technology to improve the interdependence experience instead of replacing it?

I'm still not sure how to think about this. Social problems are very complicated.

(**EDIT**: [I realized I'm being somewhat biased](#the-trap-of-projection))

It's also worth noting that the course isn't very practical, it doesn't teach the actual implementation of accessible systems which is understandable for an introduction course. But it taught me a lot about different kinds of disabilities and some good concepts and terms.

Also when it comes to learning web accessibility, it seems the best way to learn it it through practical examples. I really like [Josh Comeau](https://www.joshwcomeau.com/)'s way of teaching it: not treating it as an afterthought, but embedding accessibility tips and common mistakes throughout the course.

_The Bottom Line_: This one was okay, it's not a bad course by any means. The course isn't very practical nor intellectually deep, but it made me think about these issues -- at least for some time. I'm grateful for that. Sometimes we rarely find time for what we claim we care about.

## Footnotes

[^math-teacher]: He wasn't a particularly good math teacher, but he was a wise man and I liked him. He would often ask me, "Do you understand?" and I'd reply: "No problem, man. Don't push yourself too hard. I'll be okay." But the end of the year, he also told me: "I really like you because you're bad at math, but you don't fake it." For some reason, that made me feel good about myself.

[^memory-paradox]: I've got this example from [this paper](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5250447), it's worth reading! it explains the concept of _schema_ formation and how mastering fundamental knowledge is necessary for deeper intuition. I printed that paper and read it twice, and I even summarized it and translated parts of it into Arabic. It's that good.

[^must]: Whenever you see me say "MUST" or "SHOULD" don't take it too seriously, it's just how I speak in real life when I'm excited.

[^heidi]: [Heidi's chair](https://tenor.com/dBjyREJ4hrg.gif)

[^flowers]: for instance I noticed some flowers close their petals at night and open up in daytime, it's cool!

[^words]: some courses remind me of some bad movies! a rule of thumb in good writing is that dialogue should move the story forward. But as William Faulkner describes, a (bad) writer often write "of defeats in which nobody loses anything of value, of victories without hope and, worst of all, without pity or compassion. His griefs grieve on no universal bones, leaving no scars" -- that's how one feels after taking some courses, emptiness.

[^relative]: which is a self contradictory: if everything is relative, then the claim that everything is relative is itself relative, and possibly false!

[^nice-gregor]: "one of the worst things you can possibly say pedagogically is say, OK, if you don't know anything, don't pay attention to the next five minutes. That makes people go, well, is the course for me or not?" -- Gregor

[^a11y]: It's often written "a11y" because "accessibility" is a such long word! same pattern seen in i18n -- for internationalization.

[^dash]: I used to write em dashes, I learned about their importance in

[this course](#writing-in-the-sciences), but alas I realized it has become a red flag for AI writing. In fact, some of my friends once mentioned they started to doubt words like "genuine" and "journey" because AI tools use them a lot! (I used the word "journey" eleven times in this document... awesome...)

[^social-model]: It's called the social model of disability

[^fast-css]: One of my colleagues at the university once needed some help with CSS, she has the dashboard design but struggled to implement it, she told me ChatGPT was generating a mess. I told her I could help, it took me around 3 hours to write the entire CSS by hand. She was surprised so I explained to her the importance of a good teacher who would explain how to actually write CSS and not just the syntax, and shared some good resources.

[^self-taught]: I heard this insight from someone named Ammar Ahmed in a telegram programming group. His point deeper, as he connected it to the problem individualism in our societies.
