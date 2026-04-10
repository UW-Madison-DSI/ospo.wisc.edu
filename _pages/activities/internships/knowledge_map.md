---
title: Internships | Open Source Program Office
layout: job-listing
permalink: /activities/internships/knowledge_map
job-title: Knowledge Map
job-link: https://studentjobs.hr.wisc.edu/cw/en-us/job/511396
---
### Project leader:
Corey Jackson, (corey.jackson@wisc.edu)

### Project description: 
As part of a research grant through the Chan Zuckerberg Initiative (2022-2024),
we have developed Knowledge Map (KM), a reporting tool for survey data
taken from past research on environmental challenges faced by communities
in Dane County, Wisconsin. KM’s development was influenced by research
with local government and non-profit organizations, which displays (1) the
representativeness of the survey sample and (2) data visualizations. The
representativeness is produced by comparing the survey responses' distribution
to a selected geographic level (e.g., census tract, county). It provides an
evaluation of the representativeness of the data using the approach described
in Qi et al. (2021). The visualizations report mostly categorical data with
open-text responses using structured topic modeling. The tool has been developed
using RShiny and is available in a private repository (see: ccs-knowledge-map);
however, student turnover has left the project with several outstanding tasks
for which we would benefit from DSI’s Open Source Internship program.

### Internship Tasks:
Our project would benefit from tasks in three areas - coding/ feature
development, data analysis, and documentation. However, not all are required for
the internship.
- Coding & Development: We have a list of backlog coding updates that need to be
  completed, ranging from minor improvements, e.g., fixing navigation, to feature
  development, e.g., integrating map visualizations. The log can be accessed
  here: KM Backlog (we are converting items from Notion). Key priorities include
  improving UI responsiveness and enhancing interactivity in visualizations.
- Data Analysis: We want to improve our measures of representativeness. The
  current approach uses distributional comparisons across geographic units (e.g.,
  census tracts, counties) to determine how well the survey sample reflects the
  broader population. However, this does not account for the sample size. We
  should improve this to warn users of low N or augment the model by incorporating
  uncertainty estimates or confidence intervals to indicate the reliability of
  representativeness scores. The approach can be found here:
  - See: Qi, Miao, Owen Cahan, Morgan A. Foreman, Daniel M. Gruen, Amar K. Das,
    and Kristin P. Bennett. "Quantifying representativeness in randomized clinical
    trials using machine learning fairness metrics." JAMIA open 4, no. 3 (2021):
    ooab077.
- Documentation & Open-Source Readiness: We must ensure Knowledge Map’s
  repository follows open-source best practices to make the project open-source.
  Our project would benefit from evaluating those practices: GitHub Repository and
  an overall assessment of code structure, licensing, contributor guidelines, and
  API documentation. Additionally, we should create onboarding materials for new
  developers and data users to encourage broader engagement with KM.
Completing these would help enhance the accessibility and usability of the tool
for researchers, policymakers, and community organizations, enabling them to
make data-driven decisions with a clearer understanding of their data and its
ability to represent all community members. This work would also strengthen
the infrastructure of KM, ensuring it can be maintained and expanded upon in
the future.

### Mentorship:
The intern(s) will join a team of researchers that includes two faculty members
- Corey Jackson, Ph.D., in the Information School, and Kaiping Chen in Life
Sciences Communication. Both have expertise in computational social science/data
science and some experience developing applications with RShiny. Their team
has worked on developing KM for 1.5 years with a team of graduate students. The
UI and backend development has been led by Shelcia David Raj (an experienced
developer in the Information School’s Information Science program). However,
the project would benefit from additional contributors to lessen the burden
on Shelcia. The student could join weekly research group meetings or receive
mentorship as needed through in-person meetings or Zoom calls.

### Desired Skills:
RShiny/R, GitHub, Open Source
