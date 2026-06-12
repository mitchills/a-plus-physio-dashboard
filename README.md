# A Plus Physio — Performance Dashboard

Live at: https://mitchills.github.io/a-plus-physio-dashboard/

## Updating data
Ask Claude: "Refresh the A Plus Physio dashboard" — Claude fetches all four sources
via MCP, writes `data/latest.json`, commits and pushes. Pages redeploys in ~60 seconds.

## Data sources
- Google Ads customer 1519461427 (login-customer-id 6235799350)
- Meta Ads act_1405008824620416
- GA4 property 499618304
- Google Search Console: aplusphysio.com.au
