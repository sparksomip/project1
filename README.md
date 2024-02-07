# Project 1
<h3>Spam Detection Project</h3>

The dataset consists of information from 4601 e–mailmessages, in a study to screen e–mail for spam. For 3101 of these e–mails you known whether they are spam [response = 2] or non–spam [response = 1], and you have additional input variables describing several features of each e–mail. For the other 1500 e–mails, you have only information on the inputs. Your goal is to construct a classifier which has good performance in labeling the remaining 1500 e–mails as spam or non–spam. Note that in classifying as spam an e–mail which is actually non–spam you pay a cost of 5. Classifying as non–spam e–mails which are actually spam is less dangerous and hence you pay a cost of 1.

<h4>Input Variables</h4>  
There are 57 input variables which are described below. <br> 
- 48 quantitative predictorsmeasuring the percentage ofwords in the e–mail that match a given word. Examples include business, address, internet, etc . . . <br>     
- 6 quantitative predictors measuring the percentage of specific characters/symbols found in the e–mail. These are charSemicolon, charRoundbracket, charSquarebracket, charExclamation, charDollar and charHash. <br>
- Average length of uninterrupted sequences of capital letters [capitalAve]. Length of the longest uninterrupted sequence of capital letters [capitalLong]. Sum of the length of uninterrupted sequences of capital letters [CapitaTotal]. <br>
<br>
<h4>(Links here!)</h4>
<h4>- 📝 **FINAL CODE:** [https://github.com/sparksomip/project1/blob/main/SpamDetectionCode.Rmd]</h4>

- Problem Description: [https://github.com/sparksomip/project1/blob/main/Problem-Details.pdf]<br>
- Train Data Set: [https://github.com/sparksomip/project1/blob/main/train.csv]<br>
- Test Data Set: [https://github.com/sparksomip/project1/blob/main/test.csv]<br>
- Weight Calculation Method: [https://github.com/sparksomip/project1/blob/main/test.csv]<br>
- Result Submitted: [https://github.com/sparksomip/project1/blob/main/FInal%20Submission%20of%20Spam%20Detection_Forecast.txt]<br>
