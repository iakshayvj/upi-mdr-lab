# UPI MDR Lab

**A source-led calculator for understanding who pays what under NPCI's 2026 UPI MDR framework.**

[Open UPI MDR Lab](https://iakshayvj.github.io/upi-mdr-lab/)

## The story

The new UPI MDR rules generated plenty of headlines and very little usable clarity. I wanted a tool where a merchant or consumer could change the amount and business parameters, see the result immediately, and trace the logic back to the actual NPCI material.

UPI MDR Lab is built around the [NPCI FAQ dated 15 September 2026](https://www.npci.org.in/uploads/FA_Qs_Merchant_Discount_Rate_MDR_on_Select_UPI_P2_M_Transactions_58dba1d39e.pdf), not press summaries.

## What it covers

| | Mode | What it answers |
|---|---|---|
| 🏪 | Merchant | Estimated acceptance cost for the transaction and selected merchant profile |
| 👤 | Consumer | Makes the distinction between merchant MDR and the consumer's ₹0 direct UPI fee |
| 🧾 | GST estimate | Shows optional GST on the fee without hiding it inside the base MDR |
| 📊 | Volume | Lets merchants model the effect across monthly transaction volume |
| 🏷️ | Classification | Handles standard P2M, P2PM, industry-programme and capital-market treatment |
| 🔎 | Boundary logic | Applies the amount and classification thresholds explicitly |

## Privacy

Everything runs in the browser. Transaction values and business inputs are not sent anywhere.

## The honest bit

This is an interpretation and planning tool, not legal, tax or payment-network advice. NPCI can clarify or revise implementation details, and acquirer pricing can differ from the framework shown here. The dated primary source above is the reference point for this version.

## Run it locally

Open `index.html` in a browser. There is no build step and no backend.

## Built with Instinct

I set the brief and product questions. **Instinct researched the NPCI framework from the primary source, translated the rules into calculator logic, designed and built the interface, tested the boundary cases, and published the site to GitHub Pages.**
