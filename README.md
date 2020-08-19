# Modern face recognition with deep learning October 2019 
## Deatils has explained in report.pdf file.

This  report,  follows  as  Face  detection,  faces  are  extracted  from  images,  Pose  estimation  face 
alignment has done, Face encoding, encoding the extracted faces, Face recognition, some classifier 
has defined, Result, compere result of classifier and Conclusion. 

## Result 
We  predict  test  set  and  train  set  data  with  trained  model  in  previous  part  with  three  classifier. 
Below table and chart represent the result. 
Logistic regression (LR) classifier has 95.53% accuracy on train set and 91.66% accuracy on test 
set.  SVM  has  100%  accuracy  on  train  set  and  93.75%  accuracy  on  test  set.  KNN  has  100% 
precision on both train and test set. 

    Train    accuracy   Test Accuracy    Accuracy 
    LR        95.53%      91.66%         91.66% 
    SVM       100%        93.75%         93.75% 
    KNN       100%        100%            100% 
    
## Conclusion 
Based  on  result  KNN  and  SVM  classifier  have  100%  accuracy.  But  on  example  images  KNN 
classifier  had  better  detection  than  SVM.  Then  KNN  classifier  chose  to  do  face  recognition  on 
provided video.

