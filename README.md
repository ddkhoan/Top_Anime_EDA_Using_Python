# Top Anime Dataset: Audience Favoritism & Industry Trends

A comprehensive exploratory data analysis of 15,000 anime titles to understand audience score drivers, genre popularity, and historical production output.

## Business Problem
The anime industry has experienced explosive global growth. Understanding what historical factors, genres, and formats (TV vs. Movie vs. OVA) correlate with high audience engagement and top scores can help studios and streaming platforms optimize content acquisition and production pipelines.

## Dataset
* **Size:** 15,000 anime titles across 17 attributes.

## Tools & Skills Demonstrated
* **Language:** Python
* **Libraries:** `pandas`, `matplotlib` (and/or `seaborn`)
* **Techniques:** Missing Value Profiling, Cardinality Checks, Deduplication, Time-Series Aggregation, Exploratory Data Analysis.

## Key Insights
* Nearly 69% of titles are missing a premiered date, and other identifying fields (english_name, rank, producers) also have substantial gaps — any year-based or ranking-based analysis should be read with that in mind.
* The most-favorited anime are long-running TV series (led by One Piece, Fullmetal Alchemist: Brotherhood, and Hunter x Hunter), not movies or short-form content.
* TV and Movie types have the highest average scores (~6.8–6.9); short-form types (CM, Music, PV) score noticeably lower. This corrects an inaccurate claim in the original analysis that Movie scored highest.
* Recorded anime output grew steadily until the early 2000s and then accelerated, peaking in the 2016–2024 window — though this is based on the ~31% of titles with a known premiere year.
* Award Winning, Suspense, and Mystery are the highest-scoring genres, but the small sample size behind Award Winning (209 titles) warrants some caution in over-interpreting its top ranking.

## Contact
* LinkedIn: https://www.linkedin.com/in/khoa-nguyen-38076b365/
* Email: nd.duykhoa@gmail.com
