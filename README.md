# 3D-Human Pose Estimation (HPE) in video

Human Pose Estimation is a computer vision-based technology that identifies and classifies specific points on the human body. 33 points represent our limbs and joints to compute the angle of flexion, and measure, human pose well. 

3D human poses in video(s) can be effectively estimated with a fully convolutional model based on dilated temporal convolutions over 2D key point detection followed by 3D pose estimation. 

Keypoint estimation can be utilized to interpret movements to 3D models in the Metaverse such as Augmented Reality (AR), Virtual Reality (VR), Mixed Reality (MR) is used in association with webcam/smart phone cameras. It is used in sports industry, healthcare, Yoga, and business.

It is beneficial for physiotherapists, trainers, or artists to know the right angle of a joint in a specific work out. It aids in analysing pose/movement if it is correctly performed such as person squatting, running, bending, jumping in association with machine learning technology, is applicable to myriad fields.

Most of HPE methods are based on recording an RGB image with the optical sensor to detect body parts and over all poses. It is used for fitness, rehabilitation, augmented reality applications, and surveillance. The skeleton-based model is used in human pose estimation this is because it consists of a set of joints like ankles, knees, shoulders, elbows, wrists, and limb orientations comprising the skeletal structure of a human body.

I have used OpenCV and MediaPipe is well-balanced framework for pose estimation. It is uses BlazePose 33 landmark topology. It works in two stages – detection and tracking. As detection is not performed in each frame, MediaPipe is able to perform inference faster. 

<img src="https://user-images.githubusercontent.com/36221339/228575533-57fdf46e-f5cf-4340-bf1d-8d9e98baa6b3.png" width="60%" height="80%">

Image: https://learnopencv.com/building-a-body-posture-analysis-system-using-mediapipe/

<img src="https://user-images.githubusercontent.com/36221339/228576070-6b54dba9-73d0-42d5-85d7-30534332f3a5.PNG" width="40%" height="40%"><img src="https://user-images.githubusercontent.com/36221339/228576110-0e5dcc89-a0af-4ac0-a80d-5a2b75a4f63f.PNG" width="40%" height="40%">
<img src="https://user-images.githubusercontent.com/36221339/228576156-4ab6926b-8ef8-45cf-96c5-c48943093596.PNG" width="40%" height="40%"><img src="https://user-images.githubusercontent.com/36221339/228576183-a5fa29cd-4339-4026-b319-a3cf48491447.PNG" width="40%" height="40%">
<img src="https://user-images.githubusercontent.com/36221339/228576308-77114370-10a2-4f6f-822f-fcd17bfc3c5a.gif" width="50%" height="50%">

<img src="https://user-images.githubusercontent.com/36221339/228580561-c56b4192-0e72-42da-8061-eb65a66ebe3c.PNG" width="80%" height="70%">

#### References
1. Dare, K., Ben Abdessalem, H., Frasson, C. (2022). Application of 3D Human Pose Estimation for Behavioral Reproduction. In: Crossley, S., Popescu, E. (eds) Intelligent Tutoring Systems. ITS 2022. Lecture Notes in Computer Science, vol 13284. Springer, Cham. https://doi.org/10.1007/978-3-031-09680-8_18
2. Kukil and Vikas Gupta, OCT 18, 2022 https://learnopencv.com/yolov7-pose-vs-mediapipe-in-human-pose-estimation/#:~:text=MediaPipe%20detected%20the%20person%20on,performs%20detection%20on%20each%20frame.
3. Appl. Sci. 2022, 12(20), 10591; https://doi.org/10.3390/app122010591
4. Elisha Odemakinde, https://viso.ai/deep-learning/pose-estimation-ultimate-overview/https://viso.ai/deep-learning/pose-estimation-ultimate-overview/
5. Liubov Zatolokina, Oct 21, 2022, https://mobidev.biz/blog/human-pose-estimation-technology-guide
6. Mrinal Singh Walia — Published on Jan 11, 2022, and Last Modified on Feb 10, 2022, https://www.analyticsvidhya.com/blog/2022/01/a-comprehensive-guide-on-human-pose-estimation/
