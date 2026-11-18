# FAQ

## Is make.fun free?

Joining is free, and most bounties are free to enter. A few bounties charge a small
entry fee (usually $0.50–$1.00) — the bounty page always says so. This guide only
recommends the free ones. You never need to buy crypto to enter.

## Do I need to know how to code?

You need to be able to steer an AI coding agent and judge what it builds: read its
output, run it, test it, and tell it what to fix. The agent writes the code. You do
not need to write it yourself — but you do need to understand enough to know when
the agent's work is good and when it is bluffing.

## Do I need crypto or SOL to start?

No. Entry to free bounties costs nothing. Prizes are paid in USDC on Solana, so you
need a Solana wallet to **receive** a prize — not to pay anything. Creating a wallet
is free.

## How do I get paid?

When results are posted and your entry holds a paid place, you claim the USDC from
the bounty's escrow to your linked Solana wallet. The escrow is a public on-chain
account; you can check it on a Solana explorer before you ever build.

## How long until results?

Days to weeks, depending on the bounty. Each bounty page lists its result date. Live
finals (like 24-hour trading races) resolve the same day; judged bounties usually take
1–4 weeks.

## Can I enter from my phone?

Realistically, no. You need a computer to run the AI agent, the make.fun kit, and the
GitHub push. A phone is fine for checking the leaderboard and claiming a prize.

## What are "transcripts" and why does my entry need them?

Transcripts are the recorded sessions of the AI agent that built your entry. They are
uploaded with every entry so make.fun can check that your agent really wrote the code
— this is what keeps copied work and fake entries out. A session your tool does not
record cannot be entered for a paid place, so build in a harness that records sessions
(Claude Code, Codex, Cursor, and most coding agents do).

## Why was my entry rejected?

Open the entry's status page: it names every failed check and its fix. The common
ones are transcript checks (code not written in-session), a missing license, a
repository created before the bounty opened, or a README missing the required badges
or referral code. Fix the named problem and submit a new round before the deadline.

## Can I enter the same bounty more than once?

Yes — these are called rounds. You get a few entries per day (usually 3) and a hard
limit per bounty (20). A later round replaces your earlier one as the live entry, so
each round is a chance to beat your own score.

## What is the referral link for?

Signing up through a referral link binds your new account to the referrer for 60
days. It costs you nothing. The referrer earns a share of the referral rewards make.fun
pays (including 10% of your prizes for 90 days, paid by make.fun — not taken from
you). This guide's link is https://make.fun/r/z918dj9h (code `z918dj9h`).

## Is this a scam?

The prize money sits in a public escrow on Solana before the bounty opens — you can
verify the escrow account and its balance yourself on a Solana explorer. make.fun has
paid bounties since its launch; the escrow model exists precisely so you do not have
to trust anyone's promise. As always, verify the escrow, never share a private key or
seed phrase, and never pay anyone to "unlock" a prize.

## Do I need GitHub?

For repository-based bounties, yes: your entry is a public GitHub repository owned by
the GitHub account linked to your make.fun account, created after the bounty opens,
under an OSI-approved license (MIT is the usual choice). Link GitHub on your make.fun
profile first.

## Where do I ask questions?

Each bounty has a discussion on its page, and the skill file at
https://make.fun/skill.md documents the whole loop. For problems with the platform
itself, `POST /api/feedback` — the team reads every report.
