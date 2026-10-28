# Manifest - Reddit scrape, niche: US single-property small landlords (expense tracking, Schedule E, repairs, accountant handoff)

- Date: 2026-10-28
- Actor: harshmaur/reddit-scraper
- Step A run ID: zWP3AfwPxfDmm4tvs - dataset ID: 0YXGAiEnD5fuWPcLU (89 items, all posts)
- Step B run ID: laWv90EpParjTsbTt - dataset ID: DlemI05Hg8NampLNP (309 items = 29 posts + 280 comments)
- Estimated cost: NOT reported by the tools (no usageTotalUsd exposed). Compute stats are tiny (A: 0.0010 CU, 7s; B: 0.0016 CU, 12s). Caps set: A 0.30, B 0.95. Neither run hit its cap (both SUCCEEDED). Actual cost not verified; check the Apify console.

## Parameters
Step A: searchPosts=true, searchComments=false, searchSort=relevance, searchTime=year, maxPostsCount=10, crawlCommentsPerPost=false, withinCommunity="", includeNSFW=false.
Step B: searchTerms=[], startUrls=29 post URLs, searchPosts=false, searchComments=false, crawlCommentsPerPost=true, maxCommentsPerPost=10, includeNSFW=false.

## Keywords and counts (selected posts / comments collected in step B)
| # | Keyword | Items returned in A | Posts selected | Comments |
|---|---|---|---|---|
| 1 | I use a spreadsheet to track rental property expenses | 9 | 1 | 10 |
| 2 | Schedule E rental expenses | 10 | 2 | 20 |
| 3 | repair vs improvement rental property | 10 | 1 | 10 |
| 4 | landlord software too expensive | 10 | 5 | 44 |
| 5 | Stessa worth it | 10 | 1 | 10 |
| 6 | any alternative to Stessa | 6 | 1 | 10 |
| 7 | how do you keep track of rental expenses | 6 | 5 | 50 |
| 8 | is there an app for landlord receipts | 10 | 5 | 46 |
| 9 | rental property bookkeeping accountant | 8 | 3 | 30 |
| 10 | rental depreciation tracking | 10 | 5 | 50 |
| | Total | 89 | 29 | 280 |

Comments include nested replies (depth 0-3: 158 / 91 / 28 / 3).
Raw data stays in the Apify datasets above.
