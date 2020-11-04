# Machine Learning with Python 
## Student Final Grade Prediction - Midterm Project
*Project ini dibuat untuk memenuhi tugas UTS mata kuliah 
PEMBELAJARAN SECARA STATISTIK DAN OPTIMISASI S2TE-31-01 [SZL]*

## Team :
```
Muammar Qhadafi (2101191019)
Raafi Dwi Susanto (2101191026)
Saepul Uyun (2101191034)
```

## Dataset Source :
```
Dataset yang digunakan berasal dari UCI Machine Learning Repository 
Dataset akan dilampirkan beserta full source code dari project ini.
```
[Go To UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Student+Performance)

## Pre-Condition :
```
- 	Atribut pada dataset ini (student-mat.csv) ada 33 macam yaitu :
	1 school - student's school (binary: 'GP' - Gabriel Pereira or 'MS' - Mousinho da Silveira)
	2 sex - student's sex (binary: 'F' - female or 'M' - male)
	3 age - student's age (numeric: from 15 to 22)
	4 address - student's home address type (binary: 'U' - urban or 'R' - rural)
	5 famsize - family size (binary: 'LE3' - less or equal to 3 or 'GT3' - greater than 3)
	6 Pstatus - parent's cohabitation status (binary: 'T' - living together or 'A' - apart)
	7 Medu - mother's education (numeric: 0 - none, 1 - primary education (4th grade), 2 â€“ 5th to 9th grade, 3 â€“ secondary education or 4 â€“ higher education)
	8 Fedu - father's education (numeric: 0 - none, 1 - primary education (4th grade), 2 â€“ 5th to 9th grade, 3 â€“ secondary education or 4 â€“ higher education)
	9 Mjob - mother's job (nominal: 'teacher', 'health' care related, civil 'services' (e.g. administrative or police), 'at_home' or 'other')
	10 Fjob - father's job (nominal: 'teacher', 'health' care related, civil 'services' (e.g. administrative or police), 'at_home' or 'other')
	11 reason - reason to choose this school (nominal: close to 'home', school 'reputation', 'course' preference or 'other')
	12 guardian - student's guardian (nominal: 'mother', 'father' or 'other')
	13 traveltime - home to school travel time (numeric: 1 - <15 min., 2 - 15 to 30 min., 3 - 30 min. to 1 hour, or 4 - >1 hour)
	14 studytime - weekly study time (numeric: 1 - <2 hours, 2 - 2 to 5 hours, 3 - 5 to 10 hours, or 4 - >10 hours)
	15 failures - number of past class failures (numeric: n if 1<=n<3, else 4)
	16 schoolsup - extra educational support (binary: yes or no)
	17 famsup - family educational support (binary: yes or no)
	18 paid - extra paid classes within the course subject (Math or Portuguese) (binary: yes or no)
	19 activities - extra-curricular activities (binary: yes or no)
	20 nursery - attended nursery school (binary: yes or no)
	21 higher - wants to take higher education (binary: yes or no)
	22 internet - Internet access at home (binary: yes or no)
	23 romantic - with a romantic relationship (binary: yes or no)
	24 famrel - quality of family relationships (numeric: from 1 - very bad to 5 - excellent)
	25 freetime - free time after school (numeric: from 1 - very low to 5 - very high)
	26 goout - going out with friends (numeric: from 1 - very low to 5 - very high)
	27 Dalc - workday alcohol consumption (numeric: from 1 - very low to 5 - very high)
	28 Walc - weekend alcohol consumption (numeric: from 1 - very low to 5 - very high)
	29 health - current health status (numeric: from 1 - very bad to 5 - very good)
	30 absences - number of school absences (numeric: from 0 to 93)
	
	# these grades are related with the course subject, Math or Portuguese:
	31 G1 - first period grade (numeric: from 0 to 20)
	31 G2 - second period grade (numeric: from 0 to 20)
	32 G3 - final grade (numeric: from 0 to 20, output target)

- 	Tidak Semua dari atribut akan digunakan sebagai bahan perhitungan prediksi, atribut yang akan digunakan antara lain adalah :
	1 studytime
	2 failures
	3 famsup
	4 paid
	5 internet
	6 health
	7 absences
	8 studytime
	9 G1
	10 G2
```
