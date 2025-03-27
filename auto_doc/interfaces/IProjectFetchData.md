[**@blings/blings-player**](../README.md)

***

[@blings/blings-player](../globals.md) / IProjectFetchData

# Interface: IProjectFetchData

Defined in: [sdk.api.ts:290](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-290)

## Properties

### dataId?

> `optional` **dataId**: `null` \| `string` \| `string`[]

Defined in: [sdk.api.ts:303](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-303)

***

### env?

> `optional` **env**: `SettingsApiEnv`

Defined in: [sdk.api.ts:296](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-296)

project environment.
"dev" | "staging" | "master"
Default: production ("master")

***

### id?

> `optional` **id**: `string`

Defined in: [sdk.api.ts:302](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-302)

***

### liveControlData?

> `optional` **liveControlData**: `IJSONObject`

Defined in: [sdk.api.ts:309](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-309)

***

### projectId?

> `optional` **projectId**: `string`

Defined in: [sdk.api.ts:301](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-301)

ID for this project

***

### promisesFromMiniSDK?

> `optional` **promisesFromMiniSDK**: `object`

Defined in: [sdk.api.ts:304](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-304)

#### jsons

> **jsons**: `undefined` \| `Promise`\<`any`[]\>

#### projectData

> **projectData**: `Promise`\<[`IProjectServerData`](IProjectServerData.md)\>

***

### version?

> `optional` **version**: `string`

Defined in: [sdk.api.ts:308](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-308)
