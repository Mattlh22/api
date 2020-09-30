**Polkadot JS API**

> [README](../README.md) / [Globals](../globals.md) / ["packages/api/src/promise/Combinator"](../modules/_packages_api_src_promise_combinator_.md) / Combinator

# Class: Combinator\<**T**>

## Type parameters

* T

## Hierarchy

* **Combinator**

## Index

### Constructors

* [constructor](_packages_api_src_promise_combinator_.combinator.md#constructor)

### Methods

* [unsubscribe](_packages_api_src_promise_combinator_.combinator.md#unsubscribe)

## Constructors

### constructor

\+ **new Combinator**(`fns`: ([CombinatorFunction](../interfaces/_packages_api_src_promise_combinator_.combinatorfunction.md) \| [[CombinatorFunction](../interfaces/_packages_api_src_promise_combinator_.combinatorfunction.md), any])[], `callback`: [CombinatorCallback](../modules/_packages_api_src_promise_combinator_.md#combinatorcallback)\<T>): [Combinator](_packages_api_src_promise_combinator_.combinator.md)

*Defined in [packages/api/src/promise/Combinator.ts:28](https://github.com/polkadot-js/api/blob/9d548f787/packages/api/src/promise/Combinator.ts#L28)*

#### Parameters:

Name | Type |
------ | ------ |
`fns` | ([CombinatorFunction](../interfaces/_packages_api_src_promise_combinator_.combinatorfunction.md) \| [[CombinatorFunction](../interfaces/_packages_api_src_promise_combinator_.combinatorfunction.md), any])[] |
`callback` | [CombinatorCallback](../modules/_packages_api_src_promise_combinator_.md#combinatorcallback)\<T> |

**Returns:** [Combinator](_packages_api_src_promise_combinator_.combinator.md)

## Methods

### unsubscribe

▸ **unsubscribe**(): void

*Defined in [packages/api/src/promise/Combinator.ts:78](https://github.com/polkadot-js/api/blob/9d548f787/packages/api/src/promise/Combinator.ts#L78)*

**Returns:** void
