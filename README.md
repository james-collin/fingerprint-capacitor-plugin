# capacitor-plugin-fingerprint-compare

This plugin can be used for comparing fingerprintst

## Install

```bash
npm install capacitor-plugin-fingerprint-compare
npx cap sync
```

## API

<docgen-index>

* [`echo(...)`](#echo)
* [`openDevice()`](#opendevice)
* [`captureFingerprint()`](#capturefingerprint)
* [`compareFingerprint(...)`](#comparefingerprint)
* [Interfaces](#interfaces)

</docgen-index>

<docgen-api>
<!--Update the source file JSDoc comments and rerun docgen to update the docs below-->

### echo(...)

```typescript
echo(options: { value: string; }) => Promise<{ value: string; }>
```

| Param         | Type                            |
| ------------- | ------------------------------- |
| **`options`** | <code>{ value: string; }</code> |

**Returns:** <code>Promise&lt;{ value: string; }&gt;</code>

--------------------


### openDevice()

```typescript
openDevice() => Promise<OpenDeviceResponse>
```

**Returns:** <code>Promise&lt;<a href="#opendeviceresponse">OpenDeviceResponse</a>&gt;</code>

--------------------


### captureFingerprint()

```typescript
captureFingerprint() => Promise<FingerprintResponse>
```

**Returns:** <code>Promise&lt;<a href="#fingerprintresponse">FingerprintResponse</a>&gt;</code>

--------------------


### compareFingerprint(...)

```typescript
compareFingerprint(option: OptionFingerprints) => Promise<FingerprintResponse>
```

| Param        | Type                                                              |
| ------------ | ----------------------------------------------------------------- |
| **`option`** | <code><a href="#optionfingerprints">OptionFingerprints</a></code> |

**Returns:** <code>Promise&lt;<a href="#fingerprintresponse">FingerprintResponse</a>&gt;</code>

--------------------


### Interfaces


#### OpenDeviceResponse

| Prop          | Type                 |
| ------------- | -------------------- |
| **`success`** | <code>boolean</code> |


#### FingerprintResponse

| Prop            | Type                 |
| --------------- | -------------------- |
| **`success`**   | <code>boolean</code> |
| **`message`**   | <code>string</code>  |
| **`rawBitmap`** | <code>any</code>     |
| **`data`**      | <code>any</code>     |


#### OptionFingerprints

| Prop               | Type             |
| ------------------ | ---------------- |
| **`fingerPrints`** | <code>any</code> |

</docgen-api>
