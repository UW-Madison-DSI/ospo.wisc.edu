---
title: Internships | Open Source Program Office
layout: job-listing
permalink: /activities/internships/gyrochronology
job-title: Machine Learning Gyrochronology Age Estimator
job-link: https://studentjobs.hr.wisc.edu/cw/en-us/job/509740
---
### Project leader:
Melinda Soares-Furtado, (mmsoares@wisc.edu)

### Project description:
This astronomy research project focuses on developing a machine learning tool
to obtain reliable stellar ages from rotation periods. The project will create
an open-source Python package called the "Machine Learning Gyrochronology Age
Estimator" that automatically estimates stellar ages using gyrochronology—the
method of dating stars by measuring how fast they rotate.

#### Scientific Goal:
Stars slow their rotation as they age due to magnetic braking. By measuring
a star's rotation period and comparing it to calibration samples (star
clusters with known ages), we can estimate stellar ages. This is critical for
understanding planetary system evolution, stellar physics, and galactic history.
Unlike simple interpolation methods, this tool will use sophisticated machine
learning algorithms to capture complex relationships between rotation periods,
stellar properties (color, mass, metallicity), and age while providing reliable
uncertainty estimates.

#### Technical Goal:
Create an end-to-end automated pipeline that takes only a Gaia DR3 source ID
(stellar identifier) as input and automatically: (1) queries stellar parameters
and time-series photometry, (2) computes rotation periods from light curves, and
(3) estimates ages with error bars using ML models trained on benchmark clusters
spanning 50 million to 3+ billion years old.

#### Current Status:
Concept phase. This project would be developed from scratch using Python,
leveraging existing astronomy packages (astroquery, lightkurve, astropy) and
ML frameworks (scikit-learn, PyTorch, TensorFlow). Training datasets will be
provided by the research team.

#### Open Source Commitment:
The complete project will be made publicly available on GitHub with
comprehensive documentation, tutorials, and contribution guidelines. This will
benefit the broader astronomy community and provide the student intern with a
prominent portfolio piece and first-author publication opportunity.

The intern will contribute across the full development pipeline of this
astronomy software project. Core responsibilities include implementing automated
data retrieval systems in Python to query Gaia DR3, TESS, ZTF, and other
astronomical archives with cross-matching algorithms; developing time-series
analysis routines to detect stellar rotation periods from light curves using
algorithms like Lomb-Scargle periodograms and Gaussian processes; building
and optimizing machine learning models trained on provided cluster datasets to
predict stellar ages with uncertainty quantification; and creating comprehensive
documentation, tutorials, and a user-friendly command-line interface. The intern
will also contribute to scientific analysis, figure preparation, and manuscript
writing as first author (or second author if preferred) on a peer-reviewed
journal article.

### Intern needs:
The intern must be fluent in Python programming and familiar with machine
learning tools and frameworks such as scikit-learn, PyTorch, or TensorFlow,
as all development will be conducted in Python. Essential skills include
experience with data analysis and visualization libraries (numpy, pandas,
matplotlib), understanding of ML concepts including training/validation/testing,
overfitting, regularization, and cross-validation, and comfort with Git/GitHub
for version control. Strong problem-solving abilities, independent work skills,
and excellent written and verbal communication are required, along with genuine
interest in astronomy and willingness to learn about stellar physics.

The ideal candidate is a sophomore or junior undergraduate student (preferred
to enable multi-semester engagement) who is interested in continuing work over
multiple semesters and pursuing first-author publication. No prior astronomy
research experience is required.

