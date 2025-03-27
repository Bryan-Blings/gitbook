[**@blings/blings-player**](../README.md)

***

[@blings/blings-player](../globals.md) / ISdkSettings

# Interface: ISdkSettings

Defined in: [sdk.api.ts:16](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-16)

## Properties

### analyticsConfig?

> `optional` **analyticsConfig**: `IAnalyticsConfigAbstract`

Defined in: [sdk.api.ts:149](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-149)

***

### autoFocus?

> `optional` **autoFocus**: `boolean`

Defined in: [sdk.api.ts:134](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-134)

should player be auto focused

***

### autoFullScreen?

> `optional` **autoFullScreen**: `boolean`

Defined in: [sdk.api.ts:129](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-129)

on first play, should the video go to full screen (note: full screen is not supported in iphone)
@default: false

***

### autoplay?

> `optional` **autoplay**: `number` \| `boolean`

Defined in: [sdk.api.ts:120](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-120)

should the video start automatically or after pressing a button.
NOTE:
starting with autoplay might start the video muted according to browser's policy
see: https://developers.google.com/web/updates/2017/09/autoplay-policy-changes

***

### autoReplay?

> `optional` **autoReplay**: `boolean`

Defined in: [sdk.api.ts:123](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-123)

should video start automatically to replay once completed

***

### avoidErrorTracking?

> `optional` **avoidErrorTracking**: `boolean`

Defined in: [sdk.api.ts:143](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-143)

***

### bgColor?

> `optional` **bgColor**: `string`

Defined in: [sdk.api.ts:101](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-101)

***

### cinematic?

> `optional` **cinematic**: `boolean`

Defined in: [sdk.api.ts:30](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-30)

set to true to change the webpage to black background with the movie centered

***

### colors?

> `optional` **colors**: `object`

Defined in: [sdk.api.ts:86](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-86)

colors for the player skin and background.

#### bg?

> `optional` **bg**: `string`

#### ctrlBtns?

> `optional` **ctrlBtns**: `string`

#### loader?

> `optional` **loader**: `string`

#### progress?

> `optional` **progress**: `string`

#### rail?

> `optional` **rail**: `string`

#### thumb?

> `optional` **thumb**: `string`

***

### container

> **container**: `HTMLElement`

Defined in: [sdk.api.ts:20](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-20)

which webpage element will contain the video

***

### ctrlBtnsColor?

> `optional` **ctrlBtnsColor**: `string`

Defined in: [sdk.api.ts:100](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-100)

***

### debugLevel?

> `optional` **debugLevel**: `number`

Defined in: [sdk.api.ts:65](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-65)

The level of debug messages to show in the console.
  None = 0,
  Error = 1,
  Warning = 2,
  Info = 3,
  Verbose = 4,

***

### debugMode?

> `optional` **debugMode**: `boolean`

Defined in: [sdk.api.ts:55](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-55)

enable debug mode - showing info on the player.

***

### errorTracking?

> `optional` **errorTracking**: `boolean`

Defined in: [sdk.api.ts:142](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-142)

Send or not errors to Sentry *

***

### experimentOptimizationTechnique?

> `optional` **experimentOptimizationTechnique**: [`OptimizationType`](../enumerations/OptimizationType.md)

Defined in: [sdk.api.ts:167](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-167)

***

### experiments?

> `optional` **experiments**: [`ISettingsExperiment`](ISettingsExperiment.md)[]

Defined in: [sdk.api.ts:165](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-165)

Possible experiments for the player settings. This can be defined on the player settings when creating the player

#### Default

```ts
undefined
```

#### Example

```typescript
settings: {
   experiments: [
     {
       id: "autoplay",
       variants: [{ id: 1, value: "true" }, { id: 2, value: "false" }]
     }
   ]
```

***

### fontOverrides?

> `optional` **fontOverrides**: [`IFontOverride`](../type-aliases/IFontOverride.md)

Defined in: [sdk.api.ts:150](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-150)

***

### hideFullScreenBtn?

> `optional` **hideFullScreenBtn**: `boolean`

Defined in: [sdk.api.ts:81](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-81)

show / hide full screen toggle button
(note: full screen is not supported in iphone)

***

### identifier?

> `optional` **identifier**: `string`

Defined in: [sdk.api.ts:136](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-136)

***

### isCyclic?

> `optional` **isCyclic**: `boolean`

Defined in: [sdk.api.ts:50](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-50)

stories cyclic - back to start at the end

***

### ~~loaderColor?~~

> `optional` **loaderColor**: `string`

Defined in: [sdk.api.ts:99](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-99)

#### Deprecated

- use `colors`
colors for the loading spinner and the play/pause buttons.

***

### loadingImage?

> `optional` **loadingImage**: `string`

Defined in: [sdk.api.ts:104](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-104)

Image to show during the loading

***

### loadingText?

> `optional` **loadingText**: `string`

Defined in: [sdk.api.ts:147](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-147)

Text to show during the loading of the video *

***

### maxLoadingTime?

> `optional` **maxLoadingTime**: `number`

Defined in: [sdk.api.ts:139](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-139)

Timeout for asset loading in ms

***

### muted?

> `optional` **muted**: `boolean`

Defined in: [sdk.api.ts:112](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-112)

should the video start muted or not

***

### overlay?

> `optional` **overlay**: [`IOverlay`](IOverlay.md)

Defined in: [sdk.api.ts:168](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-168)

***

### posterFrame?

> `optional` **posterFrame**: `number`

Defined in: [sdk.api.ts:25](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-25)

which frame from the movie should be presented before playback

***

### rightToLeft?

> `optional` **rightToLeft**: `boolean`

Defined in: [sdk.api.ts:45](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-45)

stories from right to left instead of left to right - for hebrew

***

### sendUtmParams?

> `optional` **sendUtmParams**: `boolean`

Defined in: [sdk.api.ts:107](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-107)

if true, do not save utm params in analytics

***

### showBlingsLogo?

> `optional` **showBlingsLogo**: `number`

Defined in: [sdk.api.ts:144](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-144)

***

### showStoriesModeIndicators?

> `optional` **showStoriesModeIndicators**: `boolean`

Defined in: [sdk.api.ts:70](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-70)

Short animation that explains the UI of stories

***

### showStoriesModeIndicatorsText?

> `optional` **showStoriesModeIndicatorsText**: `boolean`

Defined in: [sdk.api.ts:75](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-75)

Show text in short animation that explains the UI of stories

***

### showTimeline?

> `optional` **showTimeline**: `boolean`

Defined in: [sdk.api.ts:35](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-35)

whether to show a timeline-bar

***

### storiesMode?

> `optional` **storiesMode**: `boolean`

Defined in: [sdk.api.ts:40](https://bitbucket.org/blingsio/player/src/e9d4e5a1bf54c48bcb6663f1308cce3af89efa76/src/SDK/sdk.api.ts#lines-40)

an "instagram" style stories instead for video timeline
