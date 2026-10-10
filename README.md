# Business Operations & Revenue Analysis
## Visitor Centre Shift Trial — Business Analyst Case Study

**Tools:** Microsoft Excel for the Web, PivotTables, comparative analysis  
**Project type:** Business Analysis / Operations Analytics  
**Status:** In progress

---

## 1. Project Overview

This case study explores how revenue trends, visitor footfall, commercial activity, and shift patterns can be analysed to identify potential operational improvement opportunities across five visitor centres.

The objective is to understand when visitor demand is highest, whether different activities follow similar patterns, and whether the trial shift arrangements align with demand.

The analysis uses two separate datasets:

1. A baseline and trial-month revenue dataset.
2. A trial-period dataset containing hourly footfall, visitor activities, and shift patterns.

**Portfolio note:** This is a practice case study using a generated dataset. It is not an analysis of verified historical Transport for London (TfL) operational data and does not represent actual employment with TfL.

## 2. Business Problem

How can visitor centre revenue and activity data help determine whether shift patterns align with visitor demand, and what further analysis is needed before recommending operational changes?

### Business objectives

- Compare trial-month revenue with the baseline period.
- Identify the busiest hours across visitor centres.
- Understand when commercial activities and enquiries are most frequent.
- Compare footfall patterns across shift arrangements.
- Identify potential opportunities for better operational coverage.
- Develop evidence-based recommendations while acknowledging data limitations.

## 3. Tools and Techniques

- Microsoft Excel for the Web
- PivotTables
- Revenue comparisons
- Hourly demand analysis
- Average versus total metric comparison
- Centre-level segmentation
- Business-question formulation
- Interpretation of findings and data limitations

---

## 4. Dataset A: Revenue Analysis

### Data structure

The revenue dataset covers five centres:

- Heathrow
- King's Cross
- Liverpool Street
- Piccadilly Circus
- Victoria

It contains six baseline months and one trial month, with revenue grouped into four categories:

- Merchandise
- Other
- Oyster / Travel Card
- Tours & Attractions

The analysis compares trial-month revenue with average monthly revenue across the six baseline months.

### Finding 1: Overall revenue was almost unchanged

| Metric | Revenue |
|---|---:|
| Average baseline monthly revenue | £346,700 |
| Trial-month revenue | £346,500 |
| Difference | -£200 |
| Percentage difference | Approximately -0.06% |

**Interpretation:** Trial-month revenue was almost identical to the six-month baseline monthly average. The comparison does not show a meaningful overall increase in revenue.

This does not establish whether the shift trial succeeded or failed. Further context and a more suitable comparison period may be needed.

### Finding 2: Revenue differed by category

| Revenue category | Average baseline monthly revenue | Trial-month revenue | Difference |
|---|---:|---:|---:|
| Merchandise | £40,467 | £40,300 | -£167 |
| Other | £14,500 | £14,500 | £0 |
| Oyster / Travel Card | £196,635 | £195,000 | -£1,635 |
| Tours & Attractions | £95,100 | £96,700 | +£1,600 |

**Interpretation:**

- Tours & Attractions revenue was above its baseline average.
- Oyster / Travel Card revenue was below its baseline average.
- The differences largely offset one another, leaving overall revenue almost unchanged.

These are descriptive comparisons. They do not establish that the trial shift arrangement caused the category-level changes.

*Note: Category figures are rounded, so their sum may differ slightly from the rounded overall total.*

### Finding 3: Revenue differed across centres

| Centre | Average baseline monthly revenue | Trial-month revenue | Difference |
|---|---:|---:|---:|
| Heathrow | £94,400 | £92,500 | -£1,900 |
| King's Cross | £71,383 | £72,900 | +£1,517 |
| Liverpool Street | £54,533 | £53,700 | -£833 |
| Piccadilly Circus | £71,617 | £71,100 | -£517 |
| Victoria | £54,767 | £56,300 | +£1,533 |

**Interpretation:**

- King's Cross and Victoria recorded more revenue than their baseline averages.
- Heathrow, Liverpool Street, and Piccadilly Circus recorded less.
- Performance varied by centre even though overall revenue was almost unchanged.

This suggests that an overall figure can hide differences between locations.

### Finding 4: The baseline period showed a trend

At all five centres, baseline months 5 and 6 were higher than the trial month. Revenue generally increased across the later baseline months, with a dip in month 4.

**Business implication:** Comparing the trial month with the average of all six baseline months may not provide the fairest measure of trial performance.

Seasonality, changing visitor numbers, or other external factors could explain the pattern, but the available data does not establish the cause.

### Finding 5: Commercial Activity and Visitor Demand

