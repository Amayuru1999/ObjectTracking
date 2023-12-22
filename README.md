

# Object Tracking using OpenCV

This Python script demonstrates object tracking in a video using OpenCV. The script utilizes basic object detection techniques and centroid tracking to monitor and label objects moving within a video feed.

[https://github.com/Amayuru1999/ObjectTracking/assets/116435706/0390c0d6-ff42-4e7f-bb00-1bfcc736e77e](https://github.com/Amayuru1999/ObjectTracking/assets/116435706/0390c0d6-ff42-4e7f-bb00-1bfcc736e77e)

## Requirements

- Python 3.x
- OpenCV (`cv2`)
- NumPy (`numpy`)

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/object-tracking-opencv.git
    cd object-tracking-opencv
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Place your video file (e.g., "2.mp4") in the project directory.
2. Run the script:

    ```bash
    python object_tracking.py
    ```

3. Press the `Esc` key to exit the application.

## Explanation

- The script initializes an object detection class and reads a video file frame by frame.
- It detects objects in each frame, computes their centroids, and tracks their movement.
- Objects are tracked by comparing their positions across consecutive frames.
- Detected objects are labeled with unique IDs and displayed on the video feed.

## Code Structure

The code consists of several main sections:

- **Initialization:** Importing necessary libraries, initializing variables, and setting up the object detection class.
- **Object Detection:** Detecting objects in each frame and extracting their bounding boxes and centroid positions.
- **Object Tracking:** Comparing centroid positions between frames to track objects and assigning unique IDs.
- **Visualization:** Drawing bounding boxes, centroids, and labels on the video frame for tracked objects.

## Notes

- Tweak the distance threshold and other parameters for object tracking based on your specific use case.
- This code serves as a basic demonstration and can be extended for various object tracking applications.

## Contributions

Contributions are welcome! If you have any suggestions, improvements, or feature additions, feel free to open an issue or create a pull request.
