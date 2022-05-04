# bigdataformedia
This repository is used to store the problems and insights I encountered in a specialized course: Big Data for Media in Practice

## P1: an auto makeup program based on face-recognition
See the sorce code in [auto-makeup](./auto-makeup)

Once face-recognition has done its job to locate facial features, we can fill those areas with selected colors to create an effect that looks as if makeup has been applied.

So this is how Scarlett Johansson originally looks like:

![SJ](https://user-images.githubusercontent.com/89291145/166693018-50aa0eb8-a257-4adf-aeef-08eb61304fe6.jpg)

And this is how does she look like after processing ( sorry for that^^ still working on the precision )
![SJ2](https://user-images.githubusercontent.com/89291145/166696325-354f16fa-f73a-45ab-8855-18ebaf2dae65.JPG)


Anyway~ this is the technology principle of so-called beauty filter 



## P2 : How to record a video with cute sticker by python program ?

It seems a little bit difficult, but trust me, with open-CV, that is quite easy.
OpenCV has provided a method to open your camera, which is the first step to make a selfie or a video.

Next, anyone who has basic knowledge of video knows that video is composed of frames ( also can be seen as pics ), so my idea is to implement face recognition on each frame, which finally leads to the whole video with face recognition!

My implementation: according to the face recognition result, add a sticker beyond your face, which is so simple, in fact, same as adding a watermark.

The following shows the final result: ( a lovely Washington huh? believe H

![序列 01_2](https://user-images.githubusercontent.com/89291145/166710035-7626179c-46e7-4bd7-b822-5455496a6c2f.gif)

