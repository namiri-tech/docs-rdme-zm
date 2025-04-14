---
title: 'Getting Started: DigiTax and ZRA Smart Invoicing'
excerpt: >-
  **DigiTax Zambia API Hub** contains guides and API reference pages for further
  understanding, equipping you on how to integrate with the ZRA Smart Invoicing
  System
hidden: false
---
<Cards columns={2}>
  <Card title="Navigation" icon="fa-compass">
    If you're new to the DigiTax Zambia API Hub, learn how to navigate our pages [here](https://zm.docs.digitax.tech/docs/how-to-use-this-site).
  </Card>

  <Card title="Support" icon="fa-question">
    If you get stuck, or have questions, [email us](mailto:support@namiri.tech) OR\
    Talk to us via the **DigiTax chat** on the bottom right of any page.
  </Card>

  <Card title="ZRA integration with DigiTax" icon="fa-bars">
    Explore this page and other detailed guide pages to gain understanding of the ZRA Smart Invoicing System and how DigiTax integration works.
  </Card>

  <Card title="DigiTax Zambia API Reference" icon="fa-plug">
    Get the pre-requisites, explore the API endpoints, and learn its feature set via our **interactive API reference** [here](https://zm.docs.digitax.tech/reference).
  </Card>
</Cards>

<Accordion title="DigiTax is multi-national. Explore other countries here ..." icon="fa-globe">
  You are currently reading a guide in the DigiTax Nigeria API Hub.

  If you're looking for another country or the general homepage for DigiTax API, navigate to the [DigiTax API homepage](https://docs.digitax.tech), or country-specific API hub pages (ordered alphabetically):

  * [DigiTax Kenya API hub](https://ke.docs.digitax.tech)
  * [DigiTax Nigeria API hub](https://ng.docs.digitax.tech)
  * **DigiTax Zambia API hub (You are here 🎉)**
</Accordion>

## Electronic Tax Invoicing in Zambia

African countries lately have been opting to digitize their tax systems by imposing e-Invoicing or Electronic Tax Invoicing and Reporting. Electronic Tax Invoicing is a nascent Fintech category in the Pan-African region.

Zambia is one of the countries and the country's tax authority/ regulator, **ZRA** (Zambia Revenue Authority) has an e-invoicing system, named **ZRA Smart Invoice**. In this documentation, DigiTax Zambia API Hub, we shall simply refer to it as *ZRA Smart Invoice System*.

## What is DigiTax?

**DigiTax is a ZRA-licenced smart invoice solutions provider authorized to provide tax\
compliance software**

> **ZRA** stands for Zambia Revenue Authority

DigiTax Platform, powered by Namiri Technologies Ltd, is a suite of solutions:

* DigiTax App (Mobile PWA),
* DigiTax Dashboard (Web Browser-based Desktop application) and
* DigiTax API

The first two are powered by the DigiTax API :tada:

## Tax in Zambia

ZRA, Zambia Revenue Authority, is an agency of the government of Zambia that is responsible for the assessment, collection and accounting for all revenues that are due to the government in accordance with the laws of Zambia.

There are several tax types:

* [Turnover Tax](https://www.zra.org.zm/tax-information/#turnover-tax)
* [Pay As You Earn (PAYE)](https://www.zra.org.zm/tax-information/#paye)
* [Value Added Tax](https://www.zra.org.zm/tax-information/#VAT) VAT for short
* [Income Tax](https://www.zra.org.zm/tax-information/#income-tax)
* [Withholding Tax](https://www.zra.org.zm/tax-information/#wht)
* [Presumptive Tax](https://www.zra.org.zm/tax-information/#presumptive-tax)
* [Property Transfer Tax](https://www.zra.org.zm/tax-information/#ptt)
* [Excise Duty](https://www.zra.org.zm/tax-information/#exd)
* [Base Tax](https://www.zra.org.zm/tax-information/#base-tax)
* [Insurance Premium Levy](https://www.zra.org.zm/tax-information/#ipl) IPL for short
* [Mineral Royalty](https://www.zra.org.zm/tax-information/#mineral-royalty)

Systems concerning certain tax types have been introduced and have evolved over the years.

The use of an Electronic Fiscal Device (EFD) was mandated by the EFD Law, which was passed through Act Number 17 of 2015. It has been mandatory for taxpayers registered for 2 of the taxes above (VAT and IPL) to procure, install and use an EFD.

### Smart Invoice

More recently, ZRA launched Smart Invoice. Under the new provision, it is mandatory for a taxable supplier to use an electronic invoicing system to record each sale or transaction. Electronic Fiscal Devices have been phased out following the introduction of the electronic invoicing system (Smart Invoice).

Moreover, the EFD implementation only covered Value Added Tax (VAT) and Insurance Premium Levy (IPL) while Smart Invoice will cover more types of taxes or levies such as:

* VAT
* Turnover Tax
* Rental Income
* IPL
* Tourism Levy and
* Local Excise Duty on Electric Energy

The Smart Invoice will also have a component that will provide for stock management. Smart Invoice is here to help more taxpayers become compliant (removing the need for having physical gadgets, the EFDs).

> 📘 Smart Invoice is software based while EFDs was device-based
>
> The implementation of EFDs was mainly based on physical gadgets (devices) while Smart Invoice will be software based.

Once on-boarded to Smart Invoice, you get to leverage the technological convenience this software solution provides.

## Enter DigiTax

DigiTax is your digital solution for effective, simple and painless Smart invoice tax compliance. Our suite of software products enables businesses to transmit smart invoices directly to tax authority in real-time.

**DigiTax** is a solution that sits between you, a taxpayer, and ZRA's smart invoice system.

There are four Smart Invoice solutions with varied Eligibility requirements listed on ZRA's website [here](https://www.zra.org.zm/smart-invoice-learn-more/).

The fourth one, **Certified Invoicing Systems**, involves an integration which is achieved through an interface with the Virtual Sales Data Controller (VSDC) which is a bridge between the Certified Invoicing System (CIS) and the ZRA Smart Invoice System.

However, instead of onboarding directly onto the ZRA Smart Invoice System, a process that requires significant resource investment, both time and technical resources, DigiTax does the heavy lifting for you - Making tax compliance less taxing.

> 👍 The DigiTax Platform does the heavy lifting for you - Making tax compliance less taxing!

In The DigiTax Platform, we have developed a suite of solutions:

* DigiTax POS (Android)
* DigiTax Dashboard (Responsive Web Browser-based Desktop application for e-invoicing) and
* DigiTax API (for system-to-system integration without the issue of platform hopping).