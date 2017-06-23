# iota-generate-seed

Generates suitable [IOTA](https://iotatoken.com/) seeds.

## Security

A seed is like a private key or password to access your account. Keep it private and don't lose it.
Maximum security is achieved by a random 81-chars seed. Longer seeds won't increase security.

> #### Warning: Use a TrueRNG to generate secure seeds
> Entropy of pseudorandom generators like crypto.randomBytes() is uncertain. Consider securing your funds or privacy by using a sufficient method rather than this script.

## Installation

Use [npm](https://www.npmjs.com/) to install:

```
npm install iota-generate-seed
```

## Usage

```javascript
const generate = require('iota-generate-seed');

const seed = generate();
// > 'TXKBFUZEFTDUFGB9YQSJAYBGQFEJHQVHLTOMFVFUHQCELKG9PXOTRCRHENHWBQOGRSFHGQLLLQJULFENE'
```
## Command Line Usage

```
$ npm install -g iota-generate-seed

$ iota-generate-seed
> 'SKVBOV9LARQ9SROHJJJTPREYYPYLNVE9FBCEGPCVTFMZBXFFPHN9ECGOKREHGTRBNCTTGDWZPXXZWKLIS'
```
