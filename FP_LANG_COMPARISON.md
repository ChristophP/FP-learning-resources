# FP LANGUAGE FEATURE COMPARISON

The table compares a couple of polular languages by criteria which are common
in functional programming. Since the existance of features is not always a clear
"yes or no" decision, have look at the hints for each category for a deeper
explanation on why some languages got a check or an X.

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
| Sum Types / Union Types                  | ✔️       | ✔️   |   ✔️   |     ✖️      |  ?  |    ?   |✖️

### Currying

- Scala does not have auto currying but has some syntax support for creating curried functions as described [here](https://docs.scala-lang.org/tour/currying.html).

### Type inference

Though many of the mentioned languages have type inference, the quality varies
quite a bit in terms of the number of cases in which it works.

- Haskell's and Elm's type inference works amazingly well and I have not experienced significant cases in which it doesn't work
- Scala has type inference but it doesn't seem to work in some cases like recursive definitions as mentioned [here](https://docs.scala-lang.org/tour/local-type-inference.html)

Other factors: Community, Available Libraries, existance of wholes in the type system ("any" type)
