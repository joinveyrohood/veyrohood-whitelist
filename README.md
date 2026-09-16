# VeyroHood Verify

Public site (after Pages is on):
https://joinveyrohood.github.io/veyrohood-whitelist/

Repo: https://github.com/joinveyrohood/veyrohood-whitelist

## Turn Pages on (one time, 30 seconds)

1. Open https://github.com/joinveyrohood/veyrohood-whitelist/settings/pages
2. Source: **Deploy from a branch**
3. Branch: **main** / **/ (root)**
4. Save. Wait 1–2 minutes.
5. Open https://joinveyrohood.github.io/veyrohood-whitelist/

Do not add a custom CNAME until you own a real domain.

## What is live now
- Wallet connect (MetaMask, Rabby, OKX, browser wallets)
- Robinhood Chain switch (chain id 4663)
- Missions: Follow X, Join Discord, Quote + Reply pinned post
- Usernames + links, then $0.25 ETH to treasury
- First 1000 verified = OG
- Live joined + OG counters
- Referral link after verify (20%)
- Leaderboard
- Withdraw button unlocks at $2 (instant send after you paste CONTRACT_ADDRESS from Remix)

Treasury: `0xf6F80827cBAf83798c7763FCd915C0068F2bE60C`

## After Remix
Open `index.html`, find:
```
const CONTRACT_ADDRESS="";
```
Paste your deployed pool address. Commit. Pages updates itself.
