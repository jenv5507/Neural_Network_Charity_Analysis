# Neural Network Charity Analysis

## <b>Overview of the analysis:</b>

The purpose of the analysis was to help the foundation predict where to make investments.  I was provided with a list of over 34,000 organzations that have received funding from Alphabet Soup and will be creating a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

## <b>Results</b>

Data Preprossing:
 - The Target is 'Is Successful'.
 - The features are Application Type, Affiliation, Classification Use Case, Organization, Income Amount and Ask Amount.
 - EIN, Name, Status, and Special Consideration were removed from the data before processing.

Compiling, Training, and Evaluating the Model:

![](/Resources/compile_model.png)

 - The image above is the selection for the neural network and I was able to get it to a 72.58% accuracy.
 - I made 3 separate attemps and was not able to get it to the achieved target model performance of 75%.  Following are some of the adjustments I made to to try to achieve the 75% accruacy.
  -  Added another layer
  -  Increased the nodes
  -  Changed the activation methods

## <b>Summary</b>
Since I was not able to reach the accuracy of 75%, I would recommend using another model to determine which charities were successfuly based on funding received. I would suggest using a Random Forest Classifier as it combines multiple models to help improve the accruacy and robustness and therefore, increase the overall performance of the model.  

