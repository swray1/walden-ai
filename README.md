# walden-ai

### The operating system behind modern, AI-native accounting and finance work

The skills, workflows, and thinking I use to run our CFO agency at [Walden](https://www.waldensg.com/) in a fraction of the hours it used to take.

---

## Who this is for

**The finance pro who can feel the ground moving.** Controller, CFO, senior accountant — you can already see that "AI-native" is becoming the line between the operators who compound and the ones who get compressed. You'd rather be early.

**The CPA who's out of hours, not out of demand.** Work is stacking up faster than you can staff it. Slow responses cost you money and strain relationships. You need leverage, not another hire.

**The bookkeeper or accountant hitting the same ceiling.** Overworked, underpaid, and out of room. You want to take on more client work without trading more of your life for it.

**The business owner who's just tired.** You landed here because you're drowning in the exact busywork these skills automate.

---

## What's in here

These are [Claude Code skills](https://docs.claude.com/en/docs/claude-code/skills) — reusable instruction sets that Claude picks up on its own when your request matches one. Every skill here started as a repetitive task we caught ourselves doing over and over. The ones that show up first:

- **Bank statement analysis** — turn months of statements into recurring transactions, fixed vs. variable costs, and a break-even number.
- **QBO audit-log analysis** — read a QuickBooks audit log to see what work is being done, how long it takes, and where the books are thin.
- **AR / report formatting** — convert QBO screenshots and reports into clean, paste-ready spreadsheet tables.
- **Cost & break-even modeling** — go from raw numbers to a monthly cost structure and the revenue you need to clear it.
- **Client outreach & marketing** — cold outreach, pitches, and marketing plans built around a real signal, not a template.

Each skill is a `SKILL.md` (the instructions Claude reads) plus any templates it needs. Open one up, copy the pattern, build your own.

---

## Use it in 60 seconds

```bash
git clone https://github.com/swray1/walden-ai.git
cd walden-ai

# Grab one skill
cp -r skills/bank-statement-analyzer ~/.claude/skills/

# Or take everything
cp -r skills/* ~/.claude/skills/
```

Reload Claude Code and it picks them up automatically. When your request matches a skill, Claude reaches for it on its own — you don't have to name it.

**If this saved you an hour, star the repo.** That's the only "payment" the free tier asks for, and it's how the next person like you finds it.

---

## Pick your door

### → You want to go AI-native
You're in the right place. Take the skills, fork the repo, build on them. Then [follow me on LinkedIn](#) — that's where I publish these systems before they're packaged. The operators who move first are the ones I end up building with.

### → You're a CPA with clients who need CFO work
Refer the CFO work and get paid for it. You keep doing what you're great at, your clients get the strategy layer, and you earn on the referral. **[Partner program terms — see PARTNERS.md](#).**

### → You're a bookkeeper hitting the CFO ceiling
Same idea, your direction. When a client outgrows the books, refer the CFO work up instead of losing the account. You stay the trusted contact, keep the relationship, and get paid on the referral. **[Partner program terms — see PARTNERS.md](#).**

### → You're an operator done with the busywork
Two ways I can help:
- **[Walden Solutions Group](https://www.waldensg.com/)** runs your finance function for you — fractional CFO and bookkeeping, the same workflows this repo automates, pointed at your books.
- **[Casterly.ai](#)** forecasts your cash flow from live bank data. No manual QuickBooks syncing, no spreadsheets — just your real cash position, before it becomes a problem.

---

## For CFOs, CPAs, and bookkeepers serving clients

Casterly isn't only a tool for you — it's one you can deploy for *them*. Live-bank-data cash forecasting you can put in front of every client under your advisory. Partners get early access and preferred terms. **[Get on the partner list](#).**

---

## Who's behind this

I'm Stephen — founder of [Walden](https://www.waldensg.com/) and building [Casterly.ai](#) in every other waking hour. I'm relentless about finding faster ways to deliver value with less effort. If you found this repo, you already sense there's an easier way to make yourself and your business more money — you're just not sure how. This is a step on that path.

If you got value here, the best thanks is a ⭐ and a share with the one finance person in your life who needs to see it.

## License

[MIT](LICENSE) — use them, fork them, ship them, bill with them. Attribution appreciated, never required.
