# Smart_City

1. i have made smart city like it will count how many cars passes that way
2. i have done parking space counter using twon method:
   (i) first one traditional method even in youtube it will be available like using color thresholding and count non zeros white we can done this but
   due variation in climate our accuracy may get affected.
   ![Screenshot (10)](https://github.com/sethuraman17/Smart_City/assets/116188101/5b359754-909a-40e6-b3d8-3dcbabd8449e)

   (ii) second method is like we need to implement object detection and you can;t import pre-trained models because when you see the car from eagle
    eye view the pre-trained models like yolo detect it as tooth bresh or something else so to overcome that we need to train our custom model and if
   you train 15,000 images manually it will took around 60hrs and if you buy any freelancer to do it it will cost around 10$ so i have taken the dataset
   from online sites only 50 images have trained in 1 epochs as my laptop is not advance but still i get good result but if you train 15,000 image with
   300 epochs than your model will be ultimate.
   after that the concept we are implementing here is the detecter cars center point is inside the cutom rectangle we drawn than it is consider as
   ocuupied and if the center point is away from the threshold value we fixed than it will consider as wrong position.

   ![Screenshot (9)](https://github.com/sethuraman17/Smart_City/assets/116188101/8df32e70-3509-46cc-bb29-42f7fcb4ed3c)


4. i have implemented this in my prototype which i have made:
![smart_city](https://github.com/sethuraman17/Smart_City/assets/116188101/f85cd02c-58a5-4e15-b19f-500a728f00ca)

