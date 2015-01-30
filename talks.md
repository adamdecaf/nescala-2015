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

# Speed, Correctness, or Simplicity: Choose 3

By Tom Switzer (@tixxit)

# Macros in data pipelines

By Neville Li (@sinisa_lyh)

# Comparing functional error handling in Scalaz and Scalactic

By Bill Venners

# F-Bounded Polymorphism

By Marconi Lanna (@ScalaFacts)

# Selfish UIs - Fast UIs for terminal applications

By Josh Suereth (@jsuereth)

# The interpreter pattern revisited

By Rúnar Bjarnason (@runarorama)

# Intervals: unifying uncertainty, ranges, and loops

By Erik Osheim (@d6)

# A Sane Approach to (Micro)services

By Toby Matejovsky (@tobym)

# Path Dependent Types Through the Looking Glass

By Owein (@OweinReese)

# Scala Needs YOU!

By Richard Wall

# Demystifying Type Inference

By Jon Pretty (@propensive)

# We Won! How Scala Conquered Big Data

By Dean Wampler (@deanwampler)