# Final Project - Kalman Filter for Object Tracking in Images

---

90498 - Digital Image and Signal Processing

Laurea Magistrale - Computer science

Artificial Intelligence Track

University of Genova

---

Professors:

- Francesca Odone

- Alessandro Verri

---

Student:

- Arnaud Ruymaekers

---

In this project, I implemented a Kalman filter to track the position of an object in a video. Namely, I used two different videos of a pool player making a shot and tracking the position of the ball after this impact. Doing so required computer vision and pre-processing to mask-out all the irrelevant elements and in order to find the center of the balls. After the centers of the objects have been found for each frame in the video, the path in integrated using a Kalman filter.