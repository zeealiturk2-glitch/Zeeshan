# Claude Setup Guide for Zeeshan Ali

Maintenance Manager at Hamat. Follow the steps in order; each takes a few minutes.
Menu names can change a little between app versions. If you cannot find one,
look in **Settings** or ask Claude "where is ___ in settings?".

---

## Step 1: Your profile

Open **claude.ai → your name (bottom left) → Settings → General / Profile**.

**What should Claude call you?**

```
Zeeshan
```

**What best describes your work?** Choose *Engineering*, *Operations* or the closest option.

**Personal preferences**: copy and paste this whole box:

```
My name is Zeeshan Ali. I am the Maintenance Manager at Hamat in Saudi Arabia.
I am on the client side: contractors (for example MOFCO Group) send me
quotations, and I review, compare, approve and follow up on their work.

Please:
- Reply in simple, clear English with short steps and lists.
- When I share a quotation, check all quantities, prices and totals, and tell me
  what is missing (currency, 15% VAT, validity, payment terms, warranty, schedule).
- Write emails and letters to contractors in a formal, polite style, ready to send.
- Ask me before guessing facts about my work.
```

## Step 2: Turn on memory

**Settings → Capabilities** (or **Memory**): turn on **memory / reference past chats**.
Claude will then remember your work across chats.

## Step 3: Make a Project for your work

On claude.ai click **Projects → New project**. Name it **Maintenance – Hamat**.

- **Project instructions**: paste the same text from Step 1.
- **Project files**: upload documents you use often (contractor quotations,
  price lists, contracts, maintenance schedules).

Start every work chat inside this project, so Claude always has your files.

## Step 4: Connect your apps (optional)

**Settings → Connectors**. Useful ones:

| Connector | What Claude can do |
|---|---|
| Gmail or Outlook | Read contractor emails, draft replies |
| Google Drive or OneDrive | Find and read your quotations and reports |
| Google Calendar | Plan site visits and maintenance dates |

Only connect accounts you are allowed to use for work.

## Step 5: Install the apps

- **Phone**: install **Claude** from the App Store or Google Play. Sign in with
  the same account. Good for quick emails and photos from site.
- **Computer**: use **claude.ai** in the browser, or install the **Claude desktop app**.
- **Claude Code** (what you are using now): for working with files saved in
  GitHub. The `CLAUDE.md` file in this repository tells it who you are.

## Step 6: Stay safe

- Never type your Claude password or card details into other websites or
  "unlimited tokens" tools. No tool can raise your limit; only your plan can.
- See your usage in **Settings → Usage**.
- Start a new chat for each new task. Long chats use up your limit faster.

---

## Ready-made prompts for daily work

Copy, fill in the brackets and send.

**Check a quotation**
> Review this contractor quotation. Check all totals, list anything missing or
> unclear, and tell me if any prices look high. [attach PDF]

**Compare offers**
> Compare these [2/3] quotations for [work]. Make a table of price, scope,
> warranty and terms, and recommend one. [attach files]

**Ask a contractor to correct an offer**
> Write an email to [contractor] asking them to revise quotation [ref no.]:
> add the currency, state VAT, and correct the warranty text.

**Approve work**
> Write a formal approval letter to [contractor] for quotation [ref no.],
> total [amount] SAR, starting [date].

**Maintenance plan**
> Make a preventive maintenance schedule in Excel for [fire fighting pumps /
> HVAC / generators] with monthly, quarterly and yearly tasks.

**Report to management**
> Write a one-page report on [work] for my manager: what was done, cost,
> problems, and next steps.
