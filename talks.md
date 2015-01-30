# Akka HTTP — The What, Why and How
By: Mathias Doenitz (@sirthias)

## Heritage

- from spray
  - immutable case class models around http
  - parboiled2 parsing
  - route structure and testkit
  - bugs / lack of support around message chunking
  - traps around routing dsl
- from akka
  - streams

## Provides

- If you stay within the akka-http stack then akka-http clients can be slowed down by akka-http servers or other clients
  - backpressure
  - How does it to it? Headers?
- Flow[HttpRequest, HttpResponse] interface for both clients and servers

# A Sane Approach to (Micro)services
By Toby Matejovsky (@tobym)

## When should you use microservices?

- When you have to coordinate two independent features for a deploy.
  - If one breaks you have to rollback non-breaking (independent) changes.

# Comparing functional error handling in Scalaz and Scalactic
By Bill Venners

## Comparing libraries

- scalaz.{\/, Validation} vs Or
  - Which one (from scalaz) do I use?
  - Scalactic has `Every` which has subtypes of `One` or `Many` that can be accumulated
  - Because scalaz is so general you get really obtuse results back
    - (pargeAge(19): Validation[String, Int]).filter(_ > 21) // Failure("") -- uhh??

- Note: I think we still need `Failure`, `Error`, `Successful` types that have one-line uses and accumulation or `Failure` or `Error`.

# The interpreter pattern revisited
By Rúnar Bjarnason (@runarorama)

- Given an AST you can perform computations.
- ADT's are little languages.
- `def fold[B](z: B)(f: A => B): B` is a generic interpreter
- Model the meaning / behaviour with different interpreters rather than different instances.
  - Encode the structure and compute on that.
  - [redis-algebra](https://github.com/ethul/redis-algebra) example
- What's the tradeoff between using "old/existing" coding methods and having an AST that we can interprete in different ways.
  - Then we're able to run trials, with a scala clone of [github scientist](https://github.com/github/scientist)?

# Scala Needs YOU!
By Richard Wall

- `// todo (community)` is a well known feeling around scala
- Discussions will occur on scala-internals
- Stickers for contributors

# Intervals: unifying uncertainty, ranges, and loops
By Erik Osheim (@d6)


# Demystifying Type Inference
By Jon Pretty (@propensive)


# Speed, Correctness, or Simplicity: Choose 3
By Tom Switzer (@tixxit)


# Path Dependent Types Through the Looking Glass
By Owein (@OweinReese)


# F-Bounded Polymorphism
By Marconi Lanna (@ScalaFacts)


# Macros in data pipelines
By Neville Li (@sinisa_lyh)


# Selfish UIs - Fast UIs for terminal applications
By Josh Suereth (@jsuereth)


# We Won! How Scala Conquered Big Data
By Dean Wampler (@deanwampler)
