# Detect a face and replace it with Jeffs face


Uses openCv's Haar cascade filters to find faces and then scales repalcement image to scale and then `photoshops` it on top of face locations.

```
docker run -it -v $PWD:/data kavolorn/opencv bash
```
TODO:

1. better mobile image handling
2. non-recompute
3. make it less computationally expensive
4. cache results


From
![alt text](https://github.com/townie/jeff_face_replace/blob/main/imgs/mntrush.jpg?raw=true)
to
![alt text](https://github.com/townie/jeff_face_replace/blob/main/imgs/mntrush_fin.jpg?raw=true)
