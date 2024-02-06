# TASK 2A
## Steps:
- This function (detectAndDescribe) takes an image and a feature detection method (default is SIFT), and it returns keypoints (kp) and descriptors (des) using the specified method.
- Here, the matchKeyPointsBF function takes two sets of descriptors (featuresA and featuresB) and returns good matches using a brute-force matcher with a ratio test.
- This function (visualize_matches) visualizes the feature matches by drawing them on the images.
- This function (create_panorama) takes two images and creates a panorama by detecting, describing, and matching features, applying RANSAC to find the homography matrix, and warping the images accordingly.
