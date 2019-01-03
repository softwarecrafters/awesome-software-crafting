# Awesome Software Crafting Resources

In the spirit of [awesome-software-craftsmanship](https://github.com/benas/awesome-software-craftsmanship) and many other [awesome lists](https://github.com/sindresorhus/awesome), this repository strives to provide well-curated material for different topics around, and beyond software crafting.

It's supposed to go beyond listing resources, but giving guidance about approaching a topic and what to expect from reading a book or listening to a talk.

See [CONTRIBUTING.md](./CONTRIBUTING.md) on how to add your recommendations to this collection.

----

## 💡 General

### 🌐 [List of awesome people](https://github.com/lscc/socrates-uk/wiki/List-of-awesome-people-to-recommend-to-new-devs)

A list of interesting people (not just) in tech by topic and with further links to their social media profiles or websites. Compiled at SoCraTes UK 2018.

### 🌐 [Awesome Software Craftsmanship](https://github.com/benas/awesome-software-craftsmanship)

A curated list of resources around *Software Craftsmanship*, *Clean Code* and related programming practices. Comes with a list of [conferences](https://github.com/benas/awesome-software-craftsmanship#school-conferences) and [communities](https://github.com/benas/awesome-software-craftsmanship#school-communities).

## 💻 Coding & Practice ‍

### 📖 [Test Driven Development: By Example](https://www.goodreads.com/book/show/387190.Test_Driven_Development) by Kent Beck

In this fairly short book (240p), the reader gets a short theoretical introduction to the techniques and practices that form TDD. The reader then immediately follows Kent Beck in his journey of implementing two projects from start to finish using TDD: a money example in Java and the creation of unit testing framework in Python.

Having already attended several coderetreats, reading this book was my ([@tdpauw](https://twitter.com/tdpauw)) biggest a-ha moment in understanding how TDD works and how to apply it.

## 🏗️ Architecture, Design & Modelling

## 🚀 Software Development, Process & Delivery
### 📖 [Working Effectively with Legacy Code](https://www.goodreads.com/book/show/44919.Working_Effectively_with_Legacy_Code) by Michael C. Feathers

Introduces legacy code as "code that isn't covered by tests". It explains different techniques and refactoring patterns to tackle legacy code by putting it under test. Very detailed (464 pages), but worth if you're working with legacy code a lot. The examples are in Java and C++

### 📖 [Release it!](https://www.goodreads.com/book/show/1069827.Release_It_) by Michael T. Nygard

300 pages easy to read book explaining all the patterns to turn your application into an operatable application. This should be required reading for every software engineer.

It touches things like circuit breaker, bulkhead, zero-downtime deployments, networking in datacenters (most machines have 2 or more NIC's, make sure your app connects to the right one), gracefull startup, gracefull shutdown and many more things.

Every chapter starts with a real life disaster scenario coming from the experience Michael had working in operations.

Most of what Netflix has done in his cloud transformation and what they released now as open source tools is based on this book.

A second edition has been released in 2018.

### 📖 [The Goal](https://www.goodreads.com/book/show/113934.The_Goal) by Eliyahu M. Goldratt,  Jeff Cox

A novel that introduce the reader to the general ideas of the [*Theory Of Constraints (ToC)*](https://en.wikipedia.org/wiki/Theory_of_constraints) and the [*Five Focusing Steps*](https://www.tocinstitute.org/five-focusing-steps.html) through the struggle the protagonists go through as they try to save a failing manufactoring plant that is threatened to be closed because of bad efficiency and accounting figures.

The talk **[🎥 How To Break The Rules](https://www.youtube.com/watch?v=hZFShSjAhlQ) by Dan North** serves as a great introduction to the principles applied in the stories of both books and the work of Eliyahu Goldratt.

The twitter moment [*Theory of Constraints #toc #tocot*](https://twitter.com/i/moments/1063540260179726336) introduces Theory of Constraints in 30-something tweets.

### 📖 [The Phoenix Project](https://www.goodreads.com/book/show/17255186-the-phoenix-project) by Gene Kim,  Kevin Behr, George Spafford

**The Phoenix Project** is a similar novel as The Goal, but this time applied to a struggling IT department. It tells how the protagonists fix their department by implementing DevOps practices.

During the story, the reader is taken several times to a factory to explain the problems the IT department is facing in terms of physical manufacturing problems.

The Phoenix Project puts less the emphasise on Theory of Constraints, but more on the 3 backing principles of DevOps called [*The Three Ways*](https://itrevolution.com/the-three-ways-principles-underpinning-devops/).

About *The Phoenix Project*:
> This is the IT swamp draining manual for anybody who is neck deep in alligators.
>
> -- Adrian Cockcroft, Cloud Architect at Netflix

### 📖 [Rolling Rocks Downhill: Accelerate Agile using Goldratt's TOC](https://www.goodreads.com/book/show/25460979-rolling-rocks-downhill) by Clarke Ching

Yet another novel based on **The Goal**. This time a software project that has been running late since day 1 and that needs to launch on an impossible early date, or else.

While **The Phoenix Project** mainly tells the story from an IT operations manager's point of view, **Rolling Rocks Downhill** tells the story from a software development manager's point of view.

During the story, the reader is taken several times to the company's cafetaria that several years ago was threaten to close because of too less customers but managed to over achieve by implementing the concepts behind the Theory of Constraints.

The reader is also introduced to the concept of the [*Evaporating Cloud*](https://wikipedia.org/wiki/Evaporating_Cloud), a conflict resolution diagram.

There was a time the book could be read one chapter a day in 60 days by subscribing to a mailing at https://rolls.rocks. You would then receive one chapter every day in your mailbox. But it seems to be not available anymore. That was very funny as you got at the beginning and end of every chapter some funny comments from Clarke.

Starting from chapter 24, every chapter ended with this quote to make sure the opposite happens:

> Please don't think of small batches, okay?
>
> Promise?
>
> -- Clarke Ching

### 📖 [The Bottleneck Rules: How To Get More Done at Work, Without Working Harder](https://www.goodreads.com/book/show/40279575-the-bottleneck-rules) by Clarke Ching

Very short book (108p) one can read in a day. It is basically an introduction to bottlenecks, the key concept behind [*Theory Of Constraints (ToC)*](https://en.wikipedia.org/wiki/Theory_of_constraints). 

Although Clarke studied ToC for 2 decades and he is a big fan of Eliyahu Goldratt, he had to realise that **The Goal** is too advanced and too much focused on managers of big corporations trying to solve big problems that 99% of the people will never come across. It's a 300-something pages big book and you only get to bottlenecks around page 203.

Clarke created this book to help everyday, ordinary people find and manage their bottleneck quickly no matter what industry they work in. The book contains examples from different domains.

The book explains what bottlenecks are, how to find them and how to manage them. For the management Clarke introduces the FOCCCUS formula, which is just a reformulation of the [*Five Focusing Steps*](https://www.tocinstitute.org/five-focusing-steps.html) in a more concrete and more understandable way than the original version.

If you want to read one book on ToC, I would suggest this one.

### 📖 [Measuring Continuous Delivery: The what, why, and how of measuring Continuous Delivery](https://www.goodreads.com/book/show/35508935-measuring-continuous-delivery) by Steve Smith

Yet another book about [*Theory Of Constraints (ToC)*](https://en.wikipedia.org/wiki/Theory_of_constraints), this time applied to the technology value stream aka your Continuous Delivery pipeline, i.e. from code commit to deployed in production and released to users.

Continuous Delivery is a holistic approach to software delivery. Adopting Continuous Delivery involves a bunch of technological and organisational changes. It is not these technological and organisational changes that actually make adopting Continuous Delivery hard. It is the application of them to the unique circumstances and constraints of your organisation. Your organisation is a complex, adaptive system in which every individual has a limited amount of information and the cause and effect of any event can only be established in retrospect.

So, where do you start? Which technological or organisational change are you going to adopt first?

In this book, Steve explains how by using [*The Improvement Kata*](http://www-personal.umich.edu/~mrother/The_Improvement_Kata.html), measuring the pipeline using the 4 throughput and stability metrics from the [*State of DevOps Report*](https://puppet.com/resources/whitepaper/state-of-devops-report) and [*Theory Of Constraints (ToC)*](https://en.wikipedia.org/wiki/Theory_of_constraints) to you can identify your bottleneck and identify which experiments to run to eliminate that bottleneck.

### 📖 [Accelerate](https://www.goodreads.com/book/show/35747076-accelerate) by  Nicole Forsgren, Jez Humble, Gene Kim

This book is the summary of the findings of 4 years of research in the context of the [*State of DevOps Report*](https://puppet.com/resources/whitepaper/state-of-devops-report) (starting from 2014). It confirms lots of the beliefs we've build up over the past 2 decades in the agile community. And it also has some surprising outcomes.

From the findings, you understand how different aspects ranging from transformational leadership, technological practices that make up Continuous Delivery, lean product development and lean management all influence software delivery performance, rework, organisational culture, burn-out, job satisfaction and in the end organisational performance from a financial point of view and non-commercial performance.

The book also explains how this research has been performed and how you can apply the type of questionnairs that has been used for the research to measure how well your organisation is performing.

## 🤗 Team Culture & Collaboration

## 🤔 Cognitive science, Systems theory

### 📖 [Systems Thinking: A Primer by Donella H. Meadows, Diana Wright](https://www.goodreads.com/book/show/3828902-thinking-in-systems)

A fairly short book (240 pages) giving a great introduction to Systems Thinking, or how to model and understand complex systems. The book always uses practical examples, such as economical or biological systems, to illustrate certain system behaviours. Contains a lot of diagrams, so maybe get the physical book and not an ebook version. See [The Donella Meadows Project](http://donellameadows.org/systems-thinking-resources/) for more resources on systems thinking.
