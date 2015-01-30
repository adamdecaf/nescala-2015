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


# Comparing functional error handling in Scalaz and Scalactic
By Bill Venners


# The interpreter pattern revisited
By Rúnar Bjarnason (@runarorama)


# Scala Needs YOU!
By Richard Wall


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
