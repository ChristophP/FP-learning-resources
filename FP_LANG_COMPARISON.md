# FP LANGUAGE FEATURE COMPARISON

|                                          | Haskell | Elm | Scala | TypeScript | Go  | Kotlin | Clojure
| ----------------------------------       |:-------:|:---:|:-----:|:----------:|:---:|:------:|:------:
| First Class Functions                    | ✔️       | ✔️   |   ✔️   |     ✔️      |  ✔️  |    ✔️   |✔️
| Enforced Purity/Expl. side effects       | ✔️       | ✔️   |   ✖️   |     ✖️      |  ✖️  |    ✖️   |?
| Built-in Immutable Data Structures       | ✔️       | ✔️   |   ✔️   |     ✖️      |  ?  |    ?   |?
| Immutable is Default                     | ✔️       | ✔️   |   ✔️   |     ✖️      |  ?  |    ?   |?
| Enforced Immutabilty                     | ✔️       | ✔️   |   ✖️   |     ✖️      |  ?  |    ?   |?
| Auto-Currying [hint](#currying)          | ✔️       | ✔️   |   ✖️   |     ✖️      |  ✖️  |    ?   |?
| OOP features(Classes, etc)               | ✖️       | ✖️   |   ✔️   |     ✔️      |  ?  |    ?   |✖️
| Strongly Typed                           | ✔️       | ✔️   |   ✔️   |     ✔️      |  ?  |    ?   |✖️
| Type Inference [hint](#type-inference)   | ✔️       | ✔️   |   ✔️   |     ✔️      |  ?  |    ?   |✖️
| Sum Types / Union Types                  | ✔️       | ✔️   |   ?   |     ✖️      |  ?  |    ?   |✖️

### Currying

- Scala does not have auto currying but has some syntax support for creating curried functions as described [here](https://docs.scala-lang.org/tour/currying.html).

### Type inference

Though many of the mentioned languages have type inference, the quality varies
quite a bit in terms of the number of cases in which it works.

- Haskell's and Elm's type inference works amazingly well and I have not experienced significant cases in which it doesn't work
- Scala has type inference but it doesn't seem to work in some cases like recursive definitions as mentioned [here](https://docs.scala-lang.org/tour/local-type-inference.html)

Other factors: Community, Available Libraries
