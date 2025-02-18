* Unit 1:Terminology and Notation
Because of the hybrid parentry of data mining, its practitioners often
use multiple terms to refer to the same thing. For example, in the
machine learning (artificial intelligence) field, the variable being
predicted is the output variable or target variable. To a statistician, it is
the dependent variable or the response. Here is a summary of terms
used:

Algorithm A specific procedure used to implement a particular
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

Supervised Learning The process of providing an algorithm
(logistic regression, regression tree, etc.) with records in which an
output variable of interest is known and the algorithm “learns”
how to predict this value with new records where the output is
unknown.

Target see Response.

Test Data (or Test Set) The portion of the data used only at the
end of the model building and selection process to assess how well
the final model might perform on new data.

Training Data (or Training Set) The portion of the data used
to fit a model.

Unsupervised Learning An analysis in which one attempts to
learn patterns in the data other than predicting an output value of
interest.

Validation Data (or Validation Set) The portion of the data
used to assess how well the model fits, to adjust models, and to
select the best model from among those that have been tried.
Variable Any measurement on the records, including both the
input (X) and the output (Y) variables.
