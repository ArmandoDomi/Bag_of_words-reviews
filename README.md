# Bag_of_words-reviews
Bag of words for feature extraction and then we use a svm for th classification

<br>
<br>1 Gather all the words that exist in the dataset and apply the morphological processing.
<br>2 Remove the "Stopwords".
<br>3 Remove the punctuation marks, and make a sorted list where each word appears once.
<br>4 Replace every review with a feature vector.


# Confusion Matrix
At test set
<table>
  <col>
  <colgroup span="2"></colgroup>
  <colgroup span="2"></colgroup>
  <tr>
    <td rowspan="2"></td>
    <th colspan="2" scope="colgroup">Predicted Label</th>
  </tr>
  <tr>
    <th scope="col">Negative</th>
    <th scope="col">Positive</th>
  </tr>
  <tr>
    <th scope="row">Negative</th>
    <td>362</td>
    <td>91</td>
  </tr>
  <tr>
    <th scope="row">Positive</th>
    <td>102</td>
    <td>345</td>
  </tr>
</table>



# Results
<table>
  <caption>Results at test set :</caption>
  <tr>
    <td></td>
    <th scope="col">Accuracy</th>
    <th scope="col">Presicion</th>
    <th scope="col">Recall</th>
    <th scope="col">Fmeasure</th>
    <th scope="col">Spesificity</th>
  </tr>
  <tr>
    <th scope="row">SVM</th>
    <td>0.78</td>
    <td>0.79</td>
    <td>0.77</td>
    <td>0.78</td>
    <td>0.79</td>
  </tr>
</table>
