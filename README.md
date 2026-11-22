# blkrootznews-data
News feed for Blkrootznews. Starting at the Rootz.

`news.json` holds the day's stories. blkrootznews.com loads it on every visit, and the daily news refresh replaces it each morning (America/New_York). If the file is missing or broken, the site shows the stories built into its own page instead.

Shape: `{ updated: "YYYY-MM-DD", lead, stories: [...], regional: [...], weekly: [...], monthly: [...] }`. Each story has `sec`, `title`, `dek`, `source`, `date`, `url`, and may have `q`, `state`, `img`, `alt`, `credit`.
