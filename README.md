# azure-project
Use  Custom Vision Prediction of Azure to detect whether the riders were wearing helements. 
If the model detects the probability of wearing a helment or not wearing a helment is greater than 50%, we will use opencv to make a bounding box to circle the head. 
User could interact with Custom Vision Prediction via Line Bot.
![34440AE8-2BC5-4DC5-97C5-1AA34719493D](https://user-images.githubusercontent.com/53245830/124065689-daab1b00-da69-11eb-9de9-69a2ba0c7ba0.png)
![3A73AAAB-5BAF-4C45-A08E-3](https://user-images.githubusercontent.com/53245830/124065892-3c6b8500-da6a-11eb-9d92-970f60a7ab2a.jpg)

If you set the threshold too low, you would get some bounding boxes without heads of people. 
![12BF1D6D-F183-4A0B-8DF5-C1B79AEF7C7D](https://user-images.githubusercontent.com/53245830/124065900-42616600-da6a-11eb-83ae-5c671a8dfe9a.png)
![11E7E21C-726C-4FDD-8E](https://user-images.githubusercontent.com/53245830/124065910-45f4ed00-da6a-11eb-9d34-1dc3cbe62d72.jpg)



