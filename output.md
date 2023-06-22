
 ------------  -----------------  --------------   --------------

 ### proces directery to see if there is any currept imges
 
 Total Image file count is 33126 
 Total currept imge files count is 0


 Recommendations:
 
  Column 'image_name' is categorical. Consider encoding it using label encoding or one-hot encoding.
 
  Column 'patient_id' is categorical. Consider encoding it using label encoding or one-hot encoding.
 
  Column 'sex' has missing values. Consider using dropna() or fillna().
 
  Column 'sex' is categorical. Consider encoding it using label encoding or one-hot encoding.
 
  Column 'age_approx' has missing values. Consider using dropna() or fillna().
 
  Column 'age_approx' is numerical. Consider scaling it using standard scaling or min-max scaling.
 
  Column 'anatomy_sites' has missing values. Consider using dropna() or fillna().
 
  Column 'anatomy_sites' is categorical. Consider encoding it using label encoding or one-hot encoding.
 
  Column 'diagnosis' is categorical. Consider encoding it using label encoding or one-hot encoding.
 
  Column 'benign_malignant' is categorical. Consider encoding it using label encoding or one-hot encoding.
 
  Column 'target' is numerical. Consider scaling it using standard scaling or min-max scaling.

 Recommendations - END -:

 ## DataFrame info befor process :
|    |   index | Name             |   Count | Non-Null   | Dtype   |
|---:|--------:|:-----------------|--------:|:-----------|:--------|
|  0 |       0 | image_name       |   33126 | non-null   | object  |
|  1 |       1 | patient_id       |   33126 | non-null   | object  |
|  2 |       2 | sex              |   33126 | non-null   | object  |
|  3 |       3 | age_approx       |   33126 | non-null   | float64 |
|  4 |       4 | anatomy_sites    |   33126 | non-null   | object  |
|  5 |       5 | diagnosis        |   33126 | non-null   | object  |
|  6 |       6 | benign_malignant |   33126 | non-null   | object  |
|  7 |       7 | target           |   33126 | non-null   | int64   |



 ## Missing values befor & aftre  process :
|                  |   Befor |   After |
|:-----------------|--------:|--------:|
| age_approx       |       0 |       0 |
| anatomy_sites    |       0 |       0 |
| benign_malignant |       0 |       0 |
| diagnosis        |       0 |       0 |
| image_name       |       0 |       0 |
| patient_id       |       0 |       0 |
| sex              |       0 |       0 |
| target           |       0 |       0 |



 ## Unique values befor & aftre  process :
|                  |   Befor |   After |
|:-----------------|--------:|--------:|
| age_approx       |      20 |      18 |
| anatomy_sites    |       6 |       6 |
| benign_malignant |       2 |       2 |
| diagnosis        |       9 |       5 |
| image_name       |   33126 |    1168 |
| patient_id       |    2056 |     776 |
| sex              |       2 |       2 |
| target           |       2 |       2 |



 ## Value counts befor & aftre  process :
|    | Column           | Value           |   Count Befor |   Count After |
|---:|:-----------------|:----------------|--------------:|--------------:|
|  0 | sex              | male            |         17145 |           672 |
|  1 | sex              | female          |         15981 |           496 |
|  2 | anatomy_sites    | torso           |         17372 |           556 |
|  3 | anatomy_sites    | lower extremity |          8417 |           293 |
|  4 | anatomy_sites    | upper extremity |          4983 |           191 |
|  5 | anatomy_sites    | head/neck       |          1855 |           108 |
|  6 | anatomy_sites    | palms/soles     |           375 |            14 |
|  7 | anatomy_sites    | oral/genital    |           124 |             6 |
|  8 | benign_malignant | benign          |         32542 |           584 |
|  9 | benign_malignant | malignant       |           584 |           584 |
| 10 | target           | 0               |         32542 |           584 |
| 11 | target           | 1               |           584 |           584 |



 ## Descriptive statistics befor and after the process:
|       |   age_approx |        target |   age_approx |      target |
|:------|-------------:|--------------:|-------------:|------------:|
| count |   33126      | 33126         |    1168      | 1168        |
| mean  |      48.8691 |     0.0176297 |      53.4746 |    0.5      |
| std   |      14.3656 |     0.131603  |      16.185  |    0.500214 |
| min   |       0      |     0         |      10      |    0        |
| 25%   |      40      |     0         |      40      |    0        |
| 50%   |      50      |     0         |      55      |    0.5      |
| 75%   |      60      |     0         |      65      |    1        |
| max   |      90      |     1         |      90      |    1        |


