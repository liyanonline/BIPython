# Unit 1:Terminology and Notation
Because of the hybrid parentry of data mining, its practitioners often
use multiple terms to refer to the same thing. For example, in the
machine learning (artificial intelligence) field, the variable being
predicted is the output variable or target variable. To a statistician, it is
the dependent variable or the response. Here is a summary of terms
used:

* Algorithm A specific procedure used to implement a particular
data mining technique: classification tree, discriminant analysis,
and the like.

Attribute see Predictor.
Case see Observation.
Categorical Variable A variable that takes on one of several
fixed values, for example, a flight could be on-time, delayed, or
canceled.

Confidence A performance measure in association rules of the
type “IF A and B are purchased, THEN C is also purchased.”
Confidence is the conditional probability that C will be purchased
IF A and B are purchased.
Confidence also has a broader meaning in statistics (confidence
interval), concerning the degree of error in an estimate that
results from selecting one sample as opposed to another.
Dependent Variable see Response.
Estimation see Prediction.
Factor Variable see Categorical Variable
Feature see Predictor.
Holdout Data (or Holdout Set) A sample of data not used in
fitting a model, but instead used to assess the performance of that
model. This book uses the terms validation set and test set
instead of holdout set.
Input Variable see Predictor.
Model An algorithm as applied to a dataset, complete with its
settings (many of the algorithms have parameters that the user
can adjust).
Observation The unit of analysis on which the measurements
are taken (a customer, a transaction, etc.), also called instance,
sample, example, case, record, pattern, or row. In spreadsheets,
each row typically represents a record; each column, a variable.
Note that the term “sample” here is different from its usual
meaning in statistics, where it refers to a collection of
observations.

Outcome Variable see Response.

Output Variable see Response.

The conditional probability of event A occurring given
that event B has occurred, read as “the probability that A will
occur given that B has occurred.”
Prediction The prediction of the numerical value of a
continuous output variable; also called estimation.

Predictor A variable, usually denoted by X, used as an input into
a predictive model, also called a feature, input variable,
independent variable, or from a database perspective, a field.

Profile A set of measurements on an observation (e.g., the
height, weight, and age of a person).
Record see Observation.

Response A variable, usually denoted by Y, which is the variable
being predicted in supervised learning, also called dependent
variable, output variable, target variable, or outcome variable.

Sample In the statistical community, “sample” means a
collection of observations. In the machine learning community,
“sample” means a single observation.
Score A predicted value or class. Scoring new data means using
a model developed with training data to predict output values in
new data.

Success Class The class of interest in a binary outcome (e.g.,
purchasers in the outcome purchase/no purchase).

* Supervised Learning The process of providing an algorithm
(logistic regression, regression tree, etc.) with records in which an
output variable of interest is known and the algorithm “learns”
how to predict this value with new records where the output is
unknown.

Target see Response.

* Test Data (or Test Set) The portion of the data used only at the
end of the model building and selection process to assess how well
the final model might perform on new data.

* Training Data (or Training Set) The portion of the data used
to fit a model.

* Unsupervised Learning An analysis in which one attempts to
learn patterns in the data other than predicting an output value of
interest.

* Validation Data (or Validation Set) The portion of the data
used to assess how well the model fits, to adjust models, and to
select the best model from among those that have been tried.
Variable Any measurement on the records, including both the
input (X) and the output (Y) variables.
# Unit2: Ch2 Overview of the Data Mining Process
 1. Assuming that data mining techniques are to be used in the
 following cases, identify whether the task required is supervised
 or unsupervised learning.
 a. Deciding whether to issue a loan to an applicant based on
 demographic and financial data (with reference to a database
 of similar data on prior customers).
 b. In an online bookstore, making recommendations to
 customers concerning additional items to buy based on the
 buying patterns in prior transactions.
 c. Identifying a network data packet as dangerous (virus, hacker
 attack) based on comparison to other packets whose threat
status is known.
 d. Identifying segments of similar customers.
 e. Predicting whether a company will go bankrupt based on
 comparing its financial data to those of similar bankrupt and
 nonbankrupt firms.
 f. Estimating the repair time required for an aircraft based on a
 trouble ticket.
 g. Automated sorting of mail by zip code scanning.
 h. Printing of custom discount coupons at the conclusion of a
 grocery store checkout based on what you just bought and
 what others have bought previously.
 2. Describe the difference in roles assumed by the validation
 partition and the test partition.
 3. Two models are applied to a dataset that has been partitioned.
 Model A is considerably more accurate than model B on the
 training data, but slightly less accurate than model B on the
 validation data. Which model are you more likely to consider for
 final deployment?

# Unit 3: Data Visualization
3.6 Summary: Major Visualizations and
 Operations, by Data Mining Goal
 * Prediction
 Plot outcome on the y-axis of boxplots, bar charts, and scatter
 plots.
 Study relation of outcome to categorical predictors via side-by
side boxplots, bar charts, and multiple panels.
 Study relation of outcome to numerical predictors via scatter
 plots.
 Use distribution plots (boxplot, histogram) for determining
 needed transformations of the outcome variable (and/or
 numerical predictors).
 Examine scatter plots with added color/panels/size to determine
 the need for interaction terms.
 Use various aggregation levels and zooming to determine areas of
 the data with different behavior, and to evaluate the level of global
vs. local patterns.
 * Classification
 Study relation of outcome to categorical predictors using bar
 charts with the outcome on the y-axis.
 Study relation of outcome to pairs of numerical predictors via
 color-coded scatter plots (color denotes the outcome).
 Study relation of outcome to numerical predictors via side-by-side
 boxplots: Plot boxplots of a numerical variable by outcome. Create
 similar displays for each numerical predictor. The most separable
 boxes indicate potentially useful predictors.
 Use color to represent the outcome variable on a parallel
 coordinate plot.
 Use distribution plots (boxplot, histogram) for determining
 needed transformations of numerical predictor variables.
 Examine scatter plots with added color/panels/size to determine
 the need for interaction terms.
 Use various aggregation levels and zooming to determine areas of
 the data with different behavior, and to evaluate the level of global
 vs. local patterns.
 * Time Series Forecasting
 Create line graphs at different temporal aggregations to determine
 types of patterns.
 Use zooming and panning to examine various shorter periods of
 the series to determine areas of the data with different behavior.
 Use various aggregation levels to identify global and local
 patterns.
 Identify missing values in the series (that will require handling).
 Overlay trend lines of different types to determine adequate
 modeling choices.
 * Unsupervised Learning
 Create scatter plot matrices to identify pairwise relationships and
 clustering of observations.
 Use heatmaps to examine the correlation table.
 Use various aggregation levels and zooming to determine areas of
 the data with different behavior.
 Generate a parallel coordinates plot to identify clusters of
 observations.
