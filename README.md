# 🔐 What Makes People Trade Their Privacy?

[View the Final Research Report](./무엇이%20프라이버시를%20거래하게%20만드는가_사회조사분석%20보고서.pdf)

## Project Overview

This quantitative research paper uses data from the **Digital Society Special Module** of the 2025 Korean General Social Survey (KGSS) to analyze how economic conditions affect individuals' willingness to consent to the provision of personal information. In particular, the study distinguishes objective economic indicators from individuals' **subjective economic perceptions** (subjective social status and financial satisfaction), formulates four hypotheses, and specifies four weighted least squares (WLS) regression models to test them.

Through this analysis, the study quantitatively explores the psychological mechanisms underlying consumers' willingness to trade privacy for economic benefits such as discounts or free products.

## Hypotheses

| Theoretical Background | Research Hypothesis |
|---|---|
| Privacy calculus theory | **Hypothesis 1.** As average monthly household income, an objective economic condition, increases, willingness to consent to the provision of personal information in exchange for discounts or free products will decrease. |
| Subjective social status and self-efficacy | **Hypothesis 2.** As subjective social status increases, the sense of control associated with being able to manage privacy risks independently will strengthen, thereby increasing willingness to consent to the provision of personal information in exchange for discounts or free products. |
| Present bias and the tunneling effect | **Hypothesis 3.** As financial satisfaction decreases, individuals will place greater value on immediate rewards than on future privacy risks, thereby increasing their willingness to consent to the provision of personal information. |
| Cognitive averaging | **Hypothesis 4.** When objective economic indicators and subjective assessments of one's circumstances are considered simultaneously, willingness to consent to the provision of personal information will be more closely associated with subjective economic perceptions than with objective income. |

Hypotheses 1 and 2 examine the possibility that objective economic conditions and subjective social status may operate in opposite directions with respect to willingness to consent to the provision of personal information, even though the two may be highly correlated. Objective income may affect the marginal utility of financial benefits and the assessment of privacy risks, whereas subjective social status may operate through the psychological pathways of self-efficacy and perceived control over one's circumstances. Although positing effects in opposite directions for these two variables presents interpretive limitations, this distinction is also what differentiates the present study. Rather than reducing economic conditions to a single income indicator, this study tests how objective resources and subjective perceptions of social status operate differently in situations involving the provision of personal information.

## File Structure

| File Name | Description |
|---|---|
| `kgss2025.csv` | The raw data used in the analysis. This file does not contain the full cumulative KGSS dataset; it contains the data for **2025** from the year-specific datasets. |
| `data_prep_and_analysis.ipynb` | A Python Jupyter Notebook used for data preprocessing, variable recoding, descriptive analysis, visualization, and WLS regression analysis. |
| `무엇이 프라이버시를 거래하게 만드는가_사회조사분석 보고서.pdf` | The final PDF report presenting the analysis results and their interpretation. |

## Research Findings and Insights

- **Strong explanatory power of subjective economic perceptions:** When individuals' actual financial resources (objective income) and their perceptions of their own economic circumstances (subjective perceptions) were entered into the regression model simultaneously, **the effect of objective income disappeared, whereas only the effect of subjective perceptions remained highly statistically significant.**

- **Financial deprivation and the tunneling effect (present bias):** Lower financial satisfaction was associated with a more pronounced tendency toward present-biased decision-making, in which individuals overlook the potential future loss posed by privacy violations in favor of immediate rewards such as discounts or free products.

- **The dual nature of subjective social status:** By contrast, higher subjective social status was associated with greater self-efficacy—the belief that one can remain in control—and, paradoxically, a more open attitude toward providing personal information due to greater confidence in one's ability to manage privacy risks independently.

## Team Members

Kyung Hee University: 2021100380 박찬규, 2022100672 한우진, 2023100736 신아영, 2024100558 박소윤
