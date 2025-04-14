---
title: Creating a ZRA smart invoice
deprecated: false
hidden: false
metadata:
  robots: index
---
We at Namiri Technologies, through our DigiTax Platform, have developed a suite of solutions:

* **DigiTax App** (Mobile PWA) - Coming soon
* **DigiTax Dashboard** (Web Browser-based Desktop application for e-invoicing) and
* **DigiTax API** (for system-to-system integration without the issue of platform hopping).

You can create an ZRA smart invoice through these three DigiTax solutions.

## ZRA smart invoice details

If you have joined any DigiTax webinar, then you know how to generate an invoice via the DigiTax dashboard. If you have not already joined, we invite you to email us at **[zambia@namiri.tech](mailto:zambia@namiri.tech)** and we'll set you up.

Below is a link to a recording showing how to create a Smart Invoice on the API.

[ZRA Smart Invoice on the DigiTax API](https://drive.google.com/file/d/1BgJjyE5qVhiSJQCFiPcJWpUuxiQgJEjR/view?usp=sharing)

### ZRA smart invoice sections

Below is a ZRA smart invoice with sections highlighted.

***

An ZRA smart invoice has three key components: (They are highlighted above)

1. A **QR code** redirecting to a URL on "zra.org.zm"

   The QR code above redirects to this URL: \<[https://sandboxportal.zra.org.zm/common/link/ebm/receipt/indexEbmReceiptData?Data=2002720806000WOV5SPYFHNJR6K4F](https://sandboxportal.zra.org.zm/common/link/ebm/receipt/indexEbmReceiptData?Data=2002720806000WOV5SPYFHNJR6K4F)>

   The structure is `https://sandboxportal.zra.org.zm/common/link/ebm/receipt/indexEbmReceiptData` `?Data=` `{TPIN} (10 digits)` `{ZRA Branch ID} (3 Digits)` `{Signature}`
2. The **tax breakdown** of that invoice
3. **Smart Invoice metadata** that includes:
   * Date and Time of transaction
   * Invoice number
   * Signature
   * Internal Data