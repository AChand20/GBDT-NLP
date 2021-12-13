# GBDT-NLP
GBDT on Donors Choose Dataset (NLP)
<ol>
    <li><strong>Applying GBDT on these feature sets</strong>
        <ul>
            <li><font color='red'>Set 1</font>: categorical(encoded using response coding: using probability values), numerical features + project_title(TFIDF)+  preprocessed_eassay (TFIDF)+sentiment Score of eassay(check the bellow example, include all 4 values as 4 features)</li>
            <li><font color='red'>Set 2</font>: categorical(encoded using response coding: using probability values), numerical features + project_title(TFIDF W2V)+  preprocessed_eassay (TFIDF W2V)</li>        </ul>
    </li>
    <br>
    <li><strong>The hyper paramter tuning (Considering any two hyper parameters)</strong>
        <ul>
    <li>Finding the best hyper parameter which will give the maximum AUC value</li>
    <li>Finding the best hyper paramter using k-fold cross validation/simple cross validation data</li>
    <li>Using gridsearch cv or randomsearch cv for hyper paramter tuning</li>
        </ul>
    </li>
    <br>
    <li>
    <strong>Representation of results</strong>
        <ul>
    <li>Ploting the performance of model both on train data and cross validation data for each hyper parameter</li>
    <li>After finding the best hyper parameter, training my model with it, and finding the AUC on test data and ploting the ROC curve on both train and test.
    </li>
    <li>Displaying the confusion matrix with predicted and original labels of test data points
    </li>
            </ul>
    <br>
    <li><strong>Summarizing the results at the end of the notebook<strong>
</ol>
