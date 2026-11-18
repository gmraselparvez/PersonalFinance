<div align="center">

# Personal Finance

**A focused personal finance workspace for macOS + Web.**

Track your money, budgets, cards, loans and recurring payments — without the spreadsheet clutter.

<br>

[![Version](https://img.shields.io/badge/version-1.17-7C5CFF?style=flat-square)](../../releases)
[![Build](https://img.shields.io/badge/build-144-111827?style=flat-square)](../../releases)
[![macOS](https://img.shields.io/badge/macOS-native-000000?style=flat-square&logo=apple&logoColor=white)](../../releases)
[![Web](https://img.shields.io/badge/web-live-2563EB?style=flat-square&logo=vercel&logoColor=white)](https://personalfinance-webapp.vercel.app/)

**[🚀 Open Web App](https://personalfinance-webapp.vercel.app/)** · **[📦 Download macOS](../../releases)**

</div>

---

## Overview

Personal Finance brings everyday money tracking into one place.

| | macOS | Web |
|---|:---:|:---:|
| Dashboard | ✓ | ✓ |
| Transactions & Income | ✓ | ✓ |
| Budgets | ✓ | ✓ |
| Accounts & Savings | ✓ | ✓ |
| Loans & Credit Cards | ✓ | ✓ |
| EMI & Transfers | ✓ | ✓ |
| Reports | ✓ | ✓ |
| Cloud Sync | ✓ | ✓ |
| Offline Tracking | ✓ | — |
| Backup & Restore | ✓ | ✓ |

---

## What you can manage

**Dashboard** — income, expenses, budget remaining, assets, available money and visual spending insights.

**Money** — transactions, income, bank/cash accounts and savings.

**Planning** — master budgets, monthly budgets and upcoming payments.

**Credit & Debt** — loans, credit cards and EMI plans with dedicated tracking.

**Transfers & Reports** — move money between accounts and review your financial activity.

**Sync & Backup** — cloud synchronization plus backup and restore.

---

## Credit Card Logic

Available credit accounts for obligations that have already been posted **and** commitments that have not settled yet:

```text
Available Credit
= Credit Limit
− Current Outstanding
− Unsettled / Pending Card Purchases
− Remaining EMI Amount
```

This keeps pending purchases and future EMI obligations from appearing as freely available credit.

---

## macOS First Launch

When downloading the macOS app outside the Mac App Store, **Gatekeeper may ask you to confirm the first launch**.

If you downloaded the app from the official GitHub Release and trust the source:

1. Open `PersonalFinance.app` once.
2. Go to **System Settings → Privacy & Security**.
3. Under **Security**, click **Open Anyway** for PersonalFinance.app.
4. Confirm **Open Anyway** in the final dialog.

<div align="center">

<table>
<tr>
<td align="center"><img src="assets/gatekeeper/01-gatekeeper-blocked.png" width="220" alt="Gatekeeper warning"></td>
<td align="center"><img src="assets/gatekeeper/02-privacy-security-open-anyway.png" width="360" alt="Privacy and Security Open Anyway"></td>
<td align="center"><img src="assets/gatekeeper/03-open-anyway-confirmation.png" width="220" alt="Open Anyway confirmation"></td>
</tr>
</table>

</div>

> **Security note:** Only bypass Gatekeeper when the app came from a release source you trust. The warning means macOS could not verify the app through its available trust mechanism; it does not by itself identify the app as malware.

---

## Production

### `v1.17 · Build 144`

A big design and accuracy update for the macOS app.

- **Accurate budgets** — Dashboard Expense and Budget Remaining count only Monthly Budget categories; off-budget spending is never included. Budget vs Actual shows every category with a budget-limit marker.
- **Consistent, responsive lists** — Transactions, Income, Transfers, Monthly and Master Budget share one row style and fit any window width (no sideways scrolling). Transactions can be grouped daily, weekly or monthly, and pending card purchases are always visible.
- **Details on double-click** — open any transaction, income or transfer in a details popup.
- **Credit cards** — "This Statement" summary with due countdown and reminder; completed EMIs archived per card.
- **Reports** — income trend chart and PDF export.
- **Faster entry** — remembers your last category and account, suggests categories from past descriptions, and accepts amounts like `1.5k`, `2L` or `120+80`.
- **Polish** — calendar date picker, clock-style time picker, grouped sidebar, keyboard shortcuts (⌘1–9, ⌘←/⌘→, ⌘F), undo after delete, budget alerts and a cleaner single-page Settings with a live sync status.

Previous: `v1.0 · Build 125` — the first production release.

**[View releases →](../../releases)**

---

## Privacy

This public repository contains **product documentation and release information — not application source code or private financial data**.

Never publish passwords, API keys, authentication tokens, bank/card numbers, transaction exports or private database files.

---

## Support

Found a bug or have a feature request? Open a GitHub Issue with:

- Platform + app version/build
- Steps to reproduce
- Expected vs actual behavior
- Screenshot or recording when useful

Please remove private financial information before posting.

---

<div align="center">

**Personal Finance · v1.17 Build 144**

[Web App](https://personalfinance-webapp.vercel.app/) · [Releases](../../releases) · [Issues](../../issues)

</div>
