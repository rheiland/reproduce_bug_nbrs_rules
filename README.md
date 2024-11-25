# reproduce_bug_nbrs_rules

Nov 24, 2024 (Daniel, slack)
: to anyone wanting to see the bug referenced in https://github.com/MathCancer/PhysiCell/issues/320 
(and with possible fixes in [#338](https://github.com/MathCancer/PhysiCell/pull/338) and 
[#339](https://github.com/MathCancer/PhysiCell/pull/339)), you can observe the error using the following config and rules files with the template project. 
I have used the current dev branch and the tag at 1.14.0. Both reliably produce the error. Interestingly, at the dev branch, it occurs within a few sim minutes. In 1.14.0 it occurs much later.
