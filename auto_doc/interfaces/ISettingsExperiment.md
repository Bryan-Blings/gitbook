# ISettingsExperiment

[**@blings/blings-player**](../../)

***

[@blings/blings-player](../globals.md) / ISettingsExperiment

## Interface: ISettingsExperiment

Defined in: [sdk.api.ts:232](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-232)

### Extends

* [`IExperiment`](IExperiment.md)<`JSONValue`>

### Properties

#### from?

> `optional` **from**: `ExperimentFrom`

Defined in: [sdk.api.ts:229](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-229)

From where this experiment came from. This can be either "Backend" or "SDK"

**Inherited from**

[`IExperiment`](IExperiment.md).[`from`](IExperiment.md#from)

***

#### id

> **id**: `string`

Defined in: [sdk.api.ts:236](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-236)

The identifier of the experiment. This will be one of the ISdkSettings keys

**Overrides**

[`IExperiment`](IExperiment.md).[`id`](IExperiment.md#id)

***

#### type

> **type**: `"settings-experiment"`

Defined in: [sdk.api.ts:241](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-241)

Settings experiments will always be of type "settings-experiment"

**Overrides**

[`IExperiment`](IExperiment.md).[`type`](IExperiment.md#type)

***

#### variants

> **variants**: [`Variant`](Variant.md)<`JSONValue`>\[]

Defined in: [sdk.api.ts:224](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-224)

The possible variants for this experiment

**Inherited from**

[`IExperiment`](IExperiment.md).[`variants`](IExperiment.md#variants)