Analysis of the trial-period data shows that recorded footfall, Oyster Sales, and Tours & Attractions activity are highest during the midday and early-afternoon period, broadly between 12 pm and 4 pm. All three measures decline after this period, with a particularly noticeable drop between 2–3 pm and 3–4 pm.

**Business implication:** The 12 pm–4 pm period may represent the strongest opportunity for commercial activity. Staffing arrangements could be reviewed to ensure adequate coverage during these hours.

**Limitation:** The findings describe recorded activity during the trial period. Further validation is needed before recommending changes to individual centres' shifts or opening hours.
---

## 5. Dataset B: Trial-Period Activity Analysis

### Data structure

The activity dataset contains fields including:

- Date, day, centre, shift pattern, and hour
- Total footfall
- Visitor age groups
- Tourist and local enquiries
- TfL-related enquiries
- General directions
- Oyster sales
- Photocard Oyster collection
- Tours & Attractions
- National Rail enquiries
- Refunds and other enquiries

PivotTables were used to examine the hourly distribution of visitor activity and compare patterns across shift arrangements and centres.

### Finding 5: Visitor footfall peaked between 12 pm and 3 pm

A PivotTable using hour as rows and the sum of total footfall as values showed that visitor activity was concentrated between **12 pm and 3 pm**, with the overall peak between **2 pm and 3 pm**.

The same broad peak window appeared across all five centres.

**Business interpretation:** Midday and early afternoon represent an important period for visitor demand across the locations in the dataset.

This is a useful starting point for examining shift coverage, but it does not by itself demonstrate that staffing levels were insufficient.

### Finding 6: Several activities followed the same broad pattern

Separate hourly PivotTables showed high activity between 12 pm and 3 pm for:

- Oyster sales
- Tours & Attractions
- Photocard Oyster collection
- TfL-related enquiries

Oyster sales and Tours & Attractions activity gradually declined after around 3 pm.

**Business interpretation:** The midday peak involves more than footfall alone. Several commercial and enquiry activities are concentrated in the same period.

This raises a practical operational question: are the shift arrangements providing suitable coverage during the hours when visitor demand and these activities are highest?

The data examined so far does not establish sales conversion rates, revenue per visitor, service quality, or staffing adequacy.

---

## 6. Shift Pattern Analysis

The three shift patterns are:

- 8:00 am–3:00 pm
- 9:00 am–4:00 pm
- 12:00 pm–7:00 pm

### Finding 7: Total footfall alone was not a fair comparison

Initially, the 12 pm–7 pm shift recorded the highest total footfall.

However, shifts cover different hours and may have different numbers of observations. A larger total may reflect the amount of recorded activity rather than stronger typical demand.

The analysis therefore moved to average recorded footfall to make a more meaningful comparison.

### Finding 8: Average recorded footfall was highest for the 12 pm–7 pm shift

| Shift pattern | Average recorded footfall |
|---|---:|
| 12 pm–7 pm | 54.79 |
| 9 am–4 pm | 53.87 |
| 8 am–3 pm | 50.71 |

**Interpretation:**

- The 12 pm–7 pm shift had the highest overall average.
- The 9 am–4 pm shift was second.
- The 8 am–3 pm shift had the lowest average.

The difference between the highest and lowest averages was approximately 4.08 visitors per recorded observation.

These values describe recorded footfall, not staff productivity or operational efficiency.

### Finding 9: The pattern differed by centre

| Centre | Highest average footfall | Lowest average footfall |
|---|---|---|
| Heathrow | 12 pm–7 pm | 8 am–3 pm |
| King's Cross | 12 pm–7 pm | 8 am–3 pm |
| Liverpool Street | 12 pm–7 pm | 8 am–3 pm |
| Piccadilly Circus | 12 pm–7 pm | 8 am–3 pm |
| Victoria | 9 am–4 pm | 8 am–3 pm |

**Interpretation:**

The 12 pm–7 pm shift had the highest average recorded footfall at four of the five centres. Victoria was the exception, with the 9 am–4 pm shift recording the highest average.

This suggests that the shift pattern results may vary by location. However, further checks are needed before recommending a different schedule for Victoria.

### Finding 10: Victoria's hourly pattern was not consistent across shifts

The Victoria PivotTable compared summed footfall across the hours where shift patterns overlapped.

| Hour | 12 pm–7 pm | 8 am–3 pm | 9 am–4 pm |
|---|---:|---:|---:|
| 9–10 am | — | 410 | 396 |
| 10–11 am | — | 526 | 518 |
| 11 am–12 pm | — | 561 | 573 |
| 12–1 pm | 586 | 635 | 650 |
| 1–2 pm | 609 | 655 | 635 |
| 2–3 pm | 630 | 701 | 657 |

*These are sums of recorded footfall, not averages.*

