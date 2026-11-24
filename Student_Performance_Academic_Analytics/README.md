# Student Performance & Academic Analytics

## Objective
Explore student final grades in Mathematics and Portuguese and check patterns related to study time, past failures, absences and previous grades.

## Dataset
- `student-mat.csv`: 395 Mathematics records
- `student-por.csv`: 649 Portuguese records
- `student.txt`: field descriptions
- `student-merge.R`: supplied R code showing how the two datasets are matched

The supplied merge script matches records using shared student attributes and returns 382 records. Grade columns remain separate for the two subjects.

## Tools
Python, Pandas, NumPy, Matplotlib, Seaborn and Jupyter Notebook.

## Analysis
- Checked dataset size, data types, missing values and duplicates.
- Studied final-grade distributions.
- Compared grades by study time and past failures.
- Explored absences and grade relationships.
- Compared Mathematics and Portuguese.
- Created histograms, box plots, bar charts, scatter plots and a correlation heatmap.

## Key findings
- The Mathematics dataset has 395 records and Portuguese has 649 records.
- Average final grades are 10.42/20 in Mathematics and 11.91/20 in Portuguese.
- 67.1% of Mathematics records and 84.6% of Portuguese records have G3 of at least 10.
- Studytime and Mathematics G3 have a correlation of 0.10.
- Past failures and Mathematics G3 have a correlation of -0.36.
- Absences and Mathematics G3 have a correlation of 0.03.
- Portuguese G1 and G3 have a correlation of 0.83.
- 94.9% of Mathematics records indicate an intention to pursue higher education.

## Recommendations
1. Encourage regular study routines.
2. Provide extra help to students with previous failures.
3. Monitor attendance and follow up when absences increase.
4. Use early-period grades to identify students who may need support.

## Limitations
- These are observational data; relationships do not prove cause and effect.
- The data represents two subjects and two schools.
- The merge identifies 382 matches using shared attributes; this is the method in the supplied R file.
- G3 >= 10 is used as a simple descriptive threshold.

## Resume-ready description
Explored student academic performance across Mathematics and Portuguese using Python, Pandas and Seaborn; analysed grade distributions, study time, past failures, absences and grade progression to identify patterns and suggest student-support actions.
