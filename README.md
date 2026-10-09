# Komma TPV

The store till of **Komma ERP**. It sells, charges, prints and runs the cash
drawer of a store.

## Download

| System | Download |
| --- | --- |
| **Windows 10 and 11** (64-bit) | [Latest version](https://github.com/komma-softhouse/komma-tpv-releases/releases/latest): the `.exe` file |
| **macOS 12 or later** (Apple silicon Mac) | [Latest version](https://github.com/komma-softhouse/komma-tpv-releases/releases/latest): the `.dmg` file |

Every published version is listed under
[Releases](https://github.com/komma-softhouse/komma-tpv-releases/releases).
The easiest way is to download it from the ERP itself, in
**System → Store apps**, which always links the latest version.

## What it does

- **Sells with the scanner, the keypad or the touch screen.** Barcodes, IMEIs,
  coupons and article search. Promotions apply by themselves, exactly as in the
  ERP.
- **Charges the way the store charges.** Cash with change, card, Bizum, bank
  transfer, financing with its file number, vouchers, points and customer
  deposits, mixed when needed, and gift receipts.
- **A fiscal ticket from the first moment.** Every ticket carries its number,
  its fiscal record and its QR, as if the ERP had made it. With the company in
  VERI\*FACTU the till numbers and chains its own tickets even when the network
  is down, and uploads them to the ERP when it comes back.
- **Runs the drawer.** Opening with a float, cash in and out, drawer openings,
  and closing with notes withdrawn, the card terminal total and the coin count,
  with its printed report.
- **Everything at the counter.** Top-ups with their operator and number,
  reservations, deposits, repair orders with two labels, used-device purchase
  contracts signed on screen with both sides of the ID, returns as a voucher or
  money, payment changes and invoices from a ticket.
- **Store logistics.** Shipments to other stores, receptions reporting
  differences, scanned stock counts and serial number lookup with its history.
- **Clocking.** Every employee clocks in and out with their personal code, even
  without network.
- **Updates itself.** It downloads every new version on its own and lets the
  seller install it at once or at the till closing.

## Install

### Windows

1. Download the `.exe` file of the
   [latest version](https://github.com/komma-softhouse/komma-tpv-releases/releases/latest).
2. Open it. If Windows shows "Windows protected your PC", click
   **More info → Run anyway**.
3. Komma TPV appears in the Start menu and on the desktop.

### macOS

1. Download the `.dmg` file of the
   [latest version](https://github.com/komma-softhouse/komma-tpv-releases/releases/latest).
2. Open it and drag **Komma TPV** into **Applications**.
3. Open it from Applications. The app is signed and notarized by Apple, so
   macOS opens it without warnings.

## Getting started

1. **In the ERP**, go to **Tills and printing → Devices → Pair a till** and
   choose the till. A code and its QR appear, valid for 15 minutes and for a
   single use.
2. **On the till**, read the QR with the barcode scanner (or type the ERP
   address and the code), name this till and click **Pair**. The catalogue,
   customers, employees, stock and the company's fiscal data are downloaded.
3. **Printer:** in **Settings**, choose how the thermal printer is connected
   (network, shared USB printer on Windows or a printer added in macOS) and
   click **Print a test**. The cash drawer is connected to the printer.
4. **Start selling:** sign in with your personal code, open the till with its
   float and scan the first article.

## Requirements

- Windows 10 or 11 (64-bit), or macOS 12 or later on an Apple silicon Mac
  (M1 or later).
- 4 GB of RAM and 1 GB of free disk space.
- An ESC/POS thermal printer, 80 or 58 mm (network, shared USB printer on
  Windows or a printer added in macOS) and, when used, a cash drawer connected
  to it.
- A USB barcode scanner in keyboard mode that reads 2D codes, to read the
  pairing QR.
- A connection to the company's ERP to pair it.

## Updates

The till looks for new versions when it starts and every hour, and downloads
them on its own.

- **On the sale screen** a strip offers **Update now** or **Schedule it for the
  till closing**. It never restarts in the middle of a sale.
- **On the pairing, sign-in and Settings screens**, **Check for updates**
  downloads a new version, shows its progress and restarts the till updated.
- A downloaded version nobody installed is installed the next time the till is
  closed.

## When something fails

When the till hits an unexpected error it shows an incident code and a button
to report it. The report reaches Komma with the code, the version and the
screen, without sales or customer data. Keep the code at hand if you call
support.

## Support

Komma SoftHouse · [kommasofthouse.com](https://kommasofthouse.com) · info@kommasofthouse.com