# Manifest - Reddit scrape, niche: US lawn care small businesses (mowing pricing/quoting and routing)

- Date: 2026-10-28
- Actor: harshmaur/reddit-scraper
- Step A run ID: cIIMwASZobfhFByNF - dataset ID: 8YtyM7cf41cDxQ4rh (75 items, all posts)
- Step B run ID: Gs3V6WyLN09GL2nAf - dataset ID: JlY4cJlOMCh6z0E0d (289 items = 27 posts + 262 comments)
- Estimated cost: NOT reported by the tools (no usage USD exposed). Compute stats tiny (A: 0.0008 CU, 5s; B: 0.009 CU, 65s). Caps set: A 0.30, B 0.95. Both runs SUCCEEDED, no cap hit. Actual cost not verified; check Apify console.

## Parameters
Step A: searchPosts=true, searchComments=false, searchSort=relevance, searchTime=year, maxPostsCount=10, crawlCommentsPerPost=false, withinCommunity="", includeNSFW=false.
Step B: searchTerms=[], startUrls=27 post URLs, searchPosts=false, searchComments=false, crawlCommentsPerPost=true, maxCommentsPerPost=10, includeNSFW=false.

## Keywords and counts (items returned in A / posts selected / comments in B)
| # | Keyword | A items | Posts selected | Comments |
|---|---|---|---|---|
| 1 | Jobber lawn care worth it | 8 | 3 | 26 |
| 2 | lawn care software too expensive | 9 | 4 | 40 |
| 3 | lawn mowing pricing | 7 | 2 | 20 |
| 4 | how to price lawn mowing jobs | 5 | 3 | 30 |
| 5 | lawn care estimate quote | 8 | 5 | 49 |
| 6 | lawn care route optimization | 6 | 0 | 0 |
| 7 | is there an app for lawn care routes | 8 | 2 | 17 |
| 8 | any alternative to Jobber | 8 | 3 (adjacent trades) | 30 |
| 9 | how do you keep track of lawn care customers | 8 | 5 | 50 |
| 10 | lawn care spreadsheet | 8 | 0 | 0 |
Total: 75 / 27 / 262.

## Notes
- Comments are a sample (up to 10 top-level per post as returned by the scraper, plus nested replies up to depth 3), not the most voted of the thread. Nested replies ARE returned (depth field).
- No age discards (all posts within 12 months). 16 discarded for commentsCount < 10. 32 discarded as off-topic/promo.
