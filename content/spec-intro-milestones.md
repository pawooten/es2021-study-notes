## Key Syntax and Other Milestones highlighted in Introduction of ES2021 Spec

#### ECMAScript 2016
- [** exponentiation operator](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Exponentiation)
    - [**= exponentiation assignment operator](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Exponentiation_assignment)
- [`includes` to `Array.prototype`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/includes)
    - case-sensitive when checking if an array contains strings or characters

#### ECMAScript 2017
- [General Overview (telerik)](https://www.telerik.com/blogs/ecmascript-goodies-check-out-the-es2017-major-features)
- [Async Functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/async_function)
- [Shared Memory](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/SharedArrayBuffer)
- [Atomics](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Atomics)
    - The `Atomics` object provides atomic operations as static methods.
        - Facilitates multi-threaded development
        - `Atomics` is not a constructor and cannot be instantiated with `new`. All members are static.
- static `Object` methods
    - [`Object.values`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/values)
    - [`Object.entries`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/entries)
    - [`Object.getOwnPropertyDescriptors`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/getOwnPropertyDescriptors)

#### ECMAScript 2018
- [AsyncIterator](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Symbol/asyncIterator) and async generators
- new regular expression features
    - dotAll flag
    - named capture groups
    - Unicode property escapes
    - look-behind assertions.
- object rest and spread properties

#### ECMAScript 2019
- flat and flatMap for flattening Arrays
- Object.fromEntries()
- String.trimStart() and trimEnd()

#### ECMAScript 2020
- Strings matchAll
- import()
- BigInt
- Promise.allSettled
- globalThis
- import.meta

#### ECMAScript 2021
- String.replaceAll()
- Promise.any
- AggregateError
- logical assignment operators
    - ??=
    - &&=
    - ||=
- WeakRef
- FinalizationRegistrty
- separators for numeric literals
