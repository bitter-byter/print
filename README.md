# print

Print function for JavaScript

<hr />

### Usage

```javascript
const print = require("@bitterbyter/print");

print(<data>, <type>);
```

<hr />

#### Examples

##### default

```javascript
const print = require("@bitterbyter/print");

print("Hello, World!");
```

##### warn

```javascript
const print = require("@bitterbyter/print");

let x = 0;

print(`Value of x is ${x}`, "debug");
```

<hr />

#### Types

- `count`
- `countReset`
- `debug`
- `dir`
- `dirxml`
- `error`
- `info`
- `table`
- `warn`

> Not sepcifying any type, defaults to `log`.
