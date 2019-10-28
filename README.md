# School_District_Analysis
I have used 3 different data sets "schools_complete.csv", "students_complete.csv"
and "clean_students_complete.csv". The data first has been corrected for suffixes and prefixes by defining them in function and using for loop to drop them and replace them with “ “.
Then the reading and math scores for ninth graders at Thomas High School has been replaced to NaN using the NumPy function.
Then the “clean student data” and “school data”  has been merged by the school name in one table called “clean_student_data_df”, as well as “school data replaced with nan” and “student data” merged in another table called “school_data_nan_df”.
There “district_analysis_df” that been used on “clean_student_data_df” and the “district_analysis_nan_df” on data from “school_data_nan_df”.
 The two-district summery has been concatenated on a table which has shown the changes for percentage of passing math and passing reading and overall passing percentage as ninth grades has been dropped at Thomas high school. The averages have not changed significantly.
![DistrictSummary](https://github.com/hbostanchi/School_District_Analysis/blob/master/District_Summary.png)
	 
Per school summery is also calculated on both “clean_student_data_df”  and  “school_data_nan_df”. Then I extracted the Thomas High School row from each of above tables and put them in a summary table below. The results have shown significant change for passing percentage of math, reading and overall percentage, which  has been expected by dropping some of the data.
![SchoolSummary](https://github.com/hbostanchi/School_District_Analysis/blob/master/Summary_BySchool.png)

Also Thomas high school is charter school so the school relatively affected the charter school scores and wouldn’t affect the district school at all.
![TypeSummary](https://github.com/hbostanchi/School_District_Analysis/blob/master/Summary_ByType.png)

Removing the ninth-grade scores also affected the per grade summery. This also has done on two data sets and the results were almost came identical but for ninth grade , so there is a concatenation table for Thomas high school ninth grade summery that shown the math and reading scores affect by dropping the data.
![GradeSummary](https://github.com/hbostanchi/School_District_Analysis/blob/master/Summary_byGrade.png)

Per spending summery shown the difference for the percent of the math and reading score
![SpendingSummary](https://github.com/hbostanchi/School_District_Analysis/blob/master/Summary_BySpending.png)

Lastly size summery also shown the difference for the % of the scores
![SizeSummary](https://github.com/hbostanchi/School_District_Analysis/blob/master/Summary_BySize.png)