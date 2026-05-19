# Global Cinema Performance Analysis: Blockbusters vs. Historical Flops

## Project Overview & Interactive Dashboard
An end-to-end data analytics project exploring what differentiates a billion-dollar cinematic success from a box-office flop. This project processes historical movie data to examine seasonal trends, genre financial dominance, critical audience sentiment, and public engagement metrics.

## Dashboard Preview
![Interactive Excel Dashboard](images/dashboard_snapshot.png)

## The STAR Framework Case Study

# 1. Situation
Entertainment studios face high-stakes financial risks when greenlighting projects. To optimize commercial viability, this analysis evaluates the data profiles of the world's Top 1,000 Highest-Grossing Movies against a baseline of Historical Box Office Flops to uncover hidden patterns in success and failure.

# 2. Task
* Extract, clean, and format unstructured, web-scraped cinematic data tables.
* Address missing data anomalies (such as blank revenue profiles for minor independent flops).
* Engineer statistical summaries comparing audience sentiment, runtime distributions, and public engagement metrics.
* Design an executive-ready interactive dashboard with dynamic time-frame filtering.

# 3. Action (Technical Toolstack & Execution)
   Data Engineering (Power Query): Handled advanced data ETL transformations. Cleaned structural anomalies by parsing and stripping raw text HTML string tags (`[h2]`, `[b]`, `$`) trapped in web-scraped columns to cast variables into true numeric whole/decimal data types.
   Statistical Modeling & Aggregation (Excel Pivot Tables): Constructed robust background summaries calculating multi-genre financial averages and cross-examining weighted baseline trends.
   UI/UX Dashboard Architecture (Excel Charts & Slicers): Designed an executive frontend display using custom macro currency number-formatting (`$#,##0,, "M"`), horizontal clustered distribution bars, mixed dual-axis line/column combo charts, and cross-connected interactive timeline slicers.

### 4. Results & Business Insights
   The Revenue Engine: Genre indexing proved that the Action-Adventure-Sci-Fi combination commands the highest historical revenue market share, yielding an elite average of over $449 Million per title globally.
   The Engagement Chasm: Comparative tracking showed that low-performing titles don't just suffer from poor reception (averaging a 5.3 IMDb rating); they suffer an organic collapse in visibility, drawing fewer than 6,000 public interactions compared to the hundreds of thousands captured by commercially viable films.

## Repository Structure
* `Global_Cinema_Performance_Dashboard.xlsx`: The final, complete workbook containing Power Query scripts, background Pivot Tables, and the interactive dashboard.
* `images/`: High-resolution visual snapshots of the analytical assets.
