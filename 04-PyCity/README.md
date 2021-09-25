# PyCitySchools with Pandas

## Overview of the school district analysis:

The purpose of the analysis is to Perform an analysis using school and student data to inform a school district on their budget and priorities.

## Results:


The entire ninth grade class of Thomas High School have had their scores replaced with NaN.

Replacing the ninth graders' math and reading scores with NaN resulted in the following changes for Thomas High School:
The overall passing percentage for Thomas High School fell to 65%,

The overall passing percentage for the entire district fell to 64.9%,

Thomas High School was no longer included on the list of top five schools.

When the ninth graders' of Thomas High School had their scores omitted from the calculations, the following changes occured:
The overall passing percentages of Thomas High School decreased by 0.11%,

The average scores of Thomas High School for math and reading increased by 0.06,

For the spending range of $630-644 per student, the overall passing percentage decreased by 0.1% Thomas High School is still the second best performing school in the district with an overall passing rate of 90.63% among their tenth through twelfth graders.

It is found that Average Scores and Passing Percentages do not increase as spending per student increases. In fact, the top performing school in the entire school district (Cabera High School) received $68 less per student than the lowest performing school (Johnson High School). This implies that there are more relevant factors than funding that decide average student scores.

When considering School Sizes, "Large" Schools (Over 2,000 Students) have the lowest average scores and passing percentages. The difference in performance between "Small" and "Medium" Size Schools is negligible (approximately 1%). Interestingly, all District schools in this dataset are characterized as "Large" schools. This may be an indication that students in this district learn and perform better in smaller, more intimate settings.

After analyzing the average scores for math and reading by grade level for each school, it is found that a students grade level does not affect their scores as much as the school that they attend. The average scores within each school only varries by 1-2% depending on grade level. However, the difference in scores is more apparent when comparing different schools.



## Summary: 

When reviewing the School Spending summary, this data change did not impact the spending ranges for either the average math scores or average reading scores. However, this data change did impact the spending ranges for passing percentages. According to the summary above, there was a 6% decrease in % passing math, a 7% decrease in % passing reading, and a 6% decrease in % overall passing in the $630-644 spending range.

When reviewing the School Size summary, removing the ninth grade scores did not affect the average math and reading scores, but it did affect the passing percentages for medium-sized schools (1,000-2,000). In this category, % passing math, % passing reading, and % overall passing dropped 6% each. Before the data change, the School Size summary showed that medium-sized school had a high performance (91% overall passing) compared to small (90% overall passing) and large schools (58% overall passing). Given the data change, medium size school are the second in performance (85% overall passing).

Replacing the ninth graders' scores with NaN caused Thomas High School's overall passing percentages and average scores to plummet. The district as a whole has also had its average math and reading scores decrease, as well as the overall passing percentage for students. Furthermore, Thomas High School lost its placement as a top five school within this District. However, after updating the total student counts to exclude the Thomas High School ninth graders and omitting their scores from the dataset, Thomas High School regained its high average scores and retained its position as the number two school in the District.

