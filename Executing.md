## D.EXECUTING PROJECT
### Project design and coding
Credit to CodeSpeedy by Vikrant Dey<br>
Link:https://www.codespeedy.com/fingerprint-detection-in-python/ <br>

import library in python:<br>
![image](https://user-images.githubusercontent.com/116957596/211174760-35b2ab64-610c-470d-80af-6fa5bd5092cc.png)

Viewing the test file(fingerprint to be matched)
![image](https://user-images.githubusercontent.com/116957596/211174777-a1b1f548-ea02-4eed-8f0f-f2e5aa12aa03.png)<br>

Output:<br>
![image](https://user-images.githubusercontent.com/116957596/211174839-24193670-ee32-4cb0-a645-ea4c9e388607.png)


Load Database:<br>
Using SIFT(Scale-Invariant Feature Transform) algorithm.SIFT is an algorithm in computer vision to detect and describe local features in images.This algorithm helps to extract important key-points and detect descriptors in the picture,as this help to identify for test image and image contain in the database.<br>
Coding:<br>
![image](https://user-images.githubusercontent.com/116957596/211174856-6ccb03c6-b1d9-41ee-804c-372cc68e449a.png)

After the alogrithm has been executed,we can start use matching algorithm.In this project FlannBasedMatcher() function are use to quickly find match using Cluster and Search algorithm.<br>

Coding:<br>
![image](https://user-images.githubusercontent.com/116957596/211175320-a2aacaf0-35ca-43d6-aaf2-25efd5dd7d7b.png)


Match the input fingerprint with fingerprint in the database using cv2.drawMatches() function.<br>
Coding:<br>
![image](https://user-images.githubusercontent.com/116957596/211175363-14c76de3-05e0-4a9a-a1fa-951f8301329c.png)

![image](https://user-images.githubusercontent.com/116957596/211175369-ee5b7897-596b-452b-b49f-1ae378b0fa33.png)<br>
Output:<br>
![image](https://user-images.githubusercontent.com/116957596/211175386-1a1a0890-dc4c-48cc-9989-dc8b2e0fc045.png)

