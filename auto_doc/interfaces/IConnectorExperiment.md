# IConnectorExperiment

[**@blings/blings-player**](../../)

***

[@blings/blings-player](../globals.md) / IConnectorExperiment

## Interface: IConnectorExperiment

Defined in: [sdk.api.ts:251](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-251)

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

Defined in: [sdk.api.ts:214](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-214)

The identifier of the experiment. This can be a UUID or one of the ISdkSettings keys

**Inherited from**

[`IExperiment`](IExperiment.md).[`id`](IExperiment.md#id)

***

#### type

> **type**: `"connector-experiment"`

Defined in: [sdk.api.ts:255](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-255)

Connector experiments will always be of type "connector-experiment"

**Overrides**

[`IExperiment`](IExperiment.md).[`type`](IExperiment.md#type)

***

#### variants

> **variants**: [`Variant`](Variant.md)<`JSONValue`>\[]

Defined in: [sdk.api.ts:224](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-224)

The possible variants for this experiment

**Inherited from**

[`IExperiment`](IExperiment.md).[`variants`](IExperiment.md#variants)
