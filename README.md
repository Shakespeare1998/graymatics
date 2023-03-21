# graymatics
Graymatics Problem Set

Knapsack Problem:
I have already pasted the examples given in the notebook. You can utilize a similar format to test the code for other inputs.


Balanced Brackets Problem:
I have already pasted the examples given in the notebook. You can utilize a similar format to test the code for other inputs.


Video Task:
Here, we first take the videoplayback.mp4 file as the input. I clipped the video to the required time. This is the modified_video.mp4 file. Next, we use this file and place the square on top of it. This result is saved as final_output.mp4 file.


Object Recognition in Video:
For this part, I am using the same input as the previous task. The videoplayback.mp4 file however is too big, so I clipped it down to a 1 minute video. We extract the frames of this video and run them though the model provided by you on this link. Since I utilized just the CPU on Google Colab it was taking nearly 38 minutes for a 1 minute video. To make this faster, I tried using alternate frames and every 4th frame for the classification task. This reduced the time required to 24 minutes and 13 minutes respectively. While this is still less than ideal, I utilized the GPU setup of my university to see how much time it takes. By using a GPU, the time taken for object detection in a 1 minute long video was down to approximately 6 minutes. Further improvements can be made by utilizing a custom built model for the application. I have also implemented the mini requirement of the text being in green if the confidence level is higher than 80% and red otherwise. 
In this case, I am displaying only the object detected with the highest confidence. The video I used also contains just various animals, but we can use other videos since the model provided covers a wide variety of objects.

