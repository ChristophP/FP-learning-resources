# FP LANGUAGE FEATURE COMPARISON

|                                    | Haskell | Elm | Scala | TypeScript | Go  | Kotlin | Clojure
| ---------------------------------- |:-------:|:---:|:-----:|:----------:|:---:|:------:|:------:
| First Class Functions              | ✔️       | ✔️   |   ✔️   |     ✔️      |  ✔️  |    ✔️   |✔️
| Enforced Purity/Expl. side effects | ✔️       | ✔️   |   ✖️   |     ✖️      |  ✖️  |    ✖️   |?
| Built-in Immutable Data Structures | ✔️       | ✔️   |   ✔️   |     ✖️      |  ?  |    ?   |?
| Immutable is Default               | ✔️       | ✔️   |   ✔️   |     ✖️      |  ?  |    ?   |?
| Enforced Immutabilty               | ✔️       | ✔️   |   ✖️   |     ✖️      |  ?  |    ?   |?
| Auto-Currying [hint](#currying)    | ✔️       | ✔️   |   ✖️   |     ✖️      |  ✖️  |    ?   |?
| OOP features(Classes, etc)         | ✖️       | ✖️   |   ✔️   |     ✔️      |  ?  |    ?   |✖️
| Strongly Typed                     | ✔️       | ✔️   |   ✔️   |     ✔️      |  ?  |    ?   |✖️
| Type Inference                     | ✔️       | ✔️   |   ?   |     ✔️      |  ?  |    ?   |✖️
| Sum Types / Union Types            | ✔️       | ✔️   |   ?   |     ✖️      |  ?  |    ?   |✖️

### Currying

- Scala does not have auto currying but has some syntax support for creating curried functions as described [here](https://docs.scala-lang.org/tour/currying.html).

Other factors: Community, Available Libraries
