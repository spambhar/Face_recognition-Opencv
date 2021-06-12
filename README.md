# Face_recognition-Opencv

### Using Computer vision (haar cascade classifier)
https://github.com/opencv/opencv/tree/master/data/haarcascades
<br>

## Face, Eyes and Smile Detection:

```
# import file of CascadeClassifier
face = cv2.CascadeClassifier('./detect/haarcascade_frontalface_default.xml')
eye = cv2.CascadeClassifier('./detect/haarcascade_eye_tree_eyeglasses.xml')
smile = cv2.CascadeClassifier('./detect/haarcascade_smile.xml')
```
#### Output:
![2021-06](https://user-images.githubusercontent.com/70934443/121780768-73631f00-cbbf-11eb-8186-fa2954ca5244.jpg)

<br><br>

## Count face:

#### Output:
![2021-06-12 47](https://user-images.githubusercontent.com/70934443/121780838-c4731300-cbbf-11eb-871a-9091dce8dd15.png)

<br><br>

## Body Detection:
![2021-06-12 (46)](https://user-images.githubusercontent.com/70934443/121780892-0308cd80-cbc0-11eb-8a36-a82e56bd9a26.png)

