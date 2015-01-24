# nescala 2015 notes

Website: [nescala.org](http://www.nescala.org/)

## Talks

__0800: Doors Open__
- Check in and grab some coffee

__0850: Opening Remarks__
- Let's remember why we are here thank those that made this happen

__0900: Akka HTTP — The What, Why and How__
- Mathias Doenitz (@sirthias)

If you want to provide or consume HTTP-based APIs with Scala (or Java) then this talk is for you: Akka HTTP takes reactive high-performance web interactions to the next level. Fully asynchronous & non-blocking, with a type-safe & powerful declarative API and a proper immutable HTTP model it provides an excellent tool for connecting your Scala/Akka applications to the world. In this session we’ll do a thorough double-click on akka-http, how it is used, what improvements it brings over its predecessor spray.io and why you will not want to use anything else after having tried it.

9:45am Break (5 minutes)
9:50am A Sane Approach to (Micro)services

Toby Matejovsky
 @tobym

A service-oriented architecture looks great as boxes and lines on a whiteboard, but what is it like in real life? Are the benefits of flexibility worth the overhead of administration? We've built a framework on top of Finagle that enables a simple approach to building and deploying a microservice with SBT and Scala.

10:20am Break (20 minutes)
10:40am Comparing functional error handling in Scalaz and Scalactic

Bill Venners
In this talk I'll compare and contrast the approaches to functional error handling taken by Scalaz and Scalactic. I'll look at how different opinions on typeclass coherence led to two classes in Scalaz, \/ and Validation, and just one in Scalactic, Or. I'll explain why when it comes to success values, I feel left is right and right is wrong, whereas the Scalazzi think the opposite. I'll show how the libraries use algebraic structures differently. And I'll explore how different opinions on how best to leverage functional programming (FP) in Scala led to different library designs.

11:25am Break (5 minutes)
11:30am The interpreter pattern revisited

Rúnar Bjarnason
 @runarorama

The Interpreter pattern is a classic object-oriented design pattern that has been overlooked by far too many for far too long. In this talk we will give this unsung hero the accolades it deserves. Please turn to page 243 in your Gang-of-Four book and follow along. Its dry description goes: "given a language, define a representation for its grammar along with an interpreter that uses the representation to interpret sentences in the language." But it's so much more than that! With the interpreter pattern as our hammer, every imaginable problem becomes a nail.

12pm Break (5 minutes)
12:05pm Scala Needs YOU!

Richard Wall
Give me 15 minutes and I will ask for a whole lot more! Ever wanted to feel more involved in the Scala community? Well now is your chance. We are rejuvenating the Scala contributor ecosystem and in this, perhaps the most important 15 minutes of your life ;-), you can find out how YOU can help. We'll talk documentation, bug fixes, core libraries and even big compiler changes, all in the time it takes to enjoy a latte.

12:20pm Lunch
Let's eat!

1:50pm Intervals: unifying uncertainty, ranges, and loops

Erik Osheim
 @d6

Since the 1950's, engineering disciplines have used interval arithmetic to track and bound measurement errors. For data with known uncertainty (e.g. 43±1) interval arithmetic produces a range of possible output values (e.g. 86±2). Intervals can also be used to model and operate on contiguous sets of values. Spire's Interval type is generic and can be used with any ordered data type. In this talk we'll see how algebraic type classes support arithmetic over a wide range of types, work through some cases, and see how intervals can also be used in place of Ranges, Sets, and even loops!

2:20pm Break (5 minutes)
2:25pm Demystifying Type Inference

Jon Pretty
Understanding type inference in Scala is a dark art. How does the compiler sometimes manage to conjure up exactly the correct type from an horrendous tangle of polymorphic method calls, while at other times drawing a blank at something that seems plainly obvious to everyone else? I'll cover the core ideas of type inference, show what works, what doesn't work, and why. I'll give really simple explanations of covariance and contravariance, and the differences between type parameters and type members, then show how you can exploit type inference with some good design and applied cunning.

3:10pm Break (5 minutes)
3:15pm Speed, Correctness, or Simplicity: Choose 3

Tom Switzer
 @tixxit

Speed, correctness, or simplicity: choose 2. This is the common wisdom when implementing numeric algorithms. With floating point arithmetic, we either live with floating point errors or get stuck implementing clever, but complex ways to reduce them. If we use precise types, like BigInt or Rational, we lose the speed of primitive arithmetic, but know our result is correct. This talk will focus on another option: floating point filters. We will see how Spire's FpFilter type let's us keep the speed of Doubles, the precision of BigInt, Rational or Algebraic, and with no complex error analysis.

3:30pm Break (20 minutes)
3:50pm Path Dependent Types Through the Looking Glass

Owein
 @OweinReese

It's been said before that we can program guided only by the types and the things we'd like to do with those types. But what happens if we make the types depend on the context? Instead of regular functions where we explicitly know the return type, let's use path dependent types where we don't. Let's examine what map and flatMap mean when they share the same signature. Can we get by with just one without losing the power of monadic composition? In the process of exploring these questions we'll get more comfortable with dependent types, what they are and gain insights into our every day code.

4:20pm Break (5 minutes)
4:25pm F-Bounded Polymorphism

Marconi Lanna
 @ScalaFacts

Have you seen a type signature like this before? trait T[U <: T[U]] F-bounded polymorphism, also know as self-referential types or recursive type signatures, is a powerful object-oriented technique that leverages the type system to encode constraints on generics. This talk explain how to define and use F-bounded types in Scala, enlisting the compiler to enforce advanced trait semantics meanwhile greatly reducing and simplifying your unit tests.

4:40pm Macros in data pipelines

Neville Li
 @sinisa_lyh

In this talk, I present how scala macros can be used to improve data pipeline code leveraging parquet, a columnar storage format. We use macros to generate parquet schema projection and filter predicates in compile time. Compared to the standard approach, the macros are type-safe, more concise, and user friendly.

4:55pm Break (5 minutes)
5pm Selfish UIs - Fast UIs for terminal applications

Josh Suereth
 @jsuereth

Oftentimes we spend most of our engineering efforts designing for other people. However, there are lots of utilities that we could develop to increase our own productivity. This talk gives a short tutorial for how to do the minimum amount of work creating and deploying a command line tool, including how to share and create a rich interface. We'll cover the basics of: Conscript vs. sbt-native-packager, the sbt autocompletion library and general ANSI fun in Java.

5:15pm We Won! How Scala Conquered Big Data

Dean Wampler
 @deanwampler

At @nescalas 2012, I complained that Hadoop's MapReduce is the "EJBs of our time." Hadoop, and Big Data in general, needed Function Programming and an alternative to Java. Fast Forward three years later and we find that Scalding proved that a Scala DSL is far superior to the MapReduce Java API, and Spark is now replacing MapReduce altogether. (High Fives all around!) I'll demonstrate why this happened and argue that Big Data is the Killer App for FP and Scala.

5:30pm Day one closer
When
