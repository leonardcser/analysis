I am crossposting this here from my "waldo-vision/optical.flow.demo" pull request. This repository did not exists at the time and I feel like this falls more in line with the goal of this repo.

Testing the premade CNN model using "yolov3" on CSGO footage.

It does pretty good job at tracking human objects in the environment, but it also picks and ID's some of the background as well.

Thanks to @CaptnBaguette for bringing it up in the data-classification channel in the Discord. I did not see any code posted for it, so I went ahead an made a very basic example. Everything you need to run the script is included EXCEPT for the model weights. Those can be retrieved from: https://pjreddie.com/darknet/yolo/ (it's the 237MB one).