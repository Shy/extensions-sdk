# Interface: Host

[host](../modules/host.md).Host

## Table of contents

### Methods

- [openExternal](host.Host.md#openexternal)

## Methods

### openExternal

▸ **openExternal**(`url`): `void`

Opens an external URL with the system default browser.

```typescript
window.ddClient.host.openExternal("https://docker.com");
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `url` | `string` | The URL the browser will open (must have the protocol `http` or `https`). |

#### Returns

`void`