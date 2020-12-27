# Queen-Deepfake-Detection

Inspired by the recent deepfake video created of Queen Elizabeth, this repository aims to detect if there is a detectable difference between the deepfake and real video.
The steps taken are:<br>
1. Crop video frames to the face using deep neural net
2. Score each sequential frame for structural similarity with previous frame
3. Compare scores for both videos
<br>

Video Sources:
Real: https://www.youtube.com/watch?v=KgvZnxNAThM
DeepFake: https://www.youtube.com/watch?v=IvY-Abd2FfM
