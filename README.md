# SATPose

# Introduction
The PVM (Pressure, Vision, Mocap) dataset is a large-scale multimodal human activity dataset, comprising 21 actions (covering both daily activities and fitness exercises) performed by 20 participants. The body mass index (BMI) of the 20 participants (10 males and 10 females, average age = 22.9, SD = 2.86) ranged from 18 to 28, ensuring a moderate amount of body shape variability and different ranges of mobility among them. In the dataset, it includes ground pressure images, monocular images, 2D poses extracted from monocular images, and ground truth 3D poses, collected using a pressure mat, a monocular camera, and a optical motion capture system, respectively. Finally, the PVM dataset contains approximately 800,000 frames (11 hours) of data in total. 

In the download link below, we provide all the pressure images, 2D poses and ground truth 3D poses of the PVM dataset (PVMDataset.zip), as well as monocular images of two participants in the test set (monocular_images_tiny.zip). The data in these two compressed packages are stored frame by frame. Among them, data in PVMDataset.zip is stored in the form of .npz, and each frame of .npz contains a pressure image, a 2D pose and a ground truth 3D pose with key names of pressure, pose2d and pose3d respectively.
For details, please refer to the file tree below.

![avatar](actions.png)

# Download link


# File Tree
