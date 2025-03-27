[**@blings/blings-player**](../README.md)

***

[@blings/blings-player](../globals.md) / ISdkParams

# Interface: ISdkParams

Defined in: [sdk.api.ts:345](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-345)

## Properties

### data

> **data**: `any`

Defined in: [sdk.api.ts:360](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-360)

***

### experiments?

> `optional` **experiments**: [`IExperiment`](IExperiment.md)\<[`ExperimentValues`](../type-aliases/ExperimentValues.md)\>[]

Defined in: [sdk.api.ts:367](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-367)

An array of all the experiments that this player should use. These have precedence over the experiments that are defined in the project

***

### flowDiagram?

> `optional` **flowDiagram**: `IFlowDiagram`

Defined in: [sdk.api.ts:370](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-370)

***

### polyfills?

> `optional` **polyfills**: `IPolyfills`

Defined in: [sdk.api.ts:377](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-377)

***

### project

> **project**: [`IProjectFetchData`](IProjectFetchData.md) \| `Omit`\<`Omit`\<`Omit`\<`Omit`\<[`IProjectServerData`](IProjectServerData.md), `"playerSettings"`\>, `"flowDiagram"`\>, `"overlay"`\>, `"fontOverrides"`\>

Defined in: [sdk.api.ts:346](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-346)

***

### rest?

> `optional` **rest**: `Partial`\<`IPlayerParams`\>

Defined in: [sdk.api.ts:376](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-376)

extra things that Player can get
For Blings developers only (not for external docs)
(note: currently not deep clone, so make sure to not override other stuff

***

### scenes?

> `optional` **scenes**: [`ISdkScene`](../type-aliases/ISdkScene.md)[]

Defined in: [sdk.api.ts:358](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-358)

list of video-parts ("scenes") and their order that will be played

***

### settings

> **settings**: [`ISdkSettings`](ISdkSettings.md)

Defined in: [sdk.api.ts:362](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-362)

***

### uid?

> `optional` **uid**: `string`

Defined in: [sdk.api.ts:379](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-379)

***

### utmParams?

> `optional` **utmParams**: [`UtmType`](../type-aliases/UtmType.md)

Defined in: [sdk.api.ts:378](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-378)

***

### variantSelectionSet?

> `optional` **variantSelectionSet**: [`IVariantSelectionSet`](../type-aliases/IVariantSelectionSet.md)

Defined in: [sdk.api.ts:369](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-369)
