
# School District Analysis

## Background

The school board has notified Maria and her supervisor that the
students_complete.csv file shows evidence of academic dishonesty;
specifically, reading and math grades for Thomas High School ninth
graders appear to have been altered. Although the school board does
not know the full extent of the academic dishonesty, they want to
uphold state-testing standards and have turned to Maria for help.
She has asked you to replace the math and reading scores for Thomas
High School with NaNs while keeping the rest of the data intact.
Once you’ve replaced the math and reading scores, Maria would like
you to repeat the school district analysis that you did in this module
and write up a report to describe how these changes affected the overall
analysis.


*    How is the district summary affected?
		* The district summary was minimally affected.
	    * Average Math Score went from 79.0% to 78.9%.
	    * Average reading score was unchanged.
	   *  	% Passing Math went from 75% to 74.8%.
	    * % Passing Reading went from 85.8% to 85.7%.
	    * and Overall % passing dropped from 65.2% to 64.9%

*    How is the school summary affected?

     *  The only school affected was Thomas High School so scores for other schools remained the same.

*    How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

        *   The per school summary shows a drop in:
	        * Average Math Score, Average Reading Score, % Passing Math and % Passing Reading as well as
	        * % Overall Passing. No other metrics were affected.
	        * Average Math Score and Average Reading scores dropped slightly but the % Passing Math and
	        * Percent Passing Reading as well as Overall % Passing
	        * declined significantly with drops of 28.3%, 28.4% and 28.4% respectively.

*    How does replacing the ninth-grade scores affect the following:

	  * Math and reading scores by grade

        *   Scores remain unchanged for all but Thomas High School 9th grade which were replaced by NaNs

	   * Scores by school spending

	        * Scores by school spending was minimally impacted as well and only for spending ranges 630 - 644 per student with the pattern remaining consistent. most scores declining slightly while average reading score increasing slightly.

	    * Scores by school size

			* Scores medium sized schools were affected as but only minimally. Average reading score increased slightly while the other metrics dropped slightly.

	    * Scores by school type

	        *   Scores dropped somewhat by charter schools for all measures. scores for district schools remain unchanged.

## Summary
The four major changes in the updated school district analysis after reading and math scores for
the ninth grade at Thomas High School have been replaced with NaNs.
1. values for 9th grade reading and math scores affected medium sized schools
2. scores for schools with spending ranges between 630 and 644 declined slightly
3. scores for Thomas High School declined significantly averaging a 28% drop as a result of replacing the scores
4. the district summary was minimally affected with slight declines of less than 1% for average reading, math and % passing scores.
