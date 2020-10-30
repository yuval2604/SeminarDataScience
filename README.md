# SeminarDataScience


DataScience Seminar

We are Yuval (206587982) and Gabriella (315478404), young computer science students who are passionate about data science.
When we were thinking what project we would like to be doing this semester, we instantly knew that we want to learn something new.
Since we both never had a project with Data science and Machine learning, and since we both are passionate about the medicine world - when we browsed Kaggle for an open competition, a competition related to diagnosing cancer intrigued us immediately.
We took the data from Wisconsin University Data Set, those features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the image.
The competition's purpose is to Predicting if the cancer diagnosis is benign or malignant based on several observations/feature. We used 30 features, amoung them are :

- radius (mean of distances from center to points on the perimeter)
- texture (standard deviation of gray-scale values)
- perimeter
- area
- smoothness (local variation in radius lengths)
- compactness (perimeter^2 / area - 1.0)
- concavity (severity of concave portions of the contour)
- concave points (number of concave portions of the contour)
- symmetry
- fractal dimension ("coastline approximation" - 1)

We learned that this dataset is 8 times bigger than any previously publicly released dataset. It is still fresh and the competition is still open.

When we dove a little deeper we discovered it was even more challenging than we thought - with a massive, unclean dataset that does not fit into memory - we were very excited and a little bit intimidated.

THE PROBLEM :

Breast cancer has been identified as the second largest cause of cancer deaths among women of age 40 and 55. The number of breast cancer diagnosis is estimated to be 1.2 million among women every year according to projections by the World Health Organization . According to statistics by the American cancer society in 2001, about 40,200 deaths are caused by the breast cancers and 192,000 cases consist of women who are newly diagnosed. Additional statistics as of 2006 estimated 214,460 new cancer diagnosis and total death at least 41,000 within the US . Early detection and accurate diagnosis has been crucial in reducing the number of deaths which has increased the survival rate of those diagnosed with breast cancer.


In addition to kaggle breast cancer wisconsin dataset, a we looked for another dataset of breast cancer. We found the breast histopathology images dataset on kaggle this dataset include imagesand not only a table.

Invasive Ductal Carcinoma (IDC) is the most common subtype of all breast cancers. To assign an aggressiveness grade to a whole mount sample, pathologists typically focus on the regions which contain the IDC. As a result, one of the common pre-processing steps for automatic aggressiveness grading is to delineate the exact regions of IDC inside of a whole mount slide. The dataset consisted of 162 whole mount slide images of Breast Cancer (BCa) specimens scanned at 40x. From that, 277,524 patches of size 50 x 50 were extracted (198,738 IDC negative and 78,786 IDC positive).
this dataset is divide into cases with IDC and cases without, our goal is to predict for each sample if it has IDC or not.
