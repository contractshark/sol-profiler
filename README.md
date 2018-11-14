# sol-profiler
[![npm version](https://badge.fury.io/js/sol-profiler.svg)](https://www.npmjs.com/package/sol-profiler)
[![devDependency Status](https://david-dm.org/aniket-engg/sol-profiler.svg)](https://david-dm.org/aniket-engg/sol-profiler#info=dependencies)

sol-profiler lists down the attributes of all the functions/constructor of a single `.sol` file. sol-profiler is colourful and easy to use. It displays the profile of contracts & libraries along with the `pragma` used in file. 

It marks the `library` contracts and `fallback` function explicitly, see [example](https://github.com/Aniket-Engg/sol-profiler#example).

<b>Note: </b>sol-profiler does not ensure/guarantee any kind of security or correctness of any smart-contract.

## Install
```
npm install --save-dev sol-profiler
```

## Run
```
./node_modules/.bin/sol-profiler <contract source path>
```
This does not work on imported files. You can use the available npm packages to merge the files in one.

## Example
We have attached an extensive example i.e. [sample.sol](https://github.com/Aniket-Engg/sol-profiler/blob/master/example/sample.sol). For this, profiler result will be same as in below image : 

![profiler](https://user-images.githubusercontent.com/30843294/48478720-11858180-e82b-11e8-8af2-d7945176787b.png)

## Contribution/Suggestions
Any kind of suggestions or contribution are most welcome!