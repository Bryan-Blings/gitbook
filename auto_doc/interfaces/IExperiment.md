[**@blings/blings-player**](../README.md)

***

[@blings/blings-player](../globals.md) / IExperiment

# Interface: IExperiment\<V\>

Defined in: [sdk.api.ts:210](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-210)

## Extended by

- [`ISettingsExperiment`](ISettingsExperiment.md)
- [`ISceneExperiment`](ISceneExperiment.md)
- [`IConnectorExperiment`](IConnectorExperiment.md)

## Type Parameters

### V

`V` *extends* [`ExperimentValues`](../type-aliases/ExperimentValues.md)

## Properties

### from?

> `optional` **from**: `ExperimentFrom`

Defined in: [sdk.api.ts:229](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-229)

From where this experiment came from. This can be either "Backend" or "SDK"

***

### id

> **id**: `string`

Defined in: [sdk.api.ts:214](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-214)

The identifier of the experiment. This can be a UUID or one of the ISdkSettings keys

***

### type

> **type**: [`ExperimentTypes`](../type-aliases/ExperimentTypes.md)

Defined in: [sdk.api.ts:219](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-219)

The type of the experiment. This can be either "connector-experiment" or "settings-experiment"

***

### variants

> **variants**: [`Variant`](Variant.md)\<`V`\>[]

Defined in: [sdk.api.ts:224](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-224)

The possible variants for this experiment
