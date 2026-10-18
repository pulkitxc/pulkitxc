# Pulkit Shrivastava

### I audit data before I analyze it.

Data analyst in training (3rd-year B.Tech AI/ML, Bhopal). SQL, Python, Power BI.
**Looking for a paid data analytics internship** (remote / hybrid / on-site).

---

## 🗂️ Case File #001: The dataset that lied

I spent a month building a full analytics system on a 180,519-row supply chain dataset: requirements, star schema, PostgreSQL warehouse, 20 validation tests, 24 business questions.

Then the evidence stopped adding up.

| What the data claimed | What the evidence showed |
|---|---|
| Real business across many categories and markets | Profit margin sat at ~10-11% in **every** dimension I sliced |
| Sensible product catalog | Golf balls were filed under "Electronics" |
| Normal shipping behavior | Variance patterns that real logistics don't produce |
| A continuous history | A sharp shift to synthetic data from October 2017 onward |

So I changed the question from *"what does this say about the business?"* to *"what does the evidence say about the dataset?"*

**Verdict:** 9 forensic findings (7 confirmed, 2 still open) and a 34-page report whose conclusion is *what this data can and cannot support*.

👉 **[Open the case file → dataco-supply-chain-forensics](https://github.com/pulkitxc/dataco-supply-chain-forensics)**

---

## 🧭 How I work

1. **Every dataset is a claim.** I check it before I trust it.
2. **Raw stays raw.** I keep source data and analytical data separate, so every number can be traced back.
3. **Say what the data can't support.** A confident chart on bad data is worse than no chart.

---

## 🔎 More case files

| Case | The question I asked | Finding / decision | Stack |
|---|---|---|---|
| [Bike Buyers](https://github.com/pulkitxc/europe-bike-sales-analytics) | Does income predict who buys a bike? | Barely (r = +0.05). Car ownership mattered far more (r = -0.20). | Excel |
| [Data Professional Survey](https://github.com/pulkitxc/Data-Professional-Survey-Analytics) | Does higher pay mean happier data professionals? | Learning scored well, salary satisfaction lagged. | Power BI, DAX |
| [Crypto Market Intelligence](https://github.com/pulkitxc/cryptocurrency-market-intelligence) | What does the API return that I actually need? | Split raw response from the analytical dataset before any charts. | Python, Pandas |
| [Book Price Monitor](https://github.com/pulkitxc/book-price-monitor) | What if a scraper remembered its past runs? | History, price-change detection, email alerts without duplicates. | Selenium, BeautifulSoup |
| [Layoffs SQL Analysis](https://github.com/pulkitxc/SQL-Exploratory-Data-Analysis-Layoffs-Dataset) | What do layoffs look like over time? | Cleaning, rolling totals, ranking with CTEs. | MySQL |
| [World Population EDA](https://github.com/pulkitxc/world-population-demographic-eda) | Which growth stories hide behind the totals? | CAGR, density validation, countries in decline. | Pandas, Seaborn |

---

## 🧰 Toolkit

`SQL (PostgreSQL, MySQL)` · `Python` · `Pandas` · `NumPy` · `Matplotlib / Seaborn` · `Power BI + DAX` · `Excel` · `BeautifulSoup / Selenium` · `REST APIs` · `Jupyter`

## 🚧 Next case

GTM + GA4 behavior-tracking project with a Looker Studio report.

---

## 📬 Reach me

[LinkedIn](https://www.linkedin.com/in/pulkit-shrivastava-8079a438b) · pulkitshrivastava98@gmail.com

*If you have a messy dataset and a question nobody trusts the answer to, I'd like to work on it.*
