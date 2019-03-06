**Geog. 4/595 --  Geographic Data Analysis**  
**Winter 2019 -- Due Thursday, March 21, 5pm**

Answer the following questions in clear, complete, and grammatically-correct sentences. You may, however, illustrate any specific answer by using a table or figure, with accompanying text. Be brief, but informative. *Make sure you answer all parts of a question.* The questions below probably are answerable within *a single page each*, but do not exceed two double-spaced pages (in a 10 or 12-point font, with normal margins) for *each* question (figures may be attached as additional pages). 

Because it is likely that the opportunity to discuss the questions with others will arise, you may do so, but work out and write down the answers yourself.

1.&nbsp;Many data-analytical procedures share one version or another of the same underlying conceptual model: 

&nbsp; &nbsp; &nbsp; &nbsp; *data = predictable component + unpredictable component*; or  
&nbsp; &nbsp; &nbsp; &nbsp; *data = signal + noise*; or   
&nbsp; &nbsp; &nbsp; &nbsp; *data* = *smooth component + irregular component*; or  
&nbsp; &nbsp; &nbsp; &nbsp; *data = common variation + unique variation.*

For a) regression analysis, b) analysis of variance, c) nonparameteric regression, and d) principal components or factor analysis, describe the particular version of that common conceptual model that applies, and why that conceptual model makes sense given the goals of the analysis.  Note that you shouldn't necessarily try to match the three analyses with one or another of different versions of the conceptual model--those are just examples, and there could be other ways of describing the basic model that might work better in each case.  Or it could be the case that two analyses share the same model.  It might be useful to make a table first, before writing; if so, the whole answer will probably fit on a page.

2.&nbsp;Describe the general context in which multiple linear regression analysis is applicable. (What is it used for? Are there any assumptions that underlie its use? How is it implemented in practice? (And don't just say, "by  using the `lm()` function..."!)

3.&nbsp;Many of the statistics we've seen, like the coefficient of variation, correlation coefficient, t-test, and others, are fractions, with a term in the numerator and a term in the denominator.  For as many statistics you can think of, characterize in words what the quantities in the numerator and denomentor represent, and then comment why that particular arrangement (something in the numerator, something in the denominator) makes sense in general.  Again, an efficient way of answering this question would be a table and a sentence or two.

4.&nbsp;Suppose you are in charge of the data-analysis component of a project that generates one or more data sets (or data frames), that include the following kinds of variables (i.e. columns):  

1. some kind of text identification label (like the abbreviations of the weather station names in the Oregon climate  data set);
1. locational information (e.g. latitude and longitude, or x and y);
2. one more response variables (i.e. variables that you would like to "explain" or predict); 
3. several candidate predictor variables;
4. one or more factor (or group membership) variables (like the Reach variable in the Summit Cr. data set) that identify which group a particular observation comes from or is assigned to.

Describe an overall strategy for making sense of this data set.  What kind of plots or visualizations might you apply (*and why*)?  What kind of analyses (*and why*)?
