# Functionals

_Maintained by [Bytecode Digital Agency](http://bytecode.nl)_

## Motivation

// TODO

* Ramda is too complicated and bloated
* Underscores has limitations and is not intuitive
* For Bytecode

## Installation

The only requirement for using this package is having NodeJS 10. Other versions
are not officially supported.

Install using `yarn add functionals` or `npm i functionals`.

Import using

```js
import F from 'functionals';
```

```js
const F = require('functionals');
```

## Usage

// TODO

## TODO

* Configure Typescript
* Add automated testing suite
* Configure CI
* Add `trycatch`

```js
trycatch({
    try: something(),
    catch: somethingElse(),
})
```

* Add if-then-else

```js
conditionally({
    if: something,
    then: somethingElse,
    else: otherwise,
})
```

* Add piping

```js
pipe(initialValue, [
    functionWithoutArgs,
    anotherFunctionWithoutArgs,
    [functionWithArgs, arg2, arg3], // the piped value is arg1
])
```

* Add deep merge

```js
deepmerge({key: value, key2: {key: value}}, {key2: {key: newValue}})
// Output is {key: value, key2: {key: newValue}}
```

* Add flatten array

```js
flatten([1, 2, [3, 4]])
// Output is [1, 2, 3, 4]
```

* Add most common in array

```js
mostCommon([1, 2, 2, 3, 3, 3]) // Outputs 3
```

* Add random number generator

```js
random(10, 100) // Random (pseudo-randmo) number (integer) between 10 and 100
```

* Add array splitter (Elixir style)

```js
const testArr = [1, 2, 3, 4]
const [head, tail] = F.headTail(testArr)
// Output: head = 1, tail = [2, 3, 4]
```

* Add largest in array
* If possible, add tail recursion support
* Setup documentation page

## License

Apache 2.0
