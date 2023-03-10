# Machine_Learning_Trading_Bot

## Base Model Performance
### Accuracy Level: 55%, Precison: 0.56, Recall: 0.96
![BaseModel](https://user-images.githubusercontent.com/118318397/224219698-7a02da41-191c-4f7a-80b8-959dbe763754.JPG)
![BaseModel1](https://user-images.githubusercontent.com/118318397/224219697-f7e7b572-de7c-45ea-8d36-8d6a2902ecf4.png)

## Tuning the algorithm by adjusting the Training Dataset size:
## 3 months to 6 months
### Question: What impact resulted from increasing or decreasing the training window?
### Answer: The accuracy level increased by 1% when the training window is increased from 3 months to 6 months and the recall score also improved by 2% when the training window is increased to 6 months.
![6 months](https://user-images.githubusercontent.com/118318397/224219955-998f23aa-bc6f-4e04-be51-225ddb256678.JPG)
![6months](https://user-images.githubusercontent.com/118318397/224220022-db3b5576-8f58-4bd0-a9e8-32b11e100435.png)

## 3 months to 1 month:
### Question: What impact resulted from increasing or decreasing the training window?
### Answer: The accuracy level and recall rate remain constant and do not change when the training window is decreased to 1 month.
![1Month](https://user-images.githubusercontent.com/118318397/224220149-a983b786-7807-4745-b0e3-5fa51d711461.JPG)
![1Month](https://user-images.githubusercontent.com/118318397/224220192-60f25db3-4d6b-47b2-a730-1dde8878be05.png)

## Tuning the algorithm by adjusting the SMA Input features:
## Increasing both the short and long windows to 6 and 115 respectively:
### Question: What impact resulted from increasing or decreasing either or both of the SMA windows?
### Answer: By increasing the short window from 4 to 6 and also increasing the long window from 100 to 115, the accuracy and recall have both increased for the same size of the data-set.
![BothSMA](https://user-images.githubusercontent.com/118318397/224221275-6d3b0134-962c-4b18-8501-47822a9328d1.JPG)
![BothSMA](https://user-images.githubusercontent.com/118318397/224221320-a291d803-8553-43fe-9333-3ea096916051.png)

## Increasing only the short window to 6:
### Question: What impact resulted from increasing or decreasing either or both of the SMA windows?
### Answer: When the short SMA Window is increased to 6,the accuracy score increased to 56% and the recall score increased to 99%.
![Short6](https://user-images.githubusercontent.com/118318397/224221725-36fae241-3e15-4a73-b159-f7953125fd9d.JPG)
![Short6](https://user-images.githubusercontent.com/118318397/224221755-c8902eff-72fa-44f9-9f38-a7dce0ad2457.png)

## Increasing only the long window to 115:
### Question: What impact resulted from increasing or decreasing either or both of the SMA windows?
### Answer:  The accuracy score and recall score, both increased by increasing only the long window to 115 for the same size of training data-set.
![Long115](https://user-images.githubusercontent.com/118318397/224221942-d9e59fa3-5da9-4833-ae80-0794f46a512d.JPG)
![Long115](https://user-images.githubusercontent.com/118318397/224221969-47bfe934-275c-4b1f-805d-c36b4303f9f2.png)

## Conclusion:
### Increasing the short window to 6 and long window to 115 for a 3 month training dataset produces the best set of parameters that provide us with improved trading algorithm returns. Based on these parameters, accuracy score is 56% and recall score is 99%.

## AdaBoost Classifier Model
### Question: Did this new model perform better or worse than the provided baseline model? Did this new model perform better or worse than your tuned trading algorithm?
### Answer: The accuracy increased majorly (to 83%) when compared to both, the base model (55%) and the tuned model (56%). But the recall level have decreased slightly to 0.97 in the AdaBoost model when compared with the tuned algo model (0.99) but are higher when compared to the base model (0.95).The AdaBoost model is a better perfroming model, when compared to both the base and tuned algorithm models.
![AdaBoost](https://user-images.githubusercontent.com/118318397/224222448-123e827d-b8d2-4454-b4cc-10745ae7d7af.JPG)
![AdaBoost](https://user-images.githubusercontent.com/118318397/224222468-498f410b-fcf6-4a3f-8b08-875d1b23673d.png)



