# archer-plus-usb-printer

The Plugin for printing to epson usb printer

## Install

```bash
npm install archer-plus-usb-printer
npx cap sync
```

## API

<docgen-index>

- [archer-plus-usb-printer](#archer-plus-usb-printer)
  - [Install](#install)
  - [API](#api)
    - [getPrinterList()](#getprinterlist)
    - [connectToPrinter(...)](#connecttoprinter)
    - [print(...)](#print)
    - [Interfaces](#interfaces)
      - [EpsonUSBPrinterInfo](#epsonusbprinterinfo)

</docgen-index>

<docgen-api>
<!--Update the source file JSDoc comments and rerun docgen to update the docs below-->

### getPrinterList()

```typescript
getPrinterList() => Promise<{ printerList: EpsonUSBPrinterInfo[]; }>
```

**Returns:** <code>Promise&lt;{ printerList: EpsonUSBPrinterInfo[]; }&gt;</code>

--------------------


### connectToPrinter(...)

```typescript
connectToPrinter(options: { productId: number; }) => Promise<{ connected: boolean; }>
```

| Param         | Type                                |
| ------------- | ----------------------------------- |
| **`options`** | <code>{ productId: number; }</code> |

**Returns:** <code>Promise&lt;{ connected: boolean; }&gt;</code>

--------------------


### print(...)

```typescript
print(options: { printObject: string; lineFeed?: number; }) => Promise<void>
```

| Param         | Type                                                     |
| ------------- | -------------------------------------------------------- |
| **`options`** | <code>{ printObject: string; lineFeed?: number; }</code> |

--------------------


### Interfaces


#### EpsonUSBPrinterInfo

| Prop              | Type                 |
| ----------------- | -------------------- |
| **`productId`**   | <code>number</code>  |
| **`productName`** | <code>string</code>  |
| **`connected`**   | <code>boolean</code> |

</docgen-api>
