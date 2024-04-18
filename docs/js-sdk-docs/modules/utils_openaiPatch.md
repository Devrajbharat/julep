[@julep/sdk](../README.md) / [Modules](../modules.md) / utils/openaiPatch

# Module: utils/openaiPatch

## Table of contents

### Functions

- [patchCreate](utils_openaiPatch.md#patchcreate)

## Functions

### patchCreate

▸ **patchCreate**(`client`, `scope?`): `any`

Patches the 'create' method of an OpenAI client instance to ensure a default model is used if none is specified.
This is useful for enforcing a consistent model usage across different parts of the SDK.

#### Parameters

| Name | Type | Default value | Description |
| :------ | :------ | :------ | :------ |
| `client` | `any` | `undefined` | The OpenAI client instance to be patched. |
| `scope` | `any` | `null` | Optional. The scope in which the original 'create' method is bound. Defaults to the client itself if not provided. |

#### Returns

`any`

#### Defined in

[src/utils/openaiPatch.ts:8](https://github.com/julep-ai/julep/blob/6a621b8a51de5d42cc90fb119aac3f82b9460f8a/sdks/ts/src/utils/openaiPatch.ts#L8)