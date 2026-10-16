# Kitty Manager (Om Kitty) — free & open source

A simple, mobile-friendly manager for a **discount (boli) kitty / chit fund** that runs in any browser.
No login, no server, no fees. Start with **Om Kitty**, or tap **+ New kitty** to make your own with
your own name, members and installment. Every kitty follows the **same rules**.

**Live app:** https://kumar3216549.github.io/om-kitty/ (or open `index.html` on your phone)

## Make your own kitty (2 minutes)

1. Open the app and tap **+ New kitty**.
2. Enter the kitty name, number of members (= number of months) and the monthly installment (kisht).
3. Paste member names, one per line (you can rename them later).
4. Keep or change the caller bonus (default ₹500 / ₹400 / ₹200) and the promoter month (default month 3).
5. Tap **Create kitty**. Switch between kitties from the drop-down at the top.

## The rules (same for every kitty)

| Step | Formula |
|---|---|
| Pot | members × installment |
| Winner payout | pot − winning discount (boli) |
| Net dividend | discount − total caller bonus (2nd + 3rd + 4th caller) |
| Payable per member | installment − net dividend ÷ members, **rounded up to ₹100** |
| Rounding extra | goes to the promoter |
| Promoter month | no boli; promoter takes the full pot; everyone pays the full installment |
| Foreman commission | none |
| A member can lift the pot | only once |

Each month: enter the boli, winner and callers → tick who has paid → **Submit / Month close** (locks the month).
Share the month's hisaab on WhatsApp, export PDFs, and see the consolidated report of all submitted months.

## Your data

All data stays **in your own browser** (localStorage) — nothing is uploaded anywhere.
Use **Backup data** to save a file and **Restore from backup file** to move it to another phone.
Each kitty has its own backup.

## Run your own copy

1. Click **Fork** on GitHub (or download `index.html`).
2. In your fork: **Settings → Pages → Deploy from branch → main / root**.
3. Your app is live at `https://<your-username>.github.io/om-kitty/`.

It's a single `index.html` file (React + Tailwind from CDN), so there is nothing to build.

## Contributing

Issues and pull requests are welcome — bug fixes, translations, better reports.
Please keep the calculation rules above unchanged unless the change is discussed in an issue first.

## License

[MIT](LICENSE) © 2026 Sachin Kumar Jha
