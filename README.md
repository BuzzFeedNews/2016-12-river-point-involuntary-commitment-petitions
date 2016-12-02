# Analysis of Duval County (FL) Court Data

In Florida, patients who pose a risk to themselves or others can be held in psychiatric facilities for up to 72 hours, pursuant to a law called the Baker Act. Facilities can petition the court to hold a person longer than 72 hours if they think it’s medically necessary. This analysis examines the petitions filed by River Point, a facility purchased by Universal Health Services in 2010 and located in Duval County.

This repository contains data, code, and methodologies supporting the following passage in the BuzzFeed News article, "[Intake](https://www.buzzfeed.com/rosalindadams/intake)," published December 7, 2016:

> A BuzzFeed News analysis of court records shows that in 2009, the year before UHS bought the hospital, it filed 238 petitions for involuntary commitment. Four years later, that number had grown to 1,362 — an increase of more than 470%.

> UHS said that “any claims that the Baker Act process was used improperly in any way at River Point are completely unfounded.” It attributed the increase in the number of petitions largely to increasing the number of beds for elderly patients, “who commonly have challenging mental health issues requiring involuntary commitment.”

> Therapists who filed these petitions said the doctors gave little justification for holding the patient — sometimes just a few words with almost no context.

> Public defenders who represent Baker Act patients noted this as well. The petitions filed by River Point “were often legally insufficient and lacking in supporting documentation,” said Stephanie Jaffe, a public defender in Duval County.

## Data

The data in the repository comes from the Duval County court. The court provided [case information](data/Cases_w_InvoluntaryPlacementPetitions_2016-11-07.xlsx) for petitions filed by local facilities.

## Analyses

The Python code that performs this analysis is available in [this notebook](notebooks/petition_analysis.ipynb).

## Questions/Feedback?
Please contact Kendall Taggart at kendall.taggart@buzzfeed.com.

Looking for more from BuzzFeed News? [Click here for a list of our open-sourced projects, data, and code.](https://github.com/BuzzFeedNews/everything)