The 9 am–4 pm shift did not lead in every overlapping hour. The 8 am–3 pm shift recorded higher totals in several hours, while the 9 am–4 pm shift recorded higher totals in others.

Because these are sums across recorded observations, they cannot establish which shift performs better hour by hour without accounting for the number of observations and ensuring comparable periods.

**Conclusion for Victoria:** The hourly comparison does not yet explain why the 9 am–4 pm shift had the highest overall average. More analysis is required before attributing the difference to a specific demand pattern.

---

## 7. Current Business Insights

The strongest supported insights from the analysis so far are:

1. **Revenue was almost unchanged overall.** Trial-month revenue was approximately £200 below the average monthly revenue across the six baseline months.
2. **Revenue varied by category and centre.** The overall figure hides differences between locations and revenue streams.
3. **Visitor demand was concentrated around midday.** Footfall peaked between 12 pm and 3 pm across all five centres.
4. **Several activities shared the midday peak.** Oyster sales, Tours & Attractions, photocard collections, and TfL-related enquiries were also high during this period.
5. **Shift comparisons differed by location.** The 12 pm–7 pm shift had the highest average recorded footfall at four centres, while Victoria differed.
6. **More evidence is needed before recommending a shift change.** The analysis has not yet established whether staffing levels matched demand or whether the trial caused any revenue change.

### Emerging business question

Does the current shift arrangement provide sufficient coverage during the midday demand peak, and should shift coverage be assessed separately by centre?

This is a question for further investigation, not a conclusion already proven by the data.

---

## 8. Data Limitations

The following limitations must be considered before drawing stronger conclusions:

- The datasets are generated for practice and are not verified operational records.
- The revenue and shift/activity datasets are separate. They do not currently establish a direct relationship between hourly activity and revenue.
- The baseline period shows an upward trend in later months, making the six-month average an imperfect comparison for the trial month.
- Summed footfall can be influenced by the number of records for a shift or hour.
- Average footfall per recorded observation is more informative than a sum for some comparisons, but it does not measure staff productivity, workload, or service quality.
- The analysis has not yet compared staffing headcount with footfall.
- Waiting times, queue length, sales conversion rates, and revenue per visitor have not been analysed.
- Seasonality and other external factors remain possible explanations, not confirmed causes.

---

## 9. Next Steps

The next stage is to continue from the shift coverage question rather than repeat analyses that show the same midday peak.

### Step 1: Assess shift coverage during the peak

Check which shifts are active during the 12 pm–3 pm window and which finish during or just after it.

### Step 2: Make shift comparisons more comparable

Check how many observations are available for each shift and centre. Where possible, compare the same hours and comparable dates rather than relying on totals across different coverage periods.

### Step 3: Investigate the Victoria exception

Determine whether Victoria's different average pattern persists after accounting for the number of observations and comparable hours.

### Step 4: Develop recommendations cautiously

Any proposed change should be framed as a test or pilot, not as a proven improvement.

Potential measures for evaluating a future change include:

- Hourly footfall
- Activity and enquiry volumes
- Waiting time or queue length
- Sales and revenue by hour, if available
- Staff coverage by hour
- Results across comparable dates and centres

### Step 5: Present the results

Create a simple Excel dashboard or findings summary containing:

- Baseline-versus-trial revenue comparison
- Revenue differences by centre and category
- Hourly footfall pattern
- Activity patterns
- Shift comparison
- Limitations and next steps

---

## 10. Skills Demonstrated

- Excel PivotTables
- Revenue analysis
- Baseline-versus-trial comparison
- Hourly demand analysis
- Metric selection and interpretation
- Centre-level segmentation
- Comparing totals and averages
- Identifying patterns and exceptions
- Formulating operational business questions
- Recognising limitations and avoiding unsupported causal claims
- Translating data observations into further analysis

## 11. Summary

This case study demonstrates a structured approach to analysing revenue and operational activity data using Excel.

The analysis identified a consistent midday demand peak across five centres and found that several commercial and enquiry activities were concentrated in the same period. Shift-pattern comparisons showed that the 12 pm–7 pm shift had the highest average recorded footfall at four centres, while Victoria differed.

Overall trial-month revenue was almost identical to the six-month baseline monthly average. The results provide useful questions for further investigation, but they do not yet prove that the shift trial improved revenue or that staffing levels were inadequate.

The next stage is to examine shift coverage during the midday peak, validate the comparability of the shift observations, and develop evidence-based recommendations.

---

**Project status:** In progress  
**Last completed stage:** Initial revenue comparison and trial-period activity analysis  
**Next task:** Assess which shift patterns are active during the 12 pm–3 pm peak and determine what further evidence is needed to evaluate coverage.
