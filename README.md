# Overview of Analysis
Making informed decisions when determining the budget for schools requires a lot of data. This activity was intended to gather all of the data on schools in a district, parse out the most important factors, display them in easy to read charts, and calculate any statistics that could help making a budget decision. Data points like school size, testing scores, current budget, and type of school are all important things to consider when re-orienting budget priorities. By the end of the activity, board members will be able to analyze the data displayed and decide what changes, if any, to make. 
##Results
- The impact to the district summary after the changes to T.H.S's 9th grade class were negligible. In most cases, it only changed averages by less than .5% as seen in the following images, starting with the old analysis: ![District_analysis_old](https://github.com/dylanvowell/School_District_Analysis/blob/main/Resources/district_summary_old.png?raw=true) ![District_analysis_new](https://github.com/dylanvowell/School_District_Analysis/blob/main/Resources/district_summary_new.png?raw=true)
- The school summary is not impacted almost at all outside of T.H.S's scores since removing ~400 students out of over 30k is negligable. 
- Replacing the scores of T.H.S impacts their own stat in a negligable way since removing the 9th grade scores completely only changed values by less than 1% and didn't impact them at all if you rounded to the nearest whole percent ..
- Impacts on the ninth grade scores are reflected in the following:
  - Math and reading scores by grade were significantly impacted due to 9th graders having no scores to show
  - Scores by school spending was not impacted since the differences only caused a change of less than .5% in most cases and did not impact any rounding
  - Scores by school size was not impacted in any significant way
  - Scores by school type was not impacted in any significant way
#Summary
There were no significant changes to score averages after changing the 9th grade scores to a NaN value for T.H.S. While those changes did impact total average scores, percent passing reading, percent passing math, and overall passing percent, the changes were so minute considering the fact we did not use 0 as a value, that the actual end result after rounding were identical.
