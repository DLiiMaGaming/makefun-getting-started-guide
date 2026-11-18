# Getting Started with make.fun

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/DLiiMaGaming/makefun-getting-started-guide/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/DLiiMaGaming/makefun-getting-started-guide/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

A beginner-first guide to your first make.fun bounty — from creating an account to claiming your reward. No coding experience required.

## What is make.fun?

make.fun is a platform where you build entries for bounties together with your AI agent — and get paid in USDC on Solana when your work earns a reward.

A sponsor posts a bounty with a clear brief and a prize, you build the entry with your AI agent, you submit it, and make.fun checks and scores it fairly.

Every bounty has a public brief, a stated reward, and a checking process, so you never guess what the sponsor wants. Your work is recorded in a transcript, so checking is based on what actually happened.

Most bounties are free to enter. The reward is locked in escrow up front, so the money is already set aside — and if your entry earns a reward, the payout comes from that escrow in USDC on Solana.

This guide is for the "bring the humans" competition, **bring-the-humans-02**, running **18 Nov 2026, 17:30 WIB to Saturday 21 Nov 2026, 17:30 WIB**. There is **$1,000 in total prizes, shared by the 50 highest-ranked entries**, and your score is the number of verified human signups your referral link brings in during that window.

> **Start here — sign up with my referral link**
>
> Create your make.fun account through my link — you will count as one of my verified signups for this competition:
>
> **https://make.fun/r/j2n618jy**
>
> Referral code: **j2n618jy**
>
> Use that link first, then come back and work through the steps below. It takes a couple of minutes, and it is the most useful thing you can do before you start building.

## Contents

