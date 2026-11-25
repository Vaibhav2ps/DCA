# ⚡ DCA Engine

A fast, lightweight, and responsive **Crypto Futures DCA (Dollar-Cost Averaging) Calculator** built with pure HTML, CSS, and JavaScript. Designed to help futures traders plan safety orders, manage margin multipliers, calculate average entry prices, and set hard stop-loss levels before entering a trade.

🔗 **Live Demo:** [https://github.io](https://github.io)

---

## ✨ Features

* **LONG & SHORT Visual Modes:** Dynamic theme switching (Green for LONG, Red for SHORT) to prevent accidental direction errors.
* **Custom Target Profit (%):** Calculate exact Take-Profit exit prices for any custom ROI percentage.
* **One-Click Copy:** Click any Trigger Price, Average Entry, Target Profit, or Hard Stop Loss value to copy it instantly to your clipboard.
* **Risk & Liquidation Management:** Automatically calculates total capital required, estimated liquidation price per order, and a `-50% ROI` Hard Stop Loss to protect 50% of your allocated funds.
* **Auto-Save State:** Uses browser `localStorage` to remember your last inputs and calculation results even after refreshing the page.
* **Zero Dependencies:** Single-file architecture (`index.html`)—no frameworks, no API keys, and works completely offline.

---

## 🛠️ How to Use

1. **Direction:** Select `LONG` or `SHORT`.
2. **Entry Price ($):** Enter your initial order price.
3. **Leverage (x):** Set your futures leverage (e.g., `20`, `40`, `50`).
4. **First Margin ($):** Enter the margin amount for Order #1.
5. **Multiplier (x):** Set the margin scaling factor for subsequent DCA orders (e.g., `1.5` or `2.0`).
6. **DCA Trigger Drop (%):** Set the ROI drop percentage that triggers the next safety order.
7. **Total Orders:** Choose the total number of orders (initial + safety orders).
8. **Target Profit (%):** Enter your desired ROI target (default `100%`).
9. Click **Calculate Now** and click any price in the table to copy it directly to your exchange.

---

## ⚠️ Disclaimer

This tool is built for educational and trade-planning purposes only. Estimated liquidation prices and stop-loss calculations do not account for exchange-specific maintenance margin rates, funding fees, or trading fees. Always verify numbers on your exchange before placing live orders.
