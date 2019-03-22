# HESA - SB252 (Student Statistics UK 2017/18)
## Data import

Data downloaded from [https://www.hesa.ac.uk/news/17-01-2019/sb252-higher-education-student-statistics](https://www.hesa.ac.uk/news/17-01-2019/sb252-higher-education-student-statistics)

"This bulletin covers higher education (HE) providers who submit a full Student record data return to HESA. *This includes publicly funded Higher Education Institutions, the privately funded University of Buckingham, and HE level provision at Further Education (FE) Colleges in Wales (accounting for 1,670 students in 2017/18)*"



## EDA status
Overcame problem of `geom_line` sawtooth shape (a symptom of `group` being wrong), by using `group=interaction()`. Now have many many 'correct' lines, but how do I get few/aggregate lines in the chart, instead?