- [What is make.fun?](#what-is-makefun)
- [How make.fun works](#how-makefun-works)
- [What you need](#what-you-need)
- [Step 1. Create your account](#step-1-create-your-account)
- [Step 2. Pick a bounty](#step-2-pick-a-bounty)
- [Step 3. Get the kit](#step-3-get-the-kit)
- [Step 4. Build your entry](#step-4-build-your-entry)
- [Step 5. Bundle, check, submit](#step-5-bundle-check-submit)
- [Step 6. Status, fix, resubmit](#step-6-status-fix-resubmit)
- [Step 7. Claim your reward](#step-7-claim-your-reward)
- [Let your agent do the whole thing](#let-your-agent-do-the-whole-thing)
- [Earn with your own referral link](#earn-with-your-own-referral-link)
- [Tips for a first entry](#tips-for-a-first-entry)
- [FAQ](#faq)
- [Links](#links)

## How make.fun works

Every bounty follows the same five stages.

**1. Open.** The bounty is live. Read the brief, the rules, and the deadline before you build anything — the bounty page and its kit are the source of truth.

**2. Submitted.** You bundle your entry and submit it through the make.fun CLI. Keep a copy of everything you submitted.

**3. Checked.** make.fun checks your submission against the bounty rules. The transcript shows the recorded work session behind your entry, confirming it was built in the allowed way and inside the window.

**4. Scored.** Checked entries are scored according to the bounty brief. For this competition, the score is verified human signups brought in by your referral link during the window. Other bounties score whatever their brief says — read it carefully.

**5. Paid.** If your entry earns a reward, the payout is released from escrow in USDC on Solana to your connected wallet — see [Step 7](#step-7-claim-your-reward).

Three things are worth remembering:

- **The reward is locked in escrow up front.** The sponsor commits the prize before entries are built.
- **Transcripts keep it fair.** Your agent session is recorded from the moment the competition opens — evidence your entry was built properly, in a fresh session, inside the window. Start recording before you write anything.
- **Most bounties are free to enter.** You pay nothing to submit; your costs are your time and whatever your AI agent normally costs you.

## What you need

You need four things before your first bounty. None of them is exotic, and you probably already have two of them.

- **An AI agent.** The tool that builds with you. It writes files, runs checks, fixes errors, and keeps the transcript. You instruct it in plain language; it does the detailed work and reports back.
- **A GitHub account.** Entries live in public GitHub repositories. Create one for your entry; your agent pushes its work there. If you do not have an account yet, create a free one at github.com and confirm your email first.
- **Node 22.** The make.fun CLI runs on Node.js — install version 22. A much older version can cause confusing errors that look like a broken kit.
- **A Solana wallet.** Rewards are paid in USDC on Solana. Connect a wallet you control, and double-check the address — losing access to it means losing the payout.



Start from the referral link. It matters which link you use first, because the first link you sign up through is the one that gets credit for bringing you in.

## Step 1. Create your account

1. Open **https://make.fun/r/j2n618jy** in your browser.
2. Create your make.fun account and complete the sign-up steps on screen.
3. Link your **GitHub account**. This connects your identity to the repositories your entries will live in.
4. Link your **Solana wallet**. This is where USDC rewards will go if you earn one. Double-check the address before you confirm it.
5. Install the make.fun CLI and log in from your terminal, following the instructions on the site, so your later submissions are tied to this account.

If anything here fails, fix it before moving on — a half-linked account creates problems at submission time.

## Step 2. Pick a bounty

Browse the bounties page like a menu, not a race — look for a bounty you can actually finish well before its deadline.

Read the whole brief before you choose: what to build, what the kit contains, how it is scored, and when the window closes. An exciting bounty you cannot finish is a worse pick than a simpler one you can finish cleanly.

For this competition, the bounty is bring-the-humans-02: write a beginner-friendly getting-started guide to make.fun, publish it as a public GitHub repository, and share your referral link. Score is verified human signups your link brings in between 18 Nov 2026, 17:30 WIB and Saturday 21 Nov 2026, 17:30 WIB; the total prize pool is $1,000, shared by the 50 highest-ranked entries.



## Step 3. Get the kit

Every bounty ships with a kit. The kit is a small download that tells you exactly what to build and how your entry will be checked.

1. From the bounty page, download the kit for the bounty you picked.
2. Unzip it somewhere you can find it again.
3. **Read `RULES.txt` first.** The most important file in the kit: the authoritative rules — what counts, what does not, and what gets an entry rejected. If the page and the kit ever seem to disagree, trust the rules file.
4. Then read the rest of the kit — starter files, examples, submission instructions — so you know what the finished entry should look like before writing a word.



## Step 4. Build your entry

This is where your AI agent earns its keep. The flow below is the real flow behind entries such as Port Solano and VOIDBLOOM, in beginner terms — the same pattern works for a game entry and a guide entry like this one.

**Start a fresh agent session after the competition opens.** This is a hard rule. Open a brand-new session once the window is live, and start the recording (the transcript) before you write or build anything. Work done in an old session, or before the opening time, does not count. If unsure whether your session is fresh, close it and start a new one.

**Give the agent the kit and the brief.** Point it at the bounty page, the kit, and `RULES.txt`, and tell it in plain language what the finished entry must contain — and to ask before doing anything the rules forbid.

**Use an OSI-approved licence.** Your entry must use a licence on the Open Source Initiative's approved list, such as MIT or Apache-2.0. Make sure the licence file is in the repository and the agent does not invent its own licence text. If the kit names a specific licence, use that one.

**Let the agent build, and review as it goes.** For a game entry such as Port Solano, the agent writes the code, builds the game, tests it, and fixes what breaks. For a guide entry, it writes the guide, checks the links, and tidies the formatting. The transcript records every step — exactly what the checkers need. Do not paste in outside work and pretend the agent did it; gaps in the transcript are visible.

**Check the work yourself.** Open the repository, read the guide, click the links, and try the steps as a beginner would. If a step confuses you, it will confuse a reader too — ask the agent to rewrite it. Quality means a stranger can follow your entry from start to finish without getting stuck.

## Step 5. Bundle, check, submit

When the entry is built and you have read it through, submit calmly, in order — do not rush the last step.

1. **Bundle.** Package your entry the way the kit instructs. For a guide entry, that means the finished repository with its README, licence, and any files the rules require — nothing extra, nothing missing.
2. **Check.** Run every check the kit provides, and read the results. If a check fails, fix the cause and run it again.
3. **Submit.** Submit through the make.fun CLI with the same logged-in account from Step 1. Wait for the confirmation, and note the submission ID it gives you — your proof of submission, so save it somewhere safe.



## Step 6. Status, fix, resubmit

After you submit, your entry has a status. Check it, and act on what it says.

- If the status is good, leave it alone — your entry will be scored when the window closes.
- If it shows a problem, read the message carefully — it tells you what failed: a missing file, a broken link, a licence issue, a transcript gap. Fix exactly that problem and resubmit following the kit's instructions.
- If you are unsure what the status means, re-read `RULES.txt` and the bounty page before changing anything — guessing at a fix often creates a second problem.



## Step 7. Claim your reward

If your entry earns a reward, the payout comes from the escrow in USDC on Solana.

1. Wait for scoring to finish after the window closes — scores are final only once the verified signups have been counted.
2. Check your entry's result on the bounty page and confirm the reward amount shown.
3. Follow the claim instructions on the site to release the USDC from escrow to your connected Solana wallet.
4. Confirm the USDC arrived in your wallet, and keep a record of the claim — a screenshot or a note with the date and amount.



## Let your agent do the whole thing

If you would rather hand the whole job to your agent, copy the prompt below and paste it into a fresh agent session started after the competition opens. Start the recording first, then paste.

> You are my agent for the make.fun bounty bring-the-humans-02. Read the bounty page at https://make.fun/bounty/bring-the-humans-02 and the kit I downloaded, starting with RULES.txt, and follow the rules exactly. Create a public GitHub repository named makefun-getting-started-guide under my account, and write an original, beginner-friendly getting-started guide to make.fun in README.md, about 1,800 to 2,600 words, in friendly tone and GitHub-flavoured Markdown. Include my referral link https://make.fun/r/j2n618jy and code j2n618jy where the outline asks. Use an OSI-approved licence. Do not use an old session, do not copy any starter file, and do not invent prizes, dates, or rules beyond the brief. Check every link, then bundle, check, and submit through the make.fun CLI and report the submission ID and every check result.



## Earn with your own referral link

Once your account is set up, you get your own referral link. Sharing it is how you earn score in this competition — and it is how other people find their way in.

- **First touch wins, for 60 days.** If someone clicks your link first and then signs up, that signup counts for you — even if they see another link later. That first click stays attached to you for 60 days.
- **Only verified, active signups count.** A signup counts only when it is a real, verified human who signs up and becomes active. A click alone is not a signup, and an unverified signup is not a score.
- **Fake or bot signups never count.** Automated signups, bought accounts, and other fake activity do not count — and they can get an entry disqualified. Do not buy signups, run bots, or ask anyone to create accounts they will not use. The honest path is the only path that scores.



## Tips for a first entry

- **Read the rules before you build.** It is the cheapest ten minutes in the whole process.
- **Start the transcript before you start the work.** A session that begins after the work is already done cannot prove the work.
- **Test your own instructions.** Follow your guide as if you had never seen make.fun before — every place you hesitate is a place a reader will get stuck.
- **Keep your links honest.** Check that every link goes where it says it goes, and that your referral link is exactly right. One wrong character sends people nowhere.
- **Submit with time to spare.** Leave room for one fix-and-resubmit cycle — submitting in the last ten minutes turns a small fix into a missed deadline.

## FAQ

**Does it cost anything to enter?**

Most bounties on make.fun are free to enter — you pay nothing to submit. Your only costs are your time and whatever your AI agent normally costs you. If a bounty ever did carry a cost, its brief would say so plainly.

**Is make.fun legitimate?**

Yes. make.fun is run by EZO Labs: public briefs, rewards locked in escrow up front, transcript-based checking, and payouts in USDC on Solana. Still do your own checks — read the bounty page and the kit, and only sign in and connect a wallet on the official make.fun site.

**Do I need to know how to code?**

No. You describe what you want in plain language and review what your agent produces — reading a guide draft and saying what is unclear, or testing a game and describing what is broken. The agent handles the code; you handle the judgement.

**Which AI agents are supported?**

Any capable AI agent that can work in a repository, follow a written brief, and keep a recorded transcript can be used — check the kit and bounty page for the exact expectations, since the transcript and fresh-session rule are part of checking. Pick the agent you already know, rather than learning a new one mid-bounty.

**Is my transcript private?**

Your transcript is the record of your agent session, used for checking your entry — it is shared with the checking process so the work behind your entry can be verified. Never put secrets, passwords, private keys, or wallet seed phrases in any agent session. Nothing in a bounty entry requires them.

## Links

- make.fun — https://make.fun
- Bounty bring-the-humans-02 — https://make.fun/bounty/bring-the-humans-02
- Leaderboard for bring-the-humans-02 — https://make.fun/bounty/bring-the-humans-02/leaderboard
- Sign up with my referral link — https://make.fun/r/j2n618jy
- GitHub — https://github.com
- Node.js — https://nodejs.org
- Open Source Initiative licences — https://opensource.org/licenses

---

*New to make.fun? Start with my referral link: **https://make.fun/r/j2n618jy** — code **j2n618jy**. Sign up, grab a bounty kit, and build your first entry with your AI agent. Good luck — and see you on the leaderboard.*
