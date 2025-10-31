Reactive Streams Operators (RxJS) AIM:

Explain all Reactive Stream Operators with proper code references and examples. Demonstrate the working of key operators such as map, filter, flatMap, reduce, merge, zip, and concat using a simple reactive program.

THEORY:

Reactive stream operators are small functions that modify or control data flowing through a stream. Instead of processing all data at once, they handle it asynchronously — as soon as data arrives. Operators can transform, filter, merge, or summarize values in real time.

Prerequisites:
- [Node.js](https://nodejs.org/) installed (v18+ recommended)
- RxJS installed globally or in the project:
  ```bash
  npm install rxjs

Each operator runs interactively from the terminal using process arguments:
node reactiveoperators.js <operator_name>


| Operator    | Description                                        |
| ----------- | -------------------------------------------------- | 
| `map`       | Transforms each emitted value using a function     |
| `filter`    | Filters out values that don’t match a condition    |
| `mergeMap`  | Flattens multiple inner Observables concurrently   |
| `concatMap` | Flattens Observables sequentially                  |
| `merge`     | Merges multiple Observables into one               |
| `concat`    | Concatenates Observables in sequence               |
| `zip`       | Combines values from multiple Observables pairwise |
| `reduce`    | Aggregates emitted values into a single result     |

  

Example:
node reactiveoperators.js map

SAMPLE OUTPUTS: map -> 10 map -> 20 map -> 30

filter -> 2 filter -> 4 filter -> 6

reduce -> 15

CONCLUSION:

Reactive Operators help transform and control data streams efficiently. They are essential in reactive programming to make applications asynchronous, flexible, and responsive